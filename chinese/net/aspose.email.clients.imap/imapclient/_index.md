---
title: ImapClient
second_title: Aspose.Email for .NET API 参考
description: 允许应用程序使用 Internet 消息访问协议 IMAP 访问和操作 消息
type: docs
weight: 16280
url: /zh/net/aspose.email.clients.imap/imapclient/
---
## ImapClient class

允许应用程序使用 Internet 消息访问协议 (IMAP) 访问和操作 消息。

```csharp
public sealed class ImapClient : EmailClient, IAsyncImapClient
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ImapClient](imapclient#constructor)() | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_1)(string) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_3)(string, int) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_2)(string, SecurityOptions) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_4)(string, int, SecurityOptions) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_13)(string, string, ITokenProvider) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_15)(string, string, string) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_5)(string, int, string, ITokenProvider) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_7)(string, int, string, string) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_14)(string, string, ITokenProvider, SecurityOptions) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_17)(string, string, string, bool) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_16)(string, string, string, SecurityOptions) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_6)(string, int, string, ITokenProvider, SecurityOptions) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_9)(string, int, string, string, bool) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_11)(string, int, string, string, RemoteCertificateValidationCallback) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_8)(string, int, string, string, SecurityOptions) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_18)(string, string, string, bool, SecurityOptions) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_10)(string, int, string, string, bool, SecurityOptions) | 初始化[`ImapClient`](../imapclient) class |
| [ImapClient](imapclient#constructor_12)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | 初始化[`ImapClient`](../imapclient) class |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | 获取或设置访问令牌。 |
| [AllowedAuthentication](../../aspose.email.clients.imap/imapclient/allowedauthentication) { get; set; } | 获取或设置用户认证类型允许的枚举 |
| [AnnotateSupported](../../aspose.email.clients.imap/imapclient/annotatesupported) { get; set; } | 获取是否支持 ANNOTATE 扩展的信息 查看更多：https://tools.ietf.org/html/rfc5257 |
| [AutoCommit](../../aspose.email.clients.imap/imapclient/autocommit) { get; set; } | 指示是否在更改文件夹或关闭连接之前自动执行提交操作 。 |
| [ChildrenSupported](../../aspose.email.clients.imap/imapclient/childrensupported) { get; set; } | 获取是否支持 CHILDREN 扩展的信息 查看更多：https://tools.ietf.org/html/rfc3348 |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | 包含客户端证书的集合 |
| [ClientIdentificationInfo](../../aspose.email.clients.imap/imapclient/clientidentificationinfo) { get; set; } | 获取或设置客户端标识信息 查看更多：https://tools.ietf.org/html/rfc2971 |
| [CompressSupported](../../aspose.email.clients.imap/imapclient/compresssupported) { get; set; } | 获取是否支持 COMPRESS 扩展的信息 查看更多：https://tools.ietf.org/html/rfc4978 |
| [CondstoreSupported](../../aspose.email.clients.imap/imapclient/condstoresupported) { get; set; } | 获取是否支持 CONDSTORE 扩展的信息 查看更多：https://tools.ietf.org/html/rfc7162 |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | 获取或设置定义多线程环境下连接分配模式的值 连接类型有以下几种： - 主连接是与邮件客户端一起创建和处理的连接，不能手动创建或处理。 -默认连接是某些线程的默认连接。 如果默认连接存在并且ConnectionAsgmtMode允许，则在该线程中执行的电子邮件客户端的所有方法都将隐式使用该连接。 每个线程只能存在一个默认连接。它可以手动或自动创建。它取决于 EmailClient.ConnectionAsgmtMode 属性。 可以使用 EmailClient.CreateConnection(createAsDefaultConnection = true) 方法手动创建这些连接。 如果不使用默认连接（取决于连接分配模式），则隐式使用主连接。 - 独立连接是未链接到线程。它们可以手动创建，并且必须显式用作方法参数。 可以使用 EmailClient.CreateConnection() 方法或 EmailClient.CreateConnection(createAsDefaultConnection = false) 方法手动创建这些连接。 有以下连接分配类型： - ConnectionAsgmtType.UseMainOrDefault 此模式在电子邮件客户端中默认使用。 如果默认连接尚未创建，或者连接未作为方法参数显式传递，则电子邮件客户端对来自多个线程的所有操作使用主连接。 主连接是与电子邮件客户端同时创建的连接。 用户可以使用 CreateConnection 方法为线程创建默认连接。 如果创建了线程的默认连接，它将隐式用于在此线程中调用的电子邮件客户端的所有方法。 如果未创建线程的默认连接，则将主连接用于在此调用的电子邮件客户端的所有方法thread. 用户还可以使用 CreateConnection 方法创建未与线程链接的连接（非默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接作为他想要使用的方法的参数显式传递。 用户可以另外创建任意数量的连接。每个线程只能有一个默认连接。 请注意，如果用户使用 Thread 对象进行多任务编程，默认连接可以正常工作。 如果用户使用 ConnectionPool 或使用任务对象进行多任务编程，这种模式可能会导致程序的错误行为。 为了避免这个问题，用户必须在执行的代码末尾手动处理默认连接（如果他使用它） thread. - ConnectionAsgmtType.UseMain 电子邮件客户端对来自多个线程的所有操作使用主连接。 主连接是与电子邮件客户端同时创建的连接。 用户无法创建默认连接。 用户可以使用 CreateConnection 方法创建未与线程链接的连接（非默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接作为他想要使用的方法的参数显式传递。 用户可以另外创建任意数量的连接。 - ConnectionAsgmtType.UseDefault 电子邮件客户端对来自多个线程的所有操作隐式仅使用默认连接。此模式不使用主连接。 如果尚未为某些线程创建默认连接（第一次调用电子邮件客户端方法）， 电子邮件客户端在执行第一次操作之前为线程隐式创建默认连接。 用户不能使用 CreateConnection 方法为线程创建默认连接，因为它们是自动创建的。 创建线程的默认连接时，它会隐式用于在此线程中调用的电子邮件客户端的所有方法。read. 用户还可以使用 CreateConnection 方法创建未与线程链接的连接（非默认连接）。 如果用户想要使用其他连接（不是主连接，也不是默认连接），他必须将此连接作为他想要使用的方法的参数显式传递。 用户可以另外创建任意数量的连接。每个线程只能有一个默认连接。 请注意，如果用户使用 Thread 对象进行多任务编程，默认连接可以正常工作。 如果用户使用 ConnectionPool 或使用任务对象进行多任务编程，这种模式可能会导致程序的错误行为。 为了避免这个问题，用户必须在线程中执行的代码末尾手动处理默认连接。 |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | 以毫秒为单位的连接检查周期。 默认值为 5 分钟。 |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | 获取或设置多连接模式下的连接数 |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | 获取连接的当前状态。 |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | 根据 ConnectionAsgmtMode 选项获取当前连接 |
| [CurrentFolder](../../aspose.email.clients.imap/imapclient/currentfolder) { get; set; } | 获取当前文件夹 |
| override [DefaultPort](../../aspose.email.clients.imap/imapclient/defaultport) { get; } | 获取客户端的默认端口 |
| [Delimiter](../../aspose.email.clients.imap/imapclient/delimiter) { get; set; } | 获取或设置文件夹层次结构的分隔符。 |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | 获取或设置允许启用/禁用记录器的值 |
| [EnableSupported](../../aspose.email.clients.imap/imapclient/enablesupported) { get; set; } | 获取是否支持ENABLE扩展的信息 查看更多：https://tools.ietf.org/html/rfc5161 |
| [ESearchSupported](../../aspose.email.clients.imap/imapclient/esearchsupported) { get; set; } | 获取是否支持 ESEARCH 扩展的信息 查看更多：https://tools.ietf.org/html/rfc4731 |
| [ExchangeIdAutomatically](../../aspose.email.clients.imap/imapclient/exchangeidautomatically) { get; set; } | 获取或设置值，该值指示客户端是否应自动将有关自身的信息引入服务器。 查看更多：https://tools.ietf.org/html/rfc2971 |
| [ExtendedListSupported](../../aspose.email.clients.imap/imapclient/extendedlistsupported) { get; set; } | 获取是否支持 LIST 命令扩展的信息 查看更多 https://tools.ietf.org/html/rfc5258 |
| [GmExt1Supported](../../aspose.email.clients.imap/imapclient/gmext1supported) { get; set; } | 定义是否支持 Google X-GM-EXT-1 扩展 |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | 获取或设置建立连接时使用的问候超时。 请注意，问候超时不能是无限的。 电子邮件客户端可能会执行足够长的操作。为了限制用户必须使用的操作时间[`Timeout`](../../aspose.email.clients/emailclient/timeout)财产。 此属性的值必须具有较长的时间间隔，以免妨碍长时间操作。 但在某些情况下，如果EmailClient 只使用Timeout 属性建立连接可能需要很长时间。 例如，邮件客户端可以使用自动模式来建立连接。 在此模式下，电子邮件客户端会检查所有可能的连接参数，直到建立连接。 SMTP、IMAP 和 POP3 服务器在正确建立连接的情况下向客户端发送问候字符串。 服务器可以使用隐式或显式 (START TLS) SSL/TLS 连接启动。 如果连接模式不匹配（例如，服务器等待隐式 SSL 连接，但客户端尝试建立 非安全或显式 SSL 连接），服务器将不会发送问候字符串。 在这种情况下，用户将等待很长时间，直到超时到达问候字符串，客户端进入下一个连接选项。 为避免此问题，引入了 GreetingTimeout 属性。此属性允许您设置问候字符串的超时时间， 并减少自动连接建立的时间。 |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | 获取或设置主机名。 |
| [IdSupported](../../aspose.email.clients.imap/imapclient/idsupported) { get; set; } | 获取是否支持ID扩展的信息 查看更多：https://tools.ietf.org/html/rfc2971 |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | 获取或设置日志文件名 |
| [MailboxInfo](../../aspose.email.clients.imap/imapclient/mailboxinfo) { get; } | 获取一组专用邮箱 查看更多：http://tools.ietf.org/html/rfc6154 和 https://tools.ietf.org/html/rfc8457 |
| [MoveSupported](../../aspose.email.clients.imap/imapclient/movesupported) { get; set; } | 获取是否支持MOVE扩展的信息 查看更多：https://tools.ietf.org/html/rfc6851 |
| [NamespaceSupported](../../aspose.email.clients.imap/imapclient/namespacesupported) { get; set; } | 获取是否支持 NAMESPACE 扩展的信息 查看更多：https://tools.ietf.org/html/rfc2342 |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | 获取或设置密码。 密码限制由客户端连接的服务器实现定义。 |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | 获取或设置端口。 |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | 获取或设置客户端的代理 |
| [QresyncSupported](../../aspose.email.clients.imap/imapclient/qresyncsupported) { get; set; } | 获取是否支持QRESYNC扩展的信息 查看更多：https://tools.ietf.org/html/rfc7162 |
| [QuotaSupported](../../aspose.email.clients.imap/imapclient/quotasupported) { get; set; } | 获取是否支持配额的信息 |
| [ReadOnly](../../aspose.email.clients.imap/imapclient/readonly) { get; set; } | 获取或设置值，该值指示是否允许更改邮箱的永久状态，包括每个用户的状态。 |
| [SaslIrSupported](../../aspose.email.clients.imap/imapclient/saslirsupported) { get; set; } | 获取是否支持 SASL 初始客户端响应扩展的信息 查看更多：https://tools.ietf.org/html/rfc4959 |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | 邮件客户端的安全模式 |
| [ServerIdentificationInfo](../../aspose.email.clients.imap/imapclient/serveridentificationinfo) { get; } | 获取服务器标识信息 查看更多：https://tools.ietf.org/html/rfc2971 |
| [ServerSupportedCompression](../../aspose.email.clients.imap/imapclient/serversupportedcompression) { get; } | 获取服务器支持哪些压缩类型的信息。 查看更多：https://tools.ietf.org/html/rfc4978 |
| [SortSupported](../../aspose.email.clients.imap/imapclient/sortsupported) { get; set; } | 获取是否支持排序命令的信息 |
| [SpecialUseSupported](../../aspose.email.clients.imap/imapclient/specialusesupported) { get; set; } | 获取是否支持特殊用途邮箱的信息 查看更多：https://tools.ietf.org/html/rfc6154 |
| [SupportedAuthentication](../../aspose.email.clients.imap/imapclient/supportedauthentication) { get; } | 获取服务器认证类型支持的枚举 |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | 定义要使用的 SSL/TLS 加密协议的版本。 请注意，您只能设置 .net 框架支持的协议版本。 如果您当前版本不支持某些协议版本对于 .NET 框架，它们将被忽略和跳过。 这可能会导致 TLS 安全级别降级。在这种情况下，不会生成异常！！！ 请参阅[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols)有关更多详细信息的文档。 请使用[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)如果要设置加密协议而不进行任何兼容性检查的方法。 默认值为：Tls &#x7C; tls11 &#x7C; tls12 &#x7C; tls13（如果您当前版本的 .net 框架支持这些版本的 TLS） |
| [ThreadAlgorithms](../../aspose.email.clients.imap/imapclient/threadalgorithms) { get; } | 获取支持的线程算法 |
| [ThreadSupported](../../aspose.email.clients.imap/imapclient/threadsupported) { get; set; } | 获取是否支持 Thread 命令的信息 |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | 获取或设置邮件操作的超时时间 |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | 获取或设置 TokenProvider 允许检索访问令牌。 |
| [UidPlusSupported](../../aspose.email.clients.imap/imapclient/uidplussupported) { get; set; } | 获取是否支持UIDPLUS扩展的信息 查看更多：https://tools.ietf.org/html/rfc4315 |
| [UnselectSupported](../../aspose.email.clients.imap/imapclient/unselectsupported) { get; set; } | 获取是否支持UNSELECT扩展的信息 查看更多：https://tools.ietf.org/html/rfc2342 |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | 表示是否使用身份验证。 |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | 获取或设置指示是否必须在日志文件名中使用日期的值。 |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | 获取或设置一个布尔值，该值控制是否将 DefaultCredentials 与请求一起发送。 此选项仅用于 NTLM 身份验证！ |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | 获取或设置指示客户端是否必须为重负载操作使用多个连接的值。 请注意，使用此模式不一定会导致性能提升。 |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | 获取或设置指示是否启用流水线模式的对象。 |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | 获取或设置用户名。 |
| static [DefaultFolder](../../aspose.email.clients.imap/imapclient/defaultfolder) { get; set; } | ImapClients 的默认文件夹 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_18)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_20)(IEnumerable&lt;int&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_22)(IEnumerable&lt;string&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_14)(int, ImapMessageFlags) | 将标志添加到消息 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_24)(string, ImapMessageFlags) | 将标志添加到消息 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_6)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_8)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags)(IConnection, int, ImapMessageFlags) | 将标志添加到消息 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_10)(IConnection, string, ImapMessageFlags) | 将标志添加到消息 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_19)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_21)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_23)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_15)(int, ImapMessageFlags, long) | 将标志添加到消息 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_16)(int, int, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_25)(string, ImapMessageFlags, long) | 将标志添加到消息 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_26)(string, string, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_7)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_9)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_1)(IConnection, int, ImapMessageFlags, long) | 将标志添加到消息 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_2)(IConnection, int, int, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_11)(IConnection, string, ImapMessageFlags, long) | 将标志添加到消息 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_12)(IConnection, string, string, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_17)(int, int, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_27)(string, string, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_3)(IConnection, int, int, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_13)(IConnection, string, string, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_36)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_40)(IEnumerable&lt;int&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_44)(IEnumerable&lt;string&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_28)(int, ImapMessageFlags) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_48)(string, ImapMessageFlags) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_12)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_16)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync)(IConnection, int, ImapMessageFlags) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_20)(IConnection, string, ImapMessageFlags) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_43)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_41)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_47)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_45)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_31)(int, ImapMessageFlags, CancellationToken) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_29)(int, ImapMessageFlags, long) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_32)(int, int, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_51)(string, ImapMessageFlags, CancellationToken) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_49)(string, ImapMessageFlags, long) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_52)(string, string, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_15)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_13)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_19)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_17)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_3)(IConnection, int, ImapMessageFlags, CancellationToken) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_1)(IConnection, int, ImapMessageFlags, long) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_4)(IConnection, int, int, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_23)(IConnection, string, ImapMessageFlags, CancellationToken) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_21)(IConnection, string, ImapMessageFlags, long) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_24)(IConnection, string, string, ImapMessageFlags) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_42)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_46)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_30)(int, ImapMessageFlags, long, CancellationToken) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_35)(int, int, ImapMessageFlags, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_33)(int, int, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_50)(string, ImapMessageFlags, long, CancellationToken) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_55)(string, string, ImapMessageFlags, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_53)(string, string, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_14)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_18)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_2)(IConnection, int, ImapMessageFlags, long, CancellationToken) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_7)(IConnection, int, int, ImapMessageFlags, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_5)(IConnection, int, int, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_22)(IConnection, string, ImapMessageFlags, long, CancellationToken) | 将标志添加到消息 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_27)(IConnection, string, string, ImapMessageFlags, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_25)(IConnection, string, string, ImapMessageFlags, long) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_34)(int, int, ImapMessageFlags, long, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_54)(string, string, ImapMessageFlags, long, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_6)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | 添加消息的标志 |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_26)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | 添加消息的标志 |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_4)(MailMessage) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_5)(string) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage)(IConnection, MailMessage) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_1)(IConnection, string) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_6)(string, MailMessage) | 将邮件信息上传到指定文件夹 |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_7)(string, string) | 将邮件信息上传到指定文件夹 |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_2)(IConnection, string, MailMessage) | 将邮件信息上传到指定文件夹 |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_3)(IConnection, string, string) | 将邮件信息上传到指定文件夹 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_8)(MailMessage) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_10)(string) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync)(IConnection, MailMessage) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_2)(IConnection, string) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_9)(MailMessage, CancellationToken) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_15)(string, CancellationToken) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_11)(string, MailMessage) | 将邮件信息上传到指定文件夹 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_13)(string, string) | 将邮件信息上传到指定文件夹 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_1)(IConnection, MailMessage, CancellationToken) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_7)(IConnection, string, CancellationToken) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_3)(IConnection, string, MailMessage) | 将邮件信息上传到指定文件夹 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_5)(IConnection, string, string) | 将邮件信息上传到指定文件夹 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_12)(string, MailMessage, CancellationToken) | 将邮件信息上传到指定文件夹 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_14)(string, string, CancellationToken) | 将邮件信息上传到指定文件夹 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_4)(IConnection, string, MailMessage, CancellationToken) | 将邮件信息上传到指定文件夹 |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_6)(IConnection, string, string, CancellationToken) | 将邮件信息上传到指定文件夹 |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages#appendmessages_2)(IEnumerable&lt;MailMessage&gt;) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages#appendmessages)(IConnection, IEnumerable&lt;MailMessage&gt;) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages#appendmessages_3)(string, IEnumerable&lt;MailMessage&gt;) | 将邮件信息上传到指定文件夹 |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages#appendmessages_1)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | 将邮件信息上传到指定文件夹 |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_4)(IEnumerable&lt;MailMessage&gt;) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync)(IConnection, IEnumerable&lt;MailMessage&gt;) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_5)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_6)(string, IEnumerable&lt;MailMessage&gt;) | 将邮件信息上传到当前文件夹 |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_1)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | 将邮件信息上传到当前文件夹 如果未指定当前文件夹，则使用默认文件夹。 |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_2)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | 将邮件信息上传到当前文件夹 |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_7)(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) | 将邮件信息上传到当前文件夹 |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_3)(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) | 将邮件信息上传到当前文件夹 |
| [Backup](../../aspose.email.clients.imap/imapclient/backup#backup_2)(ImapFolderInfoCollection, Stream, BackupSettings) | 备份指定文件夹的内容 |
| [Backup](../../aspose.email.clients.imap/imapclient/backup#backup_3)(ImapFolderInfoCollection, string, BackupSettings) | 备份指定文件夹的内容 |
| [Backup](../../aspose.email.clients.imap/imapclient/backup#backup)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | 备份指定文件夹的内容 |
| [Backup](../../aspose.email.clients.imap/imapclient/backup#backup_1)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | 备份指定文件夹的内容 |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_4)(ImapFolderInfoCollection, Stream, BackupSettings) | 备份指定文件夹的内容 |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_6)(ImapFolderInfoCollection, string, BackupSettings) | 备份指定文件夹的内容 |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | 备份指定文件夹的内容 |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_2)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | 备份指定文件夹的内容 |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_5)(ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) | 备份指定文件夹的内容 |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_7)(ImapFolderInfoCollection, string, BackupSettings, CancellationToken) | 备份指定文件夹的内容 |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_1)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) | 备份指定文件夹的内容 |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_3)(IConnection, ImapFolderInfoCollection, string, BackupSettings, CancellationToken) | 备份指定文件夹的内容 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_18)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_20)(IEnumerable&lt;int&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_22)(IEnumerable&lt;string&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_14)(int, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_24)(string, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_6)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_8)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags)(IConnection, int, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_10)(IConnection, string, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_19)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_21)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_23)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_15)(int, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_16)(int, int, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_25)(string, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_26)(string, string, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_7)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_9)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_1)(IConnection, int, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_2)(IConnection, int, int, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_11)(IConnection, string, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_12)(IConnection, string, string, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_17)(int, int, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_27)(string, string, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_3)(IConnection, int, int, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_13)(IConnection, string, string, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_36)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_40)(IEnumerable&lt;int&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_44)(IEnumerable&lt;string&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_28)(int, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_48)(string, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_12)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_16)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync)(IConnection, int, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_20)(IConnection, string, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_43)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_41)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_47)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_45)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_31)(int, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_29)(int, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_32)(int, int, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_51)(string, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_49)(string, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_52)(string, string, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_15)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_13)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_19)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_17)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_3)(IConnection, int, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_1)(IConnection, int, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_4)(IConnection, int, int, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_23)(IConnection, string, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_21)(IConnection, string, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_24)(IConnection, string, string, ImapMessageFlags) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_42)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_46)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_30)(int, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_35)(int, int, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_33)(int, int, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_50)(string, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_55)(string, string, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_53)(string, string, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_14)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_18)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_2)(IConnection, int, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_7)(IConnection, int, int, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_5)(IConnection, int, int, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_22)(IConnection, string, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_27)(IConnection, string, string, ImapMessageFlags, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_25)(IConnection, string, string, ImapMessageFlags, long) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_34)(int, int, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_54)(string, string, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_6)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_26)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | 更改消息的标志 |
| [ClientCapabilities](../../aspose.email.clients.imap/imapclient/clientcapabilities#clientcapabilities_1)(params string[]) | 通知服务器客户端支持哪些扩展。 请注意，此操作仅适用于服务器支持 RFC5161 查看更多 https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilities](../../aspose.email.clients.imap/imapclient/clientcapabilities#clientcapabilities)(IConnection, params string[]) | 通知服务器客户端支持哪些扩展。 请注意，此操作仅适用于服务器支持 RFC5161 查看更多 https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync#clientcapabilitiesasync_2)(params string[]) | 通知服务器客户端支持哪些扩展。 请注意，此操作仅适用于服务器支持 RFC5161 查看更多 https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync#clientcapabilitiesasync_3)(CancellationToken, params string[]) | 通知服务器客户端支持哪些扩展。 请注意，此操作仅适用于服务器支持 RFC5161 查看更多 https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync#clientcapabilitiesasync)(IConnection, params string[]) | 通知服务器客户端支持哪些扩展。 请注意，此操作仅适用于服务器支持 RFC5161 查看更多 https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync#clientcapabilitiesasync_1)(IConnection, CancellationToken, params string[]) | 通知服务器客户端支持哪些扩展。 请注意，此操作仅适用于服务器支持 RFC5161 查看更多 https://tools.ietf.org/html/rfc5161 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes)() | 提交删除 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_1)(IConnection) | 提交删除 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_7)(IEnumerable&lt;string&gt;) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_6)(int) | 提交删除 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_8)(string) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_3)(IConnection, IEnumerable&lt;string&gt;) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_2)(IConnection, int) | 提交删除 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_4)(IConnection, string) | 提交删除 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_9)(string, string) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_5)(IConnection, string, string) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync)() | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_19)(CancellationToken) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_1)(IConnection) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_13)(IEnumerable&lt;string&gt;) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_11)(int) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_15)(string) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_10)(IConnection, CancellationToken) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_4)(IConnection, IEnumerable&lt;string&gt;) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_2)(IConnection, int) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_6)(IConnection, string) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_14)(IEnumerable&lt;string&gt;, CancellationToken) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_12)(int, CancellationToken) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_18)(string, CancellationToken) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_16)(string, string) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_5)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_3)(IConnection, int, CancellationToken) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_9)(IConnection, string, CancellationToken) | 提交删除 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_7)(IConnection, string, string) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_17)(string, string, CancellationToken) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_8)(IConnection, string, string, CancellationToken) | 提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage#copymessage_2)(int, string) | 复制消息 |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage#copymessage_3)(string, string) | 复制消息 |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage#copymessage)(IConnection, int, string) | 复制消息 |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage#copymessage_1)(IConnection, string, string) | 复制消息 |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_4)(int, string) | 复制消息 |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_6)(string, string) | 复制消息 |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync)(IConnection, int, string) | 复制消息 |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_2)(IConnection, string, string) | 复制消息 |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_5)(int, string, CancellationToken) | 复制消息 |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_7)(string, string, CancellationToken) | 复制消息 |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_1)(IConnection, int, string, CancellationToken) | 复制消息 |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_3)(IConnection, string, string, CancellationToken) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_6)(IEnumerable&lt;ImapMessageInfo&gt;, string) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_7)(IEnumerable&lt;int&gt;, string) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_9)(IEnumerable&lt;string&gt;, string) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_1)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_2)(IConnection, IEnumerable&lt;int&gt;, string) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_3)(IConnection, IEnumerable&lt;string&gt;, string) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_8)(IEnumerable&lt;int&gt;, string, bool) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_5)(int, int, string) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_10)(string, string, string) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages)(IConnection, int, int, string) | 复制消息 |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_4)(IConnection, string, string, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_12)(IEnumerable&lt;ImapMessageInfo&gt;, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_14)(IEnumerable&lt;int&gt;, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_17)(IEnumerable&lt;string&gt;, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_2)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_4)(IConnection, IEnumerable&lt;int&gt;, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_6)(IConnection, IEnumerable&lt;string&gt;, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_13)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_16)(IEnumerable&lt;int&gt;, string, CancellationToken) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_18)(IEnumerable&lt;string&gt;, string, CancellationToken) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_10)(int, int, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_19)(string, string, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_3)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_5)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_7)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync)(IConnection, int, int, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_8)(IConnection, string, string, string) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_11)(int, int, string, CancellationToken) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_20)(string, string, string, CancellationToken) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_1)(IConnection, int, int, string, CancellationToken) | 复制消息 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_9)(IConnection, string, string, string, CancellationToken) | 复制消息 |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | 为未链接到线程的操作（非默认连接）创建新的独立连接。 调用此方法类似于调用 CreateConnection(createAsDefaultConnection = false) 请参阅 EmailClient.ConnectionAsgmtMode 属性的文档中的更多信息。 |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | 为操作创建新的（默认或独立的）连接。 请参阅 EmailClient.ConnectionAsgmtMode 属性的文档中的更多信息。 |
| [CreateFolder](../../aspose.email.clients.imap/imapclient/createfolder#createfolder_1)(string) | 创建一个具有指定名称的文件夹 |
| [CreateFolder](../../aspose.email.clients.imap/imapclient/createfolder#createfolder)(IConnection, string) | 创建一个具有指定名称的文件夹 |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync#createfolderasync_2)(string) | 创建一个具有指定名称的文件夹 |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync#createfolderasync)(IConnection, string) | 创建一个具有指定名称的文件夹 |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync#createfolderasync_3)(string, CancellationToken) | 创建一个具有指定名称的文件夹 |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync#createfolderasync_1)(IConnection, string, CancellationToken) | 创建一个具有指定名称的文件夹 |
| [DeleteFolder](../../aspose.email.clients.imap/imapclient/deletefolder#deletefolder_1)(string) | 删除指定的文件夹。这个方法代表IMAP DELETE command |
| [DeleteFolder](../../aspose.email.clients.imap/imapclient/deletefolder#deletefolder)(IConnection, string) | 删除指定的文件夹。这个方法代表IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync#deletefolderasync_2)(string) | 删除指定的文件夹。这个方法代表IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync#deletefolderasync)(IConnection, string) | 删除指定的文件夹。这个方法代表IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync#deletefolderasync_3)(string, CancellationToken) | 删除指定的文件夹。这个方法代表IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync#deletefolderasync_1)(IConnection, string, CancellationToken) | 删除指定的文件夹。这个方法代表IMAP DELETE command |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_6)(int) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_8)(string) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage)(IConnection, int) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_2)(IConnection, string) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_7)(int, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_9)(string, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_10)(string, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_1)(IConnection, int, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_3)(IConnection, string, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_4)(IConnection, string, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_11)(string, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_5)(IConnection, string, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_12)(int) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_16)(string) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync)(IConnection, int) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_4)(IConnection, string) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_15)(int, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_13)(int, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_17)(string, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_23)(string, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_19)(string, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_3)(IConnection, int, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_1)(IConnection, int, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_5)(IConnection, string, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_11)(IConnection, string, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_7)(IConnection, string, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_14)(int, long, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_18)(string, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_20)(string, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_22)(string, long, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_2)(IConnection, int, long, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_6)(IConnection, string, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_8)(IConnection, string, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_10)(IConnection, string, long, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_21)(string, long, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_9)(IConnection, string, long, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_18)(IEnumerable&lt;ImapMessageInfo&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_22)(IEnumerable&lt;int&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_24)(IEnumerable&lt;string&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_2)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_6)(IConnection, IEnumerable&lt;int&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_8)(IConnection, IEnumerable&lt;string&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_19)(IEnumerable&lt;ImapMessageInfo&gt;, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_20)(IEnumerable&lt;ImapMessageInfo&gt;, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_23)(IEnumerable&lt;int&gt;, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_25)(IEnumerable&lt;string&gt;, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_26)(IEnumerable&lt;string&gt;, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_16)(int, int) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_28)(string, string) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_3)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_7)(IConnection, IEnumerable&lt;int&gt;, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_9)(IConnection, IEnumerable&lt;string&gt;, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_10)(IConnection, IEnumerable&lt;string&gt;, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages)(IConnection, int, int) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_12)(IConnection, string, string) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_21)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_27)(IEnumerable&lt;string&gt;, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_17)(int, int, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_29)(string, string, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_30)(string, string, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_11)(IConnection, IEnumerable&lt;string&gt;, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_1)(IConnection, int, int, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_13)(IConnection, string, string, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_14)(IConnection, string, string, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_31)(string, string, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_15)(IConnection, string, string, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_36)(IEnumerable&lt;ImapMessageInfo&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_44)(IEnumerable&lt;int&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_48)(IEnumerable&lt;string&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_12)(IConnection, IEnumerable&lt;int&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_16)(IConnection, IEnumerable&lt;string&gt;) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_43)(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_47)(IEnumerable&lt;int&gt;, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_45)(IEnumerable&lt;int&gt;, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_49)(IEnumerable&lt;string&gt;, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_55)(IEnumerable&lt;string&gt;, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_51)(IEnumerable&lt;string&gt;, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_32)(int, int) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_56)(string, string) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_7)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_15)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_13)(IConnection, IEnumerable&lt;int&gt;, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_17)(IConnection, IEnumerable&lt;string&gt;, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_23)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_19)(IConnection, IEnumerable&lt;string&gt;, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync)(IConnection, int, int) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_24)(IConnection, string, string) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_40)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_42)(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_46)(IEnumerable&lt;int&gt;, long, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_50)(IEnumerable&lt;string&gt;, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_52)(IEnumerable&lt;string&gt;, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_54)(IEnumerable&lt;string&gt;, long, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_35)(int, int, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_33)(int, int, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_57)(string, string, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_63)(string, string, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_59)(string, string, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_6)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_14)(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_18)(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_20)(IConnection, IEnumerable&lt;string&gt;, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_22)(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_3)(IConnection, int, int, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_1)(IConnection, int, int, long) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_25)(IConnection, string, string, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_31)(IConnection, string, string, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_27)(IConnection, string, string, long) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_41)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_53)(IEnumerable&lt;string&gt;, long, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_34)(int, int, long, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_58)(string, string, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_60)(string, string, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_62)(string, string, long, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_21)(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_2)(IConnection, int, int, long, CancellationToken) | 将具有指定序列号的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_26)(IConnection, string, string, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_28)(IConnection, string, string, long, bool) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_30)(IConnection, string, string, long, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_61)(string, string, long, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_29)(IConnection, string, string, long, bool, CancellationToken) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| override [Dispose](../../aspose.email.clients.imap/imapclient/dispose)() | 使用服务器完成所有操作。 |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder#existfolder_2)(string) | 检查这个文件夹是否存在 |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder#existfolder)(IConnection, string) | 检查这个文件夹是否存在 |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder#existfolder_3)(string, out ImapFolderInfo) | 检查该文件夹是否存在，如果存在则提取文件夹信息 |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder#existfolder_1)(IConnection, string, out ImapFolderInfo) | 检查该文件夹是否存在，如果存在则提取文件夹信息 |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync#existfolderasync_2)(string) | 检查这个文件夹是否存在 |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync#existfolderasync)(IConnection, string) | 检查这个文件夹是否存在 |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync#existfolderasync_3)(string, CancellationToken) | 检查这个文件夹是否存在 |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync#existfolderasync_1)(IConnection, string, CancellationToken) | 检查这个文件夹是否存在 |
| [FetchAttachment](../../aspose.email.clients.imap/imapclient/fetchattachment#fetchattachment_1)(int, string) | 获取指定的附件 |
| [FetchAttachment](../../aspose.email.clients.imap/imapclient/fetchattachment#fetchattachment)(IConnection, int, string) | 获取指定的附件 |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync#fetchattachmentasync_2)(int, string) | 获取指定的附件 |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync#fetchattachmentasync)(IConnection, int, string) | 获取指定的附件 |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync#fetchattachmentasync_3)(int, string, CancellationToken) | 获取指定的附件 |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync#fetchattachmentasync_1)(IConnection, int, string, CancellationToken) | 获取指定的附件 |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage_3)(int) | 获取消息 |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage_5)(string) | 获取消息 |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage)(IConnection, int) | 获取消息 |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage_2)(IConnection, string) | 获取消息 |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage_4)(int, bool) | 获取消息 |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage_1)(IConnection, int, bool) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_6)(int) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_10)(string) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync)(IConnection, int) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_4)(IConnection, string) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_7)(int, bool) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_9)(int, CancellationToken) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_11)(string, CancellationToken) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_1)(IConnection, int, bool) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_3)(IConnection, int, CancellationToken) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_5)(IConnection, string, CancellationToken) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_8)(int, bool, CancellationToken) | 获取消息 |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_2)(IConnection, int, bool, CancellationToken) | 获取消息 |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | 获取消息 |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | 获取消息 |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | 获取消息 |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | 获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | 异步获取消息 |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | 异步获取消息 |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetFolderInfo](../../aspose.email.clients.imap/imapclient/getfolderinfo#getfolderinfo_1)(string) | 返回有关指定文件夹的信息而不选择它 |
| [GetFolderInfo](../../aspose.email.clients.imap/imapclient/getfolderinfo#getfolderinfo)(IConnection, string) | 返回有关指定文件夹的信息而不选择它 |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync#getfolderinfoasync_2)(string) | 返回有关指定文件夹的信息而不选择它 |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync#getfolderinfoasync)(IConnection, string) | 返回有关指定文件夹的信息而不选择它 |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync#getfolderinfoasync_3)(string, CancellationToken) | 返回有关指定文件夹的信息而不选择它 |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync#getfolderinfoasync_1)(IConnection, string, CancellationToken) | 返回有关指定文件夹的信息而不选择它 |
| [GetMessageThreads](../../aspose.email.clients.imap/imapclient/getmessagethreads#getmessagethreads_1)(BaseSearchConditions) | 获取消息线程。 |
| [GetMessageThreads](../../aspose.email.clients.imap/imapclient/getmessagethreads#getmessagethreads)(IConnection, BaseSearchConditions) | 获取消息线程。 |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync#getmessagethreadsasync_2)(BaseSearchConditions) | 获取消息线程。 |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync#getmessagethreadsasync_3)(BaseSearchConditions, CancellationToken) | 获取消息线程。 |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync#getmessagethreadsasync)(IConnection, BaseSearchConditions) | 获取消息线程。 |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync#getmessagethreadsasync_1)(IConnection, BaseSearchConditions, CancellationToken) | 获取消息线程。 |
| [GetNamespaces](../../aspose.email.clients.imap/imapclient/getnamespaces#getnamespaces)() | 获取服务器上可用的命名空间。 |
| [GetNamespaces](../../aspose.email.clients.imap/imapclient/getnamespaces#getnamespaces_1)(IConnection) | 获取服务器上可用的命名空间。 |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync#getnamespacesasync)() | 获取服务器上可用的命名空间。 |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync#getnamespacesasync_3)(CancellationToken) | 获取服务器上可用的命名空间。 |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync#getnamespacesasync_1)(IConnection) | 获取服务器上可用的命名空间。 |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync#getnamespacesasync_2)(IConnection, CancellationToken) | 获取服务器上可用的命名空间。 |
| [GetQuota](../../aspose.email.clients.imap/imapclient/getquota#getquota_1)(string) | 获取配额信息 |
| [GetQuota](../../aspose.email.clients.imap/imapclient/getquota#getquota)(IConnection, string) | 获取配额信息 |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync#getquotaasync_2)(string) | 获取配额信息 |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync#getquotaasync)(IConnection, string) | 获取配额信息 |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync#getquotaasync_3)(string, CancellationToken) | 获取配额信息 |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync#getquotaasync_1)(IConnection, string, CancellationToken) | 获取配额信息 |
| [GetQuotaRoot](../../aspose.email.clients.imap/imapclient/getquotaroot#getquotaroot_1)(string) | 获取邮箱 的配额根信息 |
| [GetQuotaRoot](../../aspose.email.clients.imap/imapclient/getquotaroot#getquotaroot)(IConnection, string) | 获取邮箱 的配额根信息 |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync#getquotarootasync_2)(string) | 获取邮箱 的配额根信息 |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync#getquotarootasync)(IConnection, string) | 获取邮箱 的配额根信息 |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync#getquotarootasync_3)(string, CancellationToken) | 获取邮箱 的配额根信息 |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync#getquotarootasync_1)(IConnection, string, CancellationToken) | 获取邮箱 的配额根信息 |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient#introduceclient)() | 将客户端信息引入服务器。 |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient#introduceclient_1)(IConnection) | 将客户端信息引入服务器。 |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient#introduceclient_3)(ImapIdentificationInfo) | 将客户端信息引入服务器。 |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient#introduceclient_2)(IConnection, ImapIdentificationInfo) | 将客户端信息引入服务器。 |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync)() | 将客户端信息引入服务器。 |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_7)(CancellationToken) | 将客户端信息引入服务器。 |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_1)(IConnection) | 将客户端信息引入服务器。 |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_5)(ImapIdentificationInfo) | 将客户端信息引入服务器。 |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_4)(IConnection, CancellationToken) | 将客户端信息引入服务器。 |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_2)(IConnection, ImapIdentificationInfo) | 将客户端信息引入服务器。 |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_6)(ImapIdentificationInfo, CancellationToken) | 将客户端信息引入服务器。 |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_3)(IConnection, ImapIdentificationInfo, CancellationToken) | 将客户端信息引入服务器。 |
| [ListAttachments](../../aspose.email.clients.imap/imapclient/listattachments)(int) | 获取邮件附件列表。 获取邮件中每个附件的信息。 |
| [ListAttachmentsAsync](../../aspose.email.clients.imap/imapclient/listattachmentsasync#listattachmentsasync)(int) | 获取邮件附件列表。 获取邮件中每个附件的信息。 |
| [ListAttachmentsAsync](../../aspose.email.clients.imap/imapclient/listattachmentsasync#listattachmentsasync_1)(int, CancellationToken) | 获取邮件附件列表。 获取邮件中每个附件的信息。 |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders)() | 获取邮箱中的文件夹列表 |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_6)(bool) | 获取邮箱中的文件夹列表 |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_1)(IConnection) | 获取邮箱中的文件夹列表 |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_7)(string) | 获取指定文件夹中的子文件夹列表 |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_2)(IConnection, bool) | 获取邮箱中的文件夹列表 |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_3)(IConnection, string) | 获取指定文件夹中的子文件夹列表 |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_8)(string, bool) | 获取指定文件夹中的子文件夹列表 |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_4)(IConnection, string, bool) | 获取指定文件夹中的子文件夹列表 |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_9)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) | 获取指定文件夹中的子文件夹列表 |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_5)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync)() | 获取邮箱中的文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_11)(bool) | 获取邮箱中的文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_19)(CancellationToken) | 获取邮箱中的文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_1)(IConnection) | 获取邮箱中的文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_13)(string) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_12)(bool, CancellationToken) | 获取邮箱中的文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_2)(IConnection, bool) | 获取邮箱中的文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_10)(IConnection, CancellationToken) | 获取邮箱中的文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_4)(IConnection, string) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_14)(string, bool) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_18)(string, CancellationToken) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_3)(IConnection, bool, CancellationToken) | 获取邮箱中的文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_5)(IConnection, string, bool) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_9)(IConnection, string, CancellationToken) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_17)(string, bool, CancellationToken) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_8)(IConnection, string, bool, CancellationToken) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_15)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_6)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_16)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) | 获取指定文件夹中的子文件夹列表 |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_7)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) | 获取指定文件夹中的子文件夹列表 |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_4)(int) | 获取有关消息的信息。 |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_6)(string) | 获取有关消息的信息。 |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage)(IConnection, int) | 获取有关消息的信息。 |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_2)(IConnection, string) | 获取有关消息的信息。 |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_5)(int, IEnumerable&lt;string&gt;) | 获取有关消息的信息。 |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_7)(string, IEnumerable&lt;string&gt;) | 获取有关消息的信息。 |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_1)(IConnection, int, IEnumerable&lt;string&gt;) | 获取有关消息的信息。 |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_3)(IConnection, string, IEnumerable&lt;string&gt;) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_8)(int) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_12)(string) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync)(IConnection, int) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_4)(IConnection, string) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_11)(int, CancellationToken) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_9)(int, IEnumerable&lt;string&gt;) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_15)(string, CancellationToken) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_13)(string, IEnumerable&lt;string&gt;) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_3)(IConnection, int, CancellationToken) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_1)(IConnection, int, IEnumerable&lt;string&gt;) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_7)(IConnection, string, CancellationToken) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_5)(IConnection, string, IEnumerable&lt;string&gt;) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_10)(int, IEnumerable&lt;string&gt;, CancellationToken) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_14)(string, IEnumerable&lt;string&gt;, CancellationToken) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_2)(IConnection, int, IEnumerable&lt;string&gt;, CancellationToken) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_6)(IConnection, string, IEnumerable&lt;string&gt;, CancellationToken) | 获取有关消息的信息。 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages)() | 获取当前文件夹中的邮件列表 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_16)(bool) | 获取当前文件夹中的邮件列表 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_1)(IConnection) | 获取当前文件夹中的邮件列表 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_19)(IEnumerable&lt;string&gt;) | 获取当前文件夹中的邮件列表 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_17)(int) | 获取当前文件夹中的邮件列表。 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_18)(long) | 获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_14)(MailQuery) | 获取当前文件夹中的邮件列表。 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_20)(string) | 获取指定文件夹中的邮件列表 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_4)(IConnection, bool) | 获取当前文件夹中的邮件列表 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_5)(IConnection, int) | 获取当前文件夹中的邮件列表。 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_6)(IConnection, long) | 获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_2)(IConnection, MailQuery) | 获取当前文件夹中的邮件列表。 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_7)(IConnection, string) | 获取指定文件夹中的邮件列表 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_15)(MailQuery, int) | 获取当前文件夹中的邮件列表。 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_23)(string, bool) | 获取指定文件夹中的邮件列表 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_25)(string, IEnumerable&lt;int&gt;) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_26)(string, IEnumerable&lt;string&gt;) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_3)(IConnection, MailQuery, int) | 获取当前文件夹中的邮件列表。 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_10)(IConnection, string, bool) | 获取指定文件夹中的邮件列表 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_12)(IConnection, string, IEnumerable&lt;int&gt;) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_13)(IConnection, string, IEnumerable&lt;string&gt;) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_24)(string, bool, IEnumerable&lt;string&gt;) | 获取指定文件夹中的邮件列表 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_21)(string, ImapListFields, int) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_22)(string, MailQuery, int) | 获取当前文件夹中的邮件列表。 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_8)(IConnection, string, ImapListFields, int) | 列出消息。 获取搜索消息的信息 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_9)(IConnection, string, MailQuery, int) | 获取当前文件夹中的邮件列表。 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_11)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync)() | 获取当前文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_25)(bool) | 获取当前文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_41)(CancellationToken) | 获取当前文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_1)(IConnection) | 获取当前文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_31)(IEnumerable&lt;string&gt;) | 获取当前文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_27)(int) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_29)(long) | 获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_21)(MailQuery) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_33)(string) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_26)(bool, CancellationToken) | 获取当前文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_6)(IConnection, bool) | 获取当前文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_20)(IConnection, CancellationToken) | 获取当前文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_8)(IConnection, int) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_10)(IConnection, long) | 获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_2)(IConnection, MailQuery) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_12)(IConnection, string) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_32)(IEnumerable&lt;string&gt;, CancellationToken) | 获取当前文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_28)(int, CancellationToken) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_30)(long, CancellationToken) | 获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_24)(MailQuery, CancellationToken) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_22)(MailQuery, int) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_36)(string, bool) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_40)(string, CancellationToken) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_7)(IConnection, bool, CancellationToken) | 获取当前文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_9)(IConnection, int, CancellationToken) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_11)(IConnection, long, CancellationToken) | 获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_5)(IConnection, MailQuery, CancellationToken) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_3)(IConnection, MailQuery, int) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_15)(IConnection, string, bool) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_19)(IConnection, string, CancellationToken) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_23)(MailQuery, int, CancellationToken) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_39)(string, bool, CancellationToken) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_37)(string, bool, IEnumerable&lt;string&gt;) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_34)(string, MailQuery, int) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_4)(IConnection, MailQuery, int, CancellationToken) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_16)(IConnection, string, bool, CancellationToken) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_13)(IConnection, string, MailQuery, int) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_38)(string, bool, IEnumerable&lt;string&gt;, CancellationToken) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_35)(string, MailQuery, int, CancellationToken) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_17)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) | 获取指定文件夹中的邮件列表 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_14)(IConnection, string, MailQuery, int, CancellationToken) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_18)(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) | 获取指定文件夹中的邮件列表 |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage#listmessagesbypage_2)(int, PageSettings) | 获取消息列表 |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage#listmessagesbypage)(PageInfo, PageSettings) | 获取消息列表 |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage#listmessagesbypage_3)(int, int, PageSettings) | 获取消息列表 |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage#listmessagesbypage_1)(MailQuery, PageInfo, PageSettings) | 获取消息列表 |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync#listmessagesbypageasync_2)(int, int, PageSettings) | 获取消息列表 |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings) | 获取消息列表 |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync#listmessagesbypageasync_3)(int, int, PageSettings, CancellationToken) | 获取消息列表 |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync#listmessagesbypageasync_1)(MailQuery, PageInfo, PageSettings, CancellationToken) | 获取消息列表 |
| [MoveFolder](../../aspose.email.clients.imap/imapclient/movefolder#movefolder_1)(string, string) | 将指定文件夹及其子文件夹移动到新位置。 |
| [MoveFolder](../../aspose.email.clients.imap/imapclient/movefolder#movefolder)(IConnection, string, string) | 将指定文件夹及其子文件夹移动到新位置。 |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync#movefolderasync_2)(string, string) | 将指定文件夹及其子文件夹移动到新位置。 |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync#movefolderasync)(IConnection, string, string) | 将指定文件夹及其子文件夹移动到新位置。 |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync#movefolderasync_3)(string, string, CancellationToken) | 将指定文件夹及其子文件夹移动到新位置。 |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync#movefolderasync_1)(IConnection, string, string, CancellationToken) | 将指定文件夹及其子文件夹移动到新位置。 |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_4)(int, string) | 移动消息 |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_6)(string, string) | 移动消息 |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage)(IConnection, int, string) | 移动消息 |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_2)(IConnection, string, string) | 移动消息 |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_5)(int, string, bool) | 移动消息 |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_7)(string, string, bool) | 移动消息 |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_1)(IConnection, int, string, bool) | 移动消息 |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_3)(IConnection, string, string, bool) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_8)(int, string) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_12)(string, string) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync)(IConnection, int, string) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_4)(IConnection, string, string) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_9)(int, string, bool) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_11)(int, string, CancellationToken) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_13)(string, string, bool) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_15)(string, string, CancellationToken) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_1)(IConnection, int, string, bool) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_3)(IConnection, int, string, CancellationToken) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_5)(IConnection, string, string, bool) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_7)(IConnection, string, string, CancellationToken) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_10)(int, string, bool, CancellationToken) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_14)(string, string, bool, CancellationToken) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_2)(IConnection, int, string, bool, CancellationToken) | 移动消息 |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_6)(IConnection, string, string, bool, CancellationToken) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_12)(IEnumerable&lt;ImapMessageInfo&gt;, string) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_14)(IEnumerable&lt;int&gt;, string) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_16)(IEnumerable&lt;string&gt;, string) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_2)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_4)(IConnection, IEnumerable&lt;int&gt;, string) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_6)(IConnection, IEnumerable&lt;string&gt;, string) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_13)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_15)(IEnumerable&lt;int&gt;, string, bool) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_17)(IEnumerable&lt;string&gt;, string, bool) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_10)(int, int, string) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_18)(string, string, string) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_3)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_5)(IConnection, IEnumerable&lt;int&gt;, string, bool) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_7)(IConnection, IEnumerable&lt;string&gt;, string, bool) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages)(IConnection, int, int, string) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_8)(IConnection, string, string, string) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_11)(int, int, string, bool) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_19)(string, string, string, bool) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_1)(IConnection, int, int, string, bool) | 移动消息 |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_9)(IConnection, string, string, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_24)(IEnumerable&lt;ImapMessageInfo&gt;, string) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_28)(IEnumerable&lt;int&gt;, string) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_32)(IEnumerable&lt;string&gt;, string) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_8)(IConnection, IEnumerable&lt;int&gt;, string) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_12)(IConnection, IEnumerable&lt;string&gt;, string) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_25)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_27)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_29)(IEnumerable&lt;int&gt;, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_31)(IEnumerable&lt;int&gt;, string, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_33)(IEnumerable&lt;string&gt;, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_35)(IEnumerable&lt;string&gt;, string, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_20)(int, int, string) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_36)(string, string, string) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_7)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_9)(IConnection, IEnumerable&lt;int&gt;, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_11)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_13)(IConnection, IEnumerable&lt;string&gt;, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_15)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync)(IConnection, int, int, string) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_16)(IConnection, string, string, string) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_26)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_30)(IEnumerable&lt;int&gt;, string, bool, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_34)(IEnumerable&lt;string&gt;, string, bool, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_21)(int, int, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_23)(int, int, string, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_37)(string, string, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_39)(string, string, string, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_6)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_10)(IConnection, IEnumerable&lt;int&gt;, string, bool, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_14)(IConnection, IEnumerable&lt;string&gt;, string, bool, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_1)(IConnection, int, int, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_3)(IConnection, int, int, string, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_17)(IConnection, string, string, string, bool) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_19)(IConnection, string, string, string, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_22)(int, int, string, bool, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_38)(string, string, string, bool, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_2)(IConnection, int, int, string, bool, CancellationToken) | 移动消息 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_18)(IConnection, string, string, string, bool, CancellationToken) | 移动消息 |
| override [Noop](../../aspose.email.clients.imap/imapclient/noop#noop)() | '无操作' 命令 |
| override [Noop](../../aspose.email.clients.imap/imapclient/noop#noop_1)(IConnection) | '无操作' 命令 |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync#noopasync)() | '无操作' 命令 |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync#noopasync_3)(CancellationToken) | '无操作' 命令 |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync#noopasync_1)(IConnection) | '无操作' 命令 |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync#noopasync_2)(IConnection, CancellationToken) | '无操作' 命令 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_18)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_20)(IEnumerable&lt;int&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_22)(IEnumerable&lt;string&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_14)(int, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_24)(string, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_6)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_8)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags)(IConnection, int, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_10)(IConnection, string, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_19)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_21)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_23)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_15)(int, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_16)(int, int, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_25)(string, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_26)(string, string, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_7)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_9)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_1)(IConnection, int, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_2)(IConnection, int, int, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_11)(IConnection, string, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_12)(IConnection, string, string, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_17)(int, int, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_27)(string, string, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_3)(IConnection, int, int, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_13)(IConnection, string, string, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_36)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_40)(IEnumerable&lt;int&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_44)(IEnumerable&lt;string&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_28)(int, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_48)(string, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_12)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_16)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync)(IConnection, int, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_20)(IConnection, string, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_43)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_41)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_47)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_45)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_31)(int, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_29)(int, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_32)(int, int, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_51)(string, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_49)(string, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_52)(string, string, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_15)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_13)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_19)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_17)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_3)(IConnection, int, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_1)(IConnection, int, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_4)(IConnection, int, int, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_23)(IConnection, string, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_21)(IConnection, string, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_24)(IConnection, string, string, ImapMessageFlags) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_42)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_46)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_30)(int, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_35)(int, int, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_33)(int, int, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_50)(string, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_55)(string, string, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_53)(string, string, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_14)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_18)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_2)(IConnection, int, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_7)(IConnection, int, int, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_5)(IConnection, int, int, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_22)(IConnection, string, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_27)(IConnection, string, string, ImapMessageFlags, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_25)(IConnection, string, string, ImapMessageFlags, long) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_34)(int, int, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_54)(string, string, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_6)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_26)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | 删除消息的标志 |
| [RenameFolder](../../aspose.email.clients.imap/imapclient/renamefolder#renamefolder_1)(string, string) | 将指定文件夹重命名为新名称 |
| [RenameFolder](../../aspose.email.clients.imap/imapclient/renamefolder#renamefolder)(IConnection, string, string) | 将指定文件夹重命名为新名称 |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync#renamefolderasync_2)(string, string) | 将指定文件夹重命名为新名称 |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync#renamefolderasync)(IConnection, string, string) | 将指定文件夹重命名为新名称 |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync#renamefolderasync_3)(string, string, CancellationToken) | 将指定文件夹重命名为新名称 |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync#renamefolderasync_1)(IConnection, string, string, CancellationToken) | 将指定文件夹重命名为新名称 |
| [RequestCheckpoint](../../aspose.email.clients.imap/imapclient/requestcheckpoint#requestcheckpoint)() | 请求当前选定邮箱的检查点。 |
| [RequestCheckpoint](../../aspose.email.clients.imap/imapclient/requestcheckpoint#requestcheckpoint_1)(IConnection) | 请求当前选定邮箱的检查点。 |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync#requestcheckpointasync)() | 请求当前选定邮箱的检查点。 |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync#requestcheckpointasync_3)(CancellationToken) | 请求当前选定邮箱的检查点。 |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync#requestcheckpointasync_1)(IConnection) | 请求当前选定邮箱的检查点。 |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync#requestcheckpointasync_2)(IConnection, CancellationToken) | 请求当前选定邮箱的检查点。 |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | 将日志记录设置重置为默认值。 |
| [Restore](../../aspose.email.clients.imap/imapclient/restore)(PersonalStorage, RestoreSettings) | 开始从给定的个人存储中恢复 imap 文件夹。 |
| [RestoreAsync](../../aspose.email.clients.imap/imapclient/restoreasync#restoreasync)(PersonalStorage, RestoreSettings) | 开始从给定的个人存储中恢复 imap 文件夹。 |
| [RestoreAsync](../../aspose.email.clients.imap/imapclient/restoreasync#restoreasync_1)(PersonalStorage, RestoreSettings, CancellationToken) | 开始从给定的个人存储中恢复 imap 文件夹。 |
| [ResumeMonitoring](../../aspose.email.clients.imap/imapclient/resumemonitoring)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState) | 恢复监视指定文件夹的消息更改。 与 StartMonitoring 方法不同，它将查找所有丢失的邮箱更改并为它们调用 回调。 |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/imapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | 恢复监视指定文件夹的消息更改。 与 StartMonitoring 方法不同，它将查找所有丢失的邮箱更改并为它们调用 回调。 |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_4)(int, Stream) | 下载具有指定序列号的消息并将其数据写入提供的流 |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_5)(int, string) | 下载指定序号的消息并将其数据写入本地文件 |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_6)(string, Stream) | 下载具有指定序列号 的消息并将其数据写入提供的流 |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_7)(string, string) | 下载指定序号 的消息，并将其数据写入本地文件 |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage)(IConnection, int, Stream) | 下载具有指定序列号的消息并将其数据写入提供的流 |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_1)(IConnection, int, string) | 下载指定序号的消息并将其数据写入本地文件 |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_2)(IConnection, string, Stream) | 下载具有指定序列号 的消息并将其数据写入提供的流 |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_3)(IConnection, string, string) | 下载指定序号 的消息，并将其数据写入本地文件 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_8)(int, Stream) | 下载具有指定序列号的消息并将其数据写入提供的流 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_10)(int, string) | 下载指定序号的消息并将其数据写入本地文件 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_12)(string, Stream) | 下载具有指定序列号 的消息并将其数据写入提供的流 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_14)(string, string) | 下载指定序号 的消息，并将其数据写入本地文件 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync)(IConnection, int, Stream) | 下载具有指定序列号的消息并将其数据写入提供的流 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_2)(IConnection, int, string) | 下载指定序号的消息并将其数据写入本地文件 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | 下载具有指定序列号 的消息并将其数据写入提供的流 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_6)(IConnection, string, string) | 下载指定序号 的消息，并将其数据写入本地文件 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | 下载具有指定序列号的消息并将其数据写入提供的流 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | 下载指定序号的消息并将其数据写入本地文件 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | 下载具有指定序列号 的消息并将其数据写入提供的流 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | 下载指定序号 的消息，并将其数据写入本地文件 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | 下载具有指定序列号的消息并将其数据写入提供的流 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | 下载指定序号的消息并将其数据写入本地文件 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | 下载具有指定序列号 的消息并将其数据写入提供的流 |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | 下载指定序号 的消息，并将其数据写入本地文件 |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder#selectfolder_2)(string) | 选择指定的文件夹 |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder#selectfolder)(IConnection, string) | 选择指定的文件夹 |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder#selectfolder_3)(string, bool?) | 选择指定的文件夹 |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder#selectfolder_1)(IConnection, string, bool?) | 选择指定的文件夹 |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_4)(string) | 选择指定的文件夹 |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync)(IConnection, string) | 选择指定的文件夹 |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_5)(string, bool?) | 选择指定的文件夹 |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_7)(string, CancellationToken) | 选择指定的文件夹 |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_1)(IConnection, string, bool?) | 选择指定的文件夹 |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_3)(IConnection, string, CancellationToken) | 选择指定的文件夹 |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_6)(string, bool?, CancellationToken) | 选择指定的文件夹 |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_2)(IConnection, string, bool?, CancellationToken) | 选择指定的文件夹 |
| [SetQuota](../../aspose.email.clients.imap/imapclient/setquota#setquota_1)(string, string, int) | 设置配额信息 |
| [SetQuota](../../aspose.email.clients.imap/imapclient/setquota#setquota)(IConnection, string, string, int) | 设置配额信息 |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync#setquotaasync_2)(string, string, int) | 设置配额信息 |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync#setquotaasync)(IConnection, string, string, int) | 设置配额信息 |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync#setquotaasync_3)(string, string, int, CancellationToken) | 设置配额信息 |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync#setquotaasync_1)(IConnection, string, string, int, CancellationToken) | 设置配额信息 |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | 定义要使用的 SSL/TLS 加密协议的版本。 此方法不安全，设置加密协议时不进行任何兼容性检查。 使用[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption)属性以安全地设置仅由 .net 框架明确支持的协议。 请注意，如果您当前的 .net 框架不支持此级别的安全性， 在尝试建立与服务器的连接时将引发异常。 |
| [SortMessageThreads](../../aspose.email.clients.imap/imapclient/sortmessagethreads#sortmessagethreads_1)(SortConditions) | 获取消息线程。 |
| [SortMessageThreads](../../aspose.email.clients.imap/imapclient/sortmessagethreads#sortmessagethreads)(IConnection, SortConditions) | 获取消息线程。 |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync#sortmessagethreadsasync_2)(SortConditions) | 对消息线程进行排序。 |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync#sortmessagethreadsasync)(IConnection, SortConditions) | 对消息线程进行排序。 |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync#sortmessagethreadsasync_3)(SortConditions, CancellationToken) | 对消息线程进行排序。 |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync#sortmessagethreadsasync_1)(IConnection, SortConditions, CancellationToken) | 对消息线程进行排序。 |
| [StartMonitoring](../../aspose.email.clients.imap/imapclient/startmonitoring#startmonitoring_1)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | 开始监视指定文件夹的消息更改。 |
| [StartMonitoringAsync](../../aspose.email.clients.imap/imapclient/startmonitoringasync#startmonitoringasync_1)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | 开始监视指定文件夹的消息更改。 |
| [StopMonitoring](../../aspose.email.clients.imap/imapclient/stopmonitoring#stopmonitoring)() | 停止对更改的任何监控。 |
| [StopMonitoring](../../aspose.email.clients.imap/imapclient/stopmonitoring#stopmonitoring_1)(string) | 停止监视指定文件夹的消息更改。 |
| [StopMonitoringAsync](../../aspose.email.clients.imap/imapclient/stopmonitoringasync#stopmonitoringasync)() | 停止对更改的任何监控。 |
| [StopMonitoringAsync](../../aspose.email.clients.imap/imapclient/stopmonitoringasync#stopmonitoringasync_1)(string) | 停止监视指定文件夹的消息更改。 |
| [SubscribeFolder](../../aspose.email.clients.imap/imapclient/subscribefolder#subscribefolder_1)(string) | 发送了将指定邮箱名称添加到服务器的“活动”邮箱集的 SUBSCRIBE 命令。 |
| [SubscribeFolder](../../aspose.email.clients.imap/imapclient/subscribefolder#subscribefolder)(IConnection, string) | 发送了将指定邮箱名称添加到服务器的“活动”邮箱集的 SUBSCRIBE 命令。 |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync#subscribefolderasync_2)(string) | 发送了将指定邮箱名称添加到服务器的“活动”邮箱集的 SUBSCRIBE 命令。 |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync#subscribefolderasync)(IConnection, string) | 发送了将指定邮箱名称添加到服务器的“活动”邮箱集的 SUBSCRIBE 命令。 |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync#subscribefolderasync_3)(string, CancellationToken) | 发送了将指定邮箱名称添加到服务器的“活动”邮箱集的 SUBSCRIBE 命令。 |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync#subscribefolderasync_1)(IConnection, string, CancellationToken) | 发送了将指定邮箱名称添加到服务器的“活动”邮箱集的 SUBSCRIBE 命令。 |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_4)(int) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_6)(string) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage)(IConnection, int) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_2)(IConnection, string) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_5)(int, long) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_7)(string, long) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_1)(IConnection, int, long) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_3)(IConnection, string, long) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_8)(int) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_12)(string) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync)(IConnection, int) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_4)(IConnection, string) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_11)(int, CancellationToken) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_9)(int, long) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_15)(string, CancellationToken) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_13)(string, long) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_3)(IConnection, int, CancellationToken) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_1)(IConnection, int, long) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_7)(IConnection, string, CancellationToken) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_5)(IConnection, string, long) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_10)(int, long, CancellationToken) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_14)(string, long, CancellationToken) | 将具有指定序列号的消息标记为未删除。 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_2)(IConnection, int, long, CancellationToken) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_6)(IConnection, string, long, CancellationToken) | 将具有指定序列号的消息标记为未删除。 |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder#unselectfolder)() | 永久删除当前选定文件夹的所有标记为已删除的邮件，并删除此文件夹的选定状态。 |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder#unselectfolder_3)(bool) | 取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则所有标记为已删除的邮件都将被删除，否则删除已取消。 请注意，此操作仅在服务器支持 RFC3691 的情况下才有效_查看更多 https://tools。 ietf.org/html/rfc3691 |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder#unselectfolder_1)(IConnection) | 永久删除当前选定文件夹的所有标记为已删除的邮件，并删除此文件夹的选定状态。 |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder#unselectfolder_2)(IConnection, bool) | 取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则所有标记为已删除的邮件都将被删除，否则删除已取消。 请注意，此操作仅在服务器支持 RFC3691 的情况下才有效_查看更多 https://tools。 ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync)() | 永久删除当前选定文件夹的所有标记为已删除的邮件，并删除此文件夹的选定状态。 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_5)(bool) | 取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则所有标记为已删除的邮件都将被删除，否则删除已取消。 请注意，此操作仅在服务器支持 RFC3691 的情况下才有效_查看更多 https://tools。 ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_7)(CancellationToken) | 永久删除当前选定文件夹的所有标记为已删除的邮件，并删除此文件夹的选定状态。 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_1)(IConnection) | 永久删除当前选定文件夹的所有标记为已删除的邮件，并删除此文件夹的选定状态。 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_6)(bool, CancellationToken) | 取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则所有标记为已删除的邮件都将被删除，否则删除已取消。 请注意，此操作仅在服务器支持 RFC3691 的情况下才有效_查看更多 https://tools。 ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_2)(IConnection, bool) | 取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则所有标记为已删除的邮件都将被删除，否则删除已取消。 请注意，此操作仅在服务器支持 RFC3691 的情况下才有效_查看更多 https://tools。 ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_4)(IConnection, CancellationToken) | 永久删除当前选定文件夹的所有标记为已删除的邮件，并删除此文件夹的选定状态。 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_3)(IConnection, bool, CancellationToken) | 取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则所有标记为已删除的邮件都将被删除，否则删除已取消。 请注意，此操作仅在服务器支持 RFC3691 的情况下才有效_查看更多 https://tools。 ietf.org/html/rfc3691 |
| [UnsubscribeFolder](../../aspose.email.clients.imap/imapclient/unsubscribefolder#unsubscribefolder_1)(string) | 发送了从服务器的“活动”邮箱集中删除指定邮箱名称的 UNSUBSCRIBE 命令 |
| [UnsubscribeFolder](../../aspose.email.clients.imap/imapclient/unsubscribefolder#unsubscribefolder)(IConnection, string) | 发送了从服务器的“活动”邮箱集中删除指定邮箱名称的 UNSUBSCRIBE 命令 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync#unsubscribefolderasync_2)(string) | 发送了从服务器的“活动”邮箱集中删除指定邮箱名称的 UNSUBSCRIBE 命令 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync#unsubscribefolderasync)(IConnection, string) | 发送了从服务器的“活动”邮箱集中删除指定邮箱名称的 UNSUBSCRIBE 命令 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync#unsubscribefolderasync_3)(string, CancellationToken) | 发送了从服务器的“活动”邮箱集中删除指定邮箱名称的 UNSUBSCRIBE 命令 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync#unsubscribefolderasync_1)(IConnection, string, CancellationToken) | 发送了从服务器的“活动”邮箱集中删除指定邮箱名称的 UNSUBSCRIBE 命令 |
| override [ValidateCredentials](../../aspose.email.clients.imap/imapclient/validatecredentials#validatecredentials)() | 执行凭据验证 |
| [ValidateCredentials](../../aspose.email.clients.imap/imapclient/validatecredentials#validatecredentials_1)(IConnection) | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync#validatecredentialsasync)() | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | 执行凭据验证 |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | 执行凭据验证 |
| static [CreateAsync](../../aspose.email.clients.imap/imapclient/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | 创建一个新的实例[`ImapClient`](../imapclient) class |

### 也可以看看

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncImapClient](../iasyncimapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
