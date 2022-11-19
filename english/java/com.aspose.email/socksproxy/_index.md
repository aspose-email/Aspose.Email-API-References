---
title: SocksProxy
second_title: Aspose.Email for Java API Reference
description: SOCKS proxy client.
type: docs
weight: 641
url: /java/com.aspose.email/socksproxy/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.Proxy](../../com.aspose.email/proxy)
```
public class SocksProxy extends Proxy
```

SOCKS proxy client. Supported versions of the protocol are SOCKS4 and SOCKS5.
## Constructors

| Constructor | Description |
| --- | --- |
| [SocksProxy(String address, int port)](#SocksProxy-java.lang.String-int-) | Initializes a new instance of the [SocksProxy](../../com.aspose.email/socksproxy) class to connect to SOCKS4 server without authentication. |
| [SocksProxy(String address, int port, byte version)](#SocksProxy-java.lang.String-int-byte-) | Initializes a new instance of the [SocksProxy](../../com.aspose.email/socksproxy) class to connect to SOCKS4 or SOCKS5 server without authentication. |
| [SocksProxy(String address, int port, String userID)](#SocksProxy-java.lang.String-int-java.lang.String-) | Initializes a new instance of the [SocksProxy](../../com.aspose.email/socksproxy) class to connect to SOCKS4 server without authentication. |
| [SocksProxy(String address, int port, String username, String password)](#SocksProxy-java.lang.String-int-java.lang.String-java.lang.String-) | Initializes a new instance of the [SocksProxy](../../com.aspose.email/socksproxy) class to connect to SOCKS5 server with defined username and password. |
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
| [getSupportedAuthenticationMethods()](#getSupportedAuthenticationMethods--) | The supported authentication methods to connect to SOCKS server |
| [getUsername()](#getUsername--) | Username for proxy authentication |
| [getVersion()](#getVersion--) | Required SOCKS server version. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddress(String value)](#setAddress-java.lang.String-) | The domain name or IP address of the proxy server |
| [setPassword(String value)](#setPassword-java.lang.String-) | Password for proxy authentication |
| [setPort(int value)](#setPort-int-) | The port number for the proxy server |
| [setSupportedAuthenticationMethods(byte value)](#setSupportedAuthenticationMethods-byte-) | The supported authentication methods to connect to SOCKS server |
| [setUpStream(System.IO.Stream stream, String address, int port)](#setUpStream-com.aspose.ms.System.IO.Stream-java.lang.String-int-) | Configures proxy-server to transport data to the target host. |
| [setUsername(String value)](#setUsername-java.lang.String-) | Username for proxy authentication |
| [setVersion(byte value)](#setVersion-byte-) | Required SOCKS server version. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SocksProxy(String address, int port) {#SocksProxy-java.lang.String-int-}
```
public SocksProxy(String address, int port)
```


Initializes a new instance of the [SocksProxy](../../com.aspose.email/socksproxy) class to connect to SOCKS4 server without authentication.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The domain name or IP address of the proxy |
| port | int | The port number of the proxy |

### SocksProxy(String address, int port, byte version) {#SocksProxy-java.lang.String-int-byte-}
```
public SocksProxy(String address, int port, byte version)
```


Initializes a new instance of the [SocksProxy](../../com.aspose.email/socksproxy) class to connect to SOCKS4 or SOCKS5 server without authentication.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The domain name or IP address of the proxy |
| port | int | The port number of the proxy |
| version | byte | Required SOCKS server version. |

### SocksProxy(String address, int port, String userID) {#SocksProxy-java.lang.String-int-java.lang.String-}
```
public SocksProxy(String address, int port, String userID)
```


Initializes a new instance of the [SocksProxy](../../com.aspose.email/socksproxy) class to connect to SOCKS4 server without authentication.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The domain name or IP address of the proxy |
| port | int | The port number of the proxy |
| userID | java.lang.String | UserID for Socks4 Identification Protocol (RFC 1413) |

### SocksProxy(String address, int port, String username, String password) {#SocksProxy-java.lang.String-int-java.lang.String-java.lang.String-}
```
public SocksProxy(String address, int port, String username, String password)
```


Initializes a new instance of the [SocksProxy](../../com.aspose.email/socksproxy) class to connect to SOCKS5 server with defined username and password.

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
### getSupportedAuthenticationMethods() {#getSupportedAuthenticationMethods--}
```
public final byte getSupportedAuthenticationMethods()
```


The supported authentication methods to connect to SOCKS server

**Returns:**
byte
### getUsername() {#getUsername--}
```
public final String getUsername()
```


Username for proxy authentication

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final byte getVersion()
```


Required SOCKS server version.

**Returns:**
byte
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

### setSupportedAuthenticationMethods(byte value) {#setSupportedAuthenticationMethods-byte-}
```
public final void setSupportedAuthenticationMethods(byte value)
```


The supported authentication methods to connect to SOCKS server

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

### setVersion(byte value) {#setVersion-byte-}
```
public final void setVersion(byte value)
```


Required SOCKS server version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

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

