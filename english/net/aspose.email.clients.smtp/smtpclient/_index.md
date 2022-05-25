---
title: SmtpClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 16860
url: /net/aspose.email.clients.smtp/smtpclient/
---
## SmtpClient class

Allows applications to send messages by using the Simple Mail Transfer Protocol (SMTP).

```csharp
public sealed class SmtpClient : EmailClient, IMailTransferAgent
```

## Constructors

| Name | Description |
| --- | --- |
| [SmtpClient](smtpclient)() | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(Configuration) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class by using configuration file settings. |
| [SmtpClient](smtpclient)(string) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, int) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, SecurityOptions) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, int, SecurityOptions) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, string, ITokenProvider) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, string, string) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, int, string, ITokenProvider) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, int, string, string) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, string, ITokenProvider, SecurityOptions) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, string, string, bool) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, string, string, SecurityOptions) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, int, string, ITokenProvider, SecurityOptions) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, int, string, string, bool) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, int, string, string, SecurityOptions) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, string, string, bool, SecurityOptions) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |
| [SmtpClient](smtpclient)(string, int, string, string, bool, SecurityOptions) | Initializes a new instance of the [`SmtpClient`](../smtpclient) class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Gets or sets the access token. |
| [AllowedAuthentication](../../aspose.email.clients.smtp/smtpclient/allowedauthentication) { get; set; } | Gets or sets enumeration of allowed by user authentication types |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Contains collection of clients certificates |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Period of connection checking up in milliseconds. Default value is 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Gets or sets quantity of connections in multy-connection mode |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Gets the current state of the connection. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Gets current connection according to ConnectionAsgmtMode option |
| override [DefaultPort](../../aspose.email.clients.smtp/smtpclient/defaultport) { get; } | Gets default port for client |
| [DeliveryMethod](../../aspose.email.clients.smtp/smtpclient/deliverymethod) { get; set; } | Gets or sets the delivery method. |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Gets or sets value which allows enable/disable logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use [`Timeout`](../../aspose.email.clients/emailclient/timeout) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment. |
| [HelloMessage](../../aspose.email.clients.smtp/smtpclient/hellomessage) { get; set; } | Gets or sets a HELO/EHLO string. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Gets or sets the host name. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Gets or sets log file name |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Gets or sets the password. Password limitations are defined by server implementation, which client connects. |
| [PickupDirectoryLocation](../../aspose.email.clients.smtp/smtpclient/pickupdirectorylocation) { get; set; } | Gets or sets the directory where applications save mail messages to be processed by the local SMTP server. Please note: only absolute path is allowed. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Gets or sets the port. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Gets or sets proxy for the client |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Security mode for a mail client |
| [SmtpQueueLocation](../../aspose.email.clients.smtp/smtpclient/smtpqueuelocation) { get; set; } | Gets or sets the directory where applications save mail messages to be processed by sending in SMTP queue. Please note: only absolute path is allowed. |
| [SupportedAuthentication](../../aspose.email.clients.smtp/smtpclient/supportedauthentication) { get; } | Gets enumeration of supported by server authentication types |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF .NET FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) documentation for more details. Please use [`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (in case if your current version of .net framework supports these versions of TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Gets or sets the timeout for mail operations |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Gets or sets TokenProvider allowing to retrieve access token. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indicates whether authentication is used. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Gets or sets value which indicates if date has to be used in log file name. |
| override [UseDefaultCredentials](../../aspose.email.clients.smtp/smtpclient/usedefaultcredentials) { get; set; } | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Gets or sets object which indicates whether the pipelining mode is enabled. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Gets or sets the username. |
| [UseTnef](../../aspose.email.clients.smtp/smtpclient/usetnef) { get; set; } | Gets or sets a boolean value that controls whether the messages are sent in TNEF format. Note, that now message is sent in TNEF format when being loaded a message contains tnef. |

## Methods

| Name | Description |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Creates new independent connection for operations not linked to threads (not default connection). Invocation of this method is similar to invocation of CreateConnection(createAsDefaultConnection = false) Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Creates new (default or independent) connection for operations. Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Finalizes all operations with a server. |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward)(string, MailAddressCollection, MailMessage) | Forwards specified message to recipient |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward)(string, MailAddressCollection, Stream) | Forwards specified message to recipient |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward)(string, string, MailMessage) | Forwards specified message to recipient |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward)(IConnection, string, MailAddressCollection, MailMessage) | Forwards specified message to recipient |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward)(IConnection, string, MailAddressCollection, Stream) | Forwards specified message to recipient |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward)(IConnection, string, string, MailMessage) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(string, MailAddressCollection, MailMessage) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(string, MailAddressCollection, Stream) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(string, string, MailMessage) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(IConnection, string, MailAddressCollection, MailMessage) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(IConnection, string, MailAddressCollection, Stream) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(IConnection, string, string, MailMessage) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(string, MailAddressCollection, MailMessage, CancellationToken) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(string, MailAddressCollection, Stream, CancellationToken) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(string, string, MailMessage, CancellationToken) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(IConnection, string, MailAddressCollection, Stream, CancellationToken) | Forwards specified message to recipient |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync)(IConnection, string, string, MailMessage, CancellationToken) | Forwards specified message to recipient |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop)() | 'No operation' command |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop)(IConnection) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync)() | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync)(CancellationToken) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync)(IConnection) | 'No operation' command |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync)(IConnection, CancellationToken) | 'No operation' command |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Resets logging settings to default. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send)(IEnumerable&lt;MailMessage&gt;) | Send the specified messages. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send)(MailMessage) | Send the specified message. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send)(MailMessageCollection) | Send the specified message collection. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send)(params MailMessage[]) | Send the specified message. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send)(IConnection, IEnumerable&lt;MailMessage&gt;) | Send the specified messages. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send)(IConnection, MailMessage) | Send the specified message. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send)(IConnection, MailMessageCollection) | Send the specified message collection. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send)(IConnection, params MailMessage[]) | Send the specified message. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send)(string, string, string, string) | Creates and sends the specified message. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send)(IConnection, string, string, string, string) | Creates and sends the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IEnumerable&lt;MailMessage&gt;) | Send the specified messages. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(MailMessage) | Send the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(MailMessageCollection) | Send the specified message collection. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(params MailMessage[]) | Send the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(CancellationToken, params MailMessage[]) | Send the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IConnection, IEnumerable&lt;MailMessage&gt;) | Send the specified messages. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IConnection, MailMessage) | Send the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IConnection, MailMessageCollection) | Send the specified message collection. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IConnection, params MailMessage[]) | Send the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Send the specified messages. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(MailMessage, CancellationToken) | Send the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(MailMessageCollection, CancellationToken) | Send the specified message collection. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IConnection, CancellationToken, params MailMessage[]) | Send the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Send the specified messages. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IConnection, MailMessage, CancellationToken) | Send the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IConnection, MailMessageCollection, CancellationToken) | Send the specified message collection. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(string, string, string, string) | Creates and sends the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IConnection, string, string, string, string) | Creates and sends the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(string, string, string, string, CancellationToken) | Creates and sends the specified message. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync)(IConnection, string, string, string, string, CancellationToken) | Creates and sends the specified message. |
| [SendToQueue](../../aspose.email.clients.smtp/smtpclient/sendtoqueue)(IEnumerable&lt;MailMessage&gt;) | Append messages to queue |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use [`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) property to safely set only protocols that definitely supported by .net framework. Please note, if your current .net framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server. |
| override [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials)() | Executes credentials validation |
| [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync)() | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync)(CancellationToken) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync)(IConnection, CancellationToken) | Executes credentials validation |

### See Also

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IMailTransferAgent](../imailtransferagent)
* namespace [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
