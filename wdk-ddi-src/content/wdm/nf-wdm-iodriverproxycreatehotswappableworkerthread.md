---
UID: NF:wdm.IoDriverProxyCreateHotSwappableWorkerThread
tech.root: kernel
title: IoDriverProxyCreateHotSwappableWorkerThread (wdm.h)
ms.date: 08/23/2022
targetos: Windows
description: Describes the IoDriverProxyCreateHotSwappableWorkerThread (wdm.h) function.
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
 - HeaderDef
api_location:
 - wdm.h
api_name:
 - IoDriverProxyCreateHotSwappableWorkerThread
f1_keywords:
 - IoDriverProxyCreateHotSwappableWorkerThread
 - wdm/IoDriverProxyCreateHotSwappableWorkerThread
dev_langs:
 - c++
helpviewer_keywords:
 - IoDriverProxyCreateHotSwappableWorkerThread
---

## -description

Describes the **IoDriverProxyCreateHotSwappableWorkerThread** function.

## -parameters

### -param DriverProxyExtension

Defines the **PDRIVER_PROXY_EXTENSION** parameter *DriverProxyExtension*.

### -param ThreadHandle

Defines the **PHANDLE** parameter *ThreadHandle*.

### -param DesiredAccess

Defines the **ULONG** parameter *DesiredAccess*.

### -param ObjectAttributes

Defines the **POBJECT_ATTRIBUTES** parameter *ObjectAttributes*.

### -param ProcessHandle

Defines the **HANDLE** parameter *ProcessHandle*.

### -param ClientId

Defines the **PCLIENT_ID** parameter *ClientId*.

### -param WorkerStartContext

Defines the **PDRIVER_PROXY_HOTSWAP_WORKER_ROUTINE_START_CONTEXT** parameter *WorkerStartContext*.

## -returns

Returns a **NTSTATUS** value.

## -remarks

## -see-also
