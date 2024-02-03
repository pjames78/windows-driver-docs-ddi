---
UID: NC:prminterface.PRM_INVOKE_HANDLER
tech.root: 
title: PRM_INVOKE_HANDLER
ms.date: 
targetos: Windows
description: 
prerelease: false
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: prminterface.h
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
 - LibDef
api_location:
 - prminterface.h
api_name:
 - PRM_INVOKE_HANDLER
f1_keywords:
 - PRM_INVOKE_HANDLER
 - prminterface/PRM_INVOKE_HANDLER
dev_langs:
 - c++
helpviewer_keywords:
 - PRM_INVOKE_HANDLER
---

## -description

This routine invokes a specific PRM handler.

## -parameters

### -param HandlerGuid

Supplies the GUID of the PRM handler to invoke.

### -param ParameterBuffer

Supplies the PRM handler parameter buffer allocated by the caller. NULL if not direct call.

### -param Reserved

Supplies the reserved field used to differentiate direct and ACPI opregion originated calls.

### -param EfiStatus

Returns the EFI status from a PRM invocation.

## -returns

This method returns NTSTATUS which contains STATUS_SUCCESS if the call was successful. Otherwise, the method returns an appropriate error code.

## -remarks

PRM_INVOKE_HANDLER is not a system routine that can be called directly by name. This routine is callable only by pointer from the address returned in a [PRM_INTERFACE](./ns-prminterface-prm_interface.md) structure. Drivers obtain the address of this routine by calling [**ExGetPrmInterface**](./nf-prminterface-exgetprminterface.md).

## -see-also

