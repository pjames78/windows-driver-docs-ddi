---
UID: NC:wdm.IOMMU_DOMAIN_ATTACH_PASID_DEVICE
tech.root: kernel
title: IOMMU_DOMAIN_ATTACH_PASID_DEVICE (wdm.h)
ms.date: 08/23/2022
targetos: Windows
description: The IOMMU_DOMAIN_ATTACH_PASID_DEVICE (wdm.h) callback function attaches a PASID sub-device to an existing domain.
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
 - IOMMU_DOMAIN_ATTACH_PASID_DEVICE
f1_keywords:
 - IOMMU_DOMAIN_ATTACH_PASID_DEVICE
 - wdm/IOMMU_DOMAIN_ATTACH_PASID_DEVICE
dev_langs:
 - c++
helpviewer_keywords:
 - IOMMU_DOMAIN_ATTACH_PASID_DEVICE
---

## -description

The **IOMMU_DOMAIN_ATTACH_PASID_DEVICE** callback function attaches a PASID sub-device to an existing domain.

## -parameters

### -param Domain

Supplies a handle to the domain that the sub-device will attach to.

### -param PasidDevice

Supplies a pointer to the PASID sub-device to be attached.

## -returns

Returns **NTSTATUS** with the following values:

| Return value | Description |
|--|--|
| STATUS_SUCCESS | On successful sub-device attachment to the domain. |
| STATUS_INSUFFICIENT_RESOURCES | Not enough memory to allocate a cached device for attach/detach bookkeeping. |
| STATUS_INVALID_PARAMETER | The sub-device is already attached to a domain. |
| STATUS_ACCESS_DENIED | The sub-device is currently not allowed to attach to this domain. |

## -remarks

## -see-also
