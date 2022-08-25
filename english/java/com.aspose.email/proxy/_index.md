---
title: Proxy
second_title: Aspose.Email for Java API Reference
description:  Base proxy client.
type: docs
weight: 578
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
| [getAddress()](#getAddress--) | The domain name or IP address of the proxy server |
| [setAddress(String value)](#setAddress-java.lang.String-) | The domain name or IP address of the proxy server |
| [getPort()](#getPort--) | The port number for the proxy server |
| [setPort(int value)](#setPort-int-) | The port number for the proxy server |
| [getUsername()](#getUsername--) | Username for proxy authentication |
| [setUsername(String value)](#setUsername-java.lang.String-) | Username for proxy authentication |
| [getPassword()](#getPassword--) | Password for proxy authentication |
| [setPassword(String value)](#setPassword-java.lang.String-) | Password for proxy authentication |
| [getStream(String address, int port)](#getStream-java.lang.String-int-) | Returns configured network stream to transport data to the required host through the proxy server. |
| [dispose()](#dispose--) | Disposes this instance and requests that the underlying TCP connection be closed. |
### getAddress() {#getAddress--}
```
public final String getAddress()
```


The domain name or IP address of the proxy server

**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


The domain name or IP address of the proxy server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPort() {#getPort--}
```
public final int getPort()
```


The port number for the proxy server

**Returns:**
int
### setPort(int value) {#setPort-int-}
```
public final void setPort(int value)
```


The port number for the proxy server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUsername() {#getUsername--}
```
public final String getUsername()
```


Username for proxy authentication

**Returns:**
java.lang.String
### setUsername(String value) {#setUsername-java.lang.String-}
```
public final void setUsername(String value)
```


Username for proxy authentication

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Password for proxy authentication

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Password for proxy authentication

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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
### dispose() {#dispose--}
```
public void dispose()
```


Disposes this instance and requests that the underlying TCP connection be closed.

