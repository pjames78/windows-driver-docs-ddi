---
UID: NS:d3d12umddi.D3D12DDI_WAVE_MMA_DATA_0103
tech.root: display
title: D3D12DDI_WAVE_MMA_DATA_0103
ms.date: 05/06/2024
targetos: Windows
description: Learn about the D3D12DDI_WAVE_MMA_DATA_0103 structure.
prerelease: false
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: d3d12umddi.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: Windows 11, version 24H2 (WDDM 3.2)
req.target-min-winversvr: 
req.target-type: 
req.typenames: D3D12DDI_WAVE_MMA_DATA_0103
typedef_isUnnamed: false
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - d3d12umddi.h
api_name:
 - D3D12DDI_WAVE_MMA_DATA_0103
f1_keywords:
 - D3D12DDI_WAVE_MMA_DATA_0103
 - d3d12umddi/D3D12DDI_WAVE_MMA_DATA_0103
dev_langs:
 - c++
helpviewer_keywords:
 - D3D12DDI_WAVE_MMA_DATA_0103
---

## -description

The **D3D12DDI_WAVE_MMA_DATA_0103** structure describes the data that is required to execute a matrix-multiply-accumulate (MMA) operation.

## -struct-fields

### -field InputDataType

[in] A [**D3D12DDI_WAVE_MMA_INPUT_DATATYPE**](ne-d3d12umddi-d3d12ddi_wave_mma_input_datatype.md) enumeration that specifies the data type of the input data.

### -field M

[in] The dimension of the matrix operation that corresponds to the number of rows in the left matrix.

### -field N

[in] The dimension of the matrix operation that corresponds to the number of columns in the right matrix.

### -field Supported

[out] Set to TRUE if the hardware supports the specified matrix dimensions and data type; otherwise FALSE.

### -field K

[out] The shared dimension between the two matrices (the number of columns in the left matrix and the number of rows in the right matrix) for which the hardware supports the operation.

### -field AccumDataTypes

[out] The [**D3D12DDI_WAVE_MMA_ACCUM_DATATYPE**](ne-d3d12umddi-d3d12ddi_wave_mma_accum_datatype.md) enumeration that specifies the supported data types for the accumulation buffer, which holds the result of the matrix operation. I

### -field RequiredWaveLaneCountMin

[out] The minimum number of wave lanes required to perform the operation.

### -field RequiredWaveLaneCountMax

[out] The maximum number of wave lanes that can be used to perform the operation.

## -remarks

The dimensions of the matrix multiplication unit is device specific, so HLSL defines the dimensions of the Wave Matrix to preserve as much flexibility in the hardware implementation that is feasible while also trying to make it useable for HLSL developers. The matrix multiplication unit is defined by three dimensions M, N, and K. The matrix multiplication unit then would defined to be a multiplication of two matrices of dimensions, MxK and KxN with a resulting matrix of size MxN.

The Wave Matrix object is defined to have sizes M, N, and K. This means that for the matrix multiply of AxB, matrix A is M rows of K elements and matrix B is K rows of N elements. A hardware implementation might support only one K value for each combination of M, N, and datatype. The possible dimensions of M and N are restricted to the allowed enum values defined by D3D12DDI_WAVE_MMA_DIMENSION M and D3D12DDI_WAVE_MMA_DIMENSION N. The K dimension is defined to be an even multiple of 16 provided by the driver through the D3D12_FEATURE_DATA_WAVE_MMA CheckFeatureSupport Caps. The K value also accessible via a function on the input matrices. This allows for programable shaders and hardcoded shaders. The K value is considered a constant and the driver should unroll loops using it, if possible.

## -see-also
