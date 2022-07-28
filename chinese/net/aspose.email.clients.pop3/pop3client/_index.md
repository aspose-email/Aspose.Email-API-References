---
title: Pop3Client
second_title: Aspose.Email for .NET API 参考
description: 允许应用程序使用邮局协议版本 3 POP3 访问和操作 邮件
type: docs
weight: 16880
url: /zh/net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

允许应用程序使用邮局协议版本 3 (POP3) 访问和操作 邮件。

```csharp
public sealed class Pop3Client : EmailClient, IAsyncPop3Client
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Pop3Client](pop3client#constructor)() | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_1)(string) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_3)(string, int) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_2)(string, SecurityOptions) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_4)(string, int, SecurityOptions) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_11)(string, string, string) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_6)(string, int, string, string) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_12)(string, string, string, SecurityOptions) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_5)(string, int, string, ITokenProvider, SecurityOptions) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_9)(string, int, string, string, RemoteCertificateValidationCallback) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_7)(string, int, string, string, SecurityOptions) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_8)(string, int, string, string, bool, SecurityOptions) | 初始化[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_10)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | 初始化[`Pop3Client`](../pop3client) class |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | 获取或设置访问令牌。 |
| [AllowedAuthentication](../../aspose.email.clients.pop3/pop3client/allowedauthentication) { get; set; } | 获取或设置用户认证类型允许的枚举 |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | 包含客户端证书的集合 |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | 获取或设置定义多线程环境下连接分配模式的值 连接类型有以下几种： - 主连接是与邮件客户端一起创建和处理的连接，不能手动创建或处理。 -默认连接是某些线程的默认连接。 如果默认连接存在并且ConnectionAsgmtMode允许，则在该线程中执行的电子邮件客户端的所有方法都将隐式使用该连接。 每个线程只能存在一个默认连接。它可以手动或自动创建。它取决于 EmailClient.ConnectionAsgmtMode 属性。 可以使用 EmailClient.CreateConnection(createAsDefaultConnection = true) 方法手动创建这些连接。 如果不使用默认连接（取决于连接分配模式），则隐式使用主连接。 - 独立连接是未链接到线程。它们可以手动创建，并且必须显式用作方法参数。 可以使用 EmailClient.CreateConnection() 方法或 EmailClient.CreateConnection(createAsDefaultConnection = false) 方法手动创建这些连接。 有以下连接分配类型： - ConnectionAsgmtType.UseMainOrDefault 此模式在电子邮件客户端中默认使用。 如果默认连接尚未创建，或者连接未作为方法参数显式传递，则电子邮件客户端对来自多个线程的所有操作使用主连接。 主连接是与电子邮件客户端同时创建的连接。 用户可以使用 CreateConnection 方法为线程创建默认连接。 如果创建了线程的默认连接，它将隐式用于在此线程中调用的电子邮件客户端的所有方法。 如果未创建线程的默认连接，则将主连接用于在此调用的电子邮件客户端的所有方法thread. 用户还可以使用 CreateConnection 方法创建未与线程链接的连接（非默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接作为他想要使用的方法的参数显式传递。 用户可以另外创建任意数量的连接。每个线程只能有一个默认连接。 请注意，如果用户使用 Thread 对象进行多任务编程，默认连接可以正常工作。 如果用户使用 ConnectionPool 或使用任务对象进行多任务编程，这种模式可能会导致程序的错误行为。 为了避免这个问题，用户必须在执行的代码末尾手动处理默认连接（如果他使用它） thread. - ConnectionAsgmtType.UseMain 电子邮件客户端对来自多个线程的所有操作使用主连接。 主连接是与电子邮件客户端同时创建的连接。 用户无法创建默认连接。 用户可以使用 CreateConnection 方法创建未与线程链接的连接（非默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接作为他想要使用的方法的参数显式传递。 用户可以另外创建任意数量的连接。 - ConnectionAsgmtType.UseDefault 电子邮件客户端对来自多个线程的所有操作隐式仅使用默认连接。此模式不使用主连接。 如果尚未为某些线程创建默认连接（第一次调用电子邮件客户端方法）， 电子邮件客户端在执行第一次操作之前为线程隐式创建默认连接。 用户不能使用 CreateConnection 方法为线程创建默认连接，因为它们是自动创建的。 创建线程的默认连接时，它会隐式用于在此线程中调用的电子邮件客户端的所有方法。read. 用户还可以使用 CreateConnection 方法创建未与线程链接的连接（非默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接作为他想要使用的方法的参数显式传递。 用户可以另外创建任意数量的连接。每个线程只能有一个默认连接。 请注意，如果用户使用 Thread 对象进行多任务编程，默认连接可以正常工作。 如果用户使用 ConnectionPool 或使用任务对象进行多任务编程，这种模式可能会导致程序的错误行为。 为了避免这个问题，用户必须在线程中执行的代码末尾手动处理默认连接。 |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | 以毫秒为单位的连接检查周期。 默认值为 5 分钟。 |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | 获取或设置多连接模式下的连接数 |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | 获取连接的当前状态。 |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | 根据 ConnectionAsgmtMode 选项获取当前连接 |
| override [DefaultPort](../../aspose.email.clients.pop3/pop3client/defaultport) { get; } | 获取客户端的默认端口 |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | 获取或设置允许启用/禁用记录器的值 |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | 获取或设置建立连接时使用的问候超时。 请注意，问候超时不能是无限的。 电子邮件客户端可能会执行足够长的操作。为了限制用户必须使用的操作时间[`Timeout`](../../aspose.email.clients/emailclient/timeout)财产。 此属性的值必须具有较长的时间间隔，以免妨碍长时间操作。 但在某些情况下，如果EmailClient 只使用Timeout 属性建立连接可能需要很长时间。 例如，邮件客户端可以使用自动模式来建立连接。 在此模式下，电子邮件客户端会检查所有可能的连接参数，直到建立连接。 SMTP、IMAP 和 POP3 服务器在正确建立连接的情况下向客户端发送问候字符串。 服务器可以使用隐式或显式 (START TLS) SSL/TLS 连接启动。 如果连接模式不匹配（例如，服务器等待隐式 SSL 连接，但客户端尝试建立 非安全或显式 SSL 连接），服务器将不会发送问候字符串。 在这种情况下，用户将等待很长时间，直到超时到达问候字符串，客户端进入下一个连接选项。 为避免此问题，引入了 GreetingTimeout 属性。此属性允许您设置问候字符串的超时时间， 并减少自动连接建立的时间。 |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | 获取或设置主机名。 |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | 获取或设置日志文件名 |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | 获取或设置密码。 密码限制由客户端连接的服务器实现定义。 |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | 获取或设置端口。 |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | 获取或设置客户端的代理 |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | 邮件客户端的安全模式 |
| [SupportedAuthentication](../../aspose.email.clients.pop3/pop3client/supportedauthentication) { get; } | 获取服务器认证类型支持的枚举 |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | 定义要使用的 SSL/TLS 加密协议的版本。 请注意，您只能设置 .net 框架支持的协议版本。 如果您当前版本不支持某些协议版本对于 .NET 框架，它们将被忽略和跳过。 这可能会导致 TLS 安全级别降级。在这种情况下，不会生成异常！！！ 请参阅[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols)有关更多详细信息的文档。 请使用[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)如果要设置加密协议而不进行任何兼容性检查的方法。 默认值为：Tls &#x7C; tls11 &#x7C; tls12 &#x7C; tls13（如果您当前版本的 .net 框架支持这些版本的 TLS） |
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
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes)() | 提交删除 |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_1)(IConnection) | 提交删除 |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_2)(int) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync)() | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_5)(CancellationToken) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_1)(IConnection) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_3)(int) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_2)(IConnection, CancellationToken) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_4)(int, CancellationToken) | 提交删除 |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | 为未链接到线程的操作（非默认连接）创建新的独立连接。 调用此方法类似于调用 CreateConnection(createAsDefaultConnection = false) 请参阅 EmailClient.ConnectionAsgmtMode 属性的文档中的更多信息。 |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | 为操作创建新的（默认或独立的）连接。 请参阅 EmailClient.ConnectionAsgmtMode 属性的文档中的更多信息。 |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_2)(int) | 删除消息 |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_3)(string) | 删除消息 |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage)(IConnection, int) | 删除消息 |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_1)(IConnection, string) | 删除消息 |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_4)(int) | 删除消息 |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_6)(string) | 删除消息 |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync)(IConnection, int) | 删除消息 |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_2)(IConnection, string) | 删除消息 |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_5)(int, CancellationToken) | 删除消息 |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_7)(string, CancellationToken) | 删除消息 |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_1)(IConnection, int, CancellationToken) | 删除消息 |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_3)(IConnection, string, CancellationToken) | 删除消息 |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages)() | 删除所有消息 |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages_1)(IConnection) | 删除所有消息 |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync)() | 删除所有消息 |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_3)(CancellationToken) | 删除所有消息 |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_1)(IConnection) | 删除所有消息 |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_2)(IConnection, CancellationToken) | 删除所有消息 |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | 使用服务器完成所有操作。 |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_2)(int) | 获取消息 |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_3)(string) | 获取消息 |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage)(IConnection, int) | 获取消息 |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_1)(IConnection, string) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_4)(int) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_6)(string) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync)(IConnection, int) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_2)(IConnection, string) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_5)(int, CancellationToken) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_7)(string, CancellationToken) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_1)(IConnection, int, CancellationToken) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_3)(IConnection, string, CancellationToken) | 获取消息 |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | 获取消息 |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | 获取消息 |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | 获取消息 |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | 获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | 异步获取消息 |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo)() | 获取邮箱状态信息 |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_3)(bool) | 获取邮箱状态信息 |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_1)(IConnection) | 获取邮箱状态信息 |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_2)(IConnection, bool) | 获取邮箱状态信息 |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync)() | 获取邮箱状态信息 |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_5)(bool) | 获取邮箱状态信息 |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_7)(CancellationToken) | 获取邮箱状态信息 |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_1)(IConnection) | 获取邮箱状态信息 |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_6)(bool, CancellationToken) | 获取邮箱状态信息 |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_2)(IConnection, bool) | 获取邮箱状态信息 |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_4)(IConnection, CancellationToken) | 获取邮箱状态信息 |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_3)(IConnection, bool, CancellationToken) | 获取邮箱状态信息 |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize)() | 获取邮箱大小 |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize_1)(IConnection) | 获取邮箱大小 |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync)() | 获取邮箱大小 |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_3)(CancellationToken) | 获取邮箱大小 |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_1)(IConnection) | 获取邮箱大小 |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_2)(IConnection, CancellationToken) | 获取邮箱大小 |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount)() | 获取消息计数 |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_3)(bool) | 获取消息计数 |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_1)(IConnection) | 获取消息计数 |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_2)(IConnection, bool) | 获取消息计数 |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync)() | 获取消息计数 |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_5)(bool) | 获取消息计数 |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_7)(CancellationToken) | 获取消息计数 |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_1)(IConnection) | 获取消息计数 |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_6)(bool, CancellationToken) | 获取消息计数 |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_2)(IConnection, bool) | 获取消息计数 |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_4)(IConnection, CancellationToken) | 获取消息计数 |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_3)(IConnection, bool, CancellationToken) | 获取消息计数 |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_2)(int) | 获取消息头 |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_3)(string) | 获取消息头 |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders)(IConnection, int) | 获取消息头 |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_1)(IConnection, string) | 获取消息头 |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_4)(int) | 获取消息头 |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_6)(string) | 获取消息头 |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync)(IConnection, int) | 获取消息头 |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_2)(IConnection, string) | 获取消息头 |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_5)(int, CancellationToken) | 获取消息头 |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_7)(string, CancellationToken) | 获取消息头 |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_1)(IConnection, int, CancellationToken) | 获取消息头 |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_3)(IConnection, string, CancellationToken) | 获取消息头 |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_4)(int) | 获取该消息的信息 |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_6)(string) | 获取该消息的信息 |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo)(IConnection, int) | 获取该消息的信息 |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_2)(IConnection, string) | 获取该消息的信息 |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_5)(int, Pop3ListFields) | 获取该消息的信息 |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_7)(string, Pop3ListFields) | 获取该消息的信息 |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_1)(IConnection, int, Pop3ListFields) | 获取该消息的信息 |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_3)(IConnection, string, Pop3ListFields) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_8)(int) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_12)(string) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync)(IConnection, int) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_4)(IConnection, string) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_11)(int, CancellationToken) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_9)(int, Pop3ListFields) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_15)(string, CancellationToken) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_13)(string, Pop3ListFields) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_3)(IConnection, int, CancellationToken) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_1)(IConnection, int, Pop3ListFields) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_7)(IConnection, string, CancellationToken) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_5)(IConnection, string, Pop3ListFields) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_10)(int, Pop3ListFields, CancellationToken) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_14)(string, Pop3ListFields, CancellationToken) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_2)(IConnection, int, Pop3ListFields, CancellationToken) | 获取该消息的信息 |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_6)(IConnection, string, Pop3ListFields, CancellationToken) | 获取该消息的信息 |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_2)(int) | 获取消息的大小 |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_3)(string) | 获取消息的大小 |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize)(IConnection, int) | 获取消息的大小 |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_1)(IConnection, string) | 获取消息的大小 |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_4)(int) | 获取消息的大小 |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_6)(string) | 获取消息的大小 |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync)(IConnection, int) | 获取消息的大小 |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_2)(IConnection, string) | 获取消息的大小 |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_5)(int, CancellationToken) | 获取消息的大小 |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_7)(string, CancellationToken) | 获取消息的大小 |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_1)(IConnection, int, CancellationToken) | 获取消息的大小 |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_3)(IConnection, string, CancellationToken) | 获取消息的大小 |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid_1)(int) | 获取消息唯一id |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid)(IConnection, int) | 获取消息唯一id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_2)(int) | 获取消息唯一id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync)(IConnection, int) | 获取消息唯一id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_3)(int, CancellationToken) | 获取消息唯一id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_1)(IConnection, int, CancellationToken) | 获取消息唯一id |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages)() | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_11)(bool) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_1)(IConnection) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_12)(IEnumerable&lt;int&gt;) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_13)(IEnumerable&lt;string&gt;) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_10)(MailQuery) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_8)(Pop3ListFields) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_5)(IConnection, bool) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_6)(IConnection, IEnumerable&lt;int&gt;) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_7)(IConnection, IEnumerable&lt;string&gt;) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_4)(IConnection, MailQuery) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_2)(IConnection, Pop3ListFields) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_9)(Pop3ListFields, bool, MailQuery) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_3)(IConnection, Pop3ListFields, bool, MailQuery) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync)() | 列出消息。 获取搜索消息的信息 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_17)(bool) | 列出消息。 获取搜索消息的信息 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_19)(CancellationToken) | 列出消息。 获取搜索消息的信息 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_1)(IConnection) | 列出消息。 获取搜索消息的信息 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_15)(MailQuery) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_11)(Pop3ListFields) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_18)(bool, CancellationToken) | 列出消息。 获取搜索消息的信息 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_8)(IConnection, bool) | 列出消息。 获取搜索消息的信息 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_10)(IConnection, CancellationToken) | 列出消息。 获取搜索消息的信息 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_6)(IConnection, MailQuery) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_2)(IConnection, Pop3ListFields) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_16)(MailQuery, CancellationToken) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_14)(Pop3ListFields, CancellationToken) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_9)(IConnection, bool, CancellationToken) | 列出消息。 获取搜索消息的信息 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_7)(IConnection, MailQuery, CancellationToken) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_5)(IConnection, Pop3ListFields, CancellationToken) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_12)(Pop3ListFields, bool, MailQuery) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_3)(IConnection, Pop3ListFields, bool, MailQuery) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_13)(Pop3ListFields, bool, MailQuery, CancellationToken) | 列出消息。 |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_4)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | 列出消息。 |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_3)(IEnumerable&lt;int&gt;) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_2)(IEnumerable&lt;Pop3MessageInfo&gt;) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_1)(IConnection, IEnumerable&lt;int&gt;) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_7)(IEnumerable&lt;int&gt;) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_5)(IEnumerable&lt;Pop3MessageInfo&gt;) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_4)(Pop3LoadMessageInfoList) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_2)(IConnection, IEnumerable&lt;int&gt;) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_8)(IEnumerable&lt;int&gt;, CancellationToken) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_6)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_3)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | 加载 Pop3MessageInfo 列表 |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_1)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | 加载 Pop3MessageInfo 列表 |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop)() | '无操作' 命令 |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop_1)(IConnection) | '无操作' 命令 |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync)() | '无操作' 命令 |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_3)(CancellationToken) | '无操作' 命令 |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_1)(IConnection) | '无操作' 命令 |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_2)(IConnection, CancellationToken) | '无操作' 命令 |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | 将日志记录设置重置为默认值。 |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_4)(int, Stream) | 获取消息并将其保存为流 |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_5)(int, string) | 获取消息并将其保存到文件中 |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_6)(string, Stream) | 获取消息并将其保存为流 |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_7)(string, string) | 获取消息并将其保存到文件中 |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage)(IConnection, int, Stream) | 获取消息并将其保存为流 |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_1)(IConnection, int, string) | 获取消息并将其保存到文件中 |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_2)(IConnection, string, Stream) | 获取消息并将其保存为流 |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_3)(IConnection, string, string) | 获取消息并将其保存到文件中 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_8)(int, Stream) | 获取消息并将其保存为流 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_10)(int, string) | 获取消息并将其保存到文件中 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_12)(string, Stream) | 获取消息并将其保存为流 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_14)(string, string) | 获取消息并将其保存到文件中 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync)(IConnection, int, Stream) | 获取消息并将其保存为流 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_2)(IConnection, int, string) | 获取消息并将其保存到文件中 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | 获取消息并将其保存为流 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_6)(IConnection, string, string) | 获取消息并将其保存到文件中 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | 获取消息并将其保存为流 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | 获取消息并将其保存到文件中 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | 获取消息并将其保存为流 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | 获取消息并将其保存到文件中 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | 获取消息并将其保存为流 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | 获取消息并将其保存到文件中 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | 获取消息并将其保存为流 |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | 获取消息并将其保存到文件中 |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | 定义要使用的 SSL/TLS 加密协议的版本。 此方法不安全，设置加密协议时不进行任何兼容性检查。 使用[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption)属性以安全地设置仅由 .net 框架明确支持的协议。 请注意，如果您当前的 .net 框架不支持此级别的安全性， 在尝试建立与服务器的连接时将引发异常。 |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages)() | 取消删除邮件。 如果任何邮件已被 POP3 服务器标记为已删除，它们将被取消标记。 |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages_1)(IConnection) | 取消删除邮件。 如果任何邮件已被 POP3 服务器标记为已删除，它们将被取消标记。 |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync)() | 取消删除邮件。 如果任何邮件已被 POP3 服务器标记为已删除，它们将被取消标记。 |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_3)(CancellationToken) | 取消删除邮件。 如果任何邮件已被 POP3 服务器标记为已删除，它们将被取消标记。 |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_1)(IConnection) | 取消删除邮件。 如果任何邮件已被 POP3 服务器标记为已删除，它们将被取消标记。 |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_2)(IConnection, CancellationToken) | 取消删除邮件。 如果任何邮件已被 POP3 服务器标记为已删除，它们将被取消标记。 |
| override [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials)() | 执行凭据验证 |
| [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials_1)(IConnection) | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync)() | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | 执行凭据验证 |
| static [CreateAsync](../../aspose.email.clients.pop3/pop3client/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | 创建一个新的实例[`Pop3Client`](../pop3client) class |

### 也可以看看

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncPop3Client](../iasyncpop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
