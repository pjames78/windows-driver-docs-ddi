---
UID: NE:d3dukmdt._DXGK_DRIVER_FEATURE
tech.root: display
title: DXGK_DRIVER_FEATURE
ms.date: 03/21/2024
targetos: Windows
description: Learn more about the DXGK_DRIVER_FEATURE enumeration.
prerelease: true
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
 - _DXGK_DRIVER_FEATURE
 - DXGK_DRIVER_FEATURE
f1_keywords:
 - _DXGK_DRIVER_FEATURE
 - d3dukmdt/_DXGK_DRIVER_FEATURE
 - DXGK_DRIVER_FEATURE
 - d3dukmdt/DXGK_DRIVER_FEATURE
dev_langs:
 - c++
helpviewer_keywords:
 - _DXGK_DRIVER_FEATURE
---

## -description

**DXGK_DRIVER_FEATURE** is an enumeration that provides the sub-IDs for driver features that a kernel-mode display miniport driver (KMD) can indicate support for.

## -enum-fields

### -field DXGK_DRIVER_FEATURE_HWSCH:0

Indicates support for hardware accelerated GPU scheduling.

### -field DXGK_DRIVER_FEATURE_HWFLIPQUEUE:1

Indicates support for hardware flip queue.

### -field DXGK_DRIVER_FEATURE_LDA_GPUPV:2

Indicates support for a linked display adapter in GPU paravirtualization.

### -field DXGK_DRIVER_FEATURE_KMD_SIGNAL_CPU_EVENT:3

Indicates support for signaling of a CPU event by KMD.

### -field DXGK_DRIVER_FEATURE_USER_MODE_SUBMISSION:4

Indicates support for user-mode submission.

### -field DXGK_DRIVER_FEATURE_SHARE_BACKING_STORE_WITH_KMD:5

Indicates support for allowing UMD to share the backing store with KMD.

### -field DXGK_DRIVER_FEATURE_RESERVED_1:6

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_2:7

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_3:8

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_4:9

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_5:10

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_6:11

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_7:12

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_8:13

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_9:14

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_10:15

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_11:16

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_12:17

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_13:18

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_14:19

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_15:20

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_16:21

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_17:22

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_18:23

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_19:24

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_20:25

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_21:26

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_22:27

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_23:28

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_24:29

Reserved.

### -field DXGK_DRIVER_FEATURE_RESERVED_25:30

Reserved.

### -field DXGK_DRIVER_FEATURE_SAMPLE:31

### -field DXGK_DRIVER_FEATURE_PAGE_BASED_MEMORY_MANAGER:32

Indicates support for page-based memory management.

### -field DXGK_DRIVER_FEATURE_KERNEL_MODE_TESTING:33

Indicates support for the kernel-mode testing interface.

### -field DXGK_DRIVER_FEATURE_64K_PT_DEMOTION_FIX:34

### -field DXGK_DRIVER_FEATURE_GPUPV_PRESENT_HWQUEUE:35

### -field DXGK_DRIVER_FEATURE_NATIVE_FENCE:36

Indicates support for native GPU fences.

### -field DXGK_DRIVER_FEATURE_MAX

Maximum value for the enumeration.

## -remarks

A WDDM feature is indentified by its "feature ID" ([**DXGK_FEATURE_ID**](../d3dukmdt/ne-d3dukmdt-dxgk_feature_id.md)) which is composed of a category ID (upper 4 bits), and the sub-ID for the feature itself within that category (**DXGK_DRIVER_FEATURE**).

Because the original feature implementations didn't categorize the feature IDs, there are a handful of feature IDs that must remain defined within category 0 for backwards compatibility, but are not driver features. This applies to the following feature IDs:

* DXGK_FEATURE_64K_PT_DEMOTION_FIX
* DXGK_FEATURE_GPUPV_PRESENT_HWQUEUE
* All feature IDs in the range of DXGK_DRIVER_FEATURE_RESERVED_1-DXGK_DRIVER_FEATURE_RESERVED_25

These feature IDs represent features that have been defined or implemented on older OS builds, and existing software checks must be able to continue to query these features by those IDs. Drivers are not required to implement support for any of these feature IDs.

## -see-also

[**DXGK_FEATURE_ID**](../d3dukmdt/ne-d3dukmdt-dxgk_feature_id.md)
