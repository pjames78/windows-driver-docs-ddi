---
UID: NS:acpitabl._ASPT_ENTRY
tech.root: acpi
title: ASPT_ENTRY (acpitabl.h)
ms.date: 02/13/2023
targetos: Windows
description: This topic describes the ASPT_ENTRY union used by the AMD Secure Processor Table (ASPT).
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
req.target-type: Windows
req.typenames: ASPT_ENTRY, *PASPT_ENTRY
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - acpitabl.h
api_name:
 - _ASPT_ENTRY
 - PASPT_ENTRY
 - ASPT_ENTRY
f1_keywords:
 - _ASPT_ENTRY
 - acpitabl/_ASPT_ENTRY
 - PASPT_ENTRY
 - acpitabl/PASPT_ENTRY
 - ASPT_ENTRY
 - acpitabl/ASPT_ENTRY
dev_langs:
 - c++
helpviewer_keywords:
 - _ASPT_ENTRY
---

## -description

This topic describes the **ASPT_ENTRY** union used by the AMD Secure Processor Table (ASPT).

## -struct-fields

### -field Header

Defines the **ASPT_ENTRY_HEADER** member **Header**.

### -field AspGlobalRegistersV1

Defines the **ASPT_ENTRY_ASP_GLOBAL_REGISTERS_V1** member **AspGlobalRegistersV1**.

### -field SevMailboxRegistersV1

Defines the **ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V1** member **SevMailboxRegistersV1**.

### -field AcpiMailboxRegistersV1

Defines the **ASPT_ENTRY_ACPI_MAILBOX_REGISTERS_V1** member **AcpiMailboxRegistersV1**.

### -field AspGlobalRegistersV2

Defines the **ASPT_ENTRY_ASP_GLOBAL_REGISTERS_V2** member **AspGlobalRegistersV2**.

### -field SevMailboxRegistersV2

Defines the **ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2** member **SevMailboxRegistersV2**.

### -field AcpiMailboxRegistersV2

Defines the **ASPT_ENTRY_ACPI_MAILBOX_REGISTERS_V2** member **AcpiMailboxRegistersV2**.

## -remarks

## -see-also
