---
UID: NS:ntddk._WHEA_MEMORY_HARDWARE_ADDRESS_INTEL
tech.root: kernel
title: WHEA_MEMORY_HARDWARE_ADDRESS_INTEL (ntddk.h)
ms.date: 02/16/2023
targetos: Windows
description: This topic describes the WHEA_MEMORY_HARDWARE_ADDRESS_INTEL structure.
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
req.typenames: WHEA_MEMORY_HARDWARE_ADDRESS_INTEL, *PWHEA_MEMORY_HARDWARE_ADDRESS_INTEL
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ntddk.h
api_name:
 - _WHEA_MEMORY_HARDWARE_ADDRESS_INTEL
 - PWHEA_MEMORY_HARDWARE_ADDRESS_INTEL
 - WHEA_MEMORY_HARDWARE_ADDRESS_INTEL
f1_keywords:
 - _WHEA_MEMORY_HARDWARE_ADDRESS_INTEL
 - ntddk/_WHEA_MEMORY_HARDWARE_ADDRESS_INTEL
 - PWHEA_MEMORY_HARDWARE_ADDRESS_INTEL
 - ntddk/PWHEA_MEMORY_HARDWARE_ADDRESS_INTEL
 - WHEA_MEMORY_HARDWARE_ADDRESS_INTEL
 - ntddk/WHEA_MEMORY_HARDWARE_ADDRESS_INTEL
dev_langs:
 - c++
helpviewer_keywords:
 - _WHEA_MEMORY_HARDWARE_ADDRESS_INTEL
---

## -description

This topic describes the **WHEA_MEMORY_HARDWARE_ADDRESS_INTEL** structure.

## -struct-fields

### -field MemDef

Defines the **WHEA_MEMORY_DEFINITION** member **MemDef**.

### -field SystemAddress

Defines the **UINT64** member **SystemAddress**.

### -field SpareSystemAddress

Defines the **UINT64** member **SpareSystemAddress**.

### -field DevicePhysicalAddress

Defines the **UINT64** member **DevicePhysicalAddress**.

### -field ChannelAddress

Defines the **UINT64** member **ChannelAddress**.

### -field RankAddress

Defines the **UINT64** member **RankAddress**.

### -field ProcessorSocketId

Defines the **UINT8** member **ProcessorSocketId**.

### -field MemoryControllerId

Defines the **UINT8** member **MemoryControllerId**.

### -field TargetId

Defines the **UINT8** member **TargetId**.

### -field LogicalChannelId

Defines the **UINT8** member **LogicalChannelId**.

### -field ChannelId

Defines the **UINT8** member **ChannelId**.

### -field SubChannelId

Defines the **UINT8** member **SubChannelId**.

### -field PhysicalRankId

Defines the **UINT8** member **PhysicalRankId**.

### -field DimmSlotId

Defines the **UINT8** member **DimmSlotId**.

### -field DimmRankId

Defines the **UINT8** member **DimmRankId**.

### -field Bank

Defines the **UINT8** member **Bank**.

### -field BankGroup

Defines the **UINT8** member **BankGroup**.

### -field Row

Defines the **UINT32** member **Row**.

### -field Column

Defines the **UINT32** member **Column**.

### -field LockStepRank

Defines the **UINT8** member **LockStepRank**.

### -field LockStepPhysicalRank

Defines the **UINT8** member **LockStepPhysicalRank**.

### -field LockStepBank

Defines the **UINT8** member **LockStepBank**.

### -field LockStepBankGroup

Defines the **UINT8** member **LockStepBankGroup**.

### -field ChipSelect

Defines the **UINT8** member **ChipSelect**.

### -field Node

Defines the **UINT8** member **Node**.

### -field ChipId

Defines the **UINT8** member **ChipId**.

### -field Reserved[40]

Reserved for future use.

## -remarks

## -see-also
