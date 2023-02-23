---
UID: NF:wdm.ZwCopyFileChunk
tech.root: kernel
title: ZwCopyFileChunk (wdm.h)
ms.date: 02/22/2023
targetos: Windows
description: This topic describes the ZwCopyFileChunk function.
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
 - ZwCopyFileChunk
f1_keywords:
 - ZwCopyFileChunk
 - wdm/ZwCopyFileChunk
dev_langs:
 - c++
helpviewer_keywords:
 - ZwCopyFileChunk
---

## -description

This topic describes the **ZwCopyFileChunk** function.

## -parameters

### -param SourceHandle

Defines the **HANDLE** parameter *SourceHandle*.

### -param DestHandle

Defines the **HANDLE** parameter *DestHandle*.

### -param Event

Defines the **HANDLE** parameter *Event*.

### -param IoStatusBlock

Defines the **PIO_STATUS_BLOCK** parameter *IoStatusBlock*.

### -param Length

Defines the **ULONG** parameter *Length*.

### -param SourceOffset

Defines the **PLARGE_INTEGER** parameter *SourceOffset*.

### -param DestOffset

Defines the **PLARGE_INTEGER** parameter *DestOffset*.

### -param SourceKey

Defines the **PULONG** parameter *SourceKey*.

### -param DestKey

Defines the **PULONG** parameter *DestKey*.

### -param Flags

Defines the **ULONG** parameter *Flags*.

## -returns

Returns a **NTSTATUS** value.

## -remarks

## -see-also
