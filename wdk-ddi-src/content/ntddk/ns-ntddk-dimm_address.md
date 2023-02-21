---
UID: NS:ntddk._DIMM_ADDRESS
tech.root: kernel
title: DIMM_ADDRESS (ntddk.h)
ms.date: 02/16/2023
targetos: Windows
description: This topic describes the DIMM_ADDRESS union.
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
req.typenames: DIMM_ADDRESS, *PDIMM_ADDRESS
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ntddk.h
api_name:
 - _DIMM_ADDRESS
 - PDIMM_ADDRESS
 - DIMM_ADDRESS
f1_keywords:
 - _DIMM_ADDRESS
 - ntddk/_DIMM_ADDRESS
 - PDIMM_ADDRESS
 - ntddk/PDIMM_ADDRESS
 - DIMM_ADDRESS
 - ntddk/DIMM_ADDRESS
dev_langs:
 - c++
helpviewer_keywords:
 - _DIMM_ADDRESS
---

## -description

This topic describes the **DIMM_ADDRESS** union.

## -struct-fields

### -field Ddr4

Defines the **Ddr4** structure.

### -field Ddr4.SocketId

Defines the **UINT64** member **SocketId**.

### -field Ddr4.MemoryControllerId

Defines the **UINT64** member **MemoryControllerId**.

### -field Ddr4.ChannelId

Defines the **UINT64** member **ChannelId**.

### -field Ddr4.DimmSlot

Defines the **UINT64** member **DimmSlot**.

### -field Ddr4.DimmRank

Defines the **UINT64** member **DimmRank**.

### -field Ddr4.Device

Defines the **UINT64** member **Device**.

### -field Ddr4.ChipSelect

Defines the **UINT64** member **ChipSelect**.

### -field Ddr4.Bank

Defines the **UINT64** member **Bank**.

### -field Ddr4.Dq

Defines the **UINT64** member **Dq**.

### -field Ddr4.Reserved

Reserved for future use.

### -field Ddr4.Row

Defines the **UINT32** member **Row**.

### -field Ddr4.Column

Defines the **UINT32** member **Column**.

### -field Ddr4.Info

Defines the **UINT64** member **Info**.

### -field Ddr5

Defines the **Ddr4** structure.

### -field Ddr5.SocketId

Defines the **UINT64** member **SocketId**.

### -field Ddr5.MemoryControllerId

Defines the **UINT64** member **MemoryControllerId**.

### -field Ddr5.ChannelId

Defines the **UINT64** member **ChannelId**.

### -field Ddr5.SubChannelId

Defines the **UINT64** member **SubChannelId**.

### -field Ddr5.DimmSlot

Defines the **UINT64** member **DimmSlot**.

### -field Ddr5.DimmRank

Defines the **UINT64** member **DimmRank**.

### -field Ddr5.Device

Defines the **UINT64** member **Device**.

### -field Ddr5.ChipId

Defines the **UINT64** member **ChipId**.

### -field Ddr5.Bank

Defines the **UINT64** member **Bank**.

### -field Ddr5.Dq

Defines the **UINT64** member **Dq**.

### -field Ddr5.Reserved

Reserved for future use.

### -field Ddr5.Row

Defines the **UINT32** member **Row**.

### -field Ddr5.Column

Defines the **UINT32** member **Column**.

### -field Ddr5.Info

Defines the **UINT64** member **Info**.

## -remarks

## -see-also
