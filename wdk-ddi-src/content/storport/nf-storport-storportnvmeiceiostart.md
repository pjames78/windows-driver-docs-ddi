---
UID: NF:storport.StorPortNvmeIceIoStart
tech.root: storage
title: StorPortNvmeIceIoStart
ms.date: 03/26/2024
targetos: Windows
description: The StorPortNvmeIceIoStart function initiates a Non-Volatile Memory Express (NVMe) input/output (IO) operation.
prerelease: false
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: storport.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - storport.h
api_name:
 - StorPortNvmeIceIoStart
f1_keywords:
 - StorPortNvmeIceIoStart
 - storport/StorPortNvmeIceIoStart
dev_langs:
 - c++
helpviewer_keywords:
 - StorPortNvmeIceIoStart
---

## -description

The **StorPortNvmeIceIoStart** function initiates a Non-Volatile Memory Express (NVMe) input/output (IO) operation.

## -parameters

### -param HwDeviceExtension

A pointer to the hardware device extension. This is a per HBA (Host Bus Adapter) context area provided by the miniport driver. The miniport driver can store HBA-specific information here.

### -param Srb

A pointer to a SCSI request block. This structure represents a single I/O request.

### -field LbaCount

The number of logical block addresses (LBAs) to be transferred.

### -param PrpCount

The number of physical region pages (PRPs) to be transferred.

### -param Prp1

A pointer to the first PRP, used in NVMe to describe the physical memory locations involved in the data transfer.

### -param Prp2

A pointer to the second PRP, used in NVMe to describe the physical memory locations involved in the data transfer.

### -param PrpList

A pointer to a list of additional PRPs.

## -returns

Returns a STOR_STATUS_XXXX value as defined in storport.h. If the Windows version is earlier than Windows 11, the function returns STOR_STATUS_NOT_IMPLEMENTED.

## -remarks

## -see-also
