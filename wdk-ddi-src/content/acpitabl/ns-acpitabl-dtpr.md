---
UID: NS:acpitabl._DTPR_TABLE
tech.root: acpi
title: DTPR
ms.date: 09/14/2023
targetos: Windows
description: This topic describes the DTPR structure.
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
req.typenames: DTPR, *PDTPR
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
 - _DTPR_TABLE
 - PDTPR
 - DTPR
f1_keywords:
 - _DTPR_TABLE
 - acpitabl/_DTPR_TABLE
 - PDTPR
 - acpitabl/PDTPR
 - DTPR
 - acpitabl/DTPR
dev_langs:
 - c++
helpviewer_keywords:
 - _DTPR_TABLE
---

## -description

This topic describes the **DTPR** structure.

## -struct-fields

### -field Signature

Defines the **UINT32** member **Signature**.

### -field Length

Defines the **UINT32** member **Length**.

### -field Revision

Defines the **UINT8** member **Revision**.

### -field Checksum

Defines the **UINT8** member **Checksum**.

### -field OEMID[6]

Defines the **UINT8** member **OEMID**.

### -field OEMTableID[8]

Defines the **UINT8** member **OEMTableID**.

### -field OEMRevision

Defines the **UINT32** member **OEMRevision**.

### -field CreatorID

Defines the **UINT32** member **CreatorID**.

### -field CreatorRevision

Defines the **UINT32** member **CreatorRevision**.

### -field Flags

Defines the **UINT32** member **Flags**.

### -field TprInstanceCount

Defines the **UINT32** member **TprInstanceCount**.

### -field TprInstanceArray[ANYSIZE_ARRAY]

Defines the **TPR_INSTANCE** member **TprInstanceArray**.

## -remarks

## -see-also
