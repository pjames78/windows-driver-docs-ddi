---
UID: NI:usbioctl.IOCTL_USB_GET_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION
tech.root: 
title: IOCTL_USB_GET_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION
ms.date: 01/26/2024
targetos: Windows
description: 
prerelease: false
req.construct-type: ioctl
req.ddi-compliance: 
req.dll: 
req.header: usbioctl.h
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - usbioctl.h
api_name:
 - IOCTL_USB_GET_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION
f1_keywords:
 - IOCTL_USB_GET_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION
 - usbioctl/IOCTL_USB_GET_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION
dev_langs:
 - c++
helpviewer_keywords:
 - IOCTL_USB_GET_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION
---

## -description

The IOCTL_USB_GET_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION request retrieves USB Port SuperSpeed-Lane information.

Client drivers must send this IOCTL at an IRQL of PASSIVE_LEVEL.

IOCTL_USB_GET_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION is a user-mode I/O control request. This request targets the USB hub device (GUID_DEVINTERFACE_USB_HUB).

## -ioctlparameters

### -ioctl-major-code

IRP_MJ_DEVICE_CONTROL

### -input-buffer

### -input-buffer-length

### -output-buffer

### -output-buffer-length

### -in-out-buffer

Both input and output buffers point to a caller-allocated USB_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION structure. On input, the ConnectionIndex member of this structure must contain a number greater than or equal to 1 that indicates the number of the port whose super-speed lane information is to be reported. The hub driver returns super-speed lane information in the remaining members of USB_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION. The IRP, the AssociatedIrp.SystemBuffer member points to the USB_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION structure.

On output, the USB_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION structure receives information about the indicated super-speed lanes from the USB hub driver.

### -inout-buffer-length

The size of a USB_NODE_CONNECTION_SUPERSPEEDPLUS_INFORMATION structure.

### -status-block

The USB stack sets Irp->IoStatus.Status to STATUS_SUCCESS if the request is successful. Otherwise, the USB stack sets Status to the appropriate error condition, such as STATUS_INVALID_PARAMETER or STATUS_INSUFFICIENT_RESOURCES.

## -remarks

## -see-also
