---
title: HttpProxy
second_title: Aspose.Email for .NET API 参考
description: HTTP 代理客户端
type: docs
weight: 16120
url: /zh/net/aspose.email.clients/httpproxy/
---
## HttpProxy class

HTTP 代理客户端。

```csharp
public class HttpProxy : Proxy, IWebProxy
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [HttpProxy](httpproxy#constructor)(string, int) | 初始化[`HttpProxy`](../httpproxy)无需身份验证即可连接到代理服务器的类。 |
| [HttpProxy](httpproxy#constructor_1)(string, int, string, string) | 初始化[`HttpProxy`](../httpproxy)使用定义的用户名和密码连接到代理服务器的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Address](../../aspose.email.clients/proxy/address) { get; set; } | 代理服务器的域名或IP地址 |
| [Credentials](../../aspose.email.clients/httpproxy/credentials) { get; set; } | 提交给代理服务器进行身份验证的凭据。 |
| [Password](../../aspose.email.clients/proxy/password) { get; set; } | 代理认证密码 |
| [Port](../../aspose.email.clients/proxy/port) { get; set; } | 代理服务器的端口号 |
| [SupportedAuthenticationMethods](../../aspose.email.clients/httpproxy/supportedauthenticationmethods) { get; set; } | 连接到 HTTP 代理的支持的身份验证方法 |
| [Username](../../aspose.email.clients/proxy/username) { get; set; } | 代理身份验证的用户名 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/proxy/dispose)() | 释放此实例并请求关闭底层 TCP 连接。 |
| virtual [GetProxy](../../aspose.email.clients/httpproxy/getproxy)(Uri) | 返回代理的 URI。 |
| [GetStream](../../aspose.email.clients/proxy/getstream)(string, int) | 返回配置的网络流以通过代理服务器将数据传输到所需的主机。 |
| virtual [IsBypassed](../../aspose.email.clients/httpproxy/isbypassed)(Uri) | 表示不应该为指定的主机使用代理。 |
| override [SetUpStream](../../aspose.email.clients/httpproxy/setupstream)(Stream, string, int) | 配置代理服务器以将数据传输到目标主机。 |

### 也可以看看

* class [Proxy](../proxy)
* 命名空间 [Aspose.Email.Clients](../../aspose.email.clients)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
