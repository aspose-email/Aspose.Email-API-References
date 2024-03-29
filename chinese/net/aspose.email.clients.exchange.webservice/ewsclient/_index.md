---
title: EWSClient
second_title: Aspose.Email for .NET API 参考
description: 使用 Exchange Web 服务 EWS 提供对 MS Exchange Server 的访问
type: docs
weight: 3680
url: /zh/net/aspose.email.clients.exchange.webservice/ewsclient/
---
## EWSClient class

使用 Exchange Web 服务 (EWS) 提供对 MS Exchange Server 的访问。

```csharp
public abstract class EWSClient : ExchangeClientBase
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | 获取或设置凭证 |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | 获取或设置日志文件名 |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | 获取或设置邮箱uri |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | 获取或设置代理。 |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | 获取或设置操作超时前等待的毫秒数。 默认值为100,000毫秒（100秒）。 |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | 获取或设置指示是否必须在日志文件名中使用日期的值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_2)(string, ICredentials) | 初始化[`EWSClient`](../ewsclient)基于类 |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_3)(string, ICredentials, WebProxy) | 初始化[`EWSClient`](../ewsclient)基于类 |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_4)(string, string, string) | 初始化[`EWSClient`](../ewsclient)基于类 |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_1)(ExchangeVersion, string, ICredentials, WebProxy) | 初始化[`EWSClient`](../ewsclient)基于类 |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_6)(string, string, string, string) | 初始化[`EWSClient`](../ewsclient)基于类 |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_5)(string, string, string, WebProxy) | 初始化[`EWSClient`](../ewsclient)基于类 |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_7)(string, string, string, string, WebProxy) | 初始化[`EWSClient`](../ewsclient)基于类 |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient)(ExchangeVersion, bool, string, string, ICredentials, WebProxy) | 初始化[`EWSClient`](../ewsclient)基于类 |
| static [GetEwsClientAsync](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclientasync)(string, ICredentials, WebProxy, CancellationToken) | 初始化[`EWSClient`](../ewsclient)基于类 |

### 也可以看看

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
