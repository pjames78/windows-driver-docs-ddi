---
UID: NF:wdm.RtlIsNtDdiVersionAvailable
title: RtlIsNtDdiVersionAvailable function (wdm.h)
description: The RtlIsNtDdiVersionAvailable routine determines if a specified version of the Microsoft Windows device driver interface (DDI) is available.
old-location: kernel\rtlisntddiversionavailable.htm
tech.root: kernel
ms.date: 04/11/2022
keywords: ["RtlIsNtDdiVersionAvailable function"]
ms.keywords: RtlIsNtDdiVersionAvailable, RtlIsNtDdiVersionAvailable routine [Kernel-Mode Driver Architecture], k109_62b3efdd-6678-4e88-92cb-eaacff80bfab.xml, kernel.rtlisntddiversionavailable, wdm/RtlIsNtDdiVersionAvailable
req.header: wdm.h
req.include-header: Wdm.h, Ntddk.h, Ntifs.h
req.target-type: Universal
req.target-min-winverclnt: Available starting with Windows Vista. A compatibility library supports this routine in earlier versions of Windows (see Remarks section).
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Rtlver.lib
req.dll: 
req.irql: PASSIVE_LEVEL
targetos: Windows
req.typenames: 
f1_keywords:
 - RtlIsNtDdiVersionAvailable
 - wdm/RtlIsNtDdiVersionAvailable
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - LibDef
api_location:
 - Rtlver.lib
 - Rtlver.dll
api_name:
 - RtlIsNtDdiVersionAvailable
---

# RtlIsNtDdiVersionAvailable function


## -description

The <b>RtlIsNtDdiVersionAvailable</b> routine determines if a specified version of the Microsoft Windows device driver interface (DDI) is available.

## -parameters

### -param Version [in]


The version of the Windows DDI that is available. The following table lists the possible values for the <i>Version</i> parameter.

<table>
<tr>
<th>Constant</th>
<th>Windows version</th>
</tr>
<tr>
<td>
NTDDI_WIN10_CO

</td>
<td>
Windows 11 21H2

</td>
</tr>
<tr>
<td>
NTDDI_WIN10_VB

</td>
<td>
Windows 10 2004

</td>
</tr>
<tr>
<td>
NTDDI_WIN10_19H1

</td>
<td>
Windows 10 1903

</td>
</tr>
<tr>
<td>
NTDDI_WIN10_RS5

</td>
<td>
Windows 10 1809

</td>
</tr>
<tr>
<td>
NTDDI_WIN10_RS4

</td>
<td>
Windows 10 1803

</td>
</tr>
<tr>
<td>
NTDDI_WIN10_RS3

</td>
<td>
Windows 10 1709

</td>
</tr>
<tr>
<td>
NTDDI_WIN10_RS2

</td>
<td>
Windows 10 1703

</td>
</tr>
<tr>
<td>
NTDDI_WIN10_RS1

</td>
<td>
Windows 10 1607

</td>
</tr>
<tr>
<td>
NTDDI_WIN10_TH2

</td>
<td>
Windows 10 1511

</td>
</tr>
<tr>
<td>
NTDDI_WIN10

</td>
<td>
Windows 10 1507

</td>
</tr>
<tr>
<td>
NTDDI_WINBLUE

</td>
<td>
Windows 8.1

</td>
</tr>
<tr>
<td>
NTDDI_WIN8

</td>
<td>
Windows 8

</td>
</tr>
<tr>
<td>
NTDDI_WIN7

</td>
<td>
Windows 7

</td>
</tr>
<tr>
<td>
NTDDI_WS08

</td>
<td>
Windows Server 2008

</td>
</tr>
<tr>
<td>
NTDDI_VISTA

</td>
<td>
Windows Vista

</td>
</tr>
<tr>
<td>
NTDDI_WS03

</td>
<td>
Windows Server 2003

</td>
</tr>
<tr>
<td>
NTDDI_WINXP

</td>
<td>
Windows XP

</td>
</tr>
<tr>
<td>
NTDDI_WIN2K

</td>
<td>
Windows 2000

</td>
</tr>
</table>
 

The NTDDI_<i>XXX</i> constants are defined in the Sdkddkver.h header file.

Additional NTDDI_<i>XXX</i> constants that specify service packs are available for the <a href="/windows-hardware/drivers/ddi/wdm/nf-wdm-rtlisservicepackversioninstalled">RtlIsServicePackVersionInstalled</a> routine. Do not use these values for <b>RtlIsNtDdiVersionAvailable</b>.

## -returns

<b>RtlIsNtDdiVersionAvailable</b> returns <b>TRUE</b> if the version of the Windows operating system that is running is the same or later than the version that the <i>Version</i> parameter specifies. Otherwise, this routine returns <b>FALSE</b>.

## -remarks

The <b>RtlIsNtDdiVersionAvailable</b> routine compares the version that the <i>Version</i> parameter specifies to the version of the Windows operating system that is currently running.

Use the <a href="/windows-hardware/drivers/ddi/wdm/nf-wdm-rtlisservicepackversioninstalled">RtlIsServicePackVersionInstalled</a> routine if you want to determine whether a particular service pack is installed.

The Windows kernel implements <b>RtlIsNtDdiVersionAvailable</b> only in Windows Vista and later versions of Windows. However, a compatibility library, Rtlver.lib, implements a version of <b>RtlIsNtDdiVersionAvailable</b> that runs in Windows 2000 and later versions of Windows. For kernel-mode drivers that include the Wdm.h header file, calls to <b>RtlIsNtDdiVersionAvailable</b> go to the version of this routine that is implemented in Rtlver.lib.

For more information about <b>RtlIsNtDdiVersionAvailable</b> and <b>RtlIsServicePackVersionInstalled</b>, see <a href="/windows-hardware/drivers/gettingstarted/platforms-and-driver-versions">Writing Drivers for Different Versions of Windows</a>.

## -see-also

<a href="/windows-hardware/drivers/ddi/wdm/nf-wdm-rtlisservicepackversioninstalled">RtlIsServicePackVersionInstalled</a>
