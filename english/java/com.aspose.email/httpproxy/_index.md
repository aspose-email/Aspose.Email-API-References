---
title: HttpProxy
second_title: Aspose.Email for Java API Reference
description:  HTTP proxy client.
type: docs
weight: 296
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
| [getSupportedAuthenticationMethods()](#getSupportedAuthenticationMethods--) | The supported authentication methods to connect to HTTP proxy |
| [setSupportedAuthenticationMethods(byte value)](#setSupportedAuthenticationMethods-byte-) | The supported authentication methods to connect to HTTP proxy |
| [setUpStream(System.IO.Stream stream, String address, int port)](#setUpStream-com.aspose.ms.System.IO.Stream-java.lang.String-int-) | Configures proxy-server to transport data to the target host. |
| [getCredentials()](#getCredentials--) | The credentials to submit to the proxy server for authentication. |
| [setCredentials(System.Net.ICredentials value)](#setCredentials-com.aspose.ms.System.Net.ICredentials-) | The credentials to submit to the proxy server for authentication. |
| [isBypassed(URI host)](#isBypassed-java.net.URI-) | Indicates that the proxy should not be used for the specified host. |
| [getProxy(URI destination)](#getProxy-java.net.URI-) | Returns the URI of a proxy. |
| [getProxy(System.Uri destination)](#getProxy-com.aspose.ms.System.Uri-) |  |
| [isBypassed(System.Uri host)](#isBypassed-com.aspose.ms.System.Uri-) |  |
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

### getSupportedAuthenticationMethods() {#getSupportedAuthenticationMethods--}
```
public final byte getSupportedAuthenticationMethods()
```


The supported authentication methods to connect to HTTP proxy

**Returns:**
byte
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

### getCredentials() {#getCredentials--}
```
public final System.Net.ICredentials getCredentials()
```


The credentials to submit to the proxy server for authentication.

**Returns:**
com.aspose.ms.System.Net.ICredentials
### setCredentials(System.Net.ICredentials value) {#setCredentials-com.aspose.ms.System.Net.ICredentials-}
```
public final void setCredentials(System.Net.ICredentials value)
```


The credentials to submit to the proxy server for authentication.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.ICredentials |  |

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
