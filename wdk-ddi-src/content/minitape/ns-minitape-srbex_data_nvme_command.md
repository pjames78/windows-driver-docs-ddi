---
UID: NS:minitape._SRBEX_DATA_NVME_COMMAND
tech.root: storage
title: SRBEX_DATA_NVME_COMMAND (minitape.h)
ms.date: 05/20/2022
targetos: Windows
description: The SRBEX_DATA_NVME_COMMAND (minitape.h) structure enables the user to frame and issue a command in NVMe format.
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: minitape.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt:
req.target-min-winversvr: Windows Server 2022
req.target-type: 
req.typenames: SRBEX_DATA_NVME_COMMAND, *PSRBEX_DATA_NVME_COMMAND
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - minitape.h
api_name:
 - _SRBEX_DATA_NVME_COMMAND
 - PSRBEX_DATA_NVME_COMMAND
 - SRBEX_DATA_NVME_COMMAND
f1_keywords:
 - _SRBEX_DATA_NVME_COMMAND
 - minitape/_SRBEX_DATA_NVME_COMMAND
 - PSRBEX_DATA_NVME_COMMAND
 - minitape/PSRBEX_DATA_NVME_COMMAND
 - SRBEX_DATA_NVME_COMMAND
 - minitape/SRBEX_DATA_NVME_COMMAND
dev_langs:
 - c++
---

## -description

See [**SRBEX_DATA_NVME_COMMAND** (*srb.h*)](../srb/ns-srb-srbex_data_nvme_command.md).

## -struct-fields

### -field Type

### -field Length

### -field ControllerHandle

### -field Reserved0

### -field CommandDWORD0

### -field CommandNSID

### -field Reserved1[2]

### -field CommandMPTR

### -field CommandPRP1

### -field CommandPRP2

### -field CommandSGL1[2]

### -field CommandCDW10

### -field CommandCDW11

### -field CommandCDW12

### -field CommandCDW13

### -field CommandCDW14

### -field CommandCDW15

### -field FabricsCommand

### -field FabricsCommand.OPC

### -field FabricsCommand.PSDT

### -field FabricsCommand.CID

### -field FabricsCommand.FCTYPE

### -field FabricsCommand.Reserved[35]

### -field FabricsCommand.Specific[24]

### -field Command

### -field Command.OPC

### -field Command.FUSE

### -field Command.Reserved

### -field Command.PSDT

### -field Command.CID

### -field Command.TypeSpecific[60]

### -field CommandType

### -field Reserved2

### -field CommandFlags

### -field ResponseFlags

### -field CommandStatus

### -field CommandStatus.DUMMYSTRUCTNAME

### -field CommandStatus.DUMMYSTRUCTNAME.P

### -field CommandStatus.DUMMYSTRUCTNAME.SC

### -field CommandStatus.DUMMYSTRUCTNAME.SCT

### -field CommandStatus.DUMMYSTRUCTNAME.CRD

### -field CommandStatus.DUMMYSTRUCTNAME.M

### -field CommandStatus.DUMMYSTRUCTNAME.DNR

### -field CommandStatus.AsUshort

### -field QID

### -field CommandTag

### -field CQEntryDW0

### -field CQEntryDW1

### -field Specific[8]

### -field SQHD

### -field SQID

## -see-also

- [**SRBEX_DATA_NVME_COMMAND** (*srb.h*)](../srb/ns-srb-srbex_data_nvme_command.md)
