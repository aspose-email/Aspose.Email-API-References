---
title: PipeliningStatus
second_title: Aspose.Email for Java API Reference
description:  Defines pipelining status for mail client.
type: docs
weight: 563
url: /java/com.aspose.email/pipeliningstatus/
---
**Inheritance:**
java.lang.Object
```
public class PipeliningStatus
```

Defines pipelining status for mail client.
## Methods

| Method | Description |
| --- | --- |
| [getSupportedByServer()](#getSupportedByServer--) | Gets value that indicates if pipelining mode is supported by a server. |
| [getClientMode()](#getClientMode--) | Gets or sets a value that defines how mail client supports the pipelining |
| [setClientMode(int value)](#setClientMode-int-) | Gets or sets a value that defines how mail client supports the pipelining |
| [getPipeliningEnabled()](#getPipeliningEnabled--) | Gets a value that defines if pipelining mode is enabled. |
| [to_PipeliningStatus(boolean mode)](#to-PipeliningStatus-boolean-) | Converts boolean value to [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object |
| [to_PipeliningStatus(int mode)](#to-PipeliningStatus-int-) | Converts [PipeliningMode](../../com.aspose.email/pipeliningmode) value to [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object |
| [to_Boolean(PipeliningStatus status)](#to-Boolean-com.aspose.email.PipeliningStatus-) | Converts [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object to boolean value |
| [to_Boolean()](#to-Boolean--) | Converts [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object to boolean value |
| [to_PipeliningMode(PipeliningStatus status)](#to-PipeliningMode-com.aspose.email.PipeliningStatus-) | Converts [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object |
| [toString()](#toString--) | Returns a string that represents the current object. |
### getSupportedByServer() {#getSupportedByServer--}
```
public final boolean getSupportedByServer()
```


Gets value that indicates if pipelining mode is supported by a server.

**Returns:**
boolean
### getClientMode() {#getClientMode--}
```
public final int getClientMode()
```


Gets or sets a value that defines how mail client supports the pipelining

**Returns:**
int
### setClientMode(int value) {#setClientMode-int-}
```
public final void setClientMode(int value)
```


Gets or sets a value that defines how mail client supports the pipelining

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPipeliningEnabled() {#getPipeliningEnabled--}
```
public final boolean getPipeliningEnabled()
```


Gets a value that defines if pipelining mode is enabled.

**Returns:**
boolean
### to_PipeliningStatus(boolean mode) {#to-PipeliningStatus-boolean-}
```
public static PipeliningStatus to_PipeliningStatus(boolean mode)
```


Converts boolean value to [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode | boolean | true if pipelining has to be used, otherwise false |

**Returns:**
[PipeliningStatus](../../com.aspose.email/pipeliningstatus) - Returns [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object
### to_PipeliningStatus(int mode) {#to-PipeliningStatus-int-}
```
public static PipeliningStatus to_PipeliningStatus(int mode)
```


Converts [PipeliningMode](../../com.aspose.email/pipeliningmode) value to [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode | int | [PipeliningMode](../../com.aspose.email/pipeliningmode) value for conversion |

**Returns:**
[PipeliningStatus](../../com.aspose.email/pipeliningstatus) - Returns [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object
### to_Boolean(PipeliningStatus status) {#to-Boolean-com.aspose.email.PipeliningStatus-}
```
public static boolean to_Boolean(PipeliningStatus status)
```


Converts [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object to boolean value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| status | [PipeliningStatus](../../com.aspose.email/pipeliningstatus) | [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object for conversion |

**Returns:**
boolean - Returns true if pipelining is used, otherwise returns false.
### to_Boolean() {#to-Boolean--}
```
public boolean to_Boolean()
```


Converts [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object to boolean value

**Returns:**
boolean - Returns true if pipelining is used, otherwise returns false.
### to_PipeliningMode(PipeliningStatus status) {#to-PipeliningMode-com.aspose.email.PipeliningStatus-}
```
public static int to_PipeliningMode(PipeliningStatus status)
```


Converts [PipeliningStatus](../../com.aspose.email/pipeliningstatus) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| status | [PipeliningStatus](../../com.aspose.email/pipeliningstatus) | A PipeliningStatus value |

**Returns:**
int - A PipeliningMode value
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
