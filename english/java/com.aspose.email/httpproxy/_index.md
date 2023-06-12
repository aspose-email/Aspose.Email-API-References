---
title: HttpProxy
second_title: Aspose.Email for Java API Reference
description: HTTP proxy client.
type: docs
weight: 297
url: /java/com.aspose.email/httpproxy/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.Proxy](../../com.aspose.email/proxy)

**All Implemented Interfaces:**
com.aspose.ms.System.Net.IWebProxy
```
public class HttpProxy extends Proxy implements System.Net.IWebProxy
```

HTTP proxy client.
## Constructors

| Constructor | Description |
| --- | --- |
| [HttpProxy(String address, int port)](#HttpProxy-java.lang.String-int-) | Initializes a new instance of the [HttpProxy](../../com.aspose.email/httpproxy) class to connect to proxy server without authentication. |
| [HttpProxy(String address, int port, String username, String password)](#HttpProxy-java.lang.String-int-java.lang.String-java.lang.String-) | Initializes a new instance of the [HttpProxy](../../com.aspose.email/httpproxy) class to connect to proxy server with defined username and password. |
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Disposes this instance and requests that the underlying TCP connection be closed. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | The domain name or IP address of the proxy server |
| [getClass()](#getClass--) |  |
| [getCredentials()](#getCredentials--) | The credentials to submit to the proxy server for authentication. |
| [getPassword()](#getPassword--) | Password for proxy authentication |
| [getPort()](#getPort--) | The port number for the proxy server |
| [getProxy(System.Uri destination)](#getProxy-com.aspose.ms.System.Uri-) |  |
| [getProxy(URI destination)](#getProxy-java.net.URI-) | Returns the URI of a proxy. |
| [getStream(String address, int port)](#getStream-java.lang.String-int-) | Returns configured network stream to transport data to the required host through the proxy server. |
| [getSupportedAuthenticationMethods()](#getSupportedAuthenticationMethods--) | The supported authentication methods to connect to HTTP proxy |
| [getUsername()](#getUsername--) | Username for proxy authentication |
| [hashCode()](#hashCode--) |  |
| [isBypassed(System.Uri host)](#isBypassed-com.aspose.ms.System.Uri-) |  |
| [isBypassed(URI host)](#isBypassed-java.net.URI-) | Indicates that the proxy should not be used for the specified host. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddress(String value)](#setAddress-java.lang.String-) | The domain name or IP address of the proxy server |
| [setCredentials(System.Net.ICredentials value)](#setCredentials-com.aspose.ms.System.Net.ICredentials-) | The credentials to submit to the proxy server for authentication. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Password for proxy authentication |
| [setPort(int value)](#setPort-int-) | The port number for the proxy server |
| [setSupportedAuthenticationMethods(byte value)](#setSupportedAuthenticationMethods-byte-) | The supported authentication methods to connect to HTTP proxy |
| [setUpStream(System.IO.Stream stream, String address, int port)](#setUpStream-com.aspose.ms.System.IO.Stream-java.lang.String-int-) | Configures proxy-server to transport data to the target host. |
| [setUsername(String value)](#setUsername-java.lang.String-) | Username for proxy authentication |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HttpProxy(String address, int port) {#HttpProxy-java.lang.String-int-}
```
public HttpProxy(String address, int port)
```


Initializes a new instance of the [HttpProxy](../../com.aspose.email/httpproxy) class to connect to proxy server without authentication.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The domain name or IP address of the proxy |
| port | int | The port number of the proxy |

### HttpProxy(String address, int port, String username, String password) {#HttpProxy-java.lang.String-int-java.lang.String-java.lang.String-}
```
public HttpProxy(String address, int port, String username, String password)
```


Initializes a new instance of the [HttpProxy](../../com.aspose.email/httpproxy) class to connect to proxy server with defined username and password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The domain name or IP address of the proxy |
| port | int | The port number of the proxy |
| username | java.lang.String | Username for authentication |
| password | java.lang.String | Password for authentication |

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
### getCredentials() {#getCredentials--}
```
public final System.Net.ICredentials getCredentials()
```


The credentials to submit to the proxy server for authentication.

**Returns:**
com.aspose.ms.System.Net.ICredentials
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
### getProxy(System.Uri destination) {#getProxy-com.aspose.ms.System.Uri-}
```
public System.Uri getProxy(System.Uri destination)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destination | com.aspose.ms.System.Uri |  |

**Returns:**
com.aspose.ms.System.Uri
### getProxy(URI destination) {#getProxy-java.net.URI-}
```
public URI getProxy(URI destination)
```


Returns the URI of a proxy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destination | java.net.URI | A System.Uri that specifies the requested Internet resource. |

**Returns:**
java.net.URI - A System.Uri instance that contains the URI of the proxy used to contact destination.
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
### getSupportedAuthenticationMethods() {#getSupportedAuthenticationMethods--}
```
public final byte getSupportedAuthenticationMethods()
```


The supported authentication methods to connect to HTTP proxy

**Returns:**
byte
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
### isBypassed(System.Uri host) {#isBypassed-com.aspose.ms.System.Uri-}
```
public boolean isBypassed(System.Uri host)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | com.aspose.ms.System.Uri |  |

**Returns:**
boolean
### isBypassed(URI host) {#isBypassed-java.net.URI-}
```
public boolean isBypassed(URI host)
```


Indicates that the proxy should not be used for the specified host.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.net.URI | The System.Uri of the host to check for proxy use. |

**Returns:**
boolean - true if the proxy server should not be used for host; otherwise, false.
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

### setCredentials(System.Net.ICredentials value) {#setCredentials-com.aspose.ms.System.Net.ICredentials-}
```
public final void setCredentials(System.Net.ICredentials value)
```


The credentials to submit to the proxy server for authentication.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.ICredentials |  |

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

### setSupportedAuthenticationMethods(byte value) {#setSupportedAuthenticationMethods-byte-}
```
public final void setSupportedAuthenticationMethods(byte value)
```


The supported authentication methods to connect to HTTP proxy

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setUpStream(System.IO.Stream stream, String address, int port) {#setUpStream-com.aspose.ms.System.IO.Stream-java.lang.String-int-}
```
public void setUpStream(System.IO.Stream stream, String address, int port)
```


Configures proxy-server to transport data to the target host.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Stream which is connected to the proxy-server. |
| address | java.lang.String | The network address of the target host we want to contact |
| port | int | The port number of the target host we want to contact |

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

