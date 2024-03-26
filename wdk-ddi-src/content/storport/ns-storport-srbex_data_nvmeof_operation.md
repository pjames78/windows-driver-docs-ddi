---
UID: NS:storport._SRBEX_DATA_NVMEOF_OPERATION
tech.root: storage
title: SRBEX_DATA_NVMEOF_OPERATION
ms.date: 03/26/2024
targetos: Windows
description: The SRBEX_DATA_NVMEOF_OPERATION structure contains information about an NVMe OF operation.
prerelease: true
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: storport.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.typenames: SRBEX_DATA_NVMEOF_OPERATION, *PSRBEX_DATA_NVMEOF_OPERATION
typedef_isUnnamed: false
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - storport.h
api_name:
 - _SRBEX_DATA_NVMEOF_OPERATION
 - PSRBEX_DATA_NVMEOF_OPERATION
 - SRBEX_DATA_NVMEOF_OPERATION
f1_keywords:
 - _SRBEX_DATA_NVMEOF_OPERATION
 - storport/_SRBEX_DATA_NVMEOF_OPERATION
 - PSRBEX_DATA_NVMEOF_OPERATION
 - storport/PSRBEX_DATA_NVMEOF_OPERATION
 - SRBEX_DATA_NVMEOF_OPERATION
 - storport/SRBEX_DATA_NVMEOF_OPERATION
dev_langs:
 - c++
helpviewer_keywords:
 - _SRBEX_DATA_NVMEOF_OPERATION
---

## -description

The **SRBEX_DATA_NVMEOF_OPERATION** structure contains information about an NVMe OF operation.

## -struct-fields

### -field Type

The type of the operation. This must be set to `SrbExDataTypeNvmeofOperation`.

### -field Length

The size of this structure, in bytes.

### -field Version

The version of this structure.

### -field Reserved1

Reserved for internal use.

### -field Flags

Operation specific flags.

### -field FunctionType

Specifies the function type. This is set to one of the values in the **STOR_NVMEOF_FUNCTION_TYPE** enum defined in storport.h.

## -remarks

## -see-also
