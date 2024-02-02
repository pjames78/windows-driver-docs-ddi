---
UID: NC:d3dkmddi.DXGKCB_FEATURE_NATIVEFENCE_CAPS_1
tech.root: display
title: DXGKCB_FEATURE_NATIVEFENCE_CAPS_1
ms.date: 04/08/2024
targetos: Windows
description: Learn more about the DXGKCB_FEATURE_NATIVEFENCE_CAPS_1 callback function.
prerelease: false
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: d3dkmddi.h
req.idl: 
req.include-header: 
req.irql: PASSIVE_LEVEL
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
 - d3dkmddi.h
api_name:
 - DXGKCB_FEATURE_NATIVEFENCE_CAPS_1
f1_keywords:
 - DXGKCB_FEATURE_NATIVEFENCE_CAPS_1
 - d3dkmddi/DXGKCB_FEATURE_NATIVEFENCE_CAPS_1
dev_langs:
 - c++
helpviewer_keywords:
 - DXGKCB_FEATURE_NATIVEFENCE_CAPS_1
---

## -description

**DXGKCB_FEATURE_NATIVEFENCE_CAPS_1** is the OS's interface table dedicated to version 1 of **DXGK_FEATURE_NATIVE_FENCE**. KMD calls **DXGKCB_FEATURE_NATIVEFENCE_CAPS_1** to determine the OS's support for the native GPU fence feature.

## -parameters

### -param pArgs

[in/out] Pointer to a [**DXGKARGCB_FEATURE_NATIVEFENCE_CAPS_1**](ns-d3dkmddi-_dxgkargcb_feature_nativefence_caps_1.md) structure in which the OS returns the support it's providing.

## -returns

**DXGKCB_FEATURE_NATIVEFENCE_CAPS_1** returns STATUS_SUCCESS if the operation succeeds. Otherwise, it returns an appropriate NTSTATUS error code.

## -remarks

For a sample code snippet and more information about native GPU fences, see [Native GPU fence objects](/windows-hardware/drivers/display/native-gpu-fence-objects.md).

## -see-also

[**DXGKARGCB_FEATURE_NATIVEFENCE_CAPS_1**](ns-d3dkmddi-_dxgkargcb_feature_nativefence_caps_1.md)

[**DXGKCBINT_FEATURE_NATIVEFENCE_1**](ns-d3dkmddi-_dxgkcbint_feature_nativefence_1.md)
