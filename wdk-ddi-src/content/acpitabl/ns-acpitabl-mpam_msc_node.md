---
UID: NS:acpitabl._MPAM_MSC_NODE
tech.root: acpi
title: MPAM_MSC_NODE (acpitabl.h)
ms.date: 02/09/2023
targetos: Windows
description: Describes the MPAM_MSC_NODE structure.
prerelease: false
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: acpitabl.h
req.include-header: Acpitabl.h
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: WIN11_NEXT
req.target-min-winversvr: 
req.target-type: 
req.typenames: MPAM_MSC_NODE, *PMPAM_MSC_NODE
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - acpitabl.h
api_name:
 - _MPAM_MSC_NODE
 - PMPAM_MSC_NODE
 - MPAM_MSC_NODE
f1_keywords:
 - _MPAM_MSC_NODE
 - acpitabl/_MPAM_MSC_NODE
 - PMPAM_MSC_NODE
 - acpitabl/PMPAM_MSC_NODE
 - MPAM_MSC_NODE
 - acpitabl/MPAM_MSC_NODE
dev_langs:
 - c++
helpviewer_keywords:
 - _MPAM_MSC_NODE
---

## -description

Describes the **MPAM_MSC_NODE** structure.

## -struct-fields

### -field Length

Defines the **UINT16** member **Length**.

### -field Reserved0

Reserved for future use.

### -field Identifier

Defines the **UINT32** member **Identifier**.

### -field BaseAddress

Defines the **UINT64** member **BaseAddress**.

### -field MmioSize

Defines the **UINT32** member **MmioSize**.

### -field OverflowInterrupt

Defines the **UINT32** member **OverflowInterrupt**.

### -field OverflowInterruptFlags

Defines the **UINT32** member **OverflowInterruptFlags**.

### -field Reserved1

Reserved for future use.

### -field OverflowInterruptAffinity

Defines the **UINT32** member **OverflowInterruptAffinity**.

### -field ErrorInterrupt

Defines the **UINT32** member **ErrorInterrupt**.

### -field ErrorInterruptFlags

Defines the **UINT32** member **ErrorInterruptFlags**.

### -field Reserved2

Reserved for future use.

### -field ErrorInterruptAffinity

Defines the **UINT32** member **ErrorInterruptAffinity**.

### -field MaxNrdyUsec

Defines the **UINT32** member **MaxNrdyUsec**.

### -field LinkedHardwareId

Defines the **UINT64** member **LinkedHardwareId**.

### -field LinkedInstanceId

Defines the **UINT32** member **LinkedInstanceId**.

### -field ResourceNodeCount

Defines the **UINT32** member **ResourceNodeCount**.

### -field ResourceNodes[ANYSIZE_ARRAY]

Defines the **MPAM_RESOURCE_NODE** member **ResourceNodes**.

## -remarks

## -see-also
