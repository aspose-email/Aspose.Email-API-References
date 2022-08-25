---
title: SocksProxy
second_title: Aspose.Email for Java API Reference
description:  SOCKS proxy client.
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
| [getVersion()](#getVersion--) | Required SOCKS server version. |
| [setVersion(byte value)](#setVersion-byte-) | Required SOCKS server version. |
| [getSupportedAuthenticationMethods()](#getSupportedAuthenticationMethods--) | The supported authentication methods to connect to SOCKS server |
| [setSupportedAuthenticationMethods(byte value)](#setSupportedAuthenticationMethods-byte-) | The supported authentication methods to connect to SOCKS server |
| [setUpStream(System.IO.Stream stream, String address, int port)](#setUpStream-com.aspose.ms.System.IO.Stream-java.lang.String-int-) | Configures proxy-server to transport data to the target host. |
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

### getVersion() {#getVersion--}
```
public final byte getVersion()
```


Required SOCKS server version.

**Returns:**
byte
### setVersion(byte value) {#setVersion-byte-}
```
public final void setVersion(byte value)
```


Required SOCKS server version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSupportedAuthenticationMethods() {#getSupportedAuthenticationMethods--}
```
public final byte getSupportedAuthenticationMethods()
```


The supported authentication methods to connect to SOCKS server

**Returns:**
byte
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

