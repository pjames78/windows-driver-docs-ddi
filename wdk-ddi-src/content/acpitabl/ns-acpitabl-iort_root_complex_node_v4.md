---
UID: NS:acpitabl._IORT_ROOT_COMPLEX_NODE_V4
tech.root: acpi
title: IORT_ROOT_COMPLEX_NODE_V4
ms.date: 09/14/2023
targetos: Windows
description: This topic describes the IORT_ROOT_COMPLEX_NODE_V4 structure.
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
req.typenames: IORT_ROOT_COMPLEX_NODE_V4, *PIORT_ROOT_COMPLEX_NODE_V4
typedef_isUnnamed: false
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - acpitabl.h
api_name:
 - _IORT_ROOT_COMPLEX_NODE_V4
 - PIORT_ROOT_COMPLEX_NODE_V4
 - IORT_ROOT_COMPLEX_NODE_V4
f1_keywords:
 - _IORT_ROOT_COMPLEX_NODE_V4
 - acpitabl/_IORT_ROOT_COMPLEX_NODE_V4
 - PIORT_ROOT_COMPLEX_NODE_V4
 - acpitabl/PIORT_ROOT_COMPLEX_NODE_V4
 - IORT_ROOT_COMPLEX_NODE_V4
 - acpitabl/IORT_ROOT_COMPLEX_NODE_V4
dev_langs:
 - c++
helpviewer_keywords:
 - _IORT_ROOT_COMPLEX_NODE_V4
---

## -description

This topic describes the **IORT_ROOT_COMPLEX_NODE_V4** structure.

## -struct-fields

### -field Header

Defines the **IORT_NODE_HEADER** member **Header**.

### -field MemoryProperties

Defines the **IORT_NODE_MEMORY_ATTRIBUTES** member **MemoryProperties**.

### -field AtsAttribute

Defines the **ULONG** member **AtsAttribute**.

### -field PciSegmentNumber

Defines the **ULONG** member **PciSegmentNumber**.

### -field MemoryAddressWidthLimit

Defines the **UCHAR** member **MemoryAddressWidthLimit**.

### -field PasidCapabilities

Defines the **USHORT** member **PasidCapabilities**.

### -field Reserved

Reserved for future use.

### -field Flags

Defines the **Flags** union.

### -field Flags.AsULONG

Defines the **ULONG** member **AsULONG**.

### -field Flags.DUMMYSTRUCTNAME

Defines the **DUMMYSTRUCTNAME** structure.

### -field Flags.DUMMYSTRUCTNAME.PasidSupported

Defines the **ULONG** member **PasidSupported**.

### -field Flags.DUMMYSTRUCTNAME.Reserved

Reserved for future use.

## -remarks

## -see-also
