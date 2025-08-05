---
title: Class EmailClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.EmailClient class. Represents the client that creates server connection by using the host credentials
type: docs
weight: 1580
url: /net/aspose.email.clients/emailclient/
---
## EmailClient class

Represents the client that creates server connection by using the host credentials.

```csharp
public abstract class EmailClient : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken/) { get; set; } | Gets or sets the access token. |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates/) { get; } | Contains collection of clients certificates |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode/) { get; set; } | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod/) { get; set; } | Period of connection checking up in milliseconds. Default value is 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity/) { get; set; } | Gets or sets quantity of connections in multy-connection mode |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate/) { get; } | Gets the current state of the connection. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection/) { get; } | Gets current connection according to ConnectionAsgmtMode option |
| virtual [DefaultPort](../../aspose.email.clients/emailclient/defaultport/) { get; } | Gets default port for client |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger/) { get; set; } | Gets or sets value which allows enable/disable logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout/) { get; set; } | Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use [`Timeout`](./timeout/) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment. |
| virtual [Host](../../aspose.email.clients/emailclient/host/) { get; set; } | Gets or sets the host name. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename/) { get; set; } | Gets or sets log file name |
| virtual [Password](../../aspose.email.clients/emailclient/password/) { get; set; } | Gets or sets the password. Password limitations are defined by server implementation, which client connects. |
| virtual [Port](../../aspose.email.clients/emailclient/port/) { get; set; } | Gets or sets the port. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy/) { get; set; } | Gets or sets proxy for the client |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions/) { get; set; } | Security mode for a mail client |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption/) { get; set; } | Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF .NET FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols/) documentation for more details. Please use [`SetSupportedEncryptionUnsafe`](./setsupportedencryptionunsafe/) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (in case if your current version of .net framework supports these versions of TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout/) { get; set; } | Gets or sets the timeout for mail operations |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider/) { get; set; } | Gets or sets TokenProvider allowing to retrieve access token. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication/) { get; set; } | Indicates whether authentication is used. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename/) { get; set; } | Gets or sets value which indicates if date has to be used in log file name. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials/) { get; set; } | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. This option is used with NTLM authentication ONLY! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection/) { get; set; } | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining/) { get; set; } | Gets or sets object which indicates whether the pipelining mode is enabled. |
| virtual [Username](../../aspose.email.clients/emailclient/username/) { get; set; } | Gets or sets the username. |

## Methods

| Name | Description |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection/#createconnection)() | Creates new independent connection for operations not linked to threads (not default connection). Invocation of this method is similar to invocation of CreateConnection(createAsDefaultConnection = false) Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection/#createconnection_1)(bool) | Creates new (default or independent) connection for operations. Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose/)() | Finalizes all operations with a server. |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities/)() |  |
| abstract [Noop](../../aspose.email.clients/emailclient/noop/#noop)() | 'No operation' command |
| abstract [Noop](../../aspose.email.clients/emailclient/noop/#noop_1)(IConnection) | 'No operation' command |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings/)() | Resets logging settings to default. |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe/)(EncryptionProtocols) | Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use [`SupportedEncryption`](./supportedencryption/) property to safely set only protocols that definitely supported by .net framework. Please note, if your current .net framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server. |
| abstract [ValidateCredentials](../../aspose.email.clients/emailclient/validatecredentials/)() | Checks if the credentials are valid |

## Events

| Name | Description |
| --- | --- |
| event [BindIPEndPoint](../../aspose.email.clients/emailclient/bindipendpoint/) | Associates a Socket with a local endpoint. |
| event [OnConnect](../../aspose.email.clients/emailclient/onconnect/) | The OnConnect event occurs when the clent establishes connection. |

### See Also

* namespace [Aspose.Email.Clients](../../aspose.email.clients/)
* assembly [Aspose.Email](../../)


