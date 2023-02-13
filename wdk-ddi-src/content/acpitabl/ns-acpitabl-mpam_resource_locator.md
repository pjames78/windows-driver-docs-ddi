---
UID: NS:acpitabl._MPAM_RESOURCE_LOCATOR
tech.root: acpi
title: MPAM_RESOURCE_LOCATOR (acpitabl.h)
ms.date: 02/09/2023
targetos: Windows
description: Describes the MPAM_RESOURCE_LOCATOR structure.
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
req.typenames: MPAM_RESOURCE_LOCATOR
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - acpitabl.h
api_name:
 - _MPAM_RESOURCE_LOCATOR
 - MPAM_RESOURCE_LOCATOR
f1_keywords:
 - _MPAM_RESOURCE_LOCATOR
 - acpitabl/_MPAM_RESOURCE_LOCATOR
 - MPAM_RESOURCE_LOCATOR
 - acpitabl/MPAM_RESOURCE_LOCATOR
dev_langs:
 - c++
helpviewer_keywords:
 - _MPAM_RESOURCE_LOCATOR
---

## -description

Describes the **MPAM_RESOURCE_LOCATOR** structure.

## -struct-fields

### -field Type

Defines the **UINT8** member **Type**.

### -field ProcessorCache

Defines the **ProcessorCache** structure.

### -field ProcessorCache.CacheReference

Defines the **UINT64** member **CacheReference**.

### -field ProcessorCache.Reserved0

Reserved for future use.

### -field Memory

Defines the **Memory** structure.

### -field Memory.ProximityDomain

Defines the **UINT64** member **ProximityDomain**.

### -field Memory.Reserved0

Reserved for future use.

### -field Smmu

Defines the **Smmu** structure.

### -field Smmu.SmmuInterface

Defines the **UINT64** member **SmmuInterface**.

### -field Smmu.Reserved0

Reserved for future use.

### -field MemorySideCache

Defines the **MemorySideCache** structure.

### -field MemorySideCache.Reserved0

Reserved for future use.

### -field MemorySideCache.Reference

Defines the **UINT32** member **Reference**.

### -field Acpi

Defines the **Acpi** structure.

### -field Acpi.AcpiHardwareId

Defines the **UINT64** member **AcpiHardwareId**.

### -field Acpi.AcpiUniqueId

Defines the **UINT32** member **AcpiUniqueId**.

### -field Interconnect

Defines the **Interconnect** structure.

### -field Interconnect.DescriptorTableOffset

Defines the **UINT64** member **DescriptorTableOffset**.

### -field Locator[MPAM_LOCATOR_SIZE]

Defines the **UINT8** member **Locator**.

## -remarks

## -see-also
