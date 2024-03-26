---
UID: NF:storport.StorPortIsDriverHotSwapEnabled
tech.root: storage
title: StorPortIsDriverHotSwapEnabled
ms.date: 03/25/2024
targetos: Windows
description: The StorPortIsDriverHotSwapEnabled function checks if the hot swap feature is enabled for a specific driver. Hot swapping is the ability to replace or add components without stopping a system.
prerelease: true
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: storport.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - storport.h
api_name:
 - StorPortIsDriverHotSwapEnabled
f1_keywords:
 - StorPortIsDriverHotSwapEnabled
 - storport/StorPortIsDriverHotSwapEnabled
dev_langs:
 - c++
helpviewer_keywords:
 - StorPortIsDriverHotSwapEnabled
---

## -description

The **StorPortIsDriverHotSwapEnabled** function checks if the hot swap feature is enabled for a specific driver. Hot swapping is the ability to replace or add components without stopping a system.

## -parameters

### -param HwDeviceExtension

A pointer to the hardware device extension. This is specific to the miniport driver instance.

### -param DriverObject

A pointer to the driver object.

## -returns

 If the driver is hot swap enabled, returns STOR_STATUS_SUCCESS, otherwise STOR_STATUS_NOT_IMPLEMENTED.

## -remarks

## -see-also
