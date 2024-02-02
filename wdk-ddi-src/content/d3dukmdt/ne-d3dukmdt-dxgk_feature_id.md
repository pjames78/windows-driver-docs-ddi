---
UID: NE:d3dukmdt._DXGK_FEATURE_ID
tech.root: display
title: DXGK_FEATURE_ID
ms.date: 04/08/2024
targetos: Windows
description: Learn more about the DXGK_FEATURE_ID enumeration.
prerelease: false
req.construct-type: enumeration
req.ddi-compliance: 
req.header: d3dukmdt.h
req.include-header: 
req.kmdf-ver: 
req.max-support: 
req.target-min-winverclnt: WIN11_NEXT
req.target-min-winversvr: 
req.target-type: 
req.typenames: 
typedef_isUnnamed: false
req.umdf-ver: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - d3dukmdt.h
api_name:
 - _DXGK_FEATURE_ID
 - DXGK_FEATURE_ID
f1_keywords:
 - _DXGK_FEATURE_ID
 - d3dukmdt/_DXGK_FEATURE_ID
 - DXGK_FEATURE_ID
 - d3dukmdt/DXGK_FEATURE_ID
dev_langs:
 - c++
helpviewer_keywords:
 - _DXGK_FEATURE_ID
---

## -description

**DXGK_FEATURE_ID** is an enumeration of WDDM features that a kernel-mode display miniport driver (KMD) can indicate support for. It's composed of a category ID (upper four bits) and a sub-ID ([**DXGK_DRIVER_FEATURE**](DXGK_DRIVER_FEATURE)) for the feature itself.

## -enum-fields

### -field DXGK_FEATURE_HWSCH

Indicates support for hardware accelerated GPU scheduling. The feature category is DXGK_FEATURE_CATEGORY_DRIVER.

### -field DXGK_FEATURE_HWFLIPQUEUE

Indicates support for hardware flip queue. The feature category is DXGK_FEATURE_CATEGORY_DRIVER.

### -field DXGK_FEATURE_LDA_GPUPV

Indicates support for a linked display adapter in GPU paravirtualization. The feature category is DXGK_FEATURE_CATEGORY_DRIVER.

### -field DXGK_FEATURE_KMD_SIGNAL_CPU_EVENT

Indicates support for signaling of a CPU event by KMD. The feature category is DXGK_FEATURE_CATEGORY_DRIVER.

### -field DXGK_FEATURE_USER_MODE_SUBMISSION

Indicates support for user-mode submission. The feature category is DXGK_FEATURE_CATEGORY_DRIVER.

### -field DXGK_FEATURE_SHARE_BACKING_STORE_WITH_KMD

Indicates support for allowing UMD to share the backing store with KMD. The feature category is DXGK_FEATURE_CATEGORY_DRIVER.

### -field DXGK_FEATURE_SAMPLE

### -field DXGK_FEATURE_PAGE_BASED_MEMORY_MANAGER

Indicates support for page-based memory management. The feature category is DXGK_FEATURE_CATEGORY_DRIVER.

### -field DXGK_FEATURE_KERNEL_MODE_TESTING

Indicates support for the kernel-mode testing interface. The feature category is DXGK_FEATURE_CATEGORY_DRIVER.

### -field DXGK_FEATURE_64K_PT_DEMOTION_FIX

### -field DXGK_FEATURE_GPUPV_PRESENT_HWQUEUE

### -field DXGK_FEATURE_NATIVE_FENCE

Indicates support for native GPU fences. The feature category is DXGK_FEATURE_CATEGORY_DRIVER.

### -field DXGK_FEATURE_GPUVAIOMMU

## -remarks

## -see-also

[**DXGK_DRIVER_FEATURE**](ne-d3dukmdt-dxgk_driver_feature.md)