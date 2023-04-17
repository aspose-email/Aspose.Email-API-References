---
title: Class SocksProxy
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.SocksProxy class. SOCKS proxy client. Supported versions of the protocol are SOCKS4 and SOCKS5
type: docs
weight: 17100
url: /net/aspose.email.clients/socksproxy/
---
## SocksProxy class

SOCKS proxy client. Supported versions of the protocol are SOCKS4 and SOCKS5.

```csharp
public class SocksProxy : Proxy
```

## Constructors

| Name | Description |
| --- | --- |
| [SocksProxy](socksproxy/#constructor)(string, int) | Initializes a new instance of the `SocksProxy` class to connect to SOCKS4 server without authentication. |
| [SocksProxy](socksproxy/#constructor_1)(string, int, SocksVersion) | Initializes a new instance of the `SocksProxy` class to connect to SOCKS4 or SOCKS5 server without authentication. |
| [SocksProxy](socksproxy/#constructor_2)(string, int, string) | Initializes a new instance of the `SocksProxy` class to connect to SOCKS4 server without authentication. |
| [SocksProxy](socksproxy/#constructor_3)(string, int, string, string) | Initializes a new instance of the `SocksProxy` class to connect to SOCKS5 server with defined username and password. |

## Properties

| Name | Description |
| --- | --- |
| [Address](../../aspose.email.clients/proxy/address/) { get; set; } | The domain name or IP address of the proxy server |
| [Password](../../aspose.email.clients/proxy/password/) { get; set; } | Password for proxy authentication |
| [Port](../../aspose.email.clients/proxy/port/) { get; set; } | The port number for the proxy server |
| [SupportedAuthenticationMethods](../../aspose.email.clients/socksproxy/supportedauthenticationmethods/) { get; set; } | The supported authentication methods to connect to SOCKS server |
| [Username](../../aspose.email.clients/proxy/username/) { get; set; } | Username for proxy authentication |
| [Version](../../aspose.email.clients/socksproxy/version/) { get; set; } | Required SOCKS server version. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/proxy/dispose/)() | Disposes this instance and requests that the underlying TCP connection be closed. |
| [GetStream](../../aspose.email.clients/proxy/getstream/)(string, int) | Returns configured network stream to transport data to the required host through the proxy server. |
| override [SetUpStream](../../aspose.email.clients/socksproxy/setupstream/)(Stream, string, int) | Configures proxy-server to transport data to the target host. |

### See Also

* class [Proxy](../proxy/)
* namespace [Aspose.Email.Clients](../../aspose.email.clients/)
* assembly [Aspose.Email](../../)


