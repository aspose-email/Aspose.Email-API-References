---
title: AutodiscoverService
second_title: Aspose.Email for .NET API 参考
description: 表示与 Exchange 自动发现服务的绑定
type: docs
weight: 3090
url: /zh/net/aspose.email.clients.exchange/autodiscoverservice/
---
## AutodiscoverService class

表示与 Exchange 自动发现服务的绑定。

```csharp
public sealed class AutodiscoverService : AutodiscoverServiceBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [AutodiscoverService](autodiscoverservice#constructor)() | 初始化[`AutodiscoverService`](../autodiscoverservice)类. |
| [AutodiscoverService](autodiscoverservice#constructor_1)(ExchangeVersion) | 初始化[`AutodiscoverService`](../autodiscoverservice)类. |
| [AutodiscoverService](autodiscoverservice#constructor_2)(string) | 初始化[`AutodiscoverService`](../autodiscoverservice)类. |
| [AutodiscoverService](autodiscoverservice#constructor_4)(Uri) | 初始化[`AutodiscoverService`](../autodiscoverservice)类. |
| [AutodiscoverService](autodiscoverservice#constructor_3)(string, ExchangeVersion) | 初始化[`AutodiscoverService`](../autodiscoverservice)类. |
| [AutodiscoverService](autodiscoverservice#constructor_5)(Uri, ExchangeVersion) | 初始化[`AutodiscoverService`](../autodiscoverservice)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding) { get; set; } | 获取或设置一个值，该值指示是否应接受 GZip 压缩编码。 |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid) { get; set; } | 获取或设置请求的请求ID。 |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname) { get; set; } | 获取或设置请求的连接组的名称。 |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer) { get; set; } | 获取或设置 cookie 容器。 |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials) { get; set; } | 获取或设置用于通过 Exchange Web 服务进行身份验证的凭据。设置 Credentials property 会自动将 UseDefaultCredentials 设置为 false。 |
| [Domain](../../aspose.email.clients.exchange/autodiscoverservice/domain) { get; set; } | 获取或设置此服务绑定的域。设置此属性时，domain 名称用于自动确定自动发现服务 URL。 |
| [EnableScpLookup](../../aspose.email.clients.exchange/autodiscoverservice/enablescplookup) { get; set; } | 获取或设置一个值，该值指示 AutodiscoverService 在确定 Autodiscover 服务 URL 时是否应执行 SCP (ServiceConnectionPoint) 记录查找。 |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders) { get; } | 获取将随每个请求发送到 EWS 的 HTTP 标头集合。 |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders) { get; } | 从最后一个响应中获取 HTTP 标头的集合。 |
| [IsExternal](../../aspose.email.clients.exchange/autodiscoverservice/isexternal) { get; } | 获取一个值，该值指示 URL 指向的自动发现服务是内部（公司网络内部） 还是外部（公司网络外部）。 |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive) { get; set; } | 获取或设置对 Internet 资源的请求是否应包含值为 Keep-alive 的 Connection HTTP 标头 |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename) { get; set; } | 获取或设置日志文件名 |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate) { get; set; } | 获取或设置一个值，该值指示是否应执行 HTTP 预认证。 |
| [RedirectionUrlValidationCallback](../../aspose.email.clients.exchange/autodiscoverservice/redirectionurlvalidationcallback) { get; set; } | 获取或设置重定向 URL 验证回调。 |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion) { get; } | 获取请求的服务器版本。 |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid) { get; set; } | 获取或设置一个标志，表示客户端是否要求服务端返回请求id。 |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies) { get; set; } | 获取或设置一个值，该值指示客户端延迟信息是否推送到服务器。 |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo) { get; } | 获取与处理最后一个请求的服务器相关的信息。 如果没有处理请求，则为空。 |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout) { get; set; } | 获取或设置发送 HTTP 请求和接收 HTTP 响应时使用的超时时间，以毫秒为单位。 默认为 100000。 |
| [Url](../../aspose.email.clients.exchange/autodiscoverservice/url) { get; set; } | 获取或设置此服务绑定的 URL。 |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename) { get; set; } | 获取或设置指示是否必须在日志文件名中使用日期的值。 |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials) { get; set; } | 获取或设置一个值，该值指示当前登录到 Windows 的用户的凭据是否应该用于 对 Exchange Web 服务进行身份验证。将 UseDefaultCredentials 设置为 true 会自动将 Credentials 属性设置为 null. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent) { get; set; } | 获取或设置用户代理。 |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy) { get; set; } | 获取或设置向 EWS 发送请求时应使用的 Web 代理。 将此属性设置为 null 以使用默认 Web 代理。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetUserSettings](../../aspose.email.clients.exchange/autodiscoverservice/getusersettings)(string, params UserSettingName[]) | 检索单个 SMTP 地址的指定设置。 |
| [GetUsersSettings](../../aspose.email.clients.exchange/autodiscoverservice/getuserssettings)(IEnumerable&lt;string&gt;, params UserSettingName[]) | 检索一组用户的指定设置。 |

### 也可以看看

* class [AutodiscoverServiceBase](../autodiscoverservicebase)
* 命名空间 [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
