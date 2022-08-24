---
UID: NF:wdm.IoRegisterDriverProxyEndpoints
tech.root: 
title: IoRegisterDriverProxyEndpoints (wdm.h)
ms.date: 08/23/2022
targetos: Windows
description: Describes the IoRegisterDriverProxyEndpoints (wdm.h) function.
prerelease: false
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: kernel
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
 - HeaderDef
api_location:
 - wdm.h
api_name:
 - IoRegisterDriverProxyEndpoints
f1_keywords:
 - IoRegisterDriverProxyEndpoints
 - wdm/IoRegisterDriverProxyEndpoints
dev_langs:
 - c++
helpviewer_keywords:
 - IoRegisterDriverProxyEndpoints
---

## -description

Describes the **IoRegisterDriverProxyEndpoints** function.

## -parameters

### -param DriverProxyExtension

Defines the **PDRIVER_PROXY_EXTENSION** parameter *DriverProxyExtension*.

### -param EndpointInfo

Defines the **PDRIVER_PROXY_ENDPOINT_INFORMATION** parameter *EndpointInfo*.

### -param Count

Defines the **ULONG** parameter *Count*.

### -param PhasedCallback

Defines the **PDRIVER_PROXY_REGISTER_CALLBACK** parameter *PhasedCallback*.

### -param Context

Defines the **PVOID** parameter *Context*.

## -returns

Returns a **NTSTATUS** value.

## -remarks

## -see-also
