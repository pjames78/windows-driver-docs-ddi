---
UID: NF:ntddk.WheaGetErrorSourceInfo
tech.root: kernel
title: WheaGetErrorSourceInfo (ntddk.h)
ms.date: 02/16/2023
targetos: Windows
description: This topic describes the WheaGetErrorSourceInfo function.
prerelease: false
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: ntddk.h
req.idl: 
req.include-header: Ntddk.h
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
 - ntddk.h
api_name:
 - WheaGetErrorSourceInfo
f1_keywords:
 - WheaGetErrorSourceInfo
 - ntddk/WheaGetErrorSourceInfo
dev_langs:
 - c++
helpviewer_keywords:
 - WheaGetErrorSourceInfo
---

## -description

This topic describes the **WheaGetErrorSourceInfo** function.

## -parameters

### -param SourceType

Defines the **WHEA_ERROR_SOURCE_TYPE** parameter *ULONG*.

### -param ErrorCount

Defines the **PULONG** parameter *ErrorCount*.

### -param SourceInfo

Defines the **PERROR_SOURCE_INFO** parameter *SourceInfo*.

### -param PoolTag

Defines the **ULONG** parameter *PoolTag*.

## -returns

Returns a **NTSTATUS** value.

## -remarks

## -see-also
