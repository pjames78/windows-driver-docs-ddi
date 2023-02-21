---
UID: NS:ntddk._WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
tech.root: kernel
title: WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL (ntddk.h)
ms.date: 02/16/2023
targetos: Windows
description: This topic describes the WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL structure.
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
req.typenames: WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL, *PWHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ntddk.h
api_name:
 - _WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
 - PWHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
 - WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
f1_keywords:
 - _WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
 - ntddk/_WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
 - PWHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
 - ntddk/PWHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
 - WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
 - ntddk/WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
dev_langs:
 - c++
helpviewer_keywords:
 - _WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL
---

## -description

This topic describes the **WHEA_PRM_ADDRESS_TRANSLATION_BUFFER_INTEL** structure.

## -struct-fields

### -field SwSmi

Defines the **UINT32** member **SwSmi**.

### -field Command

Defines the **UINT32** member **Command**.

### -field Status

Defines the **UINT32** member **Status**.

### -field SystemAddress

Defines the **UINT64** member **SystemAddress**.

### -field NmSystemAddress

Defines the **UINT64** member **NmSystemAddress**.

### -field SpareSystemAddress

Defines the **UINT64** member **SpareSystemAddress**.

### -field DevicePhysicalAddress

Defines the **UINT64** member **DevicePhysicalAddress**.

### -field ProcessorSocketId

Defines the **UINT64** member **ProcessorSocketId**.

### -field MemoryControllerId

Defines the **UINT64** member **MemoryControllerId**.

### -field NmMemoryControllerId

Defines the **UINT64** member **NmMemoryControllerId**.

### -field TargetId

Defines the **UINT64** member **TargetId**.

### -field LogicalChannelId

Defines the **UINT64** member **LogicalChannelId**.

### -field ChannelAddress

Defines the **UINT64** member **ChannelAddress**.

### -field NmChannelAddress

Defines the **UINT64** member **NmChannelAddress**.

### -field ChannelId

Defines the **UINT64** member **ChannelId**.

### -field NmChannelId

Defines the **UINT64** member **NmChannelId**.

### -field RankAddress

Defines the **UINT64** member **RankAddress**.

### -field NmRankAddress

Defines the **UINT64** member **NmRankAddress**.

### -field PhysicalRankId

Defines the **UINT64** member **PhysicalRankId**.

### -field NmPhysicalRankId

Defines the **UINT64** member **NmPhysicalRankId**.

### -field DimmSlotId

Defines the **UINT64** member **DimmSlotId**.

### -field NmDimmSlotId

Defines the **UINT64** member **NmDimmSlotId**.

### -field DimmRankId

Defines the **UINT64** member **DimmRankId**.

### -field Row

Defines the **UINT64** member **Row**.

### -field NmRow

Defines the **UINT64** member **NmRow**.

### -field Column

Defines the **UINT64** member **Column**.

### -field NmColumn

Defines the **UINT64** member **NmColumn**.

### -field Bank

Defines the **UINT64** member **Bank**.

### -field NmBank

Defines the **UINT64** member **NmBank**.

### -field BankGroup

Defines the **UINT64** member **BankGroup**.

### -field NmBankGroup

Defines the **UINT64** member **NmBankGroup**.

### -field LockStepRank

Defines the **UINT64** member **LockStepRank**.

### -field LockStepPhysicalRank

Defines the **UINT64** member **LockStepPhysicalRank**.

### -field LockStepBank

Defines the **UINT64** member **LockStepBank**.

### -field LockStepBankGroup

Defines the **UINT64** member **LockStepBankGroup**.

### -field ChipSelect

Defines the **UINT64** member **ChipSelect**.

### -field NmChipSelect

Defines the **UINT64** member ****.

### -field Node

Defines the **UINT64** member **NmChipSelect**.

### -field ChipId

Defines the **UINT64** member **ChipId**.

### -field NmChipId

Defines the **UINT64** member **NmChipId**.

## -remarks

## -see-also
