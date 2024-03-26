---
UID: NS:storport._STOR_DRIVER_PROXY_ENDPOINT_INFORMATION
tech.root: storage
title: STOR_DRIVER_PROXY_ENDPOINT_INFORMATION
ms.date: 03/26/2024
targetos: Windows
description: The STOR_DRIVER_PROXY_ENDPOINT_INFORMATION structure contain information about the driver proxy endpoint callback function.
prerelease: true
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: storport.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.typenames: STOR_DRIVER_PROXY_ENDPOINT_INFORMATION, *PSTOR_DRIVER_PROXY_ENDPOINT_INFORMATION
typedef_isUnnamed: false
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - storport.h
api_name:
 - _STOR_DRIVER_PROXY_ENDPOINT_INFORMATION
 - PSTOR_DRIVER_PROXY_ENDPOINT_INFORMATION
 - STOR_DRIVER_PROXY_ENDPOINT_INFORMATION
f1_keywords:
 - _STOR_DRIVER_PROXY_ENDPOINT_INFORMATION
 - storport/_STOR_DRIVER_PROXY_ENDPOINT_INFORMATION
 - PSTOR_DRIVER_PROXY_ENDPOINT_INFORMATION
 - storport/PSTOR_DRIVER_PROXY_ENDPOINT_INFORMATION
 - STOR_DRIVER_PROXY_ENDPOINT_INFORMATION
 - storport/STOR_DRIVER_PROXY_ENDPOINT_INFORMATION
dev_langs:
 - c++
helpviewer_keywords:
 - _STOR_DRIVER_PROXY_ENDPOINT_INFORMATION
---

## -description

The **STOR_DRIVER_PROXY_ENDPOINT_INFORMATION** structure contain information about the driver proxy endpoint callback function.

## -struct-fields

### -field Id

The ID of the driver proxy endpoint function.

### -field EndpointFunction

Pointer to the endpoint function callback.

### -field ParameterCount

The number of parameters to the *EndPointFunction*.

## -remarks

## -see-also
