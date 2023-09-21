---
UID: NS:ntddk._WHEA_SEL_RAW_EVENT
tech.root: kernel
title: WHEA_SEL_RAW_EVENT
ms.date: 09/21/2023
targetos: Windows
description: This topic describes the WHEA_SEL_RAW_EVENT structure.
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
req.typenames: WHEA_SEL_RAW_EVENT, *PWHEA_SEL_RAW_EVENT
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
 - _WHEA_SEL_RAW_EVENT
 - PWHEA_SEL_RAW_EVENT
 - WHEA_SEL_RAW_EVENT
f1_keywords:
 - _WHEA_SEL_RAW_EVENT
 - ntddk/_WHEA_SEL_RAW_EVENT
 - PWHEA_SEL_RAW_EVENT
 - ntddk/PWHEA_SEL_RAW_EVENT
 - WHEA_SEL_RAW_EVENT
 - ntddk/WHEA_SEL_RAW_EVENT
dev_langs:
 - c++
helpviewer_keywords:
 - _WHEA_SEL_RAW_EVENT
---

## -description

This topic describes the **WHEA_SEL_RAW_EVENT** structure.

## -struct-fields

### -field WheaEventLogEntry

Defines the **WHEA_EVENT_LOG_ENTRY** member **WheaEventLogEntry**.

### -field Payload[MAX_SEL_RAW_EVENT_PAYLOAD_LENGTH]

Defines the **UCHAR** member **Payload**.

## -remarks

## -see-also
