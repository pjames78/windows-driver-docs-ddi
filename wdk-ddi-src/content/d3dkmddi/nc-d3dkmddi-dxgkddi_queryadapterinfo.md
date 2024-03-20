---
UID: NC:d3dkmddi.DXGKDDI_QUERYADAPTERINFO
title: DXGKDDI_QUERYADAPTERINFO (d3dkmddi.h)
description: Learn more about the DXGKDDI_QUERYADAPTERINFO callback function.
ms.date: 03/21/2024
keywords: ["DXGKDDI_QUERYADAPTERINFO callback function"]
req.header: d3dkmddi.h
req.include-header: 
req.target-type: Desktop
req.target-min-winverclnt: Windows Vista
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: PASSIVE_LEVEL
targetos: Windows
tech.root: display
req.typenames: 
ms.custom: 19H1
f1_keywords:
 - DXGKDDI_QUERYADAPTERINFO
 - d3dkmddi/DXGKDDI_QUERYADAPTERINFO
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - UserDefined
api_location:
 - d3dkmddi.h
api_name:
 - DXGKDDI_QUERYADAPTERINFO
dev_langs:
 - c++
---

# DXGKDDI_QUERYADAPTERINFO callback function

## -description

The display miniport's (KMD's) **DxgkDdiQueryAdapterInfo** function retrieves configuration information from the graphics adapter.

## -parameters

### -param hAdapter [in]

A handle to a context block that is associated with a display adapter. The KMD previously provided this handle to *Dxgkrnl* in the **MiniportDeviceContext** output parameter of the [**DxgkDdiAddDevice**](../dispmprt/nc-dispmprt-dxgkddi_add_device.md) function.

### -param pQueryAdapterInfo [in]

A pointer to a [**DXGKARG_QUERYADAPTERINFO**](ns-d3dkmddi-_dxgkarg_queryadapterinfo.md) structure that the KMD fills with the configuration information for the graphics adapter.

## -returns

**DxgkDdiQueryAdapterInfo** returns one of the following values:

|Return code|Description|
|--- |--- |
|STATUS_SUCCESS|DxgkDdiQueryAdapterInfo successfully retrieved the configuration information.|
|STATUS_INVALID_PARAMETER|Parameters that were passed to DxgkDdiQueryAdapterInfo contained errors that prevented it from completing.|
|STATUS_NO_MEMORY|DxgkDdiQueryAdapterInfo could not allocate memory that was required for it to complete.|
|STATUS_GRAPHICS_DRIVER_MISMATCH|The display miniport driver is not compatible with the user-mode display driver that initiated the call to DxgkDdiQueryAdapterInfo (that is, supplied private data for a query to the display miniport driver).|

## -remarks

When the user-mode display driver calls the [**pfnQueryAdapterInfoCb**](../d3dumddi/nc-d3dumddi-pfnd3dddi_queryadapterinfocb.md) function, a call to the **DxgkDdiQueryAdapterInfo** function is initiated. 

If **DxgkDdiQueryAdapterInfo** receives the DXGKQAITYPE_UMDRIVERPRIVATE value in the **Type** member of the [**DXGKARG_QUERYADAPTERINFO**](ns-d3dkmddi-_dxgkarg_queryadapterinfo.md) structure that the **pQueryAdapterInfo** parameter points to, **pOutputData** points to a proprietary structure that KMD fills with the configuration information that is necessary for the user-mode display driver to identify the adapter.

If *Dxgkrnl* specifies the DXGKQAITYPE_DRIVERCAPS value in the **Type** member of DXGKARG_QUERYADAPTERINFO when the subsystem calls **DxgkDdiQueryAdapterInfo**, the display miniport driver should populate the provided [**DXGK_DRIVERCAPS**](ns-d3dkmddi-_dxgk_drivercaps.md) structure with information that the subsystem can use.

If the DirectX graphics kernel subsystem supplies the DXGKQAITYPE_QUERYSEGMENT value in the **Type** member of DXGKARG_QUERYADAPTERINFO, the display miniport driver should provide information about the memory segments that it supports. For more information about memory segments, see [Initializing Use of Memory Segments](/windows-hardware/drivers/display/initializing-use-of-memory-segments).

**DxgkDdiQueryAdapterInfo** should be made pageable.

All drivers that support WDDM 2.6 and greater must implement the **DxgkDdiQueryAdapterInfo** callback.

## -see-also

[**DXGKARG_QUERYADAPTERINFO**](ns-d3dkmddi-_dxgkarg_queryadapterinfo.md)

[**DxgkDdiAddDevice**](../dispmprt/nc-dispmprt-dxgkddi_add_device.md)

[**pfnQueryAdapterInfoCb**](../d3dumddi/nc-d3dumddi-pfnd3dddi_queryadapterinfocb.md)
