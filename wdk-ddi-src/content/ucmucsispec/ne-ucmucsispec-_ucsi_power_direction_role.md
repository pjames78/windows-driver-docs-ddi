---
UID: NE:ucmucsispec._UCSI_POWER_DIRECTION_ROLE
title: _UCSI_POWER_DIRECTION_ROLE (ucmucsispec.h)
tech.root: usbref
description: Used in the SET_PDR command. The SET_PDR command is used to set the power direction dictated by the OS Policy Manager (OPM), for the current connection.
ms.date: 04/26/2024
keywords: ["UCSI_POWER_DIRECTION_ROLE enumeration"]
ms.keywords: _UCSI_POWER_DIRECTION_ROLE, UCSI_POWER_DIRECTION_ROLE,
req.header: ucmucsispec.h
req.include-header: UcmUcsiCx.h
req.target-type: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 1.27
req.umdf-ver: N/A
req.ddi-compliance: 
req.max-support: 
req.typenames: UCSI_POWER_DIRECTION_ROLE
targetos: Windows
ms.custom: RS5
f1_keywords:
 - _UCSI_POWER_DIRECTION_ROLE
 - ucmucsispec/_UCSI_POWER_DIRECTION_ROLE
 - UCSI_POWER_DIRECTION_ROLE
 - ucmucsispec/UCSI_POWER_DIRECTION_ROLE
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ucmucsispec.h
api_name:
 - _UCSI_POWER_DIRECTION_ROLE
 - UCSI_POWER_DIRECTION_ROLE
---

# _UCSI_POWER_DIRECTION_ROLE enumeration

## -description

Used in the SET_PDR command. The SET_PDR command is used to set the power direction dictated by the OS Policy Manager (OPM), for the current connection.

## -enum-fields

### -field UcsiPowerDirectionRoleProvider

The connector initiates swap to source, if not already operating as source.

### -field UcsiPowerDirectionRoleConsumer

The connector initiates swap to sink, if not already operating as sink.

### -field UcsiPowerDirectionRoleAcceptSwap

The connector accepts power swap change requests from the port partner. If this bit is cleared, the connector rejects power swap change requests from the port partner.

### -field UcsiPowerDirectionRoleProviderAcceptSwap

This field combines the *UcsiPowerDirectionRoleProvider* and *UcsiPowerDirectionRoleAcceptSwap* fields.

### -field UcsiPowerDirectionRoleConsumerAcceptSwap

This field combines the *UcsiPowerDirectionRoleConsumer* and *UcsiPowerDirectionRoleAcceptSwap* fields.

## -remarks

For more information, see section 4.5.10 in the [UCSI spec version 1.2](https://www.intel.com/content/www/us/en/products/docs/io/universal-serial-bus/usb-type-c-ucsi-spec.html).

## -see-also

- [UCSI spec version 1.2](https://www.intel.com/content/www/us/en/products/docs/io/universal-serial-bus/usb-type-c-ucsi-spec.html)
