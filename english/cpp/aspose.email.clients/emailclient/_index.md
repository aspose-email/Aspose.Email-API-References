---
title: "Aspose::Email::Clients::EmailClient class"
linktitle: "EmailClient"
articleTitle: "EmailClient"
second_title: "Aspose.Email for C++"
description: "Represents the client that creates server connection by using the host credentials."
type: docs
weight: 10
url: /cpp/aspose.email.clients/emailclient/
---

## EmailClient class

Represents the client that creates server connection by using the host credentials.

## Constructors

| Name | Description |
| --- | --- |
| [EmailClient (9 overloads)](./emailclient/) | Initializes a new instance of the EmailClient class. |

## Methods

| Name | Description |
| --- | --- |
| [CancelAsyncOperation](./cancelasyncoperation/) | Cancels asynchronous operation. This method is used only with APM operations also known as Begin/End methods. Please do not use this method with TAP operations! |
| [ConnectionFinalize](./connectionfinalize/) | Performs finalization operation for specified connection |
| [CreateConnection (2 overloads)](./createconnection/) | Creates new independent connection for operations not linked to threads (not default connection). Invocation of this method is similar to invocation of CreateConnection(createAsDefaultConnection = false) Please see more in documentation for EmailClient.ConnectionAsgmtMode property. |
| [Dispose (2 overloads)](./dispose/) | Finalizes all operations with a server. |
| [EndGroupOperation](./endgroupoperation/) | Waits for the pending asynchronous operation to complete. |
| [get_AccessToken](./get_accesstoken/) | Gets the access token. |
| [get_ClientCertificates](./get_clientcertificates/) | Contains collection of clients certificates |
| [get_ConnectionAsgmtMode](./get_connectionasgmtmode/) | Gets value which defines mode of connection allocation in multiple threads environment |
| [get_ConnectionCheckupPeriod](./get_connectioncheckupperiod/) | Period of connection checking up in milliseconds. Default value is 5 min. |
| [get_ConnectionPool](./get_connectionpool/) | Gets connection pool for the client |
| [get_ConnectionsQuantity](./get_connectionsquantity/) | Gets quantity of connections in multy-connection mode |
| [get_ConnectionState](./get_connectionstate/) | Gets the current state of the connection. |
| [get_Credentials](./get_credentials/) |  |
| [get_CurrentConnection](./get_currentconnection/) | Gets current connection according to ConnectionAsgmtMode option |
| [get_DefaultEncoding](./get_defaultencoding/) | Gets default encoding for email client |
| [get_DefaultPort](./get_defaultport/) | Gets default port for client |
| [get_EnableLogger](./get_enablelogger/) | Gets value which allows enable/disable logger |
| [get_GreetingTimeout](./get_greetingtimeout/) | Gets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. |
| [get_Host](./get_host/) | Gets the host name. |
| [get_LogFileName](./get_logfilename/) | Gets log file name |
| [get_Logger](./get_logger/) |  |
| [get_Password](./get_password/) | Gets the password. Password limitations are defined by server implementation, which client connects. |
| [get_Port](./get_port/) | Gets the port. |
| [get_Proxy](./get_proxy/) | Gets proxy for the client |
| [get_SecurityOptions](./get_securityoptions/) | Security mode for a mail client |
| [get_SupportedEncryption](./get_supportedencryption/) | Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF .NET FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see EncryptionProtocols documentation for more details. Please use SetSupportedEncryptionUnsafe method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls | Tls11 | Tls12 | Tls13 (in case if your current version of .net framework supports these versions of TLS) |
| [get_Timeout](./get_timeout/) | Gets the timeout for mail operations |
| [get_TokenProvider](./get_tokenprovider/) | Gets TokenProvider allowing to retrieve access token. |
| [get_UseAuthentication](./get_useauthentication/) | Indicates whether authentication is used. |
| [get_UseDateInLogFileName](./get_usedateinlogfilename/) | Gets value which indicates if date has to be used in log file name. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/) | Gets a Boolean value that controls whether the DefaultCredentials are sent with requests. This option is used with NTLM authentication ONLY! |
| [get_UseMultiConnection](./get_usemulticonnection/) | Gets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing. |
| [get_UsePipelining](./get_usepipelining/) | Gets object which indicates whether the pipelining mode is enabled. |
| [get_Username](./get_username/) | Gets the username. |
| [GetCapabilities](./getcapabilities/) |  |
| [InitializeConnectionPool](./initializeconnectionpool/) |  |
| [initializeLogger](./initializelogger/) |  |
| [Noop (3 overloads)](./noop/) | 'No operation' command |
| [ResetLogSettings](./resetlogsettings/) | Resets logging settings to default. |
| [set_AccessToken](./set_accesstoken/) | Sets the access token. |
| [set_ConnectionAsgmtMode](./set_connectionasgmtmode/) | Sets value which defines mode of connection allocation in multiple threads environment |
| [set_ConnectionCheckupPeriod](./set_connectioncheckupperiod/) | Period of connection checking up in milliseconds. Default value is 5 min. |
| [set_ConnectionPool](./set_connectionpool/) | Sets connection pool for the client |
| [set_ConnectionsQuantity](./set_connectionsquantity/) | Sets quantity of connections in multy-connection mode |
| [set_Credentials](./set_credentials/) |  |
| [set_DefaultEncoding](./set_defaultencoding/) | Sets default encoding for email client |
| [set_EnableLogger](./set_enablelogger/) | Sets value which allows enable/disable logger |
| [set_GreetingTimeout](./set_greetingtimeout/) | Sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. |
| [set_Host](./set_host/) | Sets the host name. |
| [set_LogFileName](./set_logfilename/) | Sets log file name |
| [set_Logger](./set_logger/) |  |
| [set_Password](./set_password/) | Sets the password. Password limitations are defined by server implementation, which client connects. |
| [set_Port](./set_port/) | Sets the port. |
| [set_Proxy](./set_proxy/) | Sets proxy for the client |
| [set_SecurityOptions](./set_securityoptions/) | Security mode for a mail client |
| [set_SupportedEncryption](./set_supportedencryption/) | Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF .NET FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see EncryptionProtocols documentation for more details. Please use SetSupportedEncryptionUnsafe method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls | Tls11 | Tls12 | Tls13 (in case if your current version of .net framework supports these versions of TLS) |
| [set_Timeout](./set_timeout/) | Sets the timeout for mail operations |
| [set_TokenProvider](./set_tokenprovider/) | Sets TokenProvider allowing to retrieve access token. |
| [set_UseAuthentication](./set_useauthentication/) | Indicates whether authentication is used. |
| [set_UseDateInLogFileName](./set_usedateinlogfilename/) | Sets value which indicates if date has to be used in log file name. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/) | Sets a Boolean value that controls whether the DefaultCredentials are sent with requests. This option is used with NTLM authentication ONLY! |
| [set_UseMultiConnection](./set_usemulticonnection/) | Sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing. |
| [set_UsePipelining](./set_usepipelining/) | Sets object which indicates whether the pipelining mode is enabled. |
| [set_Username](./set_username/) | Sets the username. |
| [SetCredentials](./setcredentials/) |  |
| [SetSupportedEncryptionUnsafe](./setsupportedencryptionunsafe/) | Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use SupportedEncryption property to safely set only protocols that definitely supported by .net framework. Please note, if your current .net framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server. |
| [ValidateCredentials](./validatecredentials/) | Checks if the credentials are valid |
| [Aspose::Email::Clients::Imap::ImapClient](./asposeemailclientsimapimapclient/) |  |
| [Aspose::Email::Clients::Pop3::Pop3Client](./asposeemailclientspop3pop3client/) |  |
| [Aspose::Email::Clients::Smtp::SmtpClient](./asposeemailclientssmtpsmtpclient/) |  |
| [accessToken](./accesstoken/) |  |
| [clientType](./clienttype/) |  |
| [connectionPool](./connectionpool/) |  |
| [logger](./logger/) |  |
| [loggerSyncObj](./loggersyncobj/) |  |
| [logManagerSyncObj](./logmanagersyncobj/) |  |
| [password](./password/) |  |
| [tokenProvider](./tokenprovider/) |  |
| [username](./username/) |  |

