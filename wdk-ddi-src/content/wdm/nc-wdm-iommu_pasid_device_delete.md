---
UID: NC:wdm.IOMMU_PASID_DEVICE_DELETE
tech.root: kernel
title: IOMMU_PASID_DEVICE_DELETE (wdm.h)
ms.date: 08/23/2022
targetos: Windows
description: The IOMMU_PASID_DEVICE_DELETE (wdm.h) routine deletes an PASID sub-device.
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
 - IOMMU_PASID_DEVICE_DELETE
f1_keywords:
 - IOMMU_PASID_DEVICE_DELETE
 - wdm/IOMMU_PASID_DEVICE_DELETE
dev_langs:
 - c++
helpviewer_keywords:
 - IOMMU_PASID_DEVICE_DELETE
---

## -description

The **IOMMU_PASID_DEVICE_DELETE** callback function deletes an PASID sub-device.

## -parameters

### -param PasidDevice

Supplies a pointer to the PASID sub-device to be deleted.

## -returns

Returns **NTSTATUS** with the following values:

| Return value | Description |
|--|--|
| STATUS_SUCCESS | On successful deletion of the PASID sub-device. |
| STATUS_RESOURCE_IN_USE | The device is still attached to a domain. Callers are responsible detaching devices from domains before deleting the device. |

## -remarks

## -see-also
