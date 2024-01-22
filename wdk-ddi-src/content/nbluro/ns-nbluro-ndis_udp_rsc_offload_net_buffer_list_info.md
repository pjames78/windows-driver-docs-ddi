---
UID: NS:nbluro._NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
tech.root: netvista
title: NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
ms.date: 01/18/2024
targetos: Windows
description: NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO specifies the UDP receive segment coalescing (RSC) offload information for a NET_BUFFER_LIST structure.
prerelease: false
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: nbluro.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.typenames: NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO, *PNDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
typedef_isUnnamed: false
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - nbluro.h
api_name:
 - _NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
 - PNDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
 - NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
f1_keywords:
 - _NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
 - nbluro/_NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
 - PNDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
 - nbluro/PNDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
 - NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
 - nbluro/NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
dev_langs:
 - c++
helpviewer_keywords:
 - _NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO
---

## -description

The **NDIS_UDP_RSC_OFFLOAD_NET_BUFFER_LIST_INFO** structure specifies the UDP receive segment coalescing (RSC) offload information for a NET_BUFFER_LIST structure.

## -struct-fields

### -field Receive

A structure that contains the UDP RSC offload information.

### -field Receive.SegCount

The number of segments that were coalesced into the NET_BUFFER_LIST structure.

### -field Receive.SegSize

The size, in bytes, of the segments that were coalesced into the NET_BUFFER_LIST structure.

### -field Value

A PVOID version of the UDP RSC information. Miniport drivers can use this member to access the raw information instead of the specific fields.

## -remarks

## -see-also

