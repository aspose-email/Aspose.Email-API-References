---
title: Pop3Client
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 16740
url: /net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

Allows applications to access and manipulate messages by using the Post Office Protocol Version 3 (POP3).

```csharp
public sealed class Pop3Client : EmailClient
```

## Constructors

| Name | Description |
| --- | --- |
| [Pop3Client](pop3client)() | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, string, string) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, string) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, string, string, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, ITokenProvider, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, string, RemoteCertificateValidationCallback) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, string, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, string, bool, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |

## Properties

| Name | Description |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Gets or sets the access token. |
| [AllowedAuthentication](../../aspose.email.clients.pop3/pop3client/allowedauthentication) { get; set; } | Gets or sets enumeration of allowed by user authentication types |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Contains collection of clients certificates |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Period of connection checking up in milliseconds. Default value is 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Gets or sets quantity of connections in multy-connection mode |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Gets the current state of the connection. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Gets current connection according to ConnectionAsgmtMode option |
| override [DefaultPort](../../aspose.email.clients.pop3/pop3client/defaultport) { get; } | Gets default port for client |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Gets or sets value which allows enable/disable logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use [`Timeout`](../../aspose.email.clients/emailclient/timeout) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Gets or sets the host name. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Gets or sets log file name |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Gets or sets the password. Password limitations are defined by server implementation, which client connects. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Gets or sets the port. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Gets or sets proxy for the client |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Security mode for a mail client |
| [SupportedAuthentication](../../aspose.email.clients.pop3/pop3client/supportedauthentication) { get; } | Gets enumeration of supported by server authentication types |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF .NET FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) documentation for more details. Please use [`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (in case if your current version of .net framework supports these versions of TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Gets or sets the timeout for mail operations |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Gets or sets TokenProvider allowing to retrieve access token. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indicates whether authentication is used. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Gets or sets value which indicates if date has to be used in log file name. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. This option is used with NTLM authentication ONLY! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Gets or sets object which indicates whether the pipelining mode is enabled. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Gets or sets the username. |

## Methods

| Name | Description |
| --- | --- |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes)() | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes)(IConnection) | Commit the deletions |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes)(int) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync)() | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync)(CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync)(IConnection) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync)(int) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync)(IConnection, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync)(int, CancellationToken) | Commit the deletions |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Creates new independent connection for operations not linked to threads (not default connection). Invocation of this method is similar to invocation of CreateConnection(createAsDefaultConnection = false) Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Creates new (default or independent) connection for operations. Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage)(int) | Deletes the message |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage)(string) | Deletes the message |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage)(IConnection, int) | Deletes the message |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage)(IConnection, string) | Deletes the message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync)(int) | Deletes the message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync)(string) | Deletes the message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync)(IConnection, int) | Deletes the message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync)(IConnection, string) | Deletes the message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync)(int, CancellationToken) | Deletes the message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync)(string, CancellationToken) | Deletes the message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync)(IConnection, int, CancellationToken) | Deletes the message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync)(IConnection, string, CancellationToken) | Deletes the message |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages)() | Deletes all messages |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages)(IConnection) | Deletes all messages |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync)() | Deletes all messages |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync)(CancellationToken) | Deletes all messages |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync)(IConnection) | Deletes all messages |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync)(IConnection, CancellationToken) | Deletes all messages |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Finalizes all operations with a server. |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage)(int) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage)(string) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage)(IConnection, int) | Fetches the message |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage)(IConnection, string) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync)(int) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync)(string) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync)(IConnection, int) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync)(IConnection, string) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync)(int, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync)(string, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync)(IConnection, int, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync)(IConnection, string, CancellationToken) | Fetches the message |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages)(IEnumerable&lt;int&gt;) | Fetches the messages |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages)(IEnumerable&lt;string&gt;) | Fetches the messages |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Fetches the messages |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages)(IConnection, IEnumerable&lt;string&gt;) | Fetches the messages |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync)(IEnumerable&lt;int&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync)(IEnumerable&lt;string&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync)(IConnection, IEnumerable&lt;string&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync)(IEnumerable&lt;int&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Fetches the messages asynchronously |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo)() | Gets the mailbox status info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo)(bool) | Gets the mailbox status info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo)(IConnection) | Gets the mailbox status info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo)(IConnection, bool) | Gets the mailbox status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync)() | Gets the mailbox status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync)(bool) | Gets the mailbox status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync)(CancellationToken) | Gets the mailbox status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync)(IConnection) | Gets the mailbox status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync)(bool, CancellationToken) | Gets the mailbox status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync)(IConnection, bool) | Gets the mailbox status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync)(IConnection, CancellationToken) | Gets the mailbox status info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync)(IConnection, bool, CancellationToken) | Gets the mailbox status info |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize)() | Gets the size of the mailbox |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize)(IConnection) | Gets the size of the mailbox |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync)() | Gets the size of the mailbox |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync)(CancellationToken) | Gets the size of the mailbox |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync)(IConnection) | Gets the size of the mailbox |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync)(IConnection, CancellationToken) | Gets the size of the mailbox |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount)() | Gets the message count |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount)(bool) | Gets the message count |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount)(IConnection) | Gets the message count |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount)(IConnection, bool) | Gets the message count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync)() | Gets the message count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync)(bool) | Gets the message count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync)(CancellationToken) | Gets the message count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync)(IConnection) | Gets the message count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync)(bool, CancellationToken) | Gets the message count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync)(IConnection, bool) | Gets the message count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync)(IConnection, CancellationToken) | Gets the message count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync)(IConnection, bool, CancellationToken) | Gets the message count |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders)(int) | Gets the message headers |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders)(string) | Gets the message headers |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders)(IConnection, int) | Gets the message headers |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders)(IConnection, string) | Gets the message headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync)(int) | Gets the message headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync)(string) | Gets the message headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync)(IConnection, int) | Gets the message headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync)(IConnection, string) | Gets the message headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync)(int, CancellationToken) | Gets the message headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync)(string, CancellationToken) | Gets the message headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync)(IConnection, int, CancellationToken) | Gets the message headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync)(IConnection, string, CancellationToken) | Gets the message headers |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo)(int) | Gets the information for that message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo)(string) | Gets the information for that message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo)(IConnection, int) | Gets the information for that message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo)(IConnection, string) | Gets the information for that message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo)(int, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo)(string, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo)(IConnection, int, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo)(IConnection, string, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(int) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(string) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(IConnection, int) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(IConnection, string) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(int, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(int, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(string, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(string, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(IConnection, int, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(IConnection, int, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(IConnection, string, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(IConnection, string, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(int, Pop3ListFields, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(string, Pop3ListFields, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(IConnection, int, Pop3ListFields, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync)(IConnection, string, Pop3ListFields, CancellationToken) | Gets the information for that message |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize)(int) | Gets the size of the message |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize)(string) | Gets the size of the message |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize)(IConnection, int) | Gets the size of the message |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize)(IConnection, string) | Gets the size of the message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync)(int) | Gets the size of the message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync)(string) | Gets the size of the message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync)(IConnection, int) | Gets the size of the message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync)(IConnection, string) | Gets the size of the message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync)(int, CancellationToken) | Gets the size of the message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync)(string, CancellationToken) | Gets the size of the message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync)(IConnection, int, CancellationToken) | Gets the size of the message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync)(IConnection, string, CancellationToken) | Gets the size of the message |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid)(int) | Gets the message unique id |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid)(IConnection, int) | Gets the message unique id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync)(int) | Gets the message unique id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync)(IConnection, int) | Gets the message unique id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync)(int, CancellationToken) | Gets the message unique id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync)(IConnection, int, CancellationToken) | Gets the message unique id |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)() | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(bool) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(IConnection) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(IEnumerable&lt;int&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(IEnumerable&lt;string&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(MailQuery) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(Pop3ListFields) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(IConnection, bool) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(IConnection, IEnumerable&lt;int&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(IConnection, IEnumerable&lt;string&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(IConnection, MailQuery) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(IConnection, Pop3ListFields) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(Pop3ListFields, bool, MailQuery) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages)(IConnection, Pop3ListFields, bool, MailQuery) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)() | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(bool) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(CancellationToken) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(IConnection) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(MailQuery) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(Pop3ListFields) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(bool, CancellationToken) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(IConnection, bool) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(IConnection, CancellationToken) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(IConnection, MailQuery) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(IConnection, Pop3ListFields) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(MailQuery, CancellationToken) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(Pop3ListFields, CancellationToken) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(IConnection, bool, CancellationToken) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(IConnection, MailQuery, CancellationToken) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(IConnection, Pop3ListFields, CancellationToken) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(Pop3ListFields, bool, MailQuery) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(IConnection, Pop3ListFields, bool, MailQuery) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(Pop3ListFields, bool, MailQuery, CancellationToken) | Lists the messages. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | Lists the messages. |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist)(IEnumerable&lt;int&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist)(IEnumerable&lt;Pop3MessageInfo&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist)(IConnection, IEnumerable&lt;int&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync)(IEnumerable&lt;int&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync)(IEnumerable&lt;Pop3MessageInfo&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync)(IConnection, IEnumerable&lt;int&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync)(IEnumerable&lt;int&gt;, CancellationToken) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Loads list of Pop3MessageInfo |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop)() | 'No operation' command |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop)(IConnection) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync)() | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync)(CancellationToken) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync)(IConnection) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync)(IConnection, CancellationToken) | 'No operation' command |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Resets logging settings to default. |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage)(int, Stream) | Fetches and save the message as a stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage)(int, string) | Fetches and save the message into a file |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage)(string, Stream) | Fetches and save the message as a stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage)(string, string) | Fetches and save the message into a file |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage)(IConnection, int, Stream) | Fetches and save the message as a stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage)(IConnection, int, string) | Fetches and save the message into a file |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage)(IConnection, string, Stream) | Fetches and save the message as a stream |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage)(IConnection, string, string) | Fetches and save the message into a file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(int, Stream) | Fetches and save the message as a stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(int, string) | Fetches and save the message into a file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(string, Stream) | Fetches and save the message as a stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(string, string) | Fetches and save the message into a file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(IConnection, int, Stream) | Fetches and save the message as a stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(IConnection, int, string) | Fetches and save the message into a file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(IConnection, string, Stream) | Fetches and save the message as a stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(IConnection, string, string) | Fetches and save the message into a file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(int, Stream, CancellationToken) | Fetches and save the message as a stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(int, string, CancellationToken) | Fetches and save the message into a file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(string, Stream, CancellationToken) | Fetches and save the message as a stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(string, string, CancellationToken) | Fetches and save the message into a file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(IConnection, int, Stream, CancellationToken) | Fetches and save the message as a stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(IConnection, int, string, CancellationToken) | Fetches and save the message into a file |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(IConnection, string, Stream, CancellationToken) | Fetches and save the message as a stream |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync)(IConnection, string, string, CancellationToken) | Fetches and save the message into a file |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use [`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) property to safely set only protocols that definitely supported by .net framework. Please note, if your current .net framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages)() | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages)(IConnection) | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync)() | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync)(CancellationToken) | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync)(IConnection) | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync)(IConnection, CancellationToken) | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| override [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials)() | Executes credentials validation |
| [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync)() | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync)(CancellationToken) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync)(IConnection, CancellationToken) | Executes credentials validation |

### See Also

* class [EmailClient](../../aspose.email.clients/emailclient)
* namespace [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
