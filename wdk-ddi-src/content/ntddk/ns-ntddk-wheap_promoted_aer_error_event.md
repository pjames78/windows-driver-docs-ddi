---
UID: NS:ntddk._WHEAP_PROMOTED_AER_ERROR_EVENT
tech.root: kernel
title: WHEAP_PROMOTED_AER_ERROR_EVENT
ms.date: 09/21/2023
targetos: Windows
description: This topic describes the WHEAP_PROMOTED_AER_ERROR_EVENT structure.
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
req.typenames: WHEAP_PROMOTED_AER_ERROR_EVENT, *PWHEAP_PROMOTED_AER_ERROR_EVENT
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
 - _WHEAP_PROMOTED_AER_ERROR_EVENT
 - PWHEAP_PROMOTED_AER_ERROR_EVENT
 - WHEAP_PROMOTED_AER_ERROR_EVENT
f1_keywords:
 - _WHEAP_PROMOTED_AER_ERROR_EVENT
 - ntddk/_WHEAP_PROMOTED_AER_ERROR_EVENT
 - PWHEAP_PROMOTED_AER_ERROR_EVENT
 - ntddk/PWHEAP_PROMOTED_AER_ERROR_EVENT
 - WHEAP_PROMOTED_AER_ERROR_EVENT
 - ntddk/WHEAP_PROMOTED_AER_ERROR_EVENT
dev_langs:
 - c++
helpviewer_keywords:
 - _WHEAP_PROMOTED_AER_ERROR_EVENT
---

## -description

This topic describes the **WHEAP_PROMOTED_AER_ERROR_EVENT** structure.

## -struct-fields

### -field WheaEventLogEntry

Defines the **WHEA_EVENT_LOG_ENTRY** member **WheaEventLogEntry**.

### -field ErrorSeverity

Defines the **WHEA_ERROR_SEVERITY** member **ErrorSeverity**.

### -field ErrorHandlerType

Defines the **ULONG** member **ErrorHandlerType**.

### -field ErrorSourceId

Defines the **ULONG** member **ErrorSourceId**.

### -field RootErrorCommand

Defines the **ULONG** member **RootErrorCommand**.

### -field RootErrorStatus

Defines the **ULONG** member **RootErrorStatus**.

### -field DeviceAssociationBitmap

Defines the **ULONG** member **DeviceAssociationBitmap**.

## -remarks

## -see-also
