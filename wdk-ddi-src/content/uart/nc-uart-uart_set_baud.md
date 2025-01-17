---
UID: NC:uart.UART_SET_BAUD
title: UART_SET_BAUD (uart.h)
description: Changes the baud rate of the UART hardware.
tech.root: serports
ms.date: 10/19/2018
keywords: ["UART_SET_BAUD callback function"]
req.header: uart.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: Windows 10, version 1803
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.irql: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
f1_keywords:
 - UART_SET_BAUD
 - uart/UART_SET_BAUD
topic_type:
 - apiref
api_type:
 - UserDefined
api_location:
 - uart.h
api_name:
 - UART_SET_BAUD
---

# UART_SET_BAUD callback function


## -description

Changes the baud rate of the UART hardware.

## -parameters

### -param Port [_Inout_]

A pointer to a [**_CPPORT**](ns-uart-_cpport.md) structure that contains the  address of the port object that describes the UART hardware.

### -param Rate:

The baud rate to set in bits per second.

## -returns

Returns TRUE if the baud rate was programmed, FALSE otherwise.

## -prototype

```cpp
//Declaration

UART_SET_BAUD UartSetBaud;

// Definition

BOOLEAN UartSetBaud
(
	PCPPORT Port
	ULONG Rate
)
{...}

```

## -remarks

Register your implementation of this callback function by setting the appropriate member of [**UART_HARDWARE_DRIVER**](ns-uart-_uart_hardware_driver.md).

## -see-also

[**UART_HARDWARE_DRIVER**](ns-uart-_uart_hardware_driver.md)

[**_CPPORT**](ns-uart-_cpport.md)

