---
title: Class HttpProxy
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.HttpProxy class. HTTP proxy client
type: docs
weight: 16260
url: /net/aspose.email.clients/httpproxy/
---
## HttpProxy class

HTTP proxy client.

```csharp
public class HttpProxy : Proxy, IWebProxy
```

## Constructors

| Name | Description |
| --- | --- |
| [HttpProxy](httpproxy/#constructor)(string, int) | Initializes a new instance of the `HttpProxy` class to connect to proxy server without authentication. |
| [HttpProxy](httpproxy/#constructor_1)(string, int, string, string) | Initializes a new instance of the `HttpProxy` class to connect to proxy server with defined username and password. |

## Properties

| Name | Description |
| --- | --- |
| [Address](../../aspose.email.clients/proxy/address/) { get; set; } | The domain name or IP address of the proxy server |
| [Credentials](../../aspose.email.clients/httpproxy/credentials/) { get; set; } | The credentials to submit to the proxy server for authentication. |
| [Password](../../aspose.email.clients/proxy/password/) { get; set; } | Password for proxy authentication |
| [Port](../../aspose.email.clients/proxy/port/) { get; set; } | The port number for the proxy server |
| [SupportedAuthenticationMethods](../../aspose.email.clients/httpproxy/supportedauthenticationmethods/) { get; set; } | The supported authentication methods to connect to HTTP proxy |
| [Username](../../aspose.email.clients/proxy/username/) { get; set; } | Username for proxy authentication |

## Methods

| Name | Description |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/proxy/dispose/)() | Disposes this instance and requests that the underlying TCP connection be closed. |
| virtual [GetProxy](../../aspose.email.clients/httpproxy/getproxy/)(Uri) | Returns the URI of a proxy. |
| [GetStream](../../aspose.email.clients/proxy/getstream/)(string, int) | Returns configured network stream to transport data to the required host through the proxy server. |
| virtual [IsBypassed](../../aspose.email.clients/httpproxy/isbypassed/)(Uri) | Indicates that the proxy should not be used for the specified host. |
| override [SetUpStream](../../aspose.email.clients/httpproxy/setupstream/)(Stream, string, int) | Configures proxy-server to transport data to the target host. |

### See Also

* class [Proxy](../proxy/)
* namespace [Aspose.Email.Clients](../../aspose.email.clients/)
* assembly [Aspose.Email](../../)


