---
UID: NS:usb._USBD_ENDPOINT_OFFLOAD_INFORMATION_V1
tech.root: usbref
title: USBD_ENDPOINT_OFFLOAD_INFORMATION_V1
ms.date: 04/26/2024
targetos: Windows
description: Stores xHCI-specific V1 information that is used by client drivers to transfer data to and from the offloaded endpoints.
prerelease: true
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: usb.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.typenames: USBD_ENDPOINT_OFFLOAD_INFORMATION_V1, *PUSBD_ENDPOINT_OFFLOAD_INFORMATION_V1
typedef_isUnnamed: false
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - usb.h
api_name:
 - _USBD_ENDPOINT_OFFLOAD_INFORMATION_V1
 - PUSBD_ENDPOINT_OFFLOAD_INFORMATION_V1
 - USBD_ENDPOINT_OFFLOAD_INFORMATION_V1
f1_keywords:
 - _USBD_ENDPOINT_OFFLOAD_INFORMATION_V1
 - usb/_USBD_ENDPOINT_OFFLOAD_INFORMATION_V1
 - PUSBD_ENDPOINT_OFFLOAD_INFORMATION_V1
 - usb/PUSBD_ENDPOINT_OFFLOAD_INFORMATION_V1
 - USBD_ENDPOINT_OFFLOAD_INFORMATION_V1
 - usb/USBD_ENDPOINT_OFFLOAD_INFORMATION_V1
dev_langs:
 - c++
helpviewer_keywords:
 - _USBD_ENDPOINT_OFFLOAD_INFORMATION_V1
---

## -description

Stores xHCI-specific V1 information that is used by client drivers to transfer data to and from the offloaded endpoints.

## -struct-fields

### -field Size

The size of this structure.

### -field EndpointAddress

Specifies the USB-defined endpoint address.

### -field ResourceId

The resource identifier.

### -field Mode

A **[USBD_ENDPOINT_OFFLOAD_MODE](ne-usb-_usbd_endpoint_offload_mode.md)** value that indicates whether endpoint offloading is handled in software or the USB device or host controller.

### -field RootHubPortNumber

The port number of the root hub.

### -field RouteString

The route string.

### -field Speed

The speed.

### -field UsbDeviceAddress

The USB device address.

### -field SlotId

The slot identifier.

### -field MultiTT

Transaction Translator (TT) hub.

### -field LSOrFSDeviceConnectedToTTHub

### -field Reserved0

Reserved.

### -field TransferSegmentLA

The transfer segment link address.

### -field TransferSegmentVA

The transfer segment virtual address.

### -field TransferRingSize

The size of the transfer ring buffer.

### -field TransferRingInitialCycleBit

### -field MessageNumber

### -field EventRingSegmentLA

The event ring segment link address.

### -field EventRingSegmentVA

The event ring segment virtual address.

### -field EventRingSize

The size of the event ring buffer.

### -field EventRingInitialCycleBit

## see-also

- **[USBD_ENDPOINT_OFFLOAD_INFORMATION](ns-usb-_usbd_endpoint_offload_information.md)**
