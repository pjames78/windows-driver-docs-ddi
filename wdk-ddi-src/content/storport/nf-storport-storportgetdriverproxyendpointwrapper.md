---
UID: NF:storport.StorPortGetDriverProxyEndpointWrapper
tech.root: storage
title: StorPortGetDriverProxyEndpointWrapper
ms.date: 03/25/2024
targetos: Windows
description: The StorPortGetDriverProxyEndpointWrapper function returns the miniport driver proxy endpoint wrapper.
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
 - StorPortGetDriverProxyEndpointWrapper
f1_keywords:
 - StorPortGetDriverProxyEndpointWrapper
 - storport/StorPortGetDriverProxyEndpointWrapper
dev_langs:
 - c++
helpviewer_keywords:
 - StorPortGetDriverProxyEndpointWrapper
---

## -description

The **StorPortGetDriverProxyEndpointWrapper** function returns the miniport driver proxy endpoint wrapper.

## -parameters

### -param HwDeviceExtension

A pointer to the hardware device extension. This is a per-device location where the miniport driver can store device-specific information. This parameter is optional and can be null.

### -param ProxyExtension

A pointer to a **STOR_DRIVER_PROXY_EXTENSION** structure, which contains information about the driver proxy extension.

### -param Id

This is an identifier for the **STOR_DRIVER_PROXY_ENDPOINT_FUNCTION_ID** enumeration, which specifies the function ID of the driver proxy endpoint.

### -param Wrapper

A pointer to a PVOID where the function will store the result. This is an output parameter.

## -returns

Returns a STOR_STATUS_xxxx value. See storport.h for status values.

## -remarks

## -see-also
