---
title: KSCATEGORY_DATATRANSFORM
description: KSCATEGORY_DATATRANSFORM
ms.assetid: 2e5ff89a-6ec4-4bdf-b935-675c2a337efb
keywords: ["KSCATEGORY_DATATRANSFORM Device and Driver Installation"]
topic_type:
- apiref
api_name:
- KSCATEGORY_DATATRANSFORM
api_location:
- Ks.h
api_type:
- HeaderDef
ms.localizationpriority: medium
ms.date: 10/17/2018
---

# KSCATEGORY_DATATRANSFORM


The KSCATEGORY_DATATRANSFORM [device interface class](https://docs.microsoft.com/windows-hardware/drivers/install/device-interface-classes) is defined for the [kernel streaming](https://docs.microsoft.com/windows-hardware/drivers/stream/streaming-minidrivers2) (KS) functional category that transforms audio data streams.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Attribute</th>
<th align="left">Setting</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>Identifier</p></td>
<td align="left"><p>KSCATEGORY_DATATRANSFORM</p></td>
</tr>
<tr class="even">
<td align="left"><p>Class GUID</p></td>
<td align="left"><p>{2EB07EA0-7E70-11D0-A5D6-28DB04C10000}</p></td>
</tr>
</tbody>
</table>

 

Remarks
-------

Drivers for KS devices register instances of KSCATEGORY_DATATRANSFORM to indicate to the operating system that the devices support the KSCATEGORY_DATATRANSFORM functional category.

For an example of how to register this functional category in an INF file, see the *Ddksynth.inf* INF file that is included with the software synthesizer sample in the *src\\audio\\ddksynth* directory of the WDK.

For more information about this functional category, see [Installing Device Interfaces for an Audio Adapter](https://docs.microsoft.com/windows-hardware/drivers/audio/installing-device-interfaces-for-an-audio-adapter), [**KSPROPERTY_TOPOLOGY_CATEGORIES**](https://docs.microsoft.com/windows-hardware/drivers/stream/ksproperty-topology-categories), and [Requirements for a GFX Filter Factory](https://docs.microsoft.com/windows-hardware/drivers/audio/requirements-for-a-gfx-filter-factory).

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><p>Header</p></td>
<td align="left">Ks.h (include Ks.h)</td>
</tr>
</tbody>
</table>

 

 





