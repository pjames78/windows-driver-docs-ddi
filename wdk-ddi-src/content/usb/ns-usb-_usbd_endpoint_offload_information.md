---
UID: NS:usb._USBD_ENDPOINT_OFFLOAD_INFORMATION
title: _USBD_ENDPOINT_OFFLOAD_INFORMATION (usb.h)
description: Stores xHCI-specific V2 information that is used by client drivers to transfer data to and from the offloaded endpoints.
old-location: buses\usbd_endpoint_offload_information.htm
tech.root: usbref
ms.date: 04/26/2024
keywords: ["USBD_ENDPOINT_OFFLOAD_INFORMATION structure"]
ms.keywords: "*PUSBD_ENDPOINT_OFFLOAD_INFORMATION, PUSBD_ENDPOINT_OFFLOAD_INFORMATION, PUSBD_ENDPOINT_OFFLOAD_INFORMATION structure pointer [Buses], USBD_ENDPOINT_OFFLOAD_INFORMATION, USBD_ENDPOINT_OFFLOAD_INFORMATION structure [Buses], _USBD_ENDPOINT_OFFLOAD_INFORMATION, buses.usbd_endpoint_offload_information, usb/PUSBD_ENDPOINT_OFFLOAD_INFORMATION, usb/USBD_ENDPOINT_OFFLOAD_INFORMATION"
req.header: usb.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10, version 1709
req.target-min-winversvr: Windows Server 2016
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: USBD_ENDPOINT_OFFLOAD_INFORMATION, *PUSBD_ENDPOINT_OFFLOAD_INFORMATION
f1_keywords:
 - _USBD_ENDPOINT_OFFLOAD_INFORMATION
 - usb/_USBD_ENDPOINT_OFFLOAD_INFORMATION
 - PUSBD_ENDPOINT_OFFLOAD_INFORMATION
 - usb/PUSBD_ENDPOINT_OFFLOAD_INFORMATION
 - USBD_ENDPOINT_OFFLOAD_INFORMATION
 - usb/USBD_ENDPOINT_OFFLOAD_INFORMATION
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - Usb.h
api_name:
 - _USBD_ENDPOINT_OFFLOAD_INFORMATION
 - PUSBD_ENDPOINT_OFFLOAD_INFORMATION
 - USBD_ENDPOINT_OFFLOAD_INFORMATION
---

# _USBD_ENDPOINT_OFFLOAD_INFORMATION structure

## -description

Stores xHCI-specific V2 information that is used by client drivers to transfer data to and from the offloaded endpoints.

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

### -field ClientTransferRingSegmentPAIn

The physical address of the page-aligned client transfer ring input segment.

### -field ClientTransferRingSizeIn

The size of the client transfer ring input segment.

### -field ClientDataBufferPAIn

The physical address of the page-aligned client data input buffer.

### -field ClientDataBufferSizeIn

The size of the client data input buffer.

### -field ClientDataBufferLAOut

The physical address of the client data output buffer.

### -field ClientDataBufferVAOut

Pointer to the client data output buffer.

## remarks

This structure duplicates and extends **[USBD_ENDPOINT_OFFLOAD_INFORMATION_V1](ns-usb-usbd_endpoint_offload_information_v1.md)**.

## see-also

- **[USBD_ENDPOINT_OFFLOAD_INFORMATION_V1](ns-usb-usbd_endpoint_offload_information_v1.md)**
