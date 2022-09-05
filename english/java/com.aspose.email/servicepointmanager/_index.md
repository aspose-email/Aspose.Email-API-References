---
title: ServicePointManager
second_title: Aspose.Email for Java API Reference
description:  Manages the collection of ServicePoint objects.
type: docs
weight: 629
url: /java/com.aspose.email/servicepointmanager/
---
**Inheritance:**
java.lang.Object
```
public class ServicePointManager
```

Manages the collection of ServicePoint objects.
## Constructors

| Constructor | Description |
| --- | --- |
| [ServicePointManager()](#ServicePointManager--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getDefaultConnectionLimit()](#getDefaultConnectionLimit--) | Gets or sets the maximum number of concurrent connections allowed by a ServicePoint object. |
| [setDefaultConnectionLimit(int value)](#setDefaultConnectionLimit-int-) | Gets or sets the maximum number of concurrent connections allowed by a ServicePoint object. |
| [getMaxServicePointIdleTime()](#getMaxServicePointIdleTime--) | Gets or sets the maximum idle time of a ServicePoint object. |
| [setMaxServicePointIdleTime(int value)](#setMaxServicePointIdleTime-int-) | Gets or sets the maximum idle time of a ServicePoint object. |
| [getMaxServicePoints()](#getMaxServicePoints--) | Gets or sets the maximum number of ServicePoint objects to maintain at any time. |
| [setMaxServicePoints(int value)](#setMaxServicePoints-int-) | Gets or sets the maximum number of ServicePoint objects to maintain at any time. |
| [getExpect100Continue()](#getExpect100Continue--) | Gets or sets a Boolean value that determines whether 100-Continue behavior is used. |
| [setExpect100Continue(boolean value)](#setExpect100Continue-boolean-) | Gets or sets a Boolean value that determines whether 100-Continue behavior is used. |
| [getUseNagleAlgorithm()](#getUseNagleAlgorithm--) | Determines whether the Nagle algorithm is used by the service points managed by this ServicePointManager object. |
| [setUseNagleAlgorithm(boolean value)](#setUseNagleAlgorithm-boolean-) | Determines whether the Nagle algorithm is used by the service points managed by this ServicePointManager object. |
| [setTcpKeepAlive(boolean enabled, int keepAliveTime, int keepAliveInterval)](#setTcpKeepAlive-boolean-int-int-) | Enables or disables the keep-alive option on a TCP connection. |
### ServicePointManager() {#ServicePointManager--}
```
public ServicePointManager()
```


### getDefaultConnectionLimit() {#getDefaultConnectionLimit--}
```
public static int getDefaultConnectionLimit()
```


Gets or sets the maximum number of concurrent connections allowed by a ServicePoint object.

**Returns:**
int
### setDefaultConnectionLimit(int value) {#setDefaultConnectionLimit-int-}
```
public static void setDefaultConnectionLimit(int value)
```


Gets or sets the maximum number of concurrent connections allowed by a ServicePoint object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaxServicePointIdleTime() {#getMaxServicePointIdleTime--}
```
public static int getMaxServicePointIdleTime()
```


Gets or sets the maximum idle time of a ServicePoint object.

**Returns:**
int
### setMaxServicePointIdleTime(int value) {#setMaxServicePointIdleTime-int-}
```
public static void setMaxServicePointIdleTime(int value)
```


Gets or sets the maximum idle time of a ServicePoint object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaxServicePoints() {#getMaxServicePoints--}
```
public static int getMaxServicePoints()
```


Gets or sets the maximum number of ServicePoint objects to maintain at any time.

**Returns:**
int
### setMaxServicePoints(int value) {#setMaxServicePoints-int-}
```
public static void setMaxServicePoints(int value)
```


Gets or sets the maximum number of ServicePoint objects to maintain at any time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getExpect100Continue() {#getExpect100Continue--}
```
public static boolean getExpect100Continue()
```


Gets or sets a Boolean value that determines whether 100-Continue behavior is used.

**Returns:**
boolean
### setExpect100Continue(boolean value) {#setExpect100Continue-boolean-}
```
public static void setExpect100Continue(boolean value)
```


Gets or sets a Boolean value that determines whether 100-Continue behavior is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseNagleAlgorithm() {#getUseNagleAlgorithm--}
```
public static boolean getUseNagleAlgorithm()
```


Determines whether the Nagle algorithm is used by the service points managed by this ServicePointManager object.

**Returns:**
boolean
### setUseNagleAlgorithm(boolean value) {#setUseNagleAlgorithm-boolean-}
```
public static void setUseNagleAlgorithm(boolean value)
```


Determines whether the Nagle algorithm is used by the service points managed by this ServicePointManager object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTcpKeepAlive(boolean enabled, int keepAliveTime, int keepAliveInterval) {#setTcpKeepAlive-boolean-int-int-}
```
public static void setTcpKeepAlive(boolean enabled, int keepAliveTime, int keepAliveInterval)
```


Enables or disables the keep-alive option on a TCP connection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enabled | boolean | If set to true, then the TCP keep-alive option on a TCP connection will be enabled using the specified keepAliveTime and keepAliveInterval values. |
| keepAliveTime | int | Specifies the timeout, in milliseconds, with no activity until the first keep-alive packet is sent. |
| keepAliveInterval | int | Specifies the interval, in milliseconds, between when successive keep-alive packets are sent if no acknowledgement is received. |

