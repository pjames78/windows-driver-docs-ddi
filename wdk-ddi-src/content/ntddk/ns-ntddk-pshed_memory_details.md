---
UID: NS:ntddk._PSHED_MEMORY_DETAILS
tech.root: kernel
title: PSHED_MEMORY_DETAILS (ntddk.h)
ms.date: 02/16/2023
targetos: Windows
description: This topic describes the PSHED_MEMORY_DETAILS structure.
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
req.typenames: PSHED_MEMORY_DETAILS, *PPSHED_MEMORY_DETAILS
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ntddk.h
api_name:
 - _PSHED_MEMORY_DETAILS
 - PPSHED_MEMORY_DETAILS
 - PSHED_MEMORY_DETAILS
f1_keywords:
 - _PSHED_MEMORY_DETAILS
 - ntddk/_PSHED_MEMORY_DETAILS
 - PPSHED_MEMORY_DETAILS
 - ntddk/PPSHED_MEMORY_DETAILS
 - PSHED_MEMORY_DETAILS
 - ntddk/PSHED_MEMORY_DETAILS
dev_langs:
 - c++
helpviewer_keywords:
 - _PSHED_MEMORY_DETAILS
---

## -description

This topic describes the **PSHED_MEMORY_DETAILS** structure.

## -struct-fields

### -field Version

Defines the **UINT16** member **Version**.

### -field Vb

Defines the **PSHED_MEMORY_DETAILS_VALID_BITS** member **Vb**.

### -field DdrVersion

Defines the **UINT16** member **DdrVersion**.

### -field IsClosedPaged

Defines the **BOOLEAN** member **IsClosedPaged**.

### -field ColsPerRow

Defines the **UINT16** member **ColsPerRow**.

### -field PagesPerRow

Defines the **UINT16** member **PagesPerRow**.

### -field SocketCnt

Defines the **UINT8** member **SocketCnt**.

### -field ChaOnSktCnt

Defines the **UINT8** member **ChaOnSktCnt**.

### -field DimmSlotCnt

Defines the **UINT8** member **DimmSlotCnt**.

### -field SubchannelCnt

Defines the **UINT8** member **SubchannelCnt**.

## -remarks

## -see-also
