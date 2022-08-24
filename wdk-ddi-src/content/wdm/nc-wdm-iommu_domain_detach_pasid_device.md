---
UID: NC:wdm.IOMMU_DOMAIN_DETACH_PASID_DEVICE
tech.root: kernel
title: IOMMU_DOMAIN_DETACH_PASID_DEVICE (wdm.h)
ms.date: 08/23/2022
targetos: Windows
description: The IOMMU_DOMAIN_DETACH_PASID_DEVICE (wdm.h) callback function detaches a PASID sub-device from the domain it is currently attached to.
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
 - IOMMU_DOMAIN_DETACH_PASID_DEVICE
f1_keywords:
 - IOMMU_DOMAIN_DETACH_PASID_DEVICE
 - wdm/IOMMU_DOMAIN_DETACH_PASID_DEVICE
dev_langs:
 - c++
helpviewer_keywords:
 - IOMMU_DOMAIN_DETACH_PASID_DEVICE
---

## -description

The **IOMMU_DOMAIN_DETACH_PASID_DEVICE** callback function detaches a PASID sub-device from the domain it is currently attached to.

## -parameters

### -param PasidDevice

Supplies a pointer to the PASID sub-device to be detached.

## -returns

Returns **NTSTATUS** with the following values:

| Return value | Description |
|--|--|
| STATUS_SUCCESS | On successful sub-device detachment from the domain. |
| STATUS_INVALID_PARAMETER_1 | The sub-device could not be detached because it was never attached. |

## -remarks

## -see-also
