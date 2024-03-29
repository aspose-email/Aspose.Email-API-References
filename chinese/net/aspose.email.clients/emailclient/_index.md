---
title: EmailClient
second_title: Aspose.Email for .NET API 参考
description: 表示使用主机凭据创建服务器连接的客户端
type: docs
weight: 3020
url: /zh/net/aspose.email.clients/emailclient/
---
## EmailClient class

表示使用主机凭据创建服务器连接的客户端。

```csharp
public abstract class EmailClient : IDisposable
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | 获取或设置访问令牌。 |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | 包含客户端证书的集合 |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | 获取或设置定义多线程环境下连接分配模式的值 连接类型有以下几种： - 主连接是与邮件客户端一起创建和处理的连接，不能手动创建或处理。 -默认连接是某些线程的默认连接。 如果默认连接存在并且ConnectionAsgmtMode允许，则在该线程中执行的电子邮件客户端的所有方法都将隐式使用该连接。 每个线程只能存在一个默认连接。它可以手动或自动创建。它取决于 EmailClient.ConnectionAsgmtMode 属性。 可以使用 EmailClient.CreateConnection(createAsDefaultConnection = true) 方法手动创建这些连接。 如果不使用默认连接（取决于连接分配模式），则隐式使用主连接。 - 独立连接是未链接到线程。它们可以手动创建，并且必须显式用作方法参数。 可以使用 EmailClient.CreateConnection() 方法或 EmailClient.CreateConnection(createAsDefaultConnection = false) 方法手动创建这些连接。 有以下连接分配类型： - ConnectionAsgmtType.UseMainOrDefault 此模式在电子邮件客户端中默认使用。 如果默认连接尚未创建，或者连接未作为方法参数显式传递，则电子邮件客户端对来自多个线程的所有操作使用主连接。 主连接是与电子邮件客户端同时创建的连接。 用户可以使用 CreateConnection 方法为线程创建默认连接。 如果创建了线程的默认连接，它将隐式用于在此线程中调用的电子邮件客户端的所有方法。 如果未创建线程的默认连接，则将主连接用于在此调用的电子邮件客户端的所有方法thread. 用户还可以使用 CreateConnection 方法创建未与线程链接的连接（非默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接作为他想要使用的方法的参数显式传递。 用户可以另外创建任意数量的连接。每个线程只能有一个默认连接。 请注意，如果用户使用 Thread 对象进行多任务编程，默认连接可以正常工作。 如果用户使用 ConnectionPool 或使用任务对象进行多任务编程，这种模式可能会导致程序的错误行为。 为了避免这个问题，用户必须在执行的代码末尾手动处理默认连接（如果他使用它） thread. - ConnectionAsgmtType.UseMain 电子邮件客户端对来自多个线程的所有操作使用主连接。 主连接是与电子邮件客户端同时创建的连接。 用户无法创建默认连接。 用户可以使用 CreateConnection 方法创建未与线程链接的连接（非默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接作为他想要使用的方法的参数显式传递。 用户可以另外创建任意数量的连接。 - ConnectionAsgmtType.UseDefault 电子邮件客户端对来自多个线程的所有操作隐式仅使用默认连接。此模式不使用主连接。 如果尚未为某些线程创建默认连接（第一次调用电子邮件客户端方法）， 电子邮件客户端在执行第一次操作之前为线程隐式创建默认连接。 用户不能使用 CreateConnection 方法为线程创建默认连接，因为它们是自动创建的。 创建线程的默认连接时，它会隐式用于在此线程中调用的电子邮件客户端的所有方法。read. 用户还可以使用 CreateConnection 方法创建未与线程链接的连接（非默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接作为他想要使用的方法的参数显式传递。 用户可以另外创建任意数量的连接。每个线程只能有一个默认连接。 请注意，如果用户使用 Thread 对象进行多任务编程，默认连接可以正常工作。 如果用户使用 ConnectionPool 或使用任务对象进行多任务编程，这种模式可能会导致程序的错误行为。 为了避免这个问题，用户必须在线程中执行的代码末尾手动处理默认连接。 |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | 以毫秒为单位的连接检查周期。 默认值为 5 分钟。 |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | 获取或设置多连接模式下的连接数 |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | 获取连接的当前状态。 |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | 根据 ConnectionAsgmtMode 选项获取当前连接 |
| virtual [DefaultPort](../../aspose.email.clients/emailclient/defaultport) { get; } | 获取客户端的默认端口 |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | 获取或设置允许启用/禁用记录器的值 |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | 获取或设置建立连接时使用的问候超时。 请注意，问候超时不能是无限的。 电子邮件客户端可能会执行足够长的操作。为了限制用户必须使用的操作时间[`Timeout`](./timeout)财产。 此属性的值必须具有较长的时间间隔，以免妨碍长时间操作。 但在某些情况下，如果EmailClient 只使用Timeout 属性建立连接可能需要很长时间。 例如，邮件客户端可以使用自动模式来建立连接。 在此模式下，电子邮件客户端会检查所有可能的连接参数，直到建立连接。 SMTP、IMAP 和 POP3 服务器在正确建立连接的情况下向客户端发送问候字符串。 服务器可以使用隐式或显式 (START TLS) SSL/TLS 连接启动。 如果连接模式不匹配（例如，服务器等待隐式 SSL 连接，但客户端尝试建立 非安全或显式 SSL 连接），服务器将不会发送问候字符串。 在这种情况下，用户将等待很长时间，直到超时到达问候字符串，客户端进入下一个连接选项。 为避免此问题，引入了 GreetingTimeout 属性。此属性允许您设置问候字符串的超时时间， 并减少自动连接建立的时间。 |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | 获取或设置主机名。 |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | 获取或设置日志文件名 |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | 获取或设置密码。 密码限制由客户端连接的服务器实现定义。 |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | 获取或设置端口。 |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | 获取或设置客户端的代理 |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | 邮件客户端的安全模式 |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | 定义要使用的 SSL/TLS 加密协议的版本。 请注意，您只能设置 .net 框架支持的协议版本。 如果您当前版本不支持某些协议版本对于 .NET 框架，它们将被忽略和跳过。 这可能会导致 TLS 安全级别降级。在这种情况下，不会生成异常！！！ 请参阅[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols)有关更多详细信息的文档。 请使用[`SetSupportedEncryptionUnsafe`](./setsupportedencryptionunsafe)如果要设置加密协议而不进行任何兼容性检查的方法。 默认值为：Tls &#x7C; tls11 &#x7C; tls12 &#x7C; tls13（如果您当前版本的 .net 框架支持这些版本的 TLS） |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | 获取或设置邮件操作的超时时间 |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | 获取或设置 TokenProvider 允许检索访问令牌。 |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | 表示是否使用身份验证。 |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | 获取或设置指示是否必须在日志文件名中使用日期的值。 |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | 获取或设置一个布尔值，该值控制是否将 DefaultCredentials 与请求一起发送。 此选项仅用于 NTLM 身份验证！ |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | 获取或设置指示客户端是否必须为重负载操作使用多个连接的值。 请注意，使用此模式不一定会导致性能提升。 |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | 获取或设置指示是否启用流水线模式的对象。 |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | 获取或设置用户名。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection#createconnection)() | 为未链接到线程的操作（非默认连接）创建新的独立连接。 调用此方法类似于调用 CreateConnection(createAsDefaultConnection = false) 请参阅 EmailClient.ConnectionAsgmtMode 属性的文档中的更多信息。 |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection#createconnection_1)(bool) | 为操作创建新的（默认或独立的）连接。 请参阅 EmailClient.ConnectionAsgmtMode 属性的文档中的更多信息。 |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | 使用服务器完成所有操作。 |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| abstract [Noop](../../aspose.email.clients/emailclient/noop#noop)() | '无操作' 命令 |
| abstract [Noop](../../aspose.email.clients/emailclient/noop#noop_1)(IConnection) | '无操作' 命令 |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | 将日志记录设置重置为默认值。 |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | 定义要使用的 SSL/TLS 加密协议的版本。 此方法不安全，设置加密协议时不进行任何兼容性检查。 使用[`SupportedEncryption`](./supportedencryption)属性以安全地设置仅由 .net 框架明确支持的协议。 请注意，如果您当前的 .net 框架不支持此级别的安全性， 在尝试建立与服务器的连接时将引发异常。 |
| abstract [ValidateCredentials](../../aspose.email.clients/emailclient/validatecredentials)() | 检查凭据是否有效 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients](../../aspose.email.clients)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
