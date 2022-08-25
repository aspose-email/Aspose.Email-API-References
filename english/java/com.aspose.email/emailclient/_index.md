---
title: EmailClient
second_title: Aspose.Email for Java API Reference
description:  Represents the client that creates server connection by using the host credentials.
type: docs
weight: 168
url: /java/com.aspose.email/emailclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class EmailClient implements System.IDisposable, Closeable
```

Represents the client that creates server connection by using the host credentials.
## Methods

| Method | Description |
| --- | --- |
| [setSocketsLayerVersion2(boolean value)](#setSocketsLayerVersion2-boolean-) | Sets value indicating whether Sockets Layer version 2 is used. |
| [setSocketsLayerVersion2DisableSSLCertificateValidation(boolean value)](#setSocketsLayerVersion2DisableSSLCertificateValidation-boolean-) | Disable SSL certificate validation for Sockets Layer version 2 |
| [setSocketsLayerVersion2SSLSocketFactory(SSLSocketFactory value)](#setSocketsLayerVersion2SSLSocketFactory-javax.net.ssl.SSLSocketFactory-) | Set SSL Socket Factory for Sockets Layer version 2 |
| [resetLogSettings()](#resetLogSettings--) | Resets logging settings to default. |
| [getEnableLogger()](#getEnableLogger--) | Gets or sets value which allows enable/disable logger |
| [setEnableLogger(boolean value)](#setEnableLogger-boolean-) | Gets or sets value which allows enable/disable logger |
| [getLogFileName()](#getLogFileName--) | Gets or sets log file name |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Gets or sets log file name |
| [getUseDateInLogFileName()](#getUseDateInLogFileName--) | Gets or sets value which indicates if date has to be used in log file name. |
| [setUseDateInLogFileName(boolean value)](#setUseDateInLogFileName-boolean-) | Gets or sets value which indicates if date has to be used in log file name. |
| [setSupportedEncryptionUnsafe(int value)](#setSupportedEncryptionUnsafe-int-) | Defines the versions of SSL/TLS encryption protocols to be used. |
| [getSupportedEncryption()](#getSupportedEncryption--) | Defines the versions of SSL/TLS encryption protocols to be used. |
| [setSupportedEncryption(int value)](#setSupportedEncryption-int-) | Defines the versions of SSL/TLS encryption protocols to be used. |
| [getClientCertificates()](#getClientCertificates--) | Contains collection of clients certificates |
| [getUsePipelining()](#getUsePipelining--) | Gets or sets object which indicates whether the pipelining mode is enabled. |
| [setUsePipelining(PipeliningStatus value)](#setUsePipelining-com.aspose.email.PipeliningStatus-) | Gets or sets object which indicates whether the pipelining mode is enabled. |
| [getHost()](#getHost--) | Gets or sets the host name. |
| [setHost(String value)](#setHost-java.lang.String-) | Gets or sets the host name. |
| [getDefaultPort()](#getDefaultPort--) | Gets default port for client |
| [getPort()](#getPort--) | Gets or sets the port. |
| [setPort(int value)](#setPort-int-) | Gets or sets the port. |
| [getSecurityOptions()](#getSecurityOptions--) | Security mode for a mail client |
| [setSecurityOptions(int value)](#setSecurityOptions-int-) | Security mode for a mail client |
| [getUseAuthentication()](#getUseAuthentication--) | Indicates whether authentication is used. |
| [setUseAuthentication(boolean value)](#setUseAuthentication-boolean-) | Indicates whether authentication is used. |
| [getConnectionCheckupPeriod()](#getConnectionCheckupPeriod--) | Period of connection checking up in milliseconds. |
| [setConnectionCheckupPeriod(int value)](#setConnectionCheckupPeriod-int-) | Period of connection checking up in milliseconds. |
| [getUseDefaultCredentials()](#getUseDefaultCredentials--) | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [setUseDefaultCredentials(boolean value)](#setUseDefaultCredentials-boolean-) | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [getProxy()](#getProxy--) | Gets or sets proxy for the client |
| [setProxy(Proxy value)](#setProxy-com.aspose.email.Proxy-) | Gets or sets proxy for the client |
| [getTimeout()](#getTimeout--) | Gets or sets the timeout for mail operations |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the timeout for mail operations |
| [getGreetingTimeout()](#getGreetingTimeout--) | Gets or sets the greeting timeout that is used when establishing a connection. |
| [setGreetingTimeout(int value)](#setGreetingTimeout-int-) | Gets or sets the greeting timeout that is used when establishing a connection. |
| [getPassword()](#getPassword--) | Gets or sets the password. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets the password. |
| [getAccessToken()](#getAccessToken--) | Gets or sets the access token. |
| [setAccessToken(String value)](#setAccessToken-java.lang.String-) | Gets or sets the access token. |
| [getTokenProvider()](#getTokenProvider--) | Gets or sets TokenProvider allowing to retrieve access token. |
| [setTokenProvider(ITokenProvider value)](#setTokenProvider-com.aspose.email.ITokenProvider-) | Gets or sets TokenProvider allowing to retrieve access token. |
| [getUsername()](#getUsername--) | Gets or sets the username. |
| [setUsername(String value)](#setUsername-java.lang.String-) | Gets or sets the username. |
| [getCapabilities()](#getCapabilities--) | Get Capabilities. |
| [getConnectionState()](#getConnectionState--) | Gets the current state of the connection. |
| [bindIPEndPoint(BindIPEndPointHandler handler)](#bindIPEndPoint-com.aspose.email.BindIPEndPointHandler-) | Associates a Socket with a local endpoint. |
| [connectIPEndPoint(BindIPEndPointHandler handler)](#connectIPEndPoint-com.aspose.email.BindIPEndPointHandler-) | Associates a Socket with a remote endpoint. |
| [cancelAsyncOperation(System.IAsyncResult asyncResult)](#cancelAsyncOperation-com.aspose.ms.System.IAsyncResult-) | Cancels asynchronous operation. |
| [noop()](#noop--) | 'No operation' command |
| [validateCredentials()](#validateCredentials--) | Checks if the credentials are valid |
| [noop(IConnection connection)](#noop-com.aspose.email.IConnection-) | 'No operation' command |
| [dispose()](#dispose--) | Finalizes all operations with a server. |
| [close()](#close--) |  |
| [createConnection()](#createConnection--) | Creates new independent connection for operations not linked to threads (not default connection). |
| [createConnection(boolean createAsDefaultConnection)](#createConnection-boolean-) | Creates new (default or independent) connection for operations. |
| [getCurrentConnection()](#getCurrentConnection--) | Gets current connection according to ConnectionAsgmtMode option |
| [getConnectionAsgmtMode()](#getConnectionAsgmtMode--) | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. |
| [setConnectionAsgmtMode(int value)](#setConnectionAsgmtMode-int-) | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. |
| [getUseMultiConnection()](#getUseMultiConnection--) | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. |
| [setUseMultiConnection(int value)](#setUseMultiConnection-int-) | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. |
| [getConnectionsQuantity()](#getConnectionsQuantity--) | Gets or sets quantity of connections in multy-connection mode |
| [setConnectionsQuantity(int value)](#setConnectionsQuantity-int-) | Gets or sets quantity of connections in multy-connection mode |
### setSocketsLayerVersion2(boolean value) {#setSocketsLayerVersion2-boolean-}
```
public static void setSocketsLayerVersion2(boolean value)
```


Sets value indicating whether Sockets Layer version 2 is used. By default, Sockets Layer version 2 is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | False if Sockets Layer version 1 should be used. |

### setSocketsLayerVersion2DisableSSLCertificateValidation(boolean value) {#setSocketsLayerVersion2DisableSSLCertificateValidation-boolean-}
```
public static void setSocketsLayerVersion2DisableSSLCertificateValidation(boolean value)
```


Disable SSL certificate validation for Sockets Layer version 2

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSocketsLayerVersion2SSLSocketFactory(SSLSocketFactory value) {#setSocketsLayerVersion2SSLSocketFactory-javax.net.ssl.SSLSocketFactory-}
```
public static void setSocketsLayerVersion2SSLSocketFactory(SSLSocketFactory value)
```


Set SSL Socket Factory for Sockets Layer version 2

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | javax.net.ssl.SSLSocketFactory |  |

### resetLogSettings() {#resetLogSettings--}
```
public final void resetLogSettings()
```


Resets logging settings to default.

### getEnableLogger() {#getEnableLogger--}
```
public final boolean getEnableLogger()
```


Gets or sets value which allows enable/disable logger

**Returns:**
boolean
### setEnableLogger(boolean value) {#setEnableLogger-boolean-}
```
public final void setEnableLogger(boolean value)
```


Gets or sets value which allows enable/disable logger

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogFileName() {#getLogFileName--}
```
public final String getLogFileName()
```


Gets or sets log file name

**Returns:**
java.lang.String
### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public final void setLogFileName(String value)
```


