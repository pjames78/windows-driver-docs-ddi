---
UID: NC:wdm.IOMMU_PASID_DEVICE_CREATE
tech.root: kernel
title: IOMMU_PASID_DEVICE_CREATE (wdm.h)
ms.date: 10/04/2022
targetos: Windows
description: The IOMMU_PASID_DEVICE_CREATE (wdm.h) callback function takes an IOMMU_DMA_DEVICE token and spawns a new sub-device representing the newly assigned PASID.
prerelease: false
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: wdm.h
req.idl: 
req.include-header: Wdm.h
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: WIN11_NEXT
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - LibDef
api_location:
 - wdm.h
api_name:
 - IOMMU_PASID_DEVICE_CREATE
f1_keywords:
 - IOMMU_PASID_DEVICE_CREATE
 - wdm/IOMMU_PASID_DEVICE_CREATE
dev_langs:
 - c++
helpviewer_keywords:
 - IOMMU_PASID_DEVICE_CREATE
---

## -description

The **IOMMU_PASID_DEVICE_CREATE** callback function takes an IOMMU_DMA_DEVICE token and spawns a new sub-device representing the newly assigned PASID. The PASID is also returned since the sub-device token is opaque to the caller.

## -parameters

### -param DmaDevice

Supplies a pointer to the IOMMU DMA device token from which sub-devices are spawned.

### -param PasidDeviceOut

Supplies a pointer to the created IOMMU DMA sub-device.

### -param AsidOut

Supplies a pointer to hold the system-assigned PASID.

## -returns

Returns **NTSTATUS** with the following values:

| Return value | Description |
|--|--|
| STATUS_SUCCESS | On successful creation of the sub-device. PasidDeviceOut returns a valid pointer. |
| STATUS_INVALID_PARAMETER_1 | Provided device token is either invalid or is not supported by the system. |
| STATUS_INSUFFICIENT_RESOURCES | Not enough memory to allocate an **IOMMU_DMA_PASID_DEVICE** structure. |

## -remarks

## -see-also
