---
UID: NS:ntddk._WHEAP_ROW_OFFLINE_EVENT
tech.root: kernel
title: WHEAP_ROW_OFFLINE_EVENT (ntddk.h)
ms.date: 02/16/2023
targetos: Windows
description: This topic describes the WHEAP_ROW_OFFLINE_EVENT structure.
prerelease: false
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: ntddk.h
req.include-header: Ntddk.h
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: WIN11_NEXT
req.target-min-winversvr: 
req.target-type: 
req.typenames: WHEAP_ROW_OFFLINE_EVENT, *PWHEAP_ROW_OFFLINE_EVENT
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ntddk.h
api_name:
 - _WHEAP_ROW_OFFLINE_EVENT
 - PWHEAP_ROW_OFFLINE_EVENT
 - WHEAP_ROW_OFFLINE_EVENT
f1_keywords:
 - _WHEAP_ROW_OFFLINE_EVENT
 - ntddk/_WHEAP_ROW_OFFLINE_EVENT
 - PWHEAP_ROW_OFFLINE_EVENT
 - ntddk/PWHEAP_ROW_OFFLINE_EVENT
 - WHEAP_ROW_OFFLINE_EVENT
 - ntddk/WHEAP_ROW_OFFLINE_EVENT
dev_langs:
 - c++
helpviewer_keywords:
 - _WHEAP_ROW_OFFLINE_EVENT
---

## -description

This topic describes the **WHEAP_ROW_OFFLINE_EVENT** structure.

## -struct-fields

### -field WheaEventLogEntry

Defines the **WHEA_EVENT_LOG_ENTRY** member **WheaEventLogEntry**.

### -field FirstPage

Defines the **PFN_NUMBER** member **FirstPage**.

### -field LastPage

Defines the **PFN_NUMBER** member **LastPage**.

### -field Range

Defines the **UINT32** member **Range**.

### -field Status

Defines the **NTSTATUS** member **Status**.

### -field ErrorReason

Defines the **WHEA_OFFLINE_ERRS** member **ErrorReason**.

## -remarks

## -see-also