Gets or sets log file name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getUseDateInLogFileName() {#getUseDateInLogFileName--}
```
public final boolean getUseDateInLogFileName()
```


Gets or sets value which indicates if date has to be used in log file name.

**Returns:**
boolean
### setUseDateInLogFileName(boolean value) {#setUseDateInLogFileName-boolean-}
```
public final void setUseDateInLogFileName(boolean value)
```


Gets or sets value which indicates if date has to be used in log file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSupportedEncryptionUnsafe(int value) {#setSupportedEncryptionUnsafe-int-}
```
public final void setSupportedEncryptionUnsafe(int value)
```


Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use \`\`\` SupportedEncryption \`\`\`(\#getSupportedEncryption/\#setSupportedEncryption(int)) property to safely set only protocols that definitely supported by framework. Please note, if your current framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSupportedEncryption() {#getSupportedEncryption--}
```
public int getSupportedEncryption()
```


Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [EncryptionProtocols](../../com.aspose.email/encryptionprotocols) documentation for more details. Please use \#setSupportedEncryptionUnsafe(int) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls | Tls11 | Tls12 | Tls13 (in case if your current version of .net framework supports these versions of TLS)

**Returns:**
int
### setSupportedEncryption(int value) {#setSupportedEncryption-int-}
```
public void setSupportedEncryption(int value)
```


Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [EncryptionProtocols](../../com.aspose.email/encryptionprotocols) documentation for more details. Please use \#setSupportedEncryptionUnsafe(int) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls | Tls11 | Tls12 | Tls13 (in case if your current version of .net framework supports these versions of TLS)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getClientCertificates() {#getClientCertificates--}
```
public System.Security.Cryptography.X509Certificates.X509CertificateCollection getClientCertificates()
```


Contains collection of clients certificates

**Returns:**
com.aspose.ms.System.Security.Cryptography.X509Certificates.X509CertificateCollection
### getUsePipelining() {#getUsePipelining--}
```
public PipeliningStatus getUsePipelining()
```


Gets or sets object which indicates whether the pipelining mode is enabled.

**Returns:**
[PipeliningStatus](../../com.aspose.email/pipeliningstatus)
### setUsePipelining(PipeliningStatus value) {#setUsePipelining-com.aspose.email.PipeliningStatus-}
```
public void setUsePipelining(PipeliningStatus value)
```


Gets or sets object which indicates whether the pipelining mode is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PipeliningStatus](../../com.aspose.email/pipeliningstatus) |  |

### getHost() {#getHost--}
```
public String getHost()
```


Gets or sets the host name.

Value: The host name.

**Returns:**
java.lang.String
### setHost(String value) {#setHost-java.lang.String-}
```
public void setHost(String value)
```


Gets or sets the host name.

Value: The host name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultPort() {#getDefaultPort--}
```
public int getDefaultPort()
```


Gets default port for client

**Returns:**
int
### getPort() {#getPort--}
```
public int getPort()
```


Gets or sets the port.

Value: The port number.

**Returns:**
int
### setPort(int value) {#setPort-int-}
```
public void setPort(int value)
```


Gets or sets the port.

Value: The port number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSecurityOptions() {#getSecurityOptions--}
```
public int getSecurityOptions()
```


Security mode for a mail client

**Returns:**
int
### setSecurityOptions(int value) {#setSecurityOptions-int-}
```
public void setSecurityOptions(int value)
```


Security mode for a mail client

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUseAuthentication() {#getUseAuthentication--}
```
public boolean getUseAuthentication()
```


Indicates whether authentication is used.

**Returns:**
boolean
### setUseAuthentication(boolean value) {#setUseAuthentication-boolean-}
```
public void setUseAuthentication(boolean value)
```


Indicates whether authentication is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getConnectionCheckupPeriod() {#getConnectionCheckupPeriod--}
```
public int getConnectionCheckupPeriod()
```


Period of connection checking up in milliseconds. Default value is 5 min.

**Returns:**
int
### setConnectionCheckupPeriod(int value) {#setConnectionCheckupPeriod-int-}
```
public void setConnectionCheckupPeriod(int value)
```


Period of connection checking up in milliseconds. Default value is 5 min.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUseDefaultCredentials() {#getUseDefaultCredentials--}
```
public boolean getUseDefaultCredentials()
```


Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. This option is used with NTLM authentication ONLY!

**Returns:**
boolean
### setUseDefaultCredentials(boolean value) {#setUseDefaultCredentials-boolean-}
```
public void setUseDefaultCredentials(boolean value)
```


Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. This option is used with NTLM authentication ONLY!

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getProxy() {#getProxy--}
```
public Proxy getProxy()
```


Gets or sets proxy for the client

**Returns:**
[Proxy](../../com.aspose.email/proxy)
### setProxy(Proxy value) {#setProxy-com.aspose.email.Proxy-}
```
public void setProxy(Proxy value)
```


Gets or sets proxy for the client

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Proxy](../../com.aspose.email/proxy) |  |

### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Gets or sets the timeout for mail operations

Value: The timeout in milliseconds

**Returns:**
int
### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Gets or sets the timeout for mail operations

Value: The timeout in milliseconds

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGreetingTimeout() {#getGreetingTimeout--}
```
public final int getGreetingTimeout()
```


Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use \`\`\` EmailClient.Timeout \`\`\`(\#getTimeout/\#setTimeout(int)) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment.

Value: The greeting timeout in milliseconds

**Returns:**
int
### setGreetingTimeout(int value) {#setGreetingTimeout-int-}
```
public final void setGreetingTimeout(int value)
```


Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use \`\`\` EmailClient.Timeout \`\`\`(\#getTimeout/\#setTimeout(int)) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment.

Value: The greeting timeout in milliseconds

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public String getPassword()
```


Gets or sets the password. Password limitations are defined by server implementation, which client connects.

Value: The string that represents the password.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


Gets or sets the password. Password limitations are defined by server implementation, which client connects.

Value: The string that represents the password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessToken() {#getAccessToken--}
```
public String getAccessToken()
```


Gets or sets the access token.

Value: The string that represents access token.

**Returns:**
java.lang.String
### setAccessToken(String value) {#setAccessToken-java.lang.String-}
```
public void setAccessToken(String value)
```


Gets or sets the access token.

Value: The string that represents access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTokenProvider() {#getTokenProvider--}
```
public final ITokenProvider getTokenProvider()
```


Gets or sets TokenProvider allowing to retrieve access token.

**Returns:**
[ITokenProvider](../../com.aspose.email/itokenprovider)
### setTokenProvider(ITokenProvider value) {#setTokenProvider-com.aspose.email.ITokenProvider-}
```
public final void setTokenProvider(ITokenProvider value)
```


Gets or sets TokenProvider allowing to retrieve access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITokenProvider](../../com.aspose.email/itokenprovider) |  |

### getUsername() {#getUsername--}
```
public String getUsername()
```


Gets or sets the username.

Value: The username string.

**Returns:**
java.lang.String
### setUsername(String value) {#setUsername-java.lang.String-}
```
public void setUsername(String value)
```


Gets or sets the username.

Value: The username string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCapabilities() {#getCapabilities--}
```
public String[] getCapabilities()
```


Get Capabilities.

**Returns:**
java.lang.String[]
### getConnectionState() {#getConnectionState--}
```
public final int getConnectionState()
```


Gets the current state of the connection.

**Returns:**
int
### bindIPEndPoint(BindIPEndPointHandler handler) {#bindIPEndPoint-com.aspose.email.BindIPEndPointHandler-}
```
public void bindIPEndPoint(BindIPEndPointHandler handler)
```


Associates a Socket with a local endpoint.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| handler | [BindIPEndPointHandler](../../com.aspose.email/bindipendpointhandler) |  |

### connectIPEndPoint(BindIPEndPointHandler handler) {#connectIPEndPoint-com.aspose.email.BindIPEndPointHandler-}
```
public void connectIPEndPoint(BindIPEndPointHandler handler)
```


Associates a Socket with a remote endpoint.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| handler | [BindIPEndPointHandler](../../com.aspose.email/bindipendpointhandler) |  |

### cancelAsyncOperation(System.IAsyncResult asyncResult) {#cancelAsyncOperation-com.aspose.ms.System.IAsyncResult-}
```
public final void cancelAsyncOperation(System.IAsyncResult asyncResult)
```


Cancels asynchronous operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | Defines asynchronous operation to cancel. |

### noop() {#noop--}
```
public abstract void noop()
```


'No operation' command

### validateCredentials() {#validateCredentials--}
```
public abstract boolean validateCredentials()
```


Checks if the credentials are valid

**Returns:**
boolean - True if authentication was successful, otherwise false.
### noop(IConnection connection) {#noop-com.aspose.email.IConnection-}
```
public abstract void noop(IConnection connection)
```


'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

### dispose() {#dispose--}
```
public void dispose()
```


Finalizes all operations with a server.

### close() {#close--}
```
public void close()
```




### createConnection() {#createConnection--}
```
public IConnection createConnection()
```


Creates new independent connection for operations not linked to threads (not default connection). Invocation of this method is similar to invocation of CreateConnection(createAsDefaultConnection = false) Please see more in documentation for EmailClient.ConnectionAsgmtMode property.

**Returns:**
[IConnection](../../com.aspose.email/iconnection) - Returns connection object
### createConnection(boolean createAsDefaultConnection) {#createConnection-boolean-}
```
public IConnection createConnection(boolean createAsDefaultConnection)
```


Creates new (default or independent) connection for operations. Please see more in documentation for EmailClient.ConnectionAsgmtMode property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createAsDefaultConnection | boolean | Indicates if connection has to be created as default for current thread |

**Returns:**
[IConnection](../../com.aspose.email/iconnection) - Returns connection object
### getCurrentConnection() {#getCurrentConnection--}
```
public IConnection getCurrentConnection()
```


Gets current connection according to ConnectionAsgmtMode option

**Returns:**
[IConnection](../../com.aspose.email/iconnection)
### getConnectionAsgmtMode() {#getConnectionAsgmtMode--}
```
public int getConnectionAsgmtMode()
```


Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread.

**Returns:**
int
### setConnectionAsgmtMode(int value) {#setConnectionAsgmtMode-int-}
```
public void setConnectionAsgmtMode(int value)
```


Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUseMultiConnection() {#getUseMultiConnection--}
```
public int getUseMultiConnection()
```


Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing.

**Returns:**
int
### setUseMultiConnection(int value) {#setUseMultiConnection-int-}
```
public void setUseMultiConnection(int value)
```


Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getConnectionsQuantity() {#getConnectionsQuantity--}
```
public int getConnectionsQuantity()
```


Gets or sets quantity of connections in multy-connection mode

**Returns:**
int
### setConnectionsQuantity(int value) {#setConnectionsQuantity-int-}
```
public void setConnectionsQuantity(int value)
```


Gets or sets quantity of connections in multy-connection mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

