---
UID: NS:ntddk._DIMM_ADDR_VALID_BITS_DDR4
tech.root: kernel
title: DIMM_ADDR_VALID_BITS_DDR4 (ntddk.h)
ms.date: 02/16/2023
targetos: Windows
description: This topic describes the DIMM_ADDR_VALID_BITS_DDR4 structure.
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
req.typenames: DIMM_ADDR_VALID_BITS_DDR4, *PDIMM_ADDR_VALID_BITS_DDR4
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ntddk.h
api_name:
 - _DIMM_ADDR_VALID_BITS_DDR4
 - PDIMM_ADDR_VALID_BITS_DDR4
 - DIMM_ADDR_VALID_BITS_DDR4
f1_keywords:
 - _DIMM_ADDR_VALID_BITS_DDR4
 - ntddk/_DIMM_ADDR_VALID_BITS_DDR4
 - PDIMM_ADDR_VALID_BITS_DDR4
 - ntddk/PDIMM_ADDR_VALID_BITS_DDR4
 - DIMM_ADDR_VALID_BITS_DDR4
 - ntddk/DIMM_ADDR_VALID_BITS_DDR4
dev_langs:
 - c++
helpviewer_keywords:
 - _DIMM_ADDR_VALID_BITS_DDR4
---

## -description

This topic describes the **DIMM_ADDR_VALID_BITS_DDR4** structure.

## -struct-fields

### -field SocketId

Defines the **UINT32** member **SocketId**.

### -field MemoryControllerId

Defines the **UINT32** member **MemoryControllerId**.

### -field ChannelId

Defines the **UINT32** member **ChannelId**.

### -field DimmSlot

Defines the **UINT32** member **DimmSlot**.

### -field DimmRank

Defines the **UINT32** member **DimmRank**.

### -field Device

Defines the **UINT32** member **Device**.

### -field ChipSelect

Defines the **UINT32** member **ChipSelect**.

### -field Bank

Defines the **UINT32** member **Bank**.

### -field Dq

Defines the **UINT32** member **Dq**.

### -field Row

Defines the **UINT32** member **Row**.

### -field Column

Defines the **UINT32** member **Column**.

### -field Info

Defines the **UINT32** member **Info**.

### -field Reserved

Reserved for future use.

## -remarks

## -see-also
