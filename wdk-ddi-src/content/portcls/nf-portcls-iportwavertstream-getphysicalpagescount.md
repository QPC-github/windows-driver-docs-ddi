---
UID: NF:portcls.IPortWaveRTStream.GetPhysicalPagesCount
title: IPortWaveRTStream::GetPhysicalPagesCount (portcls.h)
description: The GetPhysicalPagesCount method returns the count of the physical pages in a memory descriptor list (MDL).
old-location: audio\iportwavertstream_getphysicalpagescount.htm
tech.root: audio
ms.date: 05/08/2018
keywords: ["IPortWaveRTStream::GetPhysicalPagesCount"]
ms.keywords: GetPhysicalPagesCount, GetPhysicalPagesCount method [Audio Devices], GetPhysicalPagesCount method [Audio Devices],IPortWaveRTStream interface, IPortWaveRTStream interface [Audio Devices],GetPhysicalPagesCount method, IPortWaveRTStream.GetPhysicalPagesCount, IPortWaveRTStream::GetPhysicalPagesCount, audio.iportwavertstream_getphysicalpagescount, audmp-routines_bdc74102-0337-436b-b3ac-68187fb323a4.xml, portcls/IPortWaveRTStream::GetPhysicalPagesCount
req.header: portcls.h
req.include-header: 
req.target-type: Universal
req.target-min-winverclnt: Available in Windows Vista and later Windows operating systems.
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
req.lib: 
req.dll: 
req.irql: Passive level.
targetos: Windows
req.typenames: 
f1_keywords:
 - IPortWaveRTStream::GetPhysicalPagesCount
 - portcls/IPortWaveRTStream::GetPhysicalPagesCount
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Portcls.h
api_name:
 - IPortWaveRTStream::GetPhysicalPagesCount
---

# IPortWaveRTStream::GetPhysicalPagesCount


## -description

The <code>GetPhysicalPagesCount</code> method returns the count of the physical pages in a memory descriptor list (<a href="/windows-hardware/drivers/ddi/wdm/ns-wdm-_mdl">MDL</a>).

## -parameters

### -param MemoryDescriptorList [in]


Pointer to the MDL.

## -returns

<code>GetPhysicalPagesCount</code> method returns the count of physical pages in the MDL.

## -remarks

The miniport driver uses this call to determine the number of physical pages that are contained within an MDL. The count is typically used in the process of programming the DMA hardware.

## -see-also

<a href="/windows-hardware/drivers/ddi/portcls/nn-portcls-iportwavertstream">IPortWaveRTStream</a>



<a href="/windows-hardware/drivers/ddi/portcls/nf-portcls-iportwavertstream-allocatecontiguouspagesformdl">IPortWaveRTStream::AllocateContiguousPagesForMdl</a>



<a href="/windows-hardware/drivers/ddi/portcls/nf-portcls-iportwavertstream-allocatepagesformdl">IPortWaveRTStream::AllocatePagesForMdl</a>



<a href="/windows-hardware/drivers/ddi/portcls/nf-portcls-iportwavertstream-getphysicalpageaddress">IPortWaveRTStream::GetPhysicalPageAddress</a>

