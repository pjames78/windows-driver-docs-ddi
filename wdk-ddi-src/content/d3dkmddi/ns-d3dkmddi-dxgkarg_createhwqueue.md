---
UID: NS:d3dkmddi._DXGKARG_CREATEHWQUEUE
tech.root: display
title: DXGKARG_CREATEHWQUEUE
ms.date: 03/21/2024
targetos: Windows
description: Learn more about the DXGKARG_CREATEHWQUEUE structure.
prerelease: false
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: d3dkmddi.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: Windows 10, version 1703 (WDDM 2.2)
req.target-min-winversvr: 
req.target-type: 
req.typenames: DXGKARG_CREATEHWQUEUE
typedef_isUnnamed: false
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - d3dkmddi.h
api_name:
 - _DXGKARG_CREATEHWQUEUE
 - DXGKARG_CREATEHWQUEUE
f1_keywords:
 - _DXGKARG_CREATEHWQUEUE
 - d3dkmddi/_DXGKARG_CREATEHWQUEUE
 - DXGKARG_CREATEHWQUEUE
 - d3dkmddi/DXGKARG_CREATEHWQUEUE
dev_langs:
 - c++
helpviewer_keywords:
 - _DXGKARG_CREATEHWQUEUE
---

## -description

## -struct-fields

### -field hHwQueue

[in/out] On input, *Dxgkrnl*'s handle to the hardware queue. On output, the driver's handle to the hardware queue.

### -field Flags

[in] A [**D3DDDI_CREATEHWQUEUEFLAGS**](../d3dukmdt/ns-d3dukmdt-_d3dddi_createhwqueueflags.md) structure containing the queue creation flags.

### -field PrivateDriverDataSize

[in] Size in bytes of the private driver data that **pPrivateDriverData** points to.

### -field pPrivateDriverData

[in/out] Pointer to the private driver data that was passed by the user-mode [**pfnCreateHwContextCb**](../d3dumddi/nc-d3dumddi-pfnd3dddi_createhwcontextcb.md). Since **pPrivateDriverData** is an in-out parameter, KMD can also return private data back to the UMD.

### -field hHwQueueProgressFence

[in] Handle to the GPU synchronization object created by the OS for this hardware queue. The progress fence is used to synchronize DMA buffer completion on this hardware queue.

### -field HwQueueProgressFenceCPUVirtualAddress

[in] Kernel-mode CPU virtual address that can be used to read the currently signaled value of the hardware queue progress fence.

### -field HwQueueProgressFenceGPUVirtualAddress

[in] GPU virtual address that can be used to read or write the value of the hardware queue progress fence. The queue progress fence value must monotonically increase with each new submission to the hardware queue. GPU instructions to update the queue progress fence must be inserted by the user-mode driver at the end of the DMA buffer being tracked.

## -see-also

[**DXGKDDI_CREATEHWQUEUE**](nc-d3dkmddi-dxgkddi_createhwqueue.md)
