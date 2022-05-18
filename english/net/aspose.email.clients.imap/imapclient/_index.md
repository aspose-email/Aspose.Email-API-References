---
title: ImapClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 16250
url: /net/aspose.email.clients.imap/imapclient/
---
## ImapClient class

Allows applications to access and manipulate messages by using the Internet Message Access Protocol (IMAP).

```csharp
public sealed class ImapClient : EmailClient
```

## Constructors

| Name | Description |
| --- | --- |
| [ImapClient](imapclient)() | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, ITokenProvider) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, string) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, ITokenProvider) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, ITokenProvider, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, string, bool) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, string, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, ITokenProvider, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string, bool) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string, RemoteCertificateValidationCallback) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, string, bool, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string, bool, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |

## Properties

| Name | Description |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Gets or sets the access token. |
| [AllowedAuthentication](../../aspose.email.clients.imap/imapclient/allowedauthentication) { get; set; } | Gets or sets enumeration of allowed by user authentication types |
| [AnnotateSupported](../../aspose.email.clients.imap/imapclient/annotatesupported) { get; set; } | Gets information whether ANNOTATE extension is supported See more: https://tools.ietf.org/html/rfc5257 |
| [AutoCommit](../../aspose.email.clients.imap/imapclient/autocommit) { get; set; } | Indicates, whether commit operation are executed automatically when folder is changed or before connection is closed. |
| [ChildrenSupported](../../aspose.email.clients.imap/imapclient/childrensupported) { get; set; } | Gets information whether CHILDREN extension is supported See more: https://tools.ietf.org/html/rfc3348 |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Contains collection of clients certificates |
| [ClientIdentificationInfo](../../aspose.email.clients.imap/imapclient/clientidentificationinfo) { get; set; } | Gets or sets client identification information See more: https://tools.ietf.org/html/rfc2971 |
| [CompressSupported](../../aspose.email.clients.imap/imapclient/compresssupported) { get; set; } | Gets information whether COMPRESS extension is supported See more: https://tools.ietf.org/html/rfc4978 |
| [CondstoreSupported](../../aspose.email.clients.imap/imapclient/condstoresupported) { get; set; } | Gets information whether CONDSTORE extension is supported See more: https://tools.ietf.org/html/rfc7162 |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Period of connection checking up in milliseconds. Default value is 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Gets or sets quantity of connections in multy-connection mode |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Gets the current state of the connection. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Gets current connection according to ConnectionAsgmtMode option |
| [CurrentFolder](../../aspose.email.clients.imap/imapclient/currentfolder) { get; set; } | Gets the current folder |
| override [DefaultPort](../../aspose.email.clients.imap/imapclient/defaultport) { get; } | Gets default port for client |
| [Delimiter](../../aspose.email.clients.imap/imapclient/delimiter) { get; set; } | Gets or sets delimiter of folders hierarhy. |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Gets or sets value which allows enable/disable logger |
| [EnableSupported](../../aspose.email.clients.imap/imapclient/enablesupported) { get; set; } | Gets information whether ENABLE extension is supported See more: https://tools.ietf.org/html/rfc5161 |
| [ESearchSupported](../../aspose.email.clients.imap/imapclient/esearchsupported) { get; set; } | Gets information whether ESEARCH extension is supported See more: https://tools.ietf.org/html/rfc4731 |
| [ExchangeIdAutomatically](../../aspose.email.clients.imap/imapclient/exchangeidautomatically) { get; set; } | Gets or sets value which indicates whether client should to introduce information about itself to a server automatically. See more: https://tools.ietf.org/html/rfc2971 |
| [ExtendedListSupported](../../aspose.email.clients.imap/imapclient/extendedlistsupported) { get; set; } | Gets information whether LIST Command Extension is supported See more https://tools.ietf.org/html/rfc5258 |
| [GmExt1Supported](../../aspose.email.clients.imap/imapclient/gmext1supported) { get; set; } | Defines if Google X-GM-EXT-1 extension is supported |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use [`Timeout`](../../aspose.email.clients/emailclient/timeout) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Gets or sets the host name. |
| [IdSupported](../../aspose.email.clients.imap/imapclient/idsupported) { get; set; } | Gets information whether ID extension is supported See more: https://tools.ietf.org/html/rfc2971 |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Gets or sets log file name |
| [MailboxInfo](../../aspose.email.clients.imap/imapclient/mailboxinfo) { get; } | Gets set of special-use mailboxes See more: http://tools.ietf.org/html/rfc6154 and https://tools.ietf.org/html/rfc8457 |
| [MoveSupported](../../aspose.email.clients.imap/imapclient/movesupported) { get; set; } | Gets information whether MOVE extension is supported See more: https://tools.ietf.org/html/rfc6851 |
| [NamespaceSupported](../../aspose.email.clients.imap/imapclient/namespacesupported) { get; set; } | Gets information whether NAMESPACE extension is supported See more: https://tools.ietf.org/html/rfc2342 |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Gets or sets the password. Password limitations are defined by server implementation, which client connects. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Gets or sets the port. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Gets or sets proxy for the client |
| [QresyncSupported](../../aspose.email.clients.imap/imapclient/qresyncsupported) { get; set; } | Gets information whether QRESYNC extension is supported See more: https://tools.ietf.org/html/rfc7162 |
| [QuotaSupported](../../aspose.email.clients.imap/imapclient/quotasupported) { get; set; } | Gets information whether quota is supported |
| [ReadOnly](../../aspose.email.clients.imap/imapclient/readonly) { get; set; } | Gets or sets value which indicates if changes to the permanent state of the mailbox, including per-user state, are permitted. |
| [SaslIrSupported](../../aspose.email.clients.imap/imapclient/saslirsupported) { get; set; } | Gets information whether SASL Initial Client Response extension is supported See more: https://tools.ietf.org/html/rfc4959 |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Security mode for a mail client |
| [ServerIdentificationInfo](../../aspose.email.clients.imap/imapclient/serveridentificationinfo) { get; } | Gets server identification information See more: https://tools.ietf.org/html/rfc2971 |
| [ServerSupportedCompression](../../aspose.email.clients.imap/imapclient/serversupportedcompression) { get; } | Gets information which compression types are supported by a server. See more: https://tools.ietf.org/html/rfc4978 |
| [SortSupported](../../aspose.email.clients.imap/imapclient/sortsupported) { get; set; } | Gets information whether Sort command are supported |
| [SpecialUseSupported](../../aspose.email.clients.imap/imapclient/specialusesupported) { get; set; } | Gets information whether Special-Use Mailboxes is supported See more: https://tools.ietf.org/html/rfc6154 |
| [SupportedAuthentication](../../aspose.email.clients.imap/imapclient/supportedauthentication) { get; } | Gets enumeration of supported by server authentication types |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF .NET FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) documentation for more details. Please use [`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (in case if your current version of .net framework supports these versions of TLS) |
| [ThreadAlgorithms](../../aspose.email.clients.imap/imapclient/threadalgorithms) { get; } | Gets supported thread algorithms |
| [ThreadSupported](../../aspose.email.clients.imap/imapclient/threadsupported) { get; set; } | Gets information whether Thread command are supported |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Gets or sets the timeout for mail operations |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Gets or sets TokenProvider allowing to retrieve access token. |
| [UidPlusSupported](../../aspose.email.clients.imap/imapclient/uidplussupported) { get; set; } | Gets information whether UIDPLUS extension is supported See more: https://tools.ietf.org/html/rfc4315 |
| [UnselectSupported](../../aspose.email.clients.imap/imapclient/unselectsupported) { get; set; } | Gets information whether UNSELECT extension is supported See more: https://tools.ietf.org/html/rfc2342 |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indicates whether authentication is used. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Gets or sets value which indicates if date has to be used in log file name. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. This option is used with NTLM authentication ONLY! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Gets or sets object which indicates whether the pipelining mode is enabled. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Gets or sets the username. |
| static [DefaultFolder](../../aspose.email.clients.imap/imapclient/defaultfolder) { get; set; } | Default folder for ImapClients |

## Methods

| Name | Description |
| --- | --- |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags)(IConnection, string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(int, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(string, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, int, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, string, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(int, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(int, int, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(string, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(string, string, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, int, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, int, int, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, string, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, string, string, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(int, int, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(string, string, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage)(MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage)(string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage)(IConnection, MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage)(IConnection, string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage)(string, string) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage)(IConnection, string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage)(IConnection, string, string) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(IConnection, MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(IConnection, string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(MailMessage, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(string, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(string, string) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(IConnection, MailMessage, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(IConnection, string, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(IConnection, string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(IConnection, string, string) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(string, MailMessage, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(string, string, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(IConnection, string, MailMessage, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync)(IConnection, string, string, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages)(IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages)(IConnection, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages)(string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync)(IConnection, IEnumerable&lt;MailMessage&gt;) | Uploads the mail messages to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync)(string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail messages to the current folder |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail messages to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail messages to the current folder |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync)(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail messages to the current folder |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync)(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail messages to the current folder |
| [Backup](../../aspose.email.clients.imap/imapclient/backup)(ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [Backup](../../aspose.email.clients.imap/imapclient/backup)(ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [Backup](../../aspose.email.clients.imap/imapclient/backup)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [Backup](../../aspose.email.clients.imap/imapclient/backup)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync)(ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync)(ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync)(ImapFolderInfoCollection, string, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync)(IConnection, ImapFolderInfoCollection, string, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags)(IConnection, string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(int, int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(string, string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, int, int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, string, string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(int, int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(string, string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ClientCapabilities](../../aspose.email.clients.imap/imapclient/clientcapabilities)(params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilities](../../aspose.email.clients.imap/imapclient/clientcapabilities)(IConnection, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync)(params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync)(CancellationToken, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync)(IConnection, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync)(IConnection, CancellationToken, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes)() | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes)(IConnection) | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes)(IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes)(int) | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes)(string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes)(IConnection, IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes)(IConnection, int) | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes)(IConnection, string) | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes)(string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes)(IConnection, string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)() | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IConnection) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(int) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IConnection, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IConnection, IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IConnection, int) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IConnection, string) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(int, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(string, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IConnection, int, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IConnection, string, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IConnection, string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(string, string, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync)(IConnection, string, string, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage)(int, string) | Copies the message |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage)(string, string) | Copies the message |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage)(IConnection, int, string) | Copies the message |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage)(IConnection, string, string) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync)(int, string) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync)(string, string) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync)(IConnection, int, string) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync)(IConnection, string, string) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync)(int, string, CancellationToken) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync)(string, string, CancellationToken) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync)(IConnection, int, string, CancellationToken) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync)(IConnection, string, string, CancellationToken) | Copies the message |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(IEnumerable&lt;int&gt;, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(IConnection, IEnumerable&lt;int&gt;, string) | Copy the messaeg |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(IConnection, IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(IEnumerable&lt;int&gt;, string, bool) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(int, int, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(string, string, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(IConnection, int, int, string) | Copy the messaeg |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages)(IConnection, string, string, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IEnumerable&lt;int&gt;, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IConnection, IEnumerable&lt;int&gt;, string) | Copy the messaeg |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IConnection, IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IEnumerable&lt;int&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IEnumerable&lt;string&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(int, int, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(string, string, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) | Copy the messaeg |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IConnection, int, int, string) | Copy the messaeg |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IConnection, string, string, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(int, int, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(string, string, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IConnection, int, int, string, CancellationToken) | Copy the messaeg |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync)(IConnection, string, string, string, CancellationToken) | Copy messages |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Creates new independent connection for operations not linked to threads (not default connection). Invocation of this method is similar to invocation of CreateConnection(createAsDefaultConnection = false) Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Creates new (default or independent) connection for operations. Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| [CreateFolder](../../aspose.email.clients.imap/imapclient/createfolder)(string) | Creates a folder with the specified name |
| [CreateFolder](../../aspose.email.clients.imap/imapclient/createfolder)(IConnection, string) | Creates a folder with the specified name |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync)(string) | Creates a folder with the specified name |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync)(IConnection, string) | Creates a folder with the specified name |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync)(string, CancellationToken) | Creates a folder with the specified name |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync)(IConnection, string, CancellationToken) | Creates a folder with the specified name |
| [DeleteFolder](../../aspose.email.clients.imap/imapclient/deletefolder)(string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolder](../../aspose.email.clients.imap/imapclient/deletefolder)(IConnection, string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync)(string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync)(IConnection, string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync)(string, CancellationToken) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync)(IConnection, string, CancellationToken) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(IConnection, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(IConnection, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(IConnection, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(IConnection, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(IConnection, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage)(IConnection, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync)(IConnection, string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages)(IConnection, string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;int&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;int&gt;, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;string&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;string&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(int, int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(string, string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, int, int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, string, string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IEnumerable&lt;string&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(int, int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(string, string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(string, string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, int, int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, string, string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, string, string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(string, string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync)(IConnection, string, string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| override [Dispose](../../aspose.email.clients.imap/imapclient/dispose)() | Finalizes all operations with a server. |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder)(string) | Check whether this folder exists |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder)(IConnection, string) | Check whether this folder exists |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder)(string, out ImapFolderInfo) | Check whether this folder exists, extract folder info if so |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder)(IConnection, string, out ImapFolderInfo) | Check whether this folder exists, extract folder info if so |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync)(string) | Check whether this folder exists |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync)(IConnection, string) | Check whether this folder exists |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync)(string, CancellationToken) | Check whether this folder exists |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync)(IConnection, string, CancellationToken) | Check whether this folder exists |
| [FetchAttachment](../../aspose.email.clients.imap/imapclient/fetchattachment)(int, string) | Fetches the specified attachment |
| [FetchAttachment](../../aspose.email.clients.imap/imapclient/fetchattachment)(IConnection, int, string) | Fetches the specified attachment |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync)(int, string) | Fetches the specified attachment |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync)(IConnection, int, string) | Fetches the specified attachment |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync)(int, string, CancellationToken) | Fetches the specified attachment |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync)(IConnection, int, string, CancellationToken) | Fetches the specified attachment |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage)(int) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage)(string) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage)(IConnection, int) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage)(IConnection, string) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage)(int, bool) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage)(IConnection, int, bool) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(int) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(string) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(IConnection, int) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(IConnection, string) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(int, bool) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(int, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(string, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(IConnection, int, bool) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(IConnection, int, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(IConnection, string, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(int, bool, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync)(IConnection, int, bool, CancellationToken) | Fetches the message |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages)(IEnumerable&lt;int&gt;) | Fetches the messages |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages)(IEnumerable&lt;string&gt;) | Fetches the messages |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Fetches the messages |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages)(IConnection, IEnumerable&lt;string&gt;) | Fetches the messages |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync)(IEnumerable&lt;int&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync)(IEnumerable&lt;string&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync)(IConnection, IEnumerable&lt;string&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync)(IEnumerable&lt;int&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Fetches the messages asynchronously |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetFolderInfo](../../aspose.email.clients.imap/imapclient/getfolderinfo)(string) | Returns information about the specified folder without selecting it |
| [GetFolderInfo](../../aspose.email.clients.imap/imapclient/getfolderinfo)(IConnection, string) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync)(string) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync)(IConnection, string) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync)(string, CancellationToken) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync)(IConnection, string, CancellationToken) | Returns information about the specified folder without selecting it |
| [GetMessageThreads](../../aspose.email.clients.imap/imapclient/getmessagethreads)(BaseSearchConditions) | Get message threads. |
| [GetMessageThreads](../../aspose.email.clients.imap/imapclient/getmessagethreads)(IConnection, BaseSearchConditions) | Get message threads. |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync)(BaseSearchConditions) | Get message threads. |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync)(BaseSearchConditions, CancellationToken) | Get message threads. |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync)(IConnection, BaseSearchConditions) | Get message threads. |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync)(IConnection, BaseSearchConditions, CancellationToken) | Get message threads. |
| [GetNamespaces](../../aspose.email.clients.imap/imapclient/getnamespaces)() | Gets namespaces that are available on a server. |
| [GetNamespaces](../../aspose.email.clients.imap/imapclient/getnamespaces)(IConnection) | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync)() | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync)(CancellationToken) | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync)(IConnection) | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync)(IConnection, CancellationToken) | Gets namespaces that are available on a server. |
| [GetQuota](../../aspose.email.clients.imap/imapclient/getquota)(string) | Gets quota information |
| [GetQuota](../../aspose.email.clients.imap/imapclient/getquota)(IConnection, string) | Gets quota information |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync)(string) | Gets quota information |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync)(IConnection, string) | Gets quota information |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync)(string, CancellationToken) | Gets quota information |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync)(IConnection, string, CancellationToken) | Gets quota information |
| [GetQuotaRoot](../../aspose.email.clients.imap/imapclient/getquotaroot)(string) | Gets quota root information for mailbox |
| [GetQuotaRoot](../../aspose.email.clients.imap/imapclient/getquotaroot)(IConnection, string) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync)(string) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync)(IConnection, string) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync)(string, CancellationToken) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync)(IConnection, string, CancellationToken) | Gets quota root information for mailbox |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient)() | Introduces client information to a server. |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient)(IConnection) | Introduces client information to a server. |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient)(ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient)(IConnection, ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync)() | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync)(CancellationToken) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync)(IConnection) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync)(ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync)(IConnection, CancellationToken) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync)(IConnection, ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync)(ImapIdentificationInfo, CancellationToken) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync)(IConnection, ImapIdentificationInfo, CancellationToken) | Introduces client information to a server. |
| [ListAttachments](../../aspose.email.clients.imap/imapclient/listattachments)(int) | Gets the message attachments list. Gets an information for each attachment in message. |
| [ListAttachmentsAsync](../../aspose.email.clients.imap/imapclient/listattachmentsasync)(int) | Gets the message attachments list. Gets an information for each attachment in message. |
| [ListAttachmentsAsync](../../aspose.email.clients.imap/imapclient/listattachmentsasync)(int, CancellationToken) | Gets the message attachments list. Gets an information for each attachment in message. |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders)() | Gets the list of folders in the mailbox |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders)(bool) | Gets the list of folders in the mailbox |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders)(IConnection) | Gets the list of folders in the mailbox |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders)(string) | Gets the list of subfolders in the specified folder |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders)(IConnection, bool) | Gets the list of folders in the mailbox |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders)(IConnection, string) | Gets the list of subfolders in the specified folder |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders)(string, bool) | Gets the list of subfolders in the specified folder |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders)(IConnection, string, bool) | Gets the list of subfolders in the specified folder |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)() | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(bool) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(IConnection) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(string) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(bool, CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(IConnection, bool) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(IConnection, CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(IConnection, string) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(string, bool) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(string, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(IConnection, bool, CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(IConnection, string, bool) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(IConnection, string, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(string, bool, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(IConnection, string, bool, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage)(int) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage)(string) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage)(IConnection, int) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage)(IConnection, string) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage)(int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage)(string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage)(IConnection, int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage)(IConnection, string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(int) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(string) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(IConnection, int) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(IConnection, string) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(int, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(string, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(IConnection, int, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(IConnection, int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(IConnection, string, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(IConnection, string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(int, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(string, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(IConnection, int, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync)(IConnection, string, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)() | Gets the list of messages in the current folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(bool) | Gets the list of messages in the current folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection) | Gets the list of messages in the current folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IEnumerable&lt;string&gt;) | Gets the list of messages in the current folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(MailQuery) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(string) | Gets the list of messages in the specified folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, bool) | Gets the list of messages in the current folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, MailQuery) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, string) | Gets the list of messages in the specified folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(string, bool) | Gets the list of messages in the specified folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(string, IEnumerable&lt;int&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(string, IEnumerable&lt;string&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, string, bool) | Gets the list of messages in the specified folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, string, IEnumerable&lt;int&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, string, IEnumerable&lt;string&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(string, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(string, ImapListFields, int) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, string, ImapListFields, int) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)() | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(bool) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IEnumerable&lt;string&gt;) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(MailQuery) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(string) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(bool, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, bool) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, MailQuery) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, string) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(long, CancellationToken) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(MailQuery, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(string, bool) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(string, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, bool, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, long, CancellationToken) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, MailQuery, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, string, bool) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, string, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(string, bool, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(string, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, string, bool, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(string, bool, IEnumerable&lt;string&gt;, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(string, MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, string, MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync)(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage)(int, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage)(PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage)(int, int, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage)(MailQuery, PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync)(int, int, PageSettings) | Gets the list of messages |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync)(MailQuery, PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync)(int, int, PageSettings, CancellationToken) | Gets the list of messages |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | Gets the list of messages |
| [MoveFolder](../../aspose.email.clients.imap/imapclient/movefolder)(string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolder](../../aspose.email.clients.imap/imapclient/movefolder)(IConnection, string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync)(string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync)(IConnection, string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync)(string, string, CancellationToken) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync)(IConnection, string, string, CancellationToken) | Moves specified folder and its subfolders to new location. |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage)(int, string) | Moves the message |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage)(string, string) | Moves the message |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage)(IConnection, int, string) | Moves the messaeg |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage)(IConnection, string, string) | Moves the message |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage)(int, string, bool) | Moves the message |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage)(string, string, bool) | Moves the message |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage)(IConnection, int, string, bool) | Moves the messaeg |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage)(IConnection, string, string, bool) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(int, string) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(string, string) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(IConnection, int, string) | Moves the messaeg |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(IConnection, string, string) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(int, string, bool) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(int, string, CancellationToken) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(string, string, bool) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(string, string, CancellationToken) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(IConnection, int, string, bool) | Moves the messaeg |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(IConnection, int, string, CancellationToken) | Moves the messaeg |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(IConnection, string, string, bool) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(IConnection, string, string, CancellationToken) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(int, string, bool, CancellationToken) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(string, string, bool, CancellationToken) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(IConnection, int, string, bool, CancellationToken) | Moves the messaeg |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync)(IConnection, string, string, bool, CancellationToken) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IEnumerable&lt;int&gt;, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IConnection, IEnumerable&lt;int&gt;, string) | Moves the messaeg |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IConnection, IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IEnumerable&lt;int&gt;, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(int, int, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(string, string, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IConnection, IEnumerable&lt;int&gt;, string, bool) | Moves the messaeg |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IConnection, IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IConnection, int, int, string) | Moves the messaeg |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IConnection, string, string, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(int, int, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(string, string, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IConnection, int, int, string, bool) | Moves the messaeg |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages)(IConnection, string, string, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;int&gt;, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;int&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;int&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;string&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(int, int, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(string, string, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, bool) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, int, int, string) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, string, string, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;int&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IEnumerable&lt;string&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(int, int, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(int, int, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(string, string, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(string, string, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, bool, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, int, int, string, bool) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, int, int, string, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, string, string, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, string, string, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(int, int, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(string, string, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, int, int, string, bool, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync)(IConnection, string, string, string, bool, CancellationToken) | Moves the message |
| override [Noop](../../aspose.email.clients.imap/imapclient/noop)() | 'No operation' command |
| override [Noop](../../aspose.email.clients.imap/imapclient/noop)(IConnection) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync)() | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync)(CancellationToken) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync)(IConnection) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync)(IConnection, CancellationToken) | 'No operation' command |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags)(IConnection, string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(int, int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(string, string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, int, int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, string, string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(int, int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(string, string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RenameFolder](../../aspose.email.clients.imap/imapclient/renamefolder)(string, string) | Renames a specified folder to a new name |
| [RenameFolder](../../aspose.email.clients.imap/imapclient/renamefolder)(IConnection, string, string) | Renames a specified folder to a new name |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync)(string, string) | Renames a specified folder to a new name |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync)(IConnection, string, string) | Renames a specified folder to a new name |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync)(string, string, CancellationToken) | Renames a specified folder to a new name |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync)(IConnection, string, string, CancellationToken) | Renames a specified folder to a new name |
| [RequestCheckpoint](../../aspose.email.clients.imap/imapclient/requestcheckpoint)() | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpoint](../../aspose.email.clients.imap/imapclient/requestcheckpoint)(IConnection) | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync)() | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync)(CancellationToken) | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync)(IConnection) | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync)(IConnection, CancellationToken) | Requests a checkpoint of the currently selected mailbox. |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Resets logging settings to default. |
| [Restore](../../aspose.email.clients.imap/imapclient/restore)(PersonalStorage, RestoreSettings) | Begins to restore imap folders from the given personal storage. |
| [RestoreAsync](../../aspose.email.clients.imap/imapclient/restoreasync)(PersonalStorage, RestoreSettings) | Begins to restore imap folders from the given personal storage. |
| [RestoreAsync](../../aspose.email.clients.imap/imapclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Begins to restore imap folders from the given personal storage. |
| [ResumeMonitoring](../../aspose.email.clients.imap/imapclient/resumemonitoring)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState) | Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method, it will find all missing mailbox changes and call the callback for them. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/imapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState) | Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method, it will find all missing mailbox changes and call the callback for them. |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage)(int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage)(int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage)(string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage)(string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage)(IConnection, int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage)(IConnection, int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage)(IConnection, string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage)(IConnection, string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(IConnection, int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(IConnection, int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(IConnection, string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(IConnection, string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(int, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(int, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(string, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(string, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(IConnection, int, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(IConnection, int, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(IConnection, string, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync)(IConnection, string, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder)(string) | Selects the specified folder |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder)(IConnection, string) | Selects the specified folder |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder)(string, bool?) | Selects the specified folder |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder)(IConnection, string, bool?) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync)(string) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync)(IConnection, string) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync)(string, bool?) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync)(string, CancellationToken) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync)(IConnection, string, bool?) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync)(IConnection, string, CancellationToken) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync)(string, bool?, CancellationToken) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync)(IConnection, string, bool?, CancellationToken) | Selects the specified folder |
| [SetQuota](../../aspose.email.clients.imap/imapclient/setquota)(string, string, int) | Sets quota information |
| [SetQuota](../../aspose.email.clients.imap/imapclient/setquota)(IConnection, string, string, int) | Sets quota information |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync)(string, string, int) | Sets quota information |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync)(IConnection, string, string, int) | Sets quota information |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync)(string, string, int, CancellationToken) | Sets quota information |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync)(IConnection, string, string, int, CancellationToken) | Sets quota information |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use [`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) property to safely set only protocols that definitely supported by .net framework. Please note, if your current .net framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server. |
| [SortMessageThreads](../../aspose.email.clients.imap/imapclient/sortmessagethreads)(SortConditions) | Get message threads. |
| [SortMessageThreads](../../aspose.email.clients.imap/imapclient/sortmessagethreads)(IConnection, SortConditions) | Get message threads. |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync)(SortConditions) | Sort message threads. |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync)(IConnection, SortConditions) | Sort message threads. |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync)(SortConditions, CancellationToken) | Sort message threads. |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync)(IConnection, SortConditions, CancellationToken) | Sort message threads. |
| [StartMonitoring](../../aspose.email.clients.imap/imapclient/startmonitoring)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Starts monitoring of message changes for specified folder. |
| [StartMonitoringAsync](../../aspose.email.clients.imap/imapclient/startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Starts monitoring of message changes for specified folder. |
| [StopMonitoring](../../aspose.email.clients.imap/imapclient/stopmonitoring)() | Stops any monitoring of changes. |
| [StopMonitoring](../../aspose.email.clients.imap/imapclient/stopmonitoring)(string) | Stops monitoring of message changes for specified folder. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/imapclient/stopmonitoringasync)() | Stops any monitoring of changes. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/imapclient/stopmonitoringasync)(string) | Stops monitoring of message changes for specified folder. |
| [SubscribeFolder](../../aspose.email.clients.imap/imapclient/subscribefolder)(string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolder](../../aspose.email.clients.imap/imapclient/subscribefolder)(IConnection, string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync)(string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync)(IConnection, string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync)(string, CancellationToken) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync)(IConnection, string, CancellationToken) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage)(int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage)(string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage)(IConnection, int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage)(IConnection, string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage)(int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage)(string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage)(IConnection, int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage)(IConnection, string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(IConnection, int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(IConnection, string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(int, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(string, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(IConnection, int, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(IConnection, int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(IConnection, string, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(IConnection, string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(int, long, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(string, long, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(IConnection, int, long, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync)(IConnection, string, long, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder)() | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder)(bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder)(IConnection) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder)(IConnection, bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync)() | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync)(bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync)(CancellationToken) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync)(IConnection) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync)(bool, CancellationToken) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync)(IConnection, bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync)(IConnection, CancellationToken) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync)(IConnection, bool, CancellationToken) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnsubscribeFolder](../../aspose.email.clients.imap/imapclient/unsubscribefolder)(string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolder](../../aspose.email.clients.imap/imapclient/unsubscribefolder)(IConnection, string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync)(string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync)(IConnection, string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync)(string, CancellationToken) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync)(IConnection, string, CancellationToken) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| override [ValidateCredentials](../../aspose.email.clients.imap/imapclient/validatecredentials)() | Executes credentials validation |
| [ValidateCredentials](../../aspose.email.clients.imap/imapclient/validatecredentials)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync)() | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync)(CancellationToken) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync)(IConnection, CancellationToken) | Executes credentials validation |

### See Also

* class [EmailClient](../../aspose.email.clients/emailclient)
* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
