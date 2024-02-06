---
UID: NF:prminterface.ExGetPrmInterface
tech.root: 
title: ExGetPrmInterface
ms.date: 02/05/2024
targetos: Windows
description: 
prerelease: true
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
 - HeaderDef
api_location:
 - prminterface.h
api_name:
 - ExGetPrmInterface
f1_keywords:
 - ExGetPrmInterface
 - prminterface/ExGetPrmInterface
dev_langs:
 - c++
helpviewer_keywords:
 - ExGetPrmInterface
---

## -description

This routine fills a caller-provided structure with pointers to system-supplied routines that comprise the PRM interface.

## -parameters

### -param Version [in]

A ULONG value that specifies the interface version. Set to 1 for Windows 11, version 24H2.

### -param InterfaceOut [out]

A pointer to a caller-supplied [PRM_INTERFACE](./ns-prminterface-prm_interface.md) structure which, on output, contains pointers to functions that support PRM operations.

## -returns

This method returns NTSTATUS which contains STATUS_SUCCESS if the call was successful. Otherwise, the method returns an appropriate error code.

## -remarks

## -see-also

