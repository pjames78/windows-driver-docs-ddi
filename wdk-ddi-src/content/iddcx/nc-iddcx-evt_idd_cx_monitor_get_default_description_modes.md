---
UID: NC:iddcx.EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES
title: EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES (iddcx.h)
description: EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES is called by the OS to request the default monitor mode list from the driver for the specified monitor when a monitor without a description is connected.
old-location: display\evt_idd_cx_monitor_get_default_description_modes.htm
tech.root: display
ms.date: 05/10/2018
keywords: ["EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES callback function"]
ms.keywords: EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES, EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES callback, EvtIddCxMonitorGetDefaultDescriptionModes, EvtIddCxMonitorGetDefaultDescriptionModes callback function [Display Devices], PFN_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES, PFN_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES callback function pointer [Display Devices], display.evt_idd_cx_monitor_get_default_description_modes, iddcx/EvtIddCxMonitorGetDefaultDescriptionModes
req.header: iddcx.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10
req.target-min-winversvr: Windows Server 2016
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
req.irql: _requires_same_
targetos: Windows
req.typenames: 
f1_keywords:
 - EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES
 - iddcx/EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - UserDefined
api_location:
 - iddcx.h
api_name:
 - EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES
---

# EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES callback function


## -description

<b>EVT_IDD_CX_MONITOR_GET_DEFAULT_DESCRIPTION_MODES</b> is called by the OS to request the default monitor mode list from the driver for the specified monitor when a monitor without a description is connected.

## -parameters

### -param MonitorObject


[in] A handle by the OS to identify the monitor that requires a generated list of default modes.

### -param pInArgs


[in] A pointer to a [IDARG_IN_GETDEFAULTDESCRIPTIONMODES](ns-iddcx-idarg_in_getdefaultdescriptionmodes.md) structure to be used by the driver.

### -param pOutArgs


[out] A pointer to a [IDARG_OUT_GETDEFAULTDESCRIPTIONMODES](ns-iddcx-idarg_out_getdefaultdescriptionmodes.md) structure for the driver to fill.

## -returns

(NTSTATUS) If the operation is successful, the callback function must return STATUS_SUCCESS, or another status value for which NT_SUCCESS(status) equals TRUE. Otherwise, an appropriate <a href="/windows-hardware/drivers/kernel/ntstatus-values">NTSTATUS</a> error code.

## -remarks

The driver must create at least one monitor mode for the monitor description.

