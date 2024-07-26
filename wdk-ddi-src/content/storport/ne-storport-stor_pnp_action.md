---
UID: NE:storport.STOR_PNP_ACTION
tech.root: storage
title: STOR_PNP_ACTION
ms.date: 07/25/2024
targetos: Windows
description: Learn more about the STOR_PNP_ACTION enumeration.
prerelease: false
req.construct-type: enumeration
req.ddi-compliance: 
req.header: storport.h
req.include-header: 
req.kmdf-ver: 
req.max-support: 
req.target-min-winverclnt: Windows 8.1
req.target-min-winversvr: 
req.target-type: 
req.typenames: 
typedef_isUnnamed: true
req.umdf-ver: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - storport.h
api_name:
 - STOR_PNP_ACTION
 - PSTOR_PNP_ACTION
f1_keywords:
 - STOR_PNP_ACTION
 - storport/STOR_PNP_ACTION
 - PSTOR_PNP_ACTION
 - storport/PSTOR_PNP_ACTION
dev_langs:
 - c++
helpviewer_keywords:
 - STOR_PNP_ACTION
---

## -description

**STOR_PNP_ACTION** enumerates possible Plug and Play (PnP) minor codes that a Storport miniport driver can receive.

## -enum-fields

### -field StorStartDevice:0x0

Sends a request to start the device.

### -field StorRemoveDevice:0x2

Sends a request to remove the device.

### -field StorStopDevice:0x4

Indicates that the device is stopping.

### -field StorQueryCapabilities:0x9

Sends a request to query the device's capabilities.

### -field StorQueryResourceRequirements:0xB

Sends a request to query the device's resource requirements.

### -field StorFilterResourceRequirements:0xD

Sends a request to filter the device's resource requirements.

### -field StorSurpriseRemoval:0x17

Indicates that the device has been removed unexpectedly.

## -remarks

## -see-also

[**SCSI_PNP_REQUEST_BLOCK**](../srb/ns-srb-_scsi_pnp_request_block.md)

[**SRBEX_DATA_PNP**](../srb/ns-srb-_srbex_data_pnp.md)
