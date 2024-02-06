---
UID: NC:prminterface.PRM_LOCK_MODULE
tech.root: 
title: PRM_LOCK_MODULE
ms.date: 02/05/2024
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
 - PRM_LOCK_MODULE
f1_keywords:
 - PRM_LOCK_MODULE
 - prminterface/PRM_LOCK_MODULE
dev_langs:
 - c++
helpviewer_keywords:
 - PRM_LOCK_MODULE
---

## -description

This routine locks a PRM module and prevent it from being unloaded.

## -parameters

### -param HandlerGuid [in]

Supplies the GUID of the PRM handler whose module needs to be locked.

## -returns

This method returns NTSTATUS which contains STATUS_SUCCESS if the call was successful. Otherwise, the method returns an appropriate error code.

## -remarks

PRM_LOCK_MODULE is not a system routine that can be called directly by name. This routine is callable only by pointer from the address returned in a [PRM_INTERFACE](./ns-prminterface-prm_interface.md) structure. Drivers obtain the address of this routine by calling [**ExGetPrmInterface**](./nf-prminterface-exgetprminterface.md).

## -see-also

