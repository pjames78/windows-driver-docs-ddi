---
UID: NS:acpitabl._IORT_RMR_NODE
tech.root: acpi
title: IORT_RMR_NODE
ms.date: 09/14/2023
targetos: Windows
description: This topic describes the IORT_RMR_NODE structure.
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
req.typenames: IORT_RMR_NODE, *PIORT_RMR_NODE
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
 - _IORT_RMR_NODE
 - PIORT_RMR_NODE
 - IORT_RMR_NODE
f1_keywords:
 - _IORT_RMR_NODE
 - acpitabl/_IORT_RMR_NODE
 - PIORT_RMR_NODE
 - acpitabl/PIORT_RMR_NODE
 - IORT_RMR_NODE
 - acpitabl/IORT_RMR_NODE
dev_langs:
 - c++
helpviewer_keywords:
 - _IORT_RMR_NODE
---

## -description

This topic describes the **IORT_RMR_NODE** structure.

## -struct-fields

### -field Header

### -field Flags

Defines the **Flags** union.

### -field Flags.AsULONG

Defines the **ULONG** member **AsULONG**.

### -field Flags.DUMMYSTRUCTNAME

Defines the **DUMMYSTRUCTNAME** structure.

### -field Flags.DUMMYSTRUCTNAME.RemappingPermited

Defines the **ULONG** member **RemappingPermited**.

### -field Flags.DUMMYSTRUCTNAME.AccessPrivileged

Defines the **ULONG** member **AccessPrivileged**.

### -field Flags.DUMMYSTRUCTNAME.AccessAttributes

Defines the **AccessAttributes** union.

### -field Flags.DUMMYSTRUCTNAME.AccessAttributes.AsUCHAR

Defines the **UCHAR** member **AsUCHAR**.

### -field Flags.DUMMYSTRUCTNAME.AccessAttributes.DUMMYSTRUCTNAME

Defines the **DUMMYSTRUCTNAME** structure.

### -field Flags.DUMMYSTRUCTNAME.AccessAttributes.DUMMYSTRUCTNAME.DevicenGnRnE

Defines the **UCHAR** member **DevicenGnRnE**.

### -field Flags.DUMMYSTRUCTNAME.AccessAttributes.DUMMYSTRUCTNAME.DevicenGnRE

Defines the **UCHAR** member **DevicenGnRE**.

### -field Flags.DUMMYSTRUCTNAME.AccessAttributes.DUMMYSTRUCTNAME.DevicenGRE

Defines the **UCHAR** member **DevicenGRE**.

### -field Flags.DUMMYSTRUCTNAME.AccessAttributes.DUMMYSTRUCTNAME.DeviceGRE

Defines the **UCHAR** member **DeviceGRE**.

### -field Flags.DUMMYSTRUCTNAME.AccessAttributes.DUMMYSTRUCTNAME.InnerCacheOuterNoncache

Defines the **UCHAR** member **InnerCacheOuterNoncache**.

### -field Flags.DUMMYSTRUCTNAME.AccessAttributes.DUMMYSTRUCTNAME.InnerWriteBackOuterWriteBack

Defines the **UCHAR** member **InnerWriteBackOuterWriteBack**.

### -field Flags.DUMMYSTRUCTNAME.AccessAttributes.DUMMYSTRUCTNAME.Reserved

Reserved for future use.

### -field Flags.DUMMYSTRUCTNAME.Reserved

Reserved for future use.

### -field MemoryRangeDescriptorsCount

Defines the **ULONG** member **MemoryRangeDescriptorsCount**.

### -field MemoryRangeArrayOffset

Defines the **ULONG** member **MemoryRangeArrayOffset**.

## -remarks

## -see-also
