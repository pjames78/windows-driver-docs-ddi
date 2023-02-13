---
UID: NS:acpitabl._ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
tech.root: acpi
title: ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2 (acpitabl.h)
ms.date: 02/09/2023
targetos: Windows
description: Describes the ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2 structure.
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
req.typenames: ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2, *PASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - acpitabl.h
api_name:
 - _ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
 - PASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
 - ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
f1_keywords:
 - _ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
 - acpitabl/_ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
 - PASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
 - acpitabl/PASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
 - ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
 - acpitabl/ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
dev_langs:
 - c++
helpviewer_keywords:
 - _ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2
---

## -description

Describes the **ASPT_ENTRY_SEV_MAILBOX_REGISTERS_V2** structure.

## -struct-fields

### -field Header

Defines the **ASPT_ENTRY_HEADER** member **Header**.

### -field MailboxInterruptId

Defines the **UINT8** member **MailboxInterruptId**.

### -field Reserved[3]

Reserved for future use.

### -field CmdRespRegisterOffset

Defines the **UINT32** member **CmdRespRegisterOffset**.

### -field CmdBufAddrLoRegisterOffset

Defines the **UINT32** member **CmdBufAddrLoRegisterOffset**.

### -field CmdBufAddrHiRegisterOffset

Defines the **UINT32** member **CmdBufAddrHiRegisterOffset**.

## -remarks

## -see-also
