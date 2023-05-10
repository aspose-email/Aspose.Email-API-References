---
title: Class ImapClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Imap.ImapClient class. Allows applications to access and manipulate messages by using the Internet Message Access Protocol IMAP
type: docs
weight: 16280
url: /net/aspose.email.clients.imap/imapclient/
---
## ImapClient class

Allows applications to access and manipulate messages by using the Internet Message Access Protocol (IMAP).

```csharp
public sealed class ImapClient : EmailClient, IAsyncImapClient
```

## Constructors

| Name | Description |
| --- | --- |
| [ImapClient](imapclient/#constructor)() | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_1)(string) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_3)(string, int) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_2)(string, SecurityOptions) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_4)(string, int, SecurityOptions) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_13)(string, string, ITokenProvider) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_15)(string, string, string) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_5)(string, int, string, ITokenProvider) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_7)(string, int, string, string) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_14)(string, string, ITokenProvider, SecurityOptions) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_17)(string, string, string, bool) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_16)(string, string, string, SecurityOptions) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_6)(string, int, string, ITokenProvider, SecurityOptions) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_9)(string, int, string, string, bool) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_11)(string, int, string, string, RemoteCertificateValidationCallback) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_8)(string, int, string, string, SecurityOptions) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_18)(string, string, string, bool, SecurityOptions) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_10)(string, int, string, string, bool, SecurityOptions) | Initializes a new instance of the `ImapClient` class |
| [ImapClient](imapclient/#constructor_12)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Initializes a new instance of the `ImapClient` class |

## Properties

| Name | Description |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken/) { get; set; } | Gets or sets the access token. |
| [AllowedAuthentication](../../aspose.email.clients.imap/imapclient/allowedauthentication/) { get; set; } | Gets or sets enumeration of allowed by user authentication types |
| [AnnotateSupported](../../aspose.email.clients.imap/imapclient/annotatesupported/) { get; set; } | Gets information whether ANNOTATE extension is supported See more: https://tools.ietf.org/html/rfc5257 |
| [AutoCommit](../../aspose.email.clients.imap/imapclient/autocommit/) { get; set; } | Indicates, whether commit operation are executed automatically when folder is changed or before connection is closed. |
| [ChildrenSupported](../../aspose.email.clients.imap/imapclient/childrensupported/) { get; set; } | Gets information whether CHILDREN extension is supported See more: https://tools.ietf.org/html/rfc3348 |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates/) { get; } | Contains collection of clients certificates |
| [ClientIdentificationInfo](../../aspose.email.clients.imap/imapclient/clientidentificationinfo/) { get; set; } | Gets or sets client identification information See more: https://tools.ietf.org/html/rfc2971 |
| [CompressSupported](../../aspose.email.clients.imap/imapclient/compresssupported/) { get; set; } | Gets information whether COMPRESS extension is supported See more: https://tools.ietf.org/html/rfc4978 |
| [CondstoreSupported](../../aspose.email.clients.imap/imapclient/condstoresupported/) { get; set; } | Gets information whether CONDSTORE extension is supported See more: https://tools.ietf.org/html/rfc7162 |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode/) { get; set; } | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod/) { get; set; } | Period of connection checking up in milliseconds. Default value is 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity/) { get; set; } | Gets or sets quantity of connections in multy-connection mode |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate/) { get; } | Gets the current state of the connection. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection/) { get; } | Gets current connection according to ConnectionAsgmtMode option |
| [CurrentFolder](../../aspose.email.clients.imap/imapclient/currentfolder/) { get; set; } | Gets the current folder |
| override [DefaultPort](../../aspose.email.clients.imap/imapclient/defaultport/) { get; } | Gets default port for client |
| [Delimiter](../../aspose.email.clients.imap/imapclient/delimiter/) { get; set; } | Gets or sets delimiter of folders hierarhy. |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger/) { get; set; } | Gets or sets value which allows enable/disable logger |
| [EnableSupported](../../aspose.email.clients.imap/imapclient/enablesupported/) { get; set; } | Gets information whether ENABLE extension is supported See more: https://tools.ietf.org/html/rfc5161 |
| [ESearchSupported](../../aspose.email.clients.imap/imapclient/esearchsupported/) { get; set; } | Gets information whether ESEARCH extension is supported See more: https://tools.ietf.org/html/rfc4731 |
| [ExchangeIdAutomatically](../../aspose.email.clients.imap/imapclient/exchangeidautomatically/) { get; set; } | Gets or sets value which indicates whether client should to introduce information about itself to a server automatically. See more: https://tools.ietf.org/html/rfc2971 |
| [ExtendedListSupported](../../aspose.email.clients.imap/imapclient/extendedlistsupported/) { get; set; } | Gets information whether LIST Command Extension is supported See more https://tools.ietf.org/html/rfc5258 |
| [GmExt1Supported](../../aspose.email.clients.imap/imapclient/gmext1supported/) { get; set; } | Defines if Google X-GM-EXT-1 extension is supported |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout/) { get; set; } | Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use [`Timeout`](../../aspose.email.clients/emailclient/timeout/) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment. |
| virtual [Host](../../aspose.email.clients/emailclient/host/) { get; set; } | Gets or sets the host name. |
| [IdSupported](../../aspose.email.clients.imap/imapclient/idsupported/) { get; set; } | Gets information whether ID extension is supported See more: https://tools.ietf.org/html/rfc2971 |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename/) { get; set; } | Gets or sets log file name |
| [MailboxInfo](../../aspose.email.clients.imap/imapclient/mailboxinfo/) { get; } | Gets set of special-use mailboxes See more: http://tools.ietf.org/html/rfc6154 and https://tools.ietf.org/html/rfc8457 |
| [MoveSupported](../../aspose.email.clients.imap/imapclient/movesupported/) { get; set; } | Gets information whether MOVE extension is supported See more: https://tools.ietf.org/html/rfc6851 |
| [NamespaceSupported](../../aspose.email.clients.imap/imapclient/namespacesupported/) { get; set; } | Gets information whether NAMESPACE extension is supported See more: https://tools.ietf.org/html/rfc2342 |
| virtual [Password](../../aspose.email.clients/emailclient/password/) { get; set; } | Gets or sets the password. Password limitations are defined by server implementation, which client connects. |
| virtual [Port](../../aspose.email.clients/emailclient/port/) { get; set; } | Gets or sets the port. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy/) { get; set; } | Gets or sets proxy for the client |
| [QresyncSupported](../../aspose.email.clients.imap/imapclient/qresyncsupported/) { get; set; } | Gets information whether QRESYNC extension is supported See more: https://tools.ietf.org/html/rfc7162 |
| [QuotaSupported](../../aspose.email.clients.imap/imapclient/quotasupported/) { get; set; } | Gets information whether quota is supported |
| [ReadOnly](../../aspose.email.clients.imap/imapclient/readonly/) { get; set; } | Gets or sets value which indicates if changes to the permanent state of the mailbox, including per-user state, are permitted. |
| [SaslIrSupported](../../aspose.email.clients.imap/imapclient/saslirsupported/) { get; set; } | Gets information whether SASL Initial Client Response extension is supported See more: https://tools.ietf.org/html/rfc4959 |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions/) { get; set; } | Security mode for a mail client |
| [ServerIdentificationInfo](../../aspose.email.clients.imap/imapclient/serveridentificationinfo/) { get; } | Gets server identification information See more: https://tools.ietf.org/html/rfc2971 |
| [ServerSupportedCompression](../../aspose.email.clients.imap/imapclient/serversupportedcompression/) { get; } | Gets information which compression types are supported by a server. See more: https://tools.ietf.org/html/rfc4978 |
| [SortSupported](../../aspose.email.clients.imap/imapclient/sortsupported/) { get; set; } | Gets information whether Sort command are supported |
| [SpecialUseSupported](../../aspose.email.clients.imap/imapclient/specialusesupported/) { get; set; } | Gets information whether Special-Use Mailboxes is supported See more: https://tools.ietf.org/html/rfc6154 |
| [SupportedAuthentication](../../aspose.email.clients.imap/imapclient/supportedauthentication/) { get; } | Gets enumeration of supported by server authentication types |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption/) { get; set; } | Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF .NET FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols/) documentation for more details. Please use [`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe/) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (in case if your current version of .net framework supports these versions of TLS) |
| [SupportOldServer](../../aspose.email.clients.imap/imapclient/supportoldserver/) { get; set; } | Indicates whether the old servers need to be supported when receiving messages. |
| [ThreadAlgorithms](../../aspose.email.clients.imap/imapclient/threadalgorithms/) { get; } | Gets supported thread algorithms |
| [ThreadSupported](../../aspose.email.clients.imap/imapclient/threadsupported/) { get; set; } | Gets information whether Thread command are supported |
| [Timeout](../../aspose.email.clients/emailclient/timeout/) { get; set; } | Gets or sets the timeout for mail operations |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider/) { get; set; } | Gets or sets TokenProvider allowing to retrieve access token. |
| [UidPlusSupported](../../aspose.email.clients.imap/imapclient/uidplussupported/) { get; set; } | Gets information whether UIDPLUS extension is supported See more: https://tools.ietf.org/html/rfc4315 |
| [UnselectSupported](../../aspose.email.clients.imap/imapclient/unselectsupported/) { get; set; } | Gets information whether UNSELECT extension is supported See more: https://tools.ietf.org/html/rfc2342 |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication/) { get; set; } | Indicates whether authentication is used. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename/) { get; set; } | Gets or sets value which indicates if date has to be used in log file name. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials/) { get; set; } | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. This option is used with NTLM authentication ONLY! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection/) { get; set; } | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining/) { get; set; } | Gets or sets object which indicates whether the pipelining mode is enabled. |
| virtual [Username](../../aspose.email.clients/emailclient/username/) { get; set; } | Gets or sets the username. |
| static [DefaultFolder](../../aspose.email.clients.imap/imapclient/defaultfolder/) { get; set; } | Default folder for ImapClients |

## Methods

| Name | Description |
| --- | --- |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_18)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_20)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_22)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_14)(int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_24)(string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_6)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_8)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags)(IConnection, int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_10)(IConnection, string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_19)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_21)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_23)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_15)(int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_16)(int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_25)(string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_26)(string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_7)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_9)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_1)(IConnection, int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_2)(IConnection, int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_11)(IConnection, string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_12)(IConnection, string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_17)(int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_27)(string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_3)(IConnection, int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags/#addmessageflags_13)(IConnection, string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_36)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_40)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_44)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_28)(int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_48)(string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_12)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_16)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync)(IConnection, int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_20)(IConnection, string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_43)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_41)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_47)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_45)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_31)(int, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_29)(int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_32)(int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_51)(string, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_49)(string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_52)(string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_15)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_13)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_19)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_17)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_3)(IConnection, int, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_1)(IConnection, int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_4)(IConnection, int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_23)(IConnection, string, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_21)(IConnection, string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_24)(IConnection, string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_42)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_46)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_30)(int, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_35)(int, int, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_33)(int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_50)(string, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_55)(string, string, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_53)(string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_14)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_18)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_2)(IConnection, int, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_7)(IConnection, int, int, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_5)(IConnection, int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_22)(IConnection, string, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_27)(IConnection, string, string, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_25)(IConnection, string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_34)(int, int, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_54)(string, string, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_6)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync/#addmessageflagsasync_26)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage/#appendmessage_4)(MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage/#appendmessage_5)(string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage/#appendmessage)(IConnection, MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage/#appendmessage_1)(IConnection, string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage/#appendmessage_6)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage/#appendmessage_7)(string, string) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage/#appendmessage_2)(IConnection, string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage/#appendmessage_3)(IConnection, string, string) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_8)(MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_10)(string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync)(IConnection, MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_2)(IConnection, string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_9)(MailMessage, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_15)(string, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_11)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_13)(string, string) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_1)(IConnection, MailMessage, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_7)(IConnection, string, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_3)(IConnection, string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_5)(IConnection, string, string) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_12)(string, MailMessage, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_14)(string, string, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_4)(IConnection, string, MailMessage, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync/#appendmessageasync_6)(IConnection, string, string, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages/#appendmessages_2)(IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages/#appendmessages)(IConnection, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages/#appendmessages_3)(string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages/#appendmessages_1)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync/#appendmessagesasync_4)(IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync/#appendmessagesasync)(IConnection, IEnumerable&lt;MailMessage&gt;) | Uploads the mail messages to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync/#appendmessagesasync_5)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync/#appendmessagesasync_6)(string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail messages to the current folder |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync/#appendmessagesasync_1)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail messages to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync/#appendmessagesasync_2)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail messages to the current folder |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync/#appendmessagesasync_7)(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail messages to the current folder |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync/#appendmessagesasync_3)(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail messages to the current folder |
| [Backup](../../aspose.email.clients.imap/imapclient/backup/#backup_2)(ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [Backup](../../aspose.email.clients.imap/imapclient/backup/#backup_3)(ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [Backup](../../aspose.email.clients.imap/imapclient/backup/#backup)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [Backup](../../aspose.email.clients.imap/imapclient/backup/#backup_1)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync/#backupasync_4)(ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync/#backupasync_6)(ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync/#backupasync)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync/#backupasync_2)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync/#backupasync_5)(ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync/#backupasync_7)(ImapFolderInfoCollection, string, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync/#backupasync_1)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync/#backupasync_3)(IConnection, ImapFolderInfoCollection, string, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_18)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_20)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_22)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_14)(int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_24)(string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_6)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_8)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags)(IConnection, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_10)(IConnection, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_19)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_21)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_23)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_15)(int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_16)(int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_25)(string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_26)(string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_7)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_9)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_1)(IConnection, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_2)(IConnection, int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_11)(IConnection, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_12)(IConnection, string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_17)(int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_27)(string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_3)(IConnection, int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags/#changemessageflags_13)(IConnection, string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_36)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_40)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_44)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_28)(int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_48)(string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_12)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_16)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync)(IConnection, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_20)(IConnection, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_43)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_41)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_47)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_45)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_31)(int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_29)(int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_32)(int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_51)(string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_49)(string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_52)(string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_15)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_13)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_19)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_17)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_3)(IConnection, int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_1)(IConnection, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_4)(IConnection, int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_23)(IConnection, string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_21)(IConnection, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_24)(IConnection, string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_42)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_46)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_30)(int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_35)(int, int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_33)(int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_50)(string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_55)(string, string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_53)(string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_14)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_18)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_2)(IConnection, int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_7)(IConnection, int, int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_5)(IConnection, int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_22)(IConnection, string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_27)(IConnection, string, string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_25)(IConnection, string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_34)(int, int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_54)(string, string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_6)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync/#changemessageflagsasync_26)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ClientCapabilities](../../aspose.email.clients.imap/imapclient/clientcapabilities/#clientcapabilities_1)(params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilities](../../aspose.email.clients.imap/imapclient/clientcapabilities/#clientcapabilities)(IConnection, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync/#clientcapabilitiesasync_2)(params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync/#clientcapabilitiesasync_3)(CancellationToken, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync/#clientcapabilitiesasync)(IConnection, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync/#clientcapabilitiesasync_1)(IConnection, CancellationToken, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes/#commitdeletes)() | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes/#commitdeletes_1)(IConnection) | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes/#commitdeletes_7)(IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes/#commitdeletes_6)(int) | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes/#commitdeletes_8)(string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes/#commitdeletes_3)(IConnection, IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes/#commitdeletes_2)(IConnection, int) | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes/#commitdeletes_4)(IConnection, string) | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes/#commitdeletes_9)(string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes/#commitdeletes_5)(IConnection, string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync)() | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_19)(CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_1)(IConnection) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_13)(IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_11)(int) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_15)(string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_10)(IConnection, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_4)(IConnection, IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_2)(IConnection, int) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_6)(IConnection, string) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_14)(IEnumerable&lt;string&gt;, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_12)(int, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_18)(string, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_16)(string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_5)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_3)(IConnection, int, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_9)(IConnection, string, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_7)(IConnection, string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_17)(string, string, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync/#commitdeletesasync_8)(IConnection, string, string, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage/#copymessage_2)(int, string) | Copies the message |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage/#copymessage_3)(string, string) | Copies the message |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage/#copymessage)(IConnection, int, string) | Copies the message |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage/#copymessage_1)(IConnection, string, string) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync/#copymessageasync_4)(int, string) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync/#copymessageasync_6)(string, string) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync/#copymessageasync)(IConnection, int, string) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync/#copymessageasync_2)(IConnection, string, string) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync/#copymessageasync_5)(int, string, CancellationToken) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync/#copymessageasync_7)(string, string, CancellationToken) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync/#copymessageasync_1)(IConnection, int, string, CancellationToken) | Copies the message |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync/#copymessageasync_3)(IConnection, string, string, CancellationToken) | Copies the message |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages_6)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages_7)(IEnumerable&lt;int&gt;, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages_9)(IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages_1)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages_2)(IConnection, IEnumerable&lt;int&gt;, string) | Copy the messaeg |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages_3)(IConnection, IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages_8)(IEnumerable&lt;int&gt;, string, bool) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages_5)(int, int, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages_10)(string, string, string) | Copy messages |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages)(IConnection, int, int, string) | Copy the messaeg |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages/#copymessages_4)(IConnection, string, string, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_12)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_14)(IEnumerable&lt;int&gt;, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_17)(IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_2)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_4)(IConnection, IEnumerable&lt;int&gt;, string) | Copy the messaeg |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_6)(IConnection, IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_13)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_16)(IEnumerable&lt;int&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_18)(IEnumerable&lt;string&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_10)(int, int, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_19)(string, string, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_3)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_5)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) | Copy the messaeg |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_7)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync)(IConnection, int, int, string) | Copy the messaeg |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_8)(IConnection, string, string, string) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_11)(int, int, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_20)(string, string, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_1)(IConnection, int, int, string, CancellationToken) | Copy the messaeg |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync/#copymessagesasync_9)(IConnection, string, string, string, CancellationToken) | Copy messages |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection/)() | Creates new independent connection for operations not linked to threads (not default connection). Invocation of this method is similar to invocation of CreateConnection(createAsDefaultConnection = false) Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection/)(bool) | Creates new (default or independent) connection for operations. Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| [CreateFolder](../../aspose.email.clients.imap/imapclient/createfolder/#createfolder_1)(string) | Creates a folder with the specified name |
| [CreateFolder](../../aspose.email.clients.imap/imapclient/createfolder/#createfolder)(IConnection, string) | Creates a folder with the specified name |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync/#createfolderasync_2)(string) | Creates a folder with the specified name |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync/#createfolderasync)(IConnection, string) | Creates a folder with the specified name |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync/#createfolderasync_3)(string, CancellationToken) | Creates a folder with the specified name |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync/#createfolderasync_1)(IConnection, string, CancellationToken) | Creates a folder with the specified name |
| [DeleteFolder](../../aspose.email.clients.imap/imapclient/deletefolder/#deletefolder_1)(string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolder](../../aspose.email.clients.imap/imapclient/deletefolder/#deletefolder)(IConnection, string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync/#deletefolderasync_2)(string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync/#deletefolderasync)(IConnection, string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync/#deletefolderasync_3)(string, CancellationToken) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync/#deletefolderasync_1)(IConnection, string, CancellationToken) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_6)(int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_8)(string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage)(IConnection, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_2)(IConnection, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_7)(int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_9)(string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_10)(string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_1)(IConnection, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_3)(IConnection, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_4)(IConnection, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_11)(string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage/#deletemessage_5)(IConnection, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_12)(int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_16)(string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync)(IConnection, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_4)(IConnection, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_15)(int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_13)(int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_17)(string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_23)(string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_19)(string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_3)(IConnection, int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_1)(IConnection, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_5)(IConnection, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_11)(IConnection, string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_7)(IConnection, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_14)(int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_18)(string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_20)(string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_22)(string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_2)(IConnection, int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_6)(IConnection, string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_8)(IConnection, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_10)(IConnection, string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_21)(string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync/#deletemessageasync_9)(IConnection, string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_18)(IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_22)(IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_24)(IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_2)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_6)(IConnection, IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_8)(IConnection, IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_19)(IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_20)(IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_23)(IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_25)(IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_26)(IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_16)(int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_28)(string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_3)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_7)(IConnection, IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_9)(IConnection, IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_10)(IConnection, IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages)(IConnection, int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_12)(IConnection, string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_21)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_27)(IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_17)(int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_29)(string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_30)(string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_11)(IConnection, IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_1)(IConnection, int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_13)(IConnection, string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_14)(IConnection, string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_31)(string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages/#deletemessages_15)(IConnection, string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_36)(IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_44)(IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_48)(IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_12)(IConnection, IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_16)(IConnection, IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_43)(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_47)(IEnumerable&lt;int&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_45)(IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_49)(IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_55)(IEnumerable&lt;string&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_51)(IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_32)(int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_56)(string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_7)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_15)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_13)(IConnection, IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_17)(IConnection, IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_23)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_19)(IConnection, IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync)(IConnection, int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_24)(IConnection, string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_40)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_42)(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_46)(IEnumerable&lt;int&gt;, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_50)(IEnumerable&lt;string&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_52)(IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_54)(IEnumerable&lt;string&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_35)(int, int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_33)(int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_57)(string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_63)(string, string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_59)(string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_6)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_14)(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_18)(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_20)(IConnection, IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_22)(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_3)(IConnection, int, int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_1)(IConnection, int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_25)(IConnection, string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_31)(IConnection, string, string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_27)(IConnection, string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_41)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_53)(IEnumerable&lt;string&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_34)(int, int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_58)(string, string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_60)(string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_62)(string, string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_21)(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_2)(IConnection, int, int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_26)(IConnection, string, string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_28)(IConnection, string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_30)(IConnection, string, string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_61)(string, string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync/#deletemessagesasync_29)(IConnection, string, string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| override [Dispose](../../aspose.email.clients.imap/imapclient/dispose/)() | Finalizes all operations with a server. |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder/#existfolder_2)(string) | Check whether this folder exists |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder/#existfolder)(IConnection, string) | Check whether this folder exists |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder/#existfolder_3)(string, out ImapFolderInfo) | Check whether this folder exists, extract folder info if so |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder/#existfolder_1)(IConnection, string, out ImapFolderInfo) | Check whether this folder exists, extract folder info if so |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync/#existfolderasync_2)(string) | Check whether this folder exists |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync/#existfolderasync)(IConnection, string) | Check whether this folder exists |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync/#existfolderasync_3)(string, CancellationToken) | Check whether this folder exists |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync/#existfolderasync_1)(IConnection, string, CancellationToken) | Check whether this folder exists |
| [FetchAttachment](../../aspose.email.clients.imap/imapclient/fetchattachment/#fetchattachment_1)(int, string) | Fetches the specified attachment |
| [FetchAttachment](../../aspose.email.clients.imap/imapclient/fetchattachment/#fetchattachment)(IConnection, int, string) | Fetches the specified attachment |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync/#fetchattachmentasync_2)(int, string) | Fetches the specified attachment |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync/#fetchattachmentasync)(IConnection, int, string) | Fetches the specified attachment |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync/#fetchattachmentasync_3)(int, string, CancellationToken) | Fetches the specified attachment |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync/#fetchattachmentasync_1)(IConnection, int, string, CancellationToken) | Fetches the specified attachment |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage/#fetchmessage_3)(int) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage/#fetchmessage_5)(string) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage/#fetchmessage)(IConnection, int) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage/#fetchmessage_2)(IConnection, string) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage/#fetchmessage_4)(int, bool) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage/#fetchmessage_1)(IConnection, int, bool) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_6)(int) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_10)(string) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync)(IConnection, int) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_4)(IConnection, string) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_7)(int, bool) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_9)(int, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_11)(string, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_1)(IConnection, int, bool) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_3)(IConnection, int, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_5)(IConnection, string, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_8)(int, bool, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync/#fetchmessageasync_2)(IConnection, int, bool, CancellationToken) | Fetches the message |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages/#fetchmessages_2)(IEnumerable&lt;int&gt;) | Fetches the messages |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages/#fetchmessages_3)(IEnumerable&lt;string&gt;) | Fetches the messages |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages/#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Fetches the messages |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages/#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | Fetches the messages |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync/#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync/#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync/#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync/#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync/#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync/#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync/#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync/#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Fetches the messages asynchronously |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities/)() |  |
| [GetFolderInfo](../../aspose.email.clients.imap/imapclient/getfolderinfo/#getfolderinfo_1)(string) | Returns information about the specified folder without selecting it |
| [GetFolderInfo](../../aspose.email.clients.imap/imapclient/getfolderinfo/#getfolderinfo)(IConnection, string) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync/#getfolderinfoasync_2)(string) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync/#getfolderinfoasync)(IConnection, string) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync/#getfolderinfoasync_3)(string, CancellationToken) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync/#getfolderinfoasync_1)(IConnection, string, CancellationToken) | Returns information about the specified folder without selecting it |
| [GetMessageThreads](../../aspose.email.clients.imap/imapclient/getmessagethreads/#getmessagethreads_1)(BaseSearchConditions) | Get message threads. |
| [GetMessageThreads](../../aspose.email.clients.imap/imapclient/getmessagethreads/#getmessagethreads)(IConnection, BaseSearchConditions) | Get message threads. |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync/#getmessagethreadsasync_2)(BaseSearchConditions) | Get message threads. |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync/#getmessagethreadsasync_3)(BaseSearchConditions, CancellationToken) | Get message threads. |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync/#getmessagethreadsasync)(IConnection, BaseSearchConditions) | Get message threads. |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync/#getmessagethreadsasync_1)(IConnection, BaseSearchConditions, CancellationToken) | Get message threads. |
| [GetNamespaces](../../aspose.email.clients.imap/imapclient/getnamespaces/#getnamespaces)() | Gets namespaces that are available on a server. |
| [GetNamespaces](../../aspose.email.clients.imap/imapclient/getnamespaces/#getnamespaces_1)(IConnection) | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync/#getnamespacesasync)() | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync/#getnamespacesasync_3)(CancellationToken) | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync/#getnamespacesasync_1)(IConnection) | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync/#getnamespacesasync_2)(IConnection, CancellationToken) | Gets namespaces that are available on a server. |
| [GetQuota](../../aspose.email.clients.imap/imapclient/getquota/#getquota_1)(string) | Gets quota information |
| [GetQuota](../../aspose.email.clients.imap/imapclient/getquota/#getquota)(IConnection, string) | Gets quota information |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync/#getquotaasync_2)(string) | Gets quota information |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync/#getquotaasync)(IConnection, string) | Gets quota information |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync/#getquotaasync_3)(string, CancellationToken) | Gets quota information |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync/#getquotaasync_1)(IConnection, string, CancellationToken) | Gets quota information |
| [GetQuotaRoot](../../aspose.email.clients.imap/imapclient/getquotaroot/#getquotaroot_1)(string) | Gets quota root information for mailbox |
| [GetQuotaRoot](../../aspose.email.clients.imap/imapclient/getquotaroot/#getquotaroot)(IConnection, string) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync/#getquotarootasync_2)(string) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync/#getquotarootasync)(IConnection, string) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync/#getquotarootasync_3)(string, CancellationToken) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync/#getquotarootasync_1)(IConnection, string, CancellationToken) | Gets quota root information for mailbox |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient/#introduceclient)() | Introduces client information to a server. |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient/#introduceclient_1)(IConnection) | Introduces client information to a server. |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient/#introduceclient_3)(ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient/#introduceclient_2)(IConnection, ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync/#introduceclientasync)() | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync/#introduceclientasync_7)(CancellationToken) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync/#introduceclientasync_1)(IConnection) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync/#introduceclientasync_5)(ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync/#introduceclientasync_4)(IConnection, CancellationToken) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync/#introduceclientasync_2)(IConnection, ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync/#introduceclientasync_6)(ImapIdentificationInfo, CancellationToken) | Introduces client information to a server. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync/#introduceclientasync_3)(IConnection, ImapIdentificationInfo, CancellationToken) | Introduces client information to a server. |
| [ListAttachments](../../aspose.email.clients.imap/imapclient/listattachments/)(int) | Gets the message attachments list. Gets an information for each attachment in message. |
| [ListAttachmentsAsync](../../aspose.email.clients.imap/imapclient/listattachmentsasync/#listattachmentsasync)(int) | Gets the message attachments list. Gets an information for each attachment in message. |
| [ListAttachmentsAsync](../../aspose.email.clients.imap/imapclient/listattachmentsasync/#listattachmentsasync_1)(int, CancellationToken) | Gets the message attachments list. Gets an information for each attachment in message. |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders/#listfolders)() | Gets the list of folders in the mailbox |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders/#listfolders_6)(bool) | Gets the list of folders in the mailbox |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders/#listfolders_1)(IConnection) | Gets the list of folders in the mailbox |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders/#listfolders_7)(string) | Gets the list of subfolders in the specified folder |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders/#listfolders_2)(IConnection, bool) | Gets the list of folders in the mailbox |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders/#listfolders_3)(IConnection, string) | Gets the list of subfolders in the specified folder |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders/#listfolders_8)(string, bool) | Gets the list of subfolders in the specified folder |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders/#listfolders_4)(IConnection, string, bool) | Gets the list of subfolders in the specified folder |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders/#listfolders_9)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders/#listfolders_5)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync)() | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_11)(bool) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_19)(CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_1)(IConnection) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_13)(string) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_12)(bool, CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_2)(IConnection, bool) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_10)(IConnection, CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_4)(IConnection, string) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_14)(string, bool) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_18)(string, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_3)(IConnection, bool, CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_5)(IConnection, string, bool) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_9)(IConnection, string, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_17)(string, bool, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_8)(IConnection, string, bool, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_15)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_6)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_16)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync/#listfoldersasync_7)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage/#listmessage_4)(int) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage/#listmessage_6)(string) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage/#listmessage)(IConnection, int) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage/#listmessage_2)(IConnection, string) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage/#listmessage_5)(int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage/#listmessage_7)(string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage/#listmessage_1)(IConnection, int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage/#listmessage_3)(IConnection, string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_8)(int) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_12)(string) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync)(IConnection, int) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_4)(IConnection, string) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_11)(int, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_9)(int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_15)(string, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_13)(string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_3)(IConnection, int, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_1)(IConnection, int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_7)(IConnection, string, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_5)(IConnection, string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_10)(int, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_14)(string, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_2)(IConnection, int, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync/#listmessageasync_6)(IConnection, string, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages)() | Gets the list of messages in the current folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_16)(bool) | Gets the list of messages in the current folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_1)(IConnection) | Gets the list of messages in the current folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_19)(IEnumerable&lt;string&gt;) | Gets the list of messages in the current folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_17)(int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_18)(long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_14)(MailQuery) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_20)(string) | Gets the list of messages in the specified folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_4)(IConnection, bool) | Gets the list of messages in the current folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_5)(IConnection, int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_6)(IConnection, long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_2)(IConnection, MailQuery) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_7)(IConnection, string) | Gets the list of messages in the specified folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_15)(MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_23)(string, bool) | Gets the list of messages in the specified folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_25)(string, IEnumerable&lt;int&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_26)(string, IEnumerable&lt;string&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_3)(IConnection, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_10)(IConnection, string, bool) | Gets the list of messages in the specified folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_12)(IConnection, string, IEnumerable&lt;int&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_13)(IConnection, string, IEnumerable&lt;string&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_24)(string, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_21)(string, ImapListFields, int) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_22)(string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_8)(IConnection, string, ImapListFields, int) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_9)(IConnection, string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages/#listmessages_11)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync)() | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_25)(bool) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_41)(CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_1)(IConnection) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_31)(IEnumerable&lt;string&gt;) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_27)(int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_29)(long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_21)(MailQuery) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_33)(string) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_26)(bool, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_6)(IConnection, bool) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_20)(IConnection, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_8)(IConnection, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_10)(IConnection, long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_2)(IConnection, MailQuery) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_12)(IConnection, string) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_32)(IEnumerable&lt;string&gt;, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_28)(int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_30)(long, CancellationToken) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_24)(MailQuery, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_22)(MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_36)(string, bool) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_40)(string, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_7)(IConnection, bool, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_9)(IConnection, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_11)(IConnection, long, CancellationToken) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_5)(IConnection, MailQuery, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_3)(IConnection, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_15)(IConnection, string, bool) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_19)(IConnection, string, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_23)(MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_39)(string, bool, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_37)(string, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_34)(string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_4)(IConnection, MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_16)(IConnection, string, bool, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_13)(IConnection, string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_38)(string, bool, IEnumerable&lt;string&gt;, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_35)(string, MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_17)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_14)(IConnection, string, MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync/#listmessagesasync_18)(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage/#listmessagesbypage_2)(int, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage/#listmessagesbypage)(PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage/#listmessagesbypage_3)(int, int, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage/#listmessagesbypage_1)(MailQuery, PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync/#listmessagesbypageasync_2)(int, int, PageSettings) | Gets the list of messages |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync/#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync/#listmessagesbypageasync_3)(int, int, PageSettings, CancellationToken) | Gets the list of messages |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync/#listmessagesbypageasync_1)(MailQuery, PageInfo, PageSettings, CancellationToken) | Gets the list of messages |
| [MoveFolder](../../aspose.email.clients.imap/imapclient/movefolder/#movefolder_1)(string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolder](../../aspose.email.clients.imap/imapclient/movefolder/#movefolder)(IConnection, string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync/#movefolderasync_2)(string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync/#movefolderasync)(IConnection, string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync/#movefolderasync_3)(string, string, CancellationToken) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync/#movefolderasync_1)(IConnection, string, string, CancellationToken) | Moves specified folder and its subfolders to new location. |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage/#movemessage_4)(int, string) | Moves the message |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage/#movemessage_6)(string, string) | Moves the message |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage/#movemessage)(IConnection, int, string) | Moves the messaeg |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage/#movemessage_2)(IConnection, string, string) | Moves the message |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage/#movemessage_5)(int, string, bool) | Moves the message |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage/#movemessage_7)(string, string, bool) | Moves the message |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage/#movemessage_1)(IConnection, int, string, bool) | Moves the messaeg |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage/#movemessage_3)(IConnection, string, string, bool) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_8)(int, string) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_12)(string, string) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync)(IConnection, int, string) | Moves the messaeg |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_4)(IConnection, string, string) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_9)(int, string, bool) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_11)(int, string, CancellationToken) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_13)(string, string, bool) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_15)(string, string, CancellationToken) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_1)(IConnection, int, string, bool) | Moves the messaeg |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_3)(IConnection, int, string, CancellationToken) | Moves the messaeg |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_5)(IConnection, string, string, bool) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_7)(IConnection, string, string, CancellationToken) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_10)(int, string, bool, CancellationToken) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_14)(string, string, bool, CancellationToken) | Moves the message |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_2)(IConnection, int, string, bool, CancellationToken) | Moves the messaeg |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync/#movemessageasync_6)(IConnection, string, string, bool, CancellationToken) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_12)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_14)(IEnumerable&lt;int&gt;, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_16)(IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_2)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_4)(IConnection, IEnumerable&lt;int&gt;, string) | Moves the messaeg |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_6)(IConnection, IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_13)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_15)(IEnumerable&lt;int&gt;, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_17)(IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_10)(int, int, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_18)(string, string, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_3)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_5)(IConnection, IEnumerable&lt;int&gt;, string, bool) | Moves the messaeg |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_7)(IConnection, IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages)(IConnection, int, int, string) | Moves the messaeg |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_8)(IConnection, string, string, string) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_11)(int, int, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_19)(string, string, string, bool) | Moves the message |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_1)(IConnection, int, int, string, bool) | Moves the messaeg |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages/#movemessages_9)(IConnection, string, string, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_24)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_28)(IEnumerable&lt;int&gt;, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_32)(IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_8)(IConnection, IEnumerable&lt;int&gt;, string) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_12)(IConnection, IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_25)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_27)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_29)(IEnumerable&lt;int&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_31)(IEnumerable&lt;int&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_33)(IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_35)(IEnumerable&lt;string&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_20)(int, int, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_36)(string, string, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_7)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_9)(IConnection, IEnumerable&lt;int&gt;, string, bool) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_11)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_13)(IConnection, IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_15)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync)(IConnection, int, int, string) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_16)(IConnection, string, string, string) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_26)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_30)(IEnumerable&lt;int&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_34)(IEnumerable&lt;string&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_21)(int, int, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_23)(int, int, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_37)(string, string, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_39)(string, string, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_6)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_10)(IConnection, IEnumerable&lt;int&gt;, string, bool, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_14)(IConnection, IEnumerable&lt;string&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_1)(IConnection, int, int, string, bool) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_3)(IConnection, int, int, string, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_17)(IConnection, string, string, string, bool) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_19)(IConnection, string, string, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_22)(int, int, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_38)(string, string, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_2)(IConnection, int, int, string, bool, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync/#movemessagesasync_18)(IConnection, string, string, string, bool, CancellationToken) | Moves the message |
| override [Noop](../../aspose.email.clients.imap/imapclient/noop/#noop)() | 'No operation' command |
| override [Noop](../../aspose.email.clients.imap/imapclient/noop/#noop_1)(IConnection) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync/#noopasync)() | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync/#noopasync_3)(CancellationToken) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync/#noopasync_1)(IConnection) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync/#noopasync_2)(IConnection, CancellationToken) | 'No operation' command |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_18)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_20)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_22)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_14)(int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_24)(string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_6)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_8)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags)(IConnection, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_10)(IConnection, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_19)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_21)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_23)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_15)(int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_16)(int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_25)(string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_26)(string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_7)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_9)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_1)(IConnection, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_2)(IConnection, int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_11)(IConnection, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_12)(IConnection, string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_17)(int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_27)(string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_3)(IConnection, int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags/#removemessageflags_13)(IConnection, string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_36)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_40)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_44)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_28)(int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_48)(string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_12)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_16)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync)(IConnection, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_20)(IConnection, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_43)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_41)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_47)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_45)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_31)(int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_29)(int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_32)(int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_51)(string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_49)(string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_52)(string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_15)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_13)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_19)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_17)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_3)(IConnection, int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_1)(IConnection, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_4)(IConnection, int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_23)(IConnection, string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_21)(IConnection, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_24)(IConnection, string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_42)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_46)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_30)(int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_35)(int, int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_33)(int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_50)(string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_55)(string, string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_53)(string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_14)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_18)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_2)(IConnection, int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_7)(IConnection, int, int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_5)(IConnection, int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_22)(IConnection, string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_27)(IConnection, string, string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_25)(IConnection, string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_34)(int, int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_54)(string, string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_6)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync/#removemessageflagsasync_26)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RenameFolder](../../aspose.email.clients.imap/imapclient/renamefolder/#renamefolder_1)(string, string) | Renames a specified folder to a new name |
| [RenameFolder](../../aspose.email.clients.imap/imapclient/renamefolder/#renamefolder)(IConnection, string, string) | Renames a specified folder to a new name |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync/#renamefolderasync_2)(string, string) | Renames a specified folder to a new name |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync/#renamefolderasync)(IConnection, string, string) | Renames a specified folder to a new name |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync/#renamefolderasync_3)(string, string, CancellationToken) | Renames a specified folder to a new name |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync/#renamefolderasync_1)(IConnection, string, string, CancellationToken) | Renames a specified folder to a new name |
| [RequestCheckpoint](../../aspose.email.clients.imap/imapclient/requestcheckpoint/#requestcheckpoint)() | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpoint](../../aspose.email.clients.imap/imapclient/requestcheckpoint/#requestcheckpoint_1)(IConnection) | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync/#requestcheckpointasync)() | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync/#requestcheckpointasync_3)(CancellationToken) | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync/#requestcheckpointasync_1)(IConnection) | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync/#requestcheckpointasync_2)(IConnection, CancellationToken) | Requests a checkpoint of the currently selected mailbox. |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings/)() | Resets logging settings to default. |
| [Restore](../../aspose.email.clients.imap/imapclient/restore/)(PersonalStorage, RestoreSettings) | Begins to restore imap folders from the given personal storage. |
| [RestoreAsync](../../aspose.email.clients.imap/imapclient/restoreasync/#restoreasync)(PersonalStorage, RestoreSettings) | Begins to restore imap folders from the given personal storage. |
| [RestoreAsync](../../aspose.email.clients.imap/imapclient/restoreasync/#restoreasync_1)(PersonalStorage, RestoreSettings, CancellationToken) | Begins to restore imap folders from the given personal storage. |
| [ResumeMonitoring](../../aspose.email.clients.imap/imapclient/resumemonitoring/)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState) | Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method, it will find all missing mailbox changes and call the callback for them. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/imapclient/resumemonitoringasync/)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method, it will find all missing mailbox changes and call the callback for them. |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage/#savemessage_4)(int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage/#savemessage_5)(int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage/#savemessage_6)(string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage/#savemessage_7)(string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage/#savemessage)(IConnection, int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage/#savemessage_1)(IConnection, int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage/#savemessage_2)(IConnection, string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage/#savemessage_3)(IConnection, string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_8)(int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_10)(int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_12)(string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_14)(string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync)(IConnection, int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_2)(IConnection, int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_4)(IConnection, string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_6)(IConnection, string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_9)(int, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_11)(int, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_13)(string, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_15)(string, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_3)(IConnection, int, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync/#savemessageasync_7)(IConnection, string, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder/#selectfolder_2)(string) | Selects the specified folder |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder/#selectfolder)(IConnection, string) | Selects the specified folder |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder/#selectfolder_3)(string, bool?) | Selects the specified folder |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder/#selectfolder_1)(IConnection, string, bool?) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync/#selectfolderasync_4)(string) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync/#selectfolderasync)(IConnection, string) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync/#selectfolderasync_5)(string, bool?) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync/#selectfolderasync_7)(string, CancellationToken) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync/#selectfolderasync_1)(IConnection, string, bool?) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync/#selectfolderasync_3)(IConnection, string, CancellationToken) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync/#selectfolderasync_6)(string, bool?, CancellationToken) | Selects the specified folder |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync/#selectfolderasync_2)(IConnection, string, bool?, CancellationToken) | Selects the specified folder |
| [SetQuota](../../aspose.email.clients.imap/imapclient/setquota/#setquota_1)(string, string, int) | Sets quota information |
| [SetQuota](../../aspose.email.clients.imap/imapclient/setquota/#setquota)(IConnection, string, string, int) | Sets quota information |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync/#setquotaasync_2)(string, string, int) | Sets quota information |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync/#setquotaasync)(IConnection, string, string, int) | Sets quota information |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync/#setquotaasync_3)(string, string, int, CancellationToken) | Sets quota information |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync/#setquotaasync_1)(IConnection, string, string, int, CancellationToken) | Sets quota information |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe/)(EncryptionProtocols) | Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use [`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption/) property to safely set only protocols that definitely supported by .net framework. Please note, if your current .net framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server. |
| [SortMessageThreads](../../aspose.email.clients.imap/imapclient/sortmessagethreads/#sortmessagethreads_1)(SortConditions) | Get message threads. |
| [SortMessageThreads](../../aspose.email.clients.imap/imapclient/sortmessagethreads/#sortmessagethreads)(IConnection, SortConditions) | Get message threads. |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync/#sortmessagethreadsasync_2)(SortConditions) | Sort message threads. |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync/#sortmessagethreadsasync)(IConnection, SortConditions) | Sort message threads. |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync/#sortmessagethreadsasync_3)(SortConditions, CancellationToken) | Sort message threads. |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync/#sortmessagethreadsasync_1)(IConnection, SortConditions, CancellationToken) | Sort message threads. |
| [StartMonitoring](../../aspose.email.clients.imap/imapclient/startmonitoring/#startmonitoring_1)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Starts monitoring of message changes for specified folder. |
| [StartMonitoringAsync](../../aspose.email.clients.imap/imapclient/startmonitoringasync/#startmonitoringasync_1)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Starts monitoring of message changes for specified folder. |
| [StopMonitoring](../../aspose.email.clients.imap/imapclient/stopmonitoring/#stopmonitoring)() | Stops any monitoring of changes. |
| [StopMonitoring](../../aspose.email.clients.imap/imapclient/stopmonitoring/#stopmonitoring_1)(string) | Stops monitoring of message changes for specified folder. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/imapclient/stopmonitoringasync/#stopmonitoringasync)() | Stops any monitoring of changes. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/imapclient/stopmonitoringasync/#stopmonitoringasync_1)(string) | Stops monitoring of message changes for specified folder. |
| [SubscribeFolder](../../aspose.email.clients.imap/imapclient/subscribefolder/#subscribefolder_1)(string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolder](../../aspose.email.clients.imap/imapclient/subscribefolder/#subscribefolder)(IConnection, string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync/#subscribefolderasync_2)(string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync/#subscribefolderasync)(IConnection, string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync/#subscribefolderasync_3)(string, CancellationToken) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync/#subscribefolderasync_1)(IConnection, string, CancellationToken) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage/#undeletemessage_4)(int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage/#undeletemessage_6)(string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage/#undeletemessage)(IConnection, int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage/#undeletemessage_2)(IConnection, string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage/#undeletemessage_5)(int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage/#undeletemessage_7)(string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage/#undeletemessage_1)(IConnection, int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage/#undeletemessage_3)(IConnection, string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_8)(int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_12)(string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync)(IConnection, int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_4)(IConnection, string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_11)(int, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_9)(int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_15)(string, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_13)(string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_3)(IConnection, int, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_1)(IConnection, int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_7)(IConnection, string, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_5)(IConnection, string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_10)(int, long, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_14)(string, long, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_2)(IConnection, int, long, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync/#undeletemessageasync_6)(IConnection, string, long, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder/#unselectfolder)() | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder/#unselectfolder_3)(bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder/#unselectfolder_1)(IConnection) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder/#unselectfolder_2)(IConnection, bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync/#unselectfolderasync)() | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync/#unselectfolderasync_5)(bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync/#unselectfolderasync_7)(CancellationToken) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync/#unselectfolderasync_1)(IConnection) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync/#unselectfolderasync_6)(bool, CancellationToken) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync/#unselectfolderasync_2)(IConnection, bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync/#unselectfolderasync_4)(IConnection, CancellationToken) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync/#unselectfolderasync_3)(IConnection, bool, CancellationToken) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnsubscribeFolder](../../aspose.email.clients.imap/imapclient/unsubscribefolder/#unsubscribefolder_1)(string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolder](../../aspose.email.clients.imap/imapclient/unsubscribefolder/#unsubscribefolder)(IConnection, string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync/#unsubscribefolderasync_2)(string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync/#unsubscribefolderasync)(IConnection, string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync/#unsubscribefolderasync_3)(string, CancellationToken) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync/#unsubscribefolderasync_1)(IConnection, string, CancellationToken) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| override [ValidateCredentials](../../aspose.email.clients.imap/imapclient/validatecredentials/#validatecredentials)() | Executes credentials validation |
| [ValidateCredentials](../../aspose.email.clients.imap/imapclient/validatecredentials/#validatecredentials_1)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync/#validatecredentialsasync)() | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync/#validatecredentialsasync_3)(CancellationToken) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync/#validatecredentialsasync_1)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync/#validatecredentialsasync_2)(IConnection, CancellationToken) | Executes credentials validation |
| static [CreateAsync](../../aspose.email.clients.imap/imapclient/createasync/)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Creates a new instance of the `ImapClient` class |

## Events

| Name | Description |
| --- | --- |
| event [BindIPEndPoint](../../aspose.email.clients/emailclient/bindipendpoint/) | Associates a Socket with a local endpoint. |
| event [OnConnect](../../aspose.email.clients/emailclient/onconnect/) | The OnConnect event occurs when the clent establishes connection. |

### See Also

* class [EmailClient](../../aspose.email.clients/emailclient/)
* interface [IAsyncImapClient](../iasyncimapclient/)
* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap/)
* assembly [Aspose.Email](../../)


