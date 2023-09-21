---
UID: NS:ntddk._WHEA_RECOVERY_CONTEXT_PAGE_INFO
tech.root: kernel
title: WHEA_RECOVERY_CONTEXT_PAGE_INFO
ms.date: 09/21/2023
targetos: Windows
description: This topic describes the WHEA_RECOVERY_CONTEXT_PAGE_INFO structure.
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
req.typenames: WHEA_RECOVERY_CONTEXT_PAGE_INFO, *PWHEA_RECOVERY_CONTEXT_PAGE_INFO
typedef_isUnnamed: false
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ntddk.h
api_name:
 - _WHEA_RECOVERY_CONTEXT_PAGE_INFO
 - PWHEA_RECOVERY_CONTEXT_PAGE_INFO
 - WHEA_RECOVERY_CONTEXT_PAGE_INFO
f1_keywords:
 - _WHEA_RECOVERY_CONTEXT_PAGE_INFO
 - ntddk/_WHEA_RECOVERY_CONTEXT_PAGE_INFO
 - PWHEA_RECOVERY_CONTEXT_PAGE_INFO
 - ntddk/PWHEA_RECOVERY_CONTEXT_PAGE_INFO
 - WHEA_RECOVERY_CONTEXT_PAGE_INFO
 - ntddk/WHEA_RECOVERY_CONTEXT_PAGE_INFO
dev_langs:
 - c++
helpviewer_keywords:
 - _WHEA_RECOVERY_CONTEXT_PAGE_INFO
---

## -description

This topic describes the **WHEA_RECOVERY_CONTEXT_PAGE_INFO** structure.

## -struct-fields

### -field ComponentTag

Defines the **ULONG** member **ComponentTag**.

### -field PageStatus

Defines the **NTSTATUS** member **PageStatus**.

### -field ActionTaken

Defines the **WHEA_RECOVERY_CONTEXT_ACTION_TAKEN** member **ActionTaken**.

### -field NotifyFlags

Defines the **WHEA_IN_USE_PAGE_NOTIFY_FLAGS** member **NotifyFlags**.

### -field ImmediateSuccess

Defines the **BOOLEAN** member **ImmediateSuccess**.

### -field Reserved

Reserved for future use.

### -field ActionTakenAdditionalInfo

Defines the **WHEA_RECOVERY_CONTEXT_ACTION_TAKEN_ADDITIONAL_INFO** member **ActionTakenAdditionalInfo**.

## -remarks

## -see-also
