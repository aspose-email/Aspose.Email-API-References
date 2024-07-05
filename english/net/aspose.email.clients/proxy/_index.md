---
title: Class Proxy
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Proxy class. Base proxy client
type: docs
weight: 17040
url: /net/aspose.email.clients/proxy/
---
## Proxy class

Base proxy client.

```csharp
public abstract class Proxy : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Address](../../aspose.email.clients/proxy/address/) { get; set; } | The domain name or IP address of the proxy server |
| [Password](../../aspose.email.clients/proxy/password/) { get; set; } | Password for proxy authentication |
| [Port](../../aspose.email.clients/proxy/port/) { get; set; } | The port number for the proxy server |
| [Username](../../aspose.email.clients/proxy/username/) { get; set; } | Username for proxy authentication |

## Methods

| Name | Description |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/proxy/dispose/)() | Disposes this instance and requests that the underlying TCP connection be closed. |
| [GetStream](../../aspose.email.clients/proxy/getstream/)(string, int) | Returns configured network stream to transport data to the required host through the proxy server. |
| abstract [SetUpStream](../../aspose.email.clients/proxy/setupstream/)(Stream, string, int) | Configures proxy-server to transport data to the target host. |

### See Also

* namespace [Aspose.Email.Clients](../../aspose.email.clients/)
* assembly [Aspose.Email](../../)


