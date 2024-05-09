---
UID: NF:storport.StorPortNvmeIceIoComplete
tech.root: storage
title: StorPortNvmeIceIoComplete
ms.date: 03/25/2024
targetos: Windows
description: The StorPortNvmeIceIoComplete function signals the completion of a Non-Volatile Memory Express (NVMe) input/output (IO) operation that was initiated by a previous call to StorPortNvmeIceIoStart.
prerelease: true
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
 - StorPortNvmeIceIoComplete
f1_keywords:
 - StorPortNvmeIceIoComplete
 - storport/StorPortNvmeIceIoComplete
dev_langs:
 - c++
helpviewer_keywords:
 - StorPortNvmeIceIoComplete
---

## -description

The **StorPortNvmeIceIoComplete** function signals the completion of a Non-Volatile Memory Express (NVMe) input/output (IO) operation that was initiated by a previous call to **[StorPortNvmeIceIoStart](nf-storport-storportnvmeiceiostart.md)**.

## -parameters

### -param HwDeviceExtension

A pointer to the hardware device extension. This is a per HBA (Host Bus Adapter) context area provided by the miniport driver. The miniport driver can store HBA-specific information here.

### -param Srb

A pointer to a SCSI request block. This structure represents a single I/O request.

## -returns

Returns a STOR_STATUS_XXXX value as defined in storport.h. If the Windows version is earlier than Windows 11, the function returns STOR_STATUS_NOT_IMPLEMENTED.

## -remarks

## -see-also

- **[StorPortNvmeIceIoStart](nf-storport-storportnvmeiceiostart.md)**
