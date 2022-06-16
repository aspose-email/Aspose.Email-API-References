---
title: SmtpClient
second_title: Aspose.Email for .NET API 参考
description: 允许应用程序使用简单邮件传输协议 SMTP 发送消息
type: docs
weight: 17030
url: /zh/net/aspose.email.clients.smtp/smtpclient/
---
## SmtpClient class

允许应用程序使用简单邮件传输协议 (SMTP) 发送消息。

```csharp
public sealed class SmtpClient : EmailClient, IAsyncSmtpClient, IMailTransferAgent
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SmtpClient](smtpclient#constructor)() | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_1)(Configuration) | 通过使用初始化[`SmtpClient`](../smtpclient)类 的新实例配置文件设置。 |
| [SmtpClient](smtpclient#constructor_2)(string) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_4)(string, int) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_3)(string, SecurityOptions) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_5)(string, int, SecurityOptions) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_12)(string, string, ITokenProvider) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_14)(string, string, string) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_6)(string, int, string, ITokenProvider) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_8)(string, int, string, string) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_13)(string, string, ITokenProvider, SecurityOptions) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_16)(string, string, string, bool) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_15)(string, string, string, SecurityOptions) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_7)(string, int, string, ITokenProvider, SecurityOptions) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_10)(string, int, string, string, bool) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_9)(string, int, string, string, SecurityOptions) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_17)(string, string, string, bool, SecurityOptions) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |
| [SmtpClient](smtpclient#constructor_11)(string, int, string, string, bool, SecurityOptions) | 初始化[`SmtpClient`](../smtpclient)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | 获取或设置访问令牌。 |
| [AllowedAuthentication](../../aspose.email.clients.smtp/smtpclient/allowedauthentication) { get; set; } | 获取或设置用户认证类型允许的枚举 |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | 包含客户端证书集合 |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | 获取或设置定义多线程环境中连接分配模式的值 有以下连接类型: - 主连接是与邮件客户端一起创建和处理的连接。不能手动创建或处理。 - 默认连接是某些线程的默认连接。 如果默认连接存在且 ConnectionAsgmtMode 允许，则在此线程中执行的电子邮件客户端的所有方法都将隐式使用此连接。 每个线程只能存在一个默认连接。它可以手动或自动创建。它取决于 EmailClient.ConnectionAsgmtMode 属性。 这些连接可以使用 EmailClient.CreateConnection(createAsDefaultConnection = true) 方法手动创建。 如果不使用默认连接（取决于连接分配模式），则隐式使用主连接而不是它。 - 独立连接是未链接到线程的连接。它们可以手动创建，并且必须显式用作方法参数。 可以使用 EmailClient.CreateConnection() 方法或 EmailClient.CreateConnection(createAsDefaultConnection = false) 方法手动创建这些连接。 有以下连接分配类型: - ConnectionAsgmtType.UseMainOrDefault 此模式在电子邮件客户端中默认使用。 如果默认连接尚未创建，或者连接未作为方法参数显式传递，则电子邮件客户端对来自多个线程的所有操作使用主连接。 主连接是与电子邮件客户端一样同时创建的连接。 用户可以使用 CreateConnection 方法为线程创建默认连接。 如果创建了线程的默认连接，它会隐式用于在此线程中调用的电子邮件客户端的所有方法。 如果未创建线程的默认连接，则主连接用于在此线程中调用的电子邮件客户端的所有方法。 用户还可以使用 CreateConnection 方法创建未与线程链接的连接（不是默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接显式传递为他想要使用的方法的参数。 用户可以另外创建任意数量的连接。每个线程只能有一个默认连接。 请注意，如果用户使用 Thread 对象进行多任务编程，默认连接可以正常工作。 如果用户使用 ConnectionPool 或使用 Task 对象进行多任务编程，这种模式可能会导致程序的错误行为。 为避免此问题，用户必须在线程中执行的代码末尾手动处理默认连接（如果他使用它）。 - ConnectionAsgmtType.UseMain 电子邮件客户端对来自多个线程的所有操作使用主连接。 主连接是与电子邮件客户端一样同时创建的连接。 用户无法创建默认连接。 用户可以使用 CreateConnection 方法创建未与线程链接的连接（不是默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接显式传递为他想要使用的方法的参数。 用户可以另外创建任意数量的连接。 - ConnectionAsgmtType.UseDefault 电子邮件客户端对来自多个线程的所有操作隐式仅使用默认连接。在此模式下不使用主连接。 如果尚未为某个线程创建默认连接（第一次调用电子邮件客户端方法），则 电子邮件客户端在执行第一个操作之前为线程隐式创建默认连接。 用户无法使用 CreateConnection 方法为线程创建默认连接，因为它们是自动创建的。 当创建线程的默认连接时，它被隐式地用于在这个thread.read中调用的电子邮件客户端的所有方法。 用户还可以使用 CreateConnection 方法创建未与线程链接的连接（不是默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接显式传递为他想要使用的方法的参数。 用户可以另外创建任意数量的连接。每个线程只能有一个默认连接。 请注意，如果用户使用 Thread 对象进行多任务编程，默认连接可以正常工作。 如果用户使用 ConnectionPool 或使用 Task 对象进行多任务编程，这种模式可能会导致程序的错误行为。 为避免此问题，用户必须在线程中执行的代码末尾手动设置默认连接。 |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | 连接检查周期（以毫秒为单位）。 默认值为 5 分钟。 |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | 获取或设置多连接模式下的连接数 |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | 获取连接的当前状态。 |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | 根据 ConnectionAsgmtMode 选项获取当前连接 |
| override [DefaultPort](../../aspose.email.clients.smtp/smtpclient/defaultport) { get; } | 获取客户端的默认端口 |
| [DeliveryMethod](../../aspose.email.clients.smtp/smtpclient/deliverymethod) { get; set; } | 获取或设置传递方式。 |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | 获取或设置允许启用/禁用记录器的值 |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | 获取或设置建立连接时使用的问候超时。 请注意，问候超时不能无限。 电子邮件客户端可能会执行足够长的操作。要限制操作时间，用户必须使用[`Timeout`](../../aspose.email.clients/emailclient/timeout)属性。 此属性的值必须有很长的时间间隔才能防止长时间操作。 但在某些情况下，如果EmailClient 只使用Timeout 属性建立连接可能需要很长时间。 例如，邮件客户端可以使用自动模式来建立连接。 在这种模式下，电子邮件客户端会遍历所有可能的连接参数，直到建立连接。 SMTP、IMAP 和 POP3 服务器在正确连接建立的情况下向客户端发送问候字符串。 服务器可以使用隐式或显式 (START TLS) SSL/TLS 连接启动。 如果连接模式不匹配（例如，服务器等待隐式 SSL 连接，但客户端尝试建立 非安全或显式 SSL 连接），服务器获胜'不发送问候字符串。 在这种情况下，用户将等待很长时间，直到超时到达问候字符串，客户端进入下一个连接选项。 为避免此问题，引入了 GreetingTimeout 属性。此属性允许您设置问候字符串 的超时时间，并减少自动建立连接的时间。 |
| [HelloMessage](../../aspose.email.clients.smtp/smtpclient/hellomessage) { get; set; } | 获取或设置 HELO/EHLO 字符串。 |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | 获取或设置主机名。 |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | 获取或设置日志文件名 |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | 获取或设置密码。 密码限制由客户端连接的服务器实现定义。 |
| [PickupDirectoryLocation](../../aspose.email.clients.smtp/smtpclient/pickupdirectorylocation) { get; set; } | 获取或设置应用程序保存要由本地 SMTP 服务器处理的邮件消息的目录。 请注意:只允许使用绝对路径。 |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | 获取或设置端口。 |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | 获取或设置客户端代理 |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | 邮件客户端的安全模式 |
| [SmtpQueueLocation](../../aspose.email.clients.smtp/smtpclient/smtpqueuelocation) { get; set; } | 获取或设置应用程序保存要通过在 SMTP 队列中发送处理的邮件消息的目录。 请注意:只允许使用绝对路径。 |
| [SupportedAuthentication](../../aspose.email.clients.smtp/smtpclient/supportedauthentication) { get; } | 获取服务器认证类型支持的枚举 |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | 定义要使用的 SSL/TLS 加密协议的版本。 请注意，您只能设置.net框架支持的协议版本。 如果您当前版本的 .NET 框架不支持某些版本的协议，它们将被忽略并跳过。 这可能会导致 TLS 安全级别降级。在这种情况下不会产生异常！！！ 请参阅[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols)文档了解更多详细信息。 如果要设置加密协议，请使用[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)方法兼容性检查。 默认值为:Tls &#x7C; tls11 &#x7C; tls12 &#x7C; TLS13（如果您当前版本的 .net 框架支持这些版本的 TLS） |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | 获取或设置邮件操作的超时时间 |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | 获取或设置 TokenProvider 允许检索访问令牌。 |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | 表示是否使用认证。 |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | 获取或设置指示是否必须在日志文件名中使用日期的值。 |
| override [UseDefaultCredentials](../../aspose.email.clients.smtp/smtpclient/usedefaultcredentials) { get; set; } | 获取或设置一个布尔值，该值控制 DefaultCredentials 是否随请求一起发送。 |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | 获取或设置指示客户端是否必须使用多个连接进行重负载操作的值。 请注意，使用此模式不一定会导致性能提升。 |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | 获取或设置指示是否启用流水线模式的对象。 |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | 获取或设置用户名。 |
| [UseTnef](../../aspose.email.clients.smtp/smtpclient/usetnef) { get; set; } | 获取或设置一个布尔值，用于控制消息是否以 TNEF 格式发送。 注意，现在消息在加载时以 TNEF 格式发送，消息包含 tnef。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | 为未链接到线程的操作（非默认连接）创建新的独立连接。 调用此方法类似于调用 CreateConnection(createAsDefaultConnection = false) 请在文档中查看 EmailClient.ConnectionAsgmtMode 属性的更多信息。 |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | 为操作创建新的（默认或独立的）连接。 请在 EmailClient.ConnectionAsgmtMode 属性的文档中查看更多信息。 |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | 完成与服务器的所有操作。 |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_3)(string, MailAddressCollection, MailMessage) | 将指定消息转发给收件人 |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_4)(string, MailAddressCollection, Stream) | 将指定消息转发给收件人 |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_5)(string, string, MailMessage) | 将指定消息转发给收件人 |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward)(IConnection, string, MailAddressCollection, MailMessage) | 将指定的消息转发给收件人 |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_1)(IConnection, string, MailAddressCollection, Stream) | 将指定的消息转发给收件人 |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_2)(IConnection, string, string, MailMessage) | 将指定的消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_6)(string, MailAddressCollection, MailMessage) | 将指定消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_8)(string, MailAddressCollection, Stream) | 将指定消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_10)(string, string, MailMessage) | 将指定消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync)(IConnection, string, MailAddressCollection, MailMessage) | 将指定的消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_2)(IConnection, string, MailAddressCollection, Stream) | 将指定的消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_4)(IConnection, string, string, MailMessage) | 将指定的消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_7)(string, MailAddressCollection, MailMessage, CancellationToken) | 将指定消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_9)(string, MailAddressCollection, Stream, CancellationToken) | 将指定消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_11)(string, string, MailMessage, CancellationToken) | 将指定消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_1)(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) | 将指定的消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_3)(IConnection, string, MailAddressCollection, Stream, CancellationToken) | 将指定的消息转发给收件人 |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_5)(IConnection, string, string, MailMessage, CancellationToken) | 将指定的消息转发给收件人 |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop)() | '无操作'命令 |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop_1)(IConnection) | 'No operation' 命令 |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync)() | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_3)(CancellationToken) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_1)(IConnection) | 'No operation' 命令 |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_2)(IConnection, CancellationToken) | 'No operation' 命令 |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | 将日志记录设置重置为默认值。 |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_8)(IEnumerable&lt;MailMessage&gt;) | 发送指定消息。 |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_5)(MailMessage) | 发送指定消息。 |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_6)(MailMessageCollection) | 发送指定的消息集合。 |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_7)(params MailMessage[]) | 发送指定消息。 |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_3)(IConnection, IEnumerable&lt;MailMessage&gt;) | 发送指定消息。 |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send)(IConnection, MailMessage) | 发送指定消息。 |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_1)(IConnection, MailMessageCollection) | 发送指定的消息集合。 |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_2)(IConnection, params MailMessage[]) | 发送指定消息。 |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_9)(string, string, string, string) | 创建并发送指定的消息。 |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_4)(IConnection, string, string, string, string) | 创建并发送指定的消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_16)(IEnumerable&lt;MailMessage&gt;) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_11)(MailMessage) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_13)(MailMessageCollection) | 发送指定的消息集合。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_15)(params MailMessage[]) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_10)(SmtpSend) |  |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_20)(CancellationToken, params MailMessage[]) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_5)(IConnection, IEnumerable&lt;MailMessage&gt;) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync)(IConnection, MailMessage) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_2)(IConnection, MailMessageCollection) | 发送指定的消息集合。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_4)(IConnection, params MailMessage[]) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_17)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_12)(MailMessage, CancellationToken) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_14)(MailMessageCollection, CancellationToken) | 发送指定的消息集合。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_9)(IConnection, CancellationToken, params MailMessage[]) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_6)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_1)(IConnection, MailMessage, CancellationToken) | 发送指定消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_3)(IConnection, MailMessageCollection, CancellationToken) | 发送指定的消息集合。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_18)(string, string, string, string) | 创建并发送指定的消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_7)(IConnection, string, string, string, string) | 创建并发送指定的消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_19)(string, string, string, string, CancellationToken) | 创建并发送指定的消息。 |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_8)(IConnection, string, string, string, string, CancellationToken) | 创建并发送指定的消息。 |
| [SendToQueue](../../aspose.email.clients.smtp/smtpclient/sendtoqueue)(IEnumerable&lt;MailMessage&gt;) | 将消息附加到队列 |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | 定义要使用的 SSL/TLS 加密协议的版本。 此方法不安全，并且在设置加密协议时没有任何兼容性检查。 使用[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption)属性来安全地设置仅由 .net 框架明确支持的协议。 请注意，如果您当前的 .net 框架不支持此级别的安全性，则 在尝试建立与服务器的连接时会抛出异常。 |
| override [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials)() | 执行凭据验证 |
| [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials_1)(IConnection) | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync)() | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | 执行凭证验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | 执行凭据验证 |
| static [CreateAsync](../../aspose.email.clients.smtp/smtpclient/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | 创建[`SmtpClient`](../smtpclient)类的新实例 |

### 也可以看看

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncSmtpClient](../iasyncsmtpclient)
* interface [IMailTransferAgent](../imailtransferagent)
* 命名空间 [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
