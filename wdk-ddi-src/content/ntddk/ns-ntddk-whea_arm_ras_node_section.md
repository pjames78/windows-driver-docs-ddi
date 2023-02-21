---
UID: NS:ntddk._WHEA_ARM_RAS_NODE_SECTION
tech.root: kernel
title: WHEA_ARM_RAS_NODE_SECTION (ntddk.h)
ms.date: 02/16/2023
targetos: Windows
description: This topic describes the WHEA_ARM_RAS_NODE_SECTION structure.
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
req.typenames: WHEA_ARM_RAS_NODE_SECTION, *PWHEA_ARM_RAS_NODE_SECTION
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ntddk.h
api_name:
 - _WHEA_ARM_RAS_NODE_SECTION
 - PWHEA_ARM_RAS_NODE_SECTION
 - WHEA_ARM_RAS_NODE_SECTION
f1_keywords:
 - _WHEA_ARM_RAS_NODE_SECTION
 - ntddk/_WHEA_ARM_RAS_NODE_SECTION
 - PWHEA_ARM_RAS_NODE_SECTION
 - ntddk/PWHEA_ARM_RAS_NODE_SECTION
 - WHEA_ARM_RAS_NODE_SECTION
 - ntddk/WHEA_ARM_RAS_NODE_SECTION
dev_langs:
 - c++
helpviewer_keywords:
 - _WHEA_ARM_RAS_NODE_SECTION
---

## -description

This topic describes the **WHEA_ARM_RAS_NODE_SECTION** structure.

## -struct-fields

### -field NodeFieldCount

Defines the **UINT32** member **NodeFieldCount**.

### -field NodeIndex

Defines the **UINT32** member **NodeIndex**.

### -field InterfaceType

Defines the **UINT8** member **InterfaceType**.

### -field Reserved[7]

Reserved for future use.

### -field ErrFr

Defines the **UINT64** member **ErrFr**.

### -field ErrCtlr

Defines the **UINT64** member **ErrCtlr**.

### -field ErrStatus

Defines the **UINT64** member **ErrStatus**.

### -field ErrAddr

Defines the **UINT64** member **ErrAddr**.

### -field ErrMisc0

Defines the **UINT64** member **ErrMisc0**.

### -field ErrMisc1

Defines the **UINT64** member **ErrMisc1**.

### -field ErrMisc2

Defines the **UINT64** member **ErrMisc2**.

### -field ErrMisc3

Defines the **UINT64** member **ErrMisc3**.

## -remarks

## -see-also
