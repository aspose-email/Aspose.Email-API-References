---
title: Proxy
second_title: Aspose.Email for Java API Reference
description: Base proxy client.
type: docs
weight: 600
url: /java/com.aspose.email/proxy/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public abstract class Proxy implements System.IDisposable
```

Base proxy client.
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Disposes this instance and requests that the underlying TCP connection be closed. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | The domain name or IP address of the proxy server |
| [getClass()](#getClass--) |  |
| [getPassword()](#getPassword--) | Password for proxy authentication |
| [getPort()](#getPort--) | The port number for the proxy server |
| [getStream(String address, int port)](#getStream-java.lang.String-int-) | Returns configured network stream to transport data to the required host through the proxy server. |
| [getUsername()](#getUsername--) | Username for proxy authentication |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddress(String value)](#setAddress-java.lang.String-) | The domain name or IP address of the proxy server |
| [setPassword(String value)](#setPassword-java.lang.String-) | Password for proxy authentication |
| [setPort(int value)](#setPort-int-) | The port number for the proxy server |
| [setUsername(String value)](#setUsername-java.lang.String-) | Username for proxy authentication |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### dispose() {#dispose--}
```
public void dispose()
```


Disposes this instance and requests that the underlying TCP connection be closed.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddress() {#getAddress--}
```
public final String getAddress()
```


The domain name or IP address of the proxy server

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Password for proxy authentication

**Returns:**
java.lang.String
### getPort() {#getPort--}
```
public final int getPort()
```


The port number for the proxy server

**Returns:**
int
### getStream(String address, int port) {#getStream-java.lang.String-int-}
```
public System.IO.Stream getStream(String address, int port)
```


Returns configured network stream to transport data to the required host through the proxy server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The domain name of the host we want to contact |
| port | int | The port number of the host we want to contact |

**Returns:**
com.aspose.ms.System.IO.Stream - Returns configure network stream to connect with required host through the proxy server.
### getUsername() {#getUsername--}
```
public final String getUsername()
```


Username for proxy authentication

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


The domain name or IP address of the proxy server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Password for proxy authentication

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPort(int value) {#setPort-int-}
```
public final void setPort(int value)
```


The port number for the proxy server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUsername(String value) {#setUsername-java.lang.String-}
```
public final void setUsername(String value)
```


Username for proxy authentication

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

