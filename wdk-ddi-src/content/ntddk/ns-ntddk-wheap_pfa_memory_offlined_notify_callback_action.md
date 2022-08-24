---
UID: NS:ntddk._WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
tech.root: kernel
title: WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION (ntddk.h)
ms.date: 08/23/2022
targetos: Windows
description: Describes the WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION (ntddk.h) structure.
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
req.typenames: WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION, *PWHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ntddk.h
api_name:
 - _WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
 - PWHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
 - WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
f1_keywords:
 - _WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
 - ntddk/_WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
 - PWHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
 - ntddk/PWHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
 - WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
 - ntddk/WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
dev_langs:
 - c++
helpviewer_keywords:
 - _WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION
---

## -description

Describes the **WHEAP_PFA_MEMORY_OFFLINED_NOTIFY_CALLBACK_ACTION** structure.

## -struct-fields

### -field WheaEventLogEntry

Defines the **WHEA_EVENT_LOG_ENTRY** member **WheaEventLogEntry**.

### -field Page

Defines the **ULONG** member **Page**.

### -field ComponentTag

Defines the **ULONG** member **ComponentTag**.

### -field Status

Defines the **NTSTATUS** member **Status**.

### -field ActionTaken

Defines the **WHEA_RECOVERY_CONTEXT_ACTION_TAKEN** member **ActionTaken**.

### -field ActionTakenAdditionalInfo

Defines the **WHEA_RECOVERY_CONTEXT_ACTION_TAKEN** member **ActionTakenAdditionalInfo**.

## -remarks

## -see-also
