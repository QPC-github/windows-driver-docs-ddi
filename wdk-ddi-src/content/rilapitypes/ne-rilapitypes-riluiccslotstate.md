---
UID: NE:rilapitypes.RILUICCSLOTSTATE
title: RILUICCSLOTSTATE (rilapitypes.h)
description: "Microsoft reserves the RILUICCSLOTSTATE enumeration for internal use only. Don't use this enumeration in your code."
old-location: netvista\riluiccslotstate_2.htm
tech.root: netvista
ms.date: 02/26/2018
keywords: ["RILUICCSLOTSTATE enumeration"]
ms.keywords: RILUICCSLOTSTATE, RILUICCSLOTSTATE enumeration [Network Drivers Starting with Windows Vista], RIL_UICCSLOT_ACTIVE, RIL_UICCSLOT_EMPTY, RIL_UICCSLOT_ERROR, RIL_UICCSLOT_MAX, RIL_UICCSLOT_NOT_READY, RIL_UICCSLOT_OFF, netvista.riluiccslotstate_2, rilapitypes/RILUICCSLOTSTATE, rilapitypes/RIL_UICCSLOT_ACTIVE, rilapitypes/RIL_UICCSLOT_EMPTY, rilapitypes/RIL_UICCSLOT_ERROR, rilapitypes/RIL_UICCSLOT_MAX, rilapitypes/RIL_UICCSLOT_NOT_READY, rilapitypes/RIL_UICCSLOT_OFF
req.header: rilapitypes.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
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
req.lib: NtosKrnl.exe
req.dll: 
req.irql: 
targetos: Windows
req.typenames: RILUICCSLOTSTATE
req.product: Windows 10 or later.
f1_keywords:
 - RILUICCSLOTSTATE
 - rilapitypes/RILUICCSLOTSTATE
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - rilapitypes.h
api_name:
 - RILUICCSLOTSTATE
---

# RILUICCSLOTSTATE enumeration (rilapitypes.h)


## -description

This topic supports the Windows driver infrastructure and is not intended to be used directly from your code.

## -enum-fields

### -field RIL_UICCSLOT_OFF_EMPTY

### -field RIL_UICCSLOT_OFF

### -field RIL_UICCSLOT_EMPTY

### -field RIL_UICCSLOT_NOT_READY

### -field RIL_UICCSLOT_ACTIVE

### -field RIL_UICCSLOT_ERROR

### -field RIL_UICCSLOT_MAX

## -syntax

```cpp
typedef enum _RILUICCSLOTSTATE {
  RIL_UICCSLOT_OFF,
  RIL_UICCSLOT_EMPTY,
  RIL_UICCSLOT_NOT_READY,
  RIL_UICCSLOT_ACTIVE,
  RIL_UICCSLOT_ERROR,
  RIL_UICCSLOT_MAX
} RILUICCSLOTSTATE;
```

