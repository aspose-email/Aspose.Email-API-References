---
title: SmtpClient
second_title: Aspose.Email for Java API Reference
description: Allows applications to send messages by using the Simple Mail Transfer Protocol SMTP.
type: docs
weight: 658
url: /java/com.aspose.email/smtpclient/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.EmailClient](../../com.aspose.email/emailclient)

**All Implemented Interfaces:**
[com.aspose.email.IMailTransferAgent](../../com.aspose.email/imailtransferagent)
```
public final class SmtpClient extends EmailClient implements IMailTransferAgent
```

Allows applications to send messages by using the Simple Mail Transfer Protocol (SMTP).
## Constructors

| Constructor | Description |
| --- | --- |
| [SmtpClient()](#SmtpClient--) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host)](#SmtpClient-java.lang.String-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, short securityOptions)](#SmtpClient-java.lang.String-short-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, int port)](#SmtpClient-java.lang.String-int-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, int port, int securityOptions)](#SmtpClient-java.lang.String-int-int-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, String username, String password)](#SmtpClient-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, String username, String password, int securityOptions)](#SmtpClient-java.lang.String-java.lang.String-java.lang.String-int-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, int port, String username, String password)](#SmtpClient-java.lang.String-int-java.lang.String-java.lang.String-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, int port, String username, String password, int securityOptions)](#SmtpClient-java.lang.String-int-java.lang.String-java.lang.String-int-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, String username, String authInfo, boolean useOAuth)](#SmtpClient-java.lang.String-java.lang.String-java.lang.String-boolean-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, String username, String authInfo, boolean useOAuth, int securityOptions)](#SmtpClient-java.lang.String-java.lang.String-java.lang.String-boolean-int-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, int port, String username, String authInfo, boolean useOAuth)](#SmtpClient-java.lang.String-int-java.lang.String-java.lang.String-boolean-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, int port, String username, String authInfo, boolean useOAuth, int securityOptions)](#SmtpClient-java.lang.String-int-java.lang.String-java.lang.String-boolean-int-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, String username, ITokenProvider tokenProvider)](#SmtpClient-java.lang.String-java.lang.String-com.aspose.email.ITokenProvider-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, String username, ITokenProvider tokenProvider, int securityOptions)](#SmtpClient-java.lang.String-java.lang.String-com.aspose.email.ITokenProvider-int-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, int port, String username, ITokenProvider tokenProvider)](#SmtpClient-java.lang.String-int-java.lang.String-com.aspose.email.ITokenProvider-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
| [SmtpClient(String host, int port, String username, ITokenProvider tokenProvider, int securityOptions)](#SmtpClient-java.lang.String-int-java.lang.String-com.aspose.email.ITokenProvider-int-) | Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class. |
## Methods

| Method | Description |
| --- | --- |
| [beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message)](#beginForward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-) | Begins forward email asynchronously. |
| [beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback)](#beginForward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins forward email asynchronously. |
| [beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback, Object state)](#beginForward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins forward email asynchronously. |
| [beginForward(IConnection connection, String sender, String recipient, MailMessage message)](#beginForward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-) | Begins forward email asynchronously. |
| [beginForward(IConnection connection, String sender, String recipient, MailMessage message, System.AsyncCallback callback)](#beginForward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins forward email asynchronously. |
| [beginForward(IConnection connection, String sender, String recipient, MailMessage message, System.AsyncCallback callback, Object state)](#beginForward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins forward email asynchronously. |
| [beginForward(String sender, MailAddressCollection recipients, MailMessage message)](#beginForward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-) | Begins forward email asynchronously. |
| [beginForward(String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback)](#beginForward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins forward email asynchronously. |
| [beginForward(String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback, Object state)](#beginForward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins forward email asynchronously. |
| [beginForward(String sender, String recipient, MailMessage message)](#beginForward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-) | Begins forward email asynchronously. |
| [beginForward(String sender, String recipient, MailMessage message, System.AsyncCallback callback)](#beginForward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins forward email asynchronously. |
| [beginForward(String sender, String recipient, MailMessage message, System.AsyncCallback callback, Object state)](#beginForward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins forward email asynchronously. |
| [beginNoop()](#beginNoop--) | Begins to execute 'No operation' command |
| [beginNoop(IConnection connection)](#beginNoop-com.aspose.email.IConnection-) | Begins to execute 'No operation' command |
| [beginNoop(IConnection connection, System.AsyncCallback callback)](#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins to execute 'No operation' command |
| [beginNoop(IConnection connection, System.AsyncCallback callback, Object state)](#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute 'No operation' command |
| [beginNoop(System.AsyncCallback callback)](#beginNoop-com.aspose.ms.System.AsyncCallback-) | Begins to execute 'No operation' command |
| [beginNoop(System.AsyncCallback callback, Object state)](#beginNoop-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute 'No operation' command |
| [beginSend(IConnection connection, MailMessage message)](#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, MailMessage message, System.AsyncCallback callback)](#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, MailMessage message, System.AsyncCallback callback, Object state)](#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, MailMessage[] messages)](#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage...-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages, System.AsyncCallback callback)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages, System.AsyncCallback callback, Object state)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback, Object state)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, String from, String recipients, String subject, String body)](#beginSend-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, String from, String recipients, String subject, String body, System.AsyncCallback callback)](#beginSend-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, String from, String recipients, String subject, String body, System.AsyncCallback callback, Object state)](#beginSend-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(MailMessage message)](#beginSend-com.aspose.email.MailMessage-) | Begins sending email asynchronously. |
| [beginSend(MailMessage message, System.AsyncCallback callback)](#beginSend-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(MailMessage message, System.AsyncCallback callback, Object state)](#beginSend-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(MailMessage[] messages)](#beginSend-com.aspose.email.MailMessage...-) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages, System.AsyncCallback callback)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages, System.AsyncCallback callback, Object state)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback, Object state)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(String from, String recipients, String subject, String body)](#beginSend-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Begins sending email asynchronously. |
| [beginSend(String from, String recipients, String subject, String body, System.AsyncCallback callback)](#beginSend-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(String from, String recipients, String subject, String body, System.AsyncCallback callback, Object state)](#beginSend-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSendQueue()](#beginSendQueue--) | Begins to execute 'No operation' command |
| [beginSendQueue(System.AsyncCallback callback)](#beginSendQueue-com.aspose.ms.System.AsyncCallback-) | Begins to execute 'No operation' command |
| [beginSendQueue(System.AsyncCallback callback, Object state)](#beginSendQueue-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute 'No operation' command |
| [beginValidateCredentials()](#beginValidateCredentials--) | Begins to execute credentials validation |
| [beginValidateCredentials(IConnection connection)](#beginValidateCredentials-com.aspose.email.IConnection-) | Begins to execute credentials validation |
| [beginValidateCredentials(IConnection connection, System.AsyncCallback callback)](#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins to execute credentials validation |
| [beginValidateCredentials(IConnection connection, System.AsyncCallback callback, Object state)](#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute credentials validation |
| [beginValidateCredentials(System.AsyncCallback callback)](#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-) | Begins to execute credentials validation |
| [beginValidateCredentials(System.AsyncCallback callback, Object state)](#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute credentials validation |
| [bindIPEndPoint(BindIPEndPointHandler handler)](#bindIPEndPoint-com.aspose.email.BindIPEndPointHandler-) | Associates a Socket with a local endpoint. |
| [cancelAsyncOperation(System.IAsyncResult asyncResult)](#cancelAsyncOperation-com.aspose.ms.System.IAsyncResult-) | Cancels asynchronous operation. |
| [close()](#close--) |  |
| [connectIPEndPoint(BindIPEndPointHandler handler)](#connectIPEndPoint-com.aspose.email.BindIPEndPointHandler-) | Associates a Socket with a remote endpoint. |
| [createConnection()](#createConnection--) | Creates new independent connection for operations not linked to threads (not default connection). |
| [createConnection(boolean createAsDefaultConnection)](#createConnection-boolean-) | Creates new (default or independent) connection for operations. |
| [dispose()](#dispose--) | Finalizes all operations with a server. |
| [endBeginSendQueue(System.IAsyncResult asyncResult)](#endBeginSendQueue-com.aspose.ms.System.IAsyncResult-) | Waits for the pending asynchronous operation to complete. |
| [endForward(System.IAsyncResult asyncResult)](#endForward-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endNoop(System.IAsyncResult asyncResult)](#endNoop-com.aspose.ms.System.IAsyncResult-) | Waits for the pending asynchronous operation to complete. |
| [endSend(System.IAsyncResult asyncResult)](#endSend-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endValidateCredentials(System.IAsyncResult asyncResult)](#endValidateCredentials-com.aspose.ms.System.IAsyncResult-) | Waits for the pending asynchronous operation to complete. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [forward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message)](#forward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-) | Forwards specified message to recipient |
| [forward(IConnection connection, String sender, MailAddressCollection recipients, InputStream messageStream)](#forward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-java.io.InputStream-) | Forwards specified message to recipient |
| [forward(IConnection connection, String sender, String recipient, MailMessage message)](#forward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-) | Forwards specified message to recipient |
| [forward(String sender, MailAddressCollection recipients, MailMessage message)](#forward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-) | Forwards specified message to recipient |
| [forward(String sender, MailAddressCollection recipients, InputStream messageStream)](#forward-java.lang.String-com.aspose.email.MailAddressCollection-java.io.InputStream-) | Forwards specified message to recipient |
| [forward(String sender, String recipient, MailMessage message)](#forward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-) | Forwards specified message to recipient |
| [getAccessToken()](#getAccessToken--) | Gets or sets the access token. |
| [getAllowedAuthentication()](#getAllowedAuthentication--) | Gets or sets enumeration of allowed by user authentication types |
| [getCapabilities()](#getCapabilities--) | Get Capabilities. |
| [getClass()](#getClass--) |  |
| [getClientCertificates()](#getClientCertificates--) | Contains collection of clients certificates |
| [getConnectionAsgmtMode()](#getConnectionAsgmtMode--) | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. |
| [getConnectionCheckupPeriod()](#getConnectionCheckupPeriod--) | Period of connection checking up in milliseconds. |
| [getConnectionState()](#getConnectionState--) | Gets the current state of the connection. |
| [getConnectionsQuantity()](#getConnectionsQuantity--) | Gets or sets quantity of connections in multy-connection mode |
| [getCurrentConnection()](#getCurrentConnection--) | Gets current connection according to ConnectionAsgmtMode option |
| [getDefaultPort()](#getDefaultPort--) | Gets default port for client |
| [getDeliveryMethod()](#getDeliveryMethod--) | Gets or sets the delivery method. |
| [getEnableLogger()](#getEnableLogger--) | Gets or sets value which allows enable/disable logger |
| [getGreetingTimeout()](#getGreetingTimeout--) | Gets or sets the greeting timeout that is used when establishing a connection. |
| [getHelloMessage()](#getHelloMessage--) | Gets or sets a HELO/EHLO string. |
| [getHost()](#getHost--) | Gets or sets the host name. |
| [getLogFileName()](#getLogFileName--) | Gets or sets log file name |
| [getPassword()](#getPassword--) | Gets or sets the password. |
| [getPickupDirectoryLocation()](#getPickupDirectoryLocation--) | Gets or sets the directory where applications save mail messages to be processed by the local SMTP server. |
| [getPort()](#getPort--) | Gets or sets the port. |
| [getProxy()](#getProxy--) | Gets or sets proxy for the client |
| [getSecurityOptions()](#getSecurityOptions--) | Security mode for a mail client |
| [getSmtpQueueLocation()](#getSmtpQueueLocation--) | Gets or sets the directory where applications save mail messages to be processed by sending in SMTP queue. |
| [getSupportedAuthentication()](#getSupportedAuthentication--) | Gets enumeration of supported by server authentication types |
| [getSupportedEncryption()](#getSupportedEncryption--) | Defines the versions of SSL/TLS encryption protocols to be used. |
| [getTimeout()](#getTimeout--) | Gets or sets the timeout for mail operations |
| [getTokenProvider()](#getTokenProvider--) | Gets or sets TokenProvider allowing to retrieve access token. |
| [getUseAuthentication()](#getUseAuthentication--) | Indicates whether authentication is used. |
| [getUseDateInLogFileName()](#getUseDateInLogFileName--) | Gets or sets value which indicates if date has to be used in log file name. |
| [getUseDefaultCredentials()](#getUseDefaultCredentials--) | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [getUseMultiConnection()](#getUseMultiConnection--) | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. |
| [getUsePipelining()](#getUsePipelining--) | Gets or sets object which indicates whether the pipelining mode is enabled. |
| [getUseTnef()](#getUseTnef--) | Gets or sets a boolean value that controls whether the messages are sent in TNEF format. |
| [getUsername()](#getUsername--) | Gets or sets the username. |
| [hashCode()](#hashCode--) |  |
| [noop()](#noop--) | 'No operation' command |
| [noop(IConnection connection)](#noop-com.aspose.email.IConnection-) | 'No operation' command |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetLogSettings()](#resetLogSettings--) | Resets logging settings to default. |
| [send(IConnection connection, MailMessage message)](#send-com.aspose.email.IConnection-com.aspose.email.MailMessage-) | Send the specified message. |
| [send(IConnection connection, MailMessage[] messages)](#send-com.aspose.email.IConnection-com.aspose.email.MailMessage...-) | Send the specified message. |
| [send(IConnection connection, MailMessageCollection messages)](#send-com.aspose.email.IConnection-com.aspose.email.MailMessageCollection-) | Send the specified message collection. |
| [send(IConnection connection, Iterable<MailMessage> messages)](#send-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--) | Send the specified messages. |
| [send(IConnection connection, String from, String recipients, String subject, String body)](#send-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Creates and sends the specified message. |
| [send(MailMessage message)](#send-com.aspose.email.MailMessage-) | Send the specified message. |
| [send(MailMessage[] messages)](#send-com.aspose.email.MailMessage...-) | Send the specified message. |
| [send(MailMessageCollection messages)](#send-com.aspose.email.MailMessageCollection-) | Send the specified message collection. |
| [send(Iterable<MailMessage> messages)](#send-java.lang.Iterable-com.aspose.email.MailMessage--) | Send the specified messages. |
| [send(String from, String recipients, String subject, String body)](#send-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Creates and sends the specified message. |
| [sendToQueue(Iterable<MailMessage> messages)](#sendToQueue-java.lang.Iterable-com.aspose.email.MailMessage--) | Append messages to queue |
| [setAccessToken(String value)](#setAccessToken-java.lang.String-) | Gets or sets the access token. |
| [setAllowedAuthentication(long value)](#setAllowedAuthentication-long-) | Gets or sets enumeration of allowed by user authentication types |
| [setConnectionAsgmtMode(int value)](#setConnectionAsgmtMode-int-) | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. |
| [setConnectionCheckupPeriod(int value)](#setConnectionCheckupPeriod-int-) | Period of connection checking up in milliseconds. |
| [setConnectionsQuantity(int value)](#setConnectionsQuantity-int-) | Gets or sets quantity of connections in multy-connection mode |
| [setDeliveryMethod(int value)](#setDeliveryMethod-int-) | Gets or sets the delivery method. |
| [setEnableLogger(boolean value)](#setEnableLogger-boolean-) | Gets or sets value which allows enable/disable logger |
| [setFailedSending(System.EventHandler<FailedMailMessageEventArgs> handler)](#setFailedSending-com.aspose.ms.System.EventHandler-com.aspose.email.FailedMailMessageEventArgs--) | Adds or removes subscriber for notifications about failed sending operations in smtp queue |
| [setGreetingTimeout(int value)](#setGreetingTimeout-int-) | Gets or sets the greeting timeout that is used when establishing a connection. |
| [setHelloMessage(String value)](#setHelloMessage-java.lang.String-) | Gets or sets a HELO/EHLO string. |
| [setHost(String value)](#setHost-java.lang.String-) | Gets or sets the host name. |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Gets or sets log file name |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets the password. |
| [setPickupDirectoryLocation(String value)](#setPickupDirectoryLocation-java.lang.String-) | Gets or sets the directory where applications save mail messages to be processed by the local SMTP server. |
| [setPort(int value)](#setPort-int-) | Gets or sets the port. |
| [setProxy(Proxy value)](#setProxy-com.aspose.email.Proxy-) | Gets or sets proxy for the client |
| [setSecurityOptions(int value)](#setSecurityOptions-int-) | Security mode for a mail client |
| [setShowCredentialsInLog(boolean value)](#setShowCredentialsInLog-boolean-) | Sets value indicating whether Credentials should be displayed in the log. |
| [setSmtpQueueLocation(String value)](#setSmtpQueueLocation-java.lang.String-) | Gets or sets the directory where applications save mail messages to be processed by sending in SMTP queue. |
| [setSocketsLayerVersion2(boolean value)](#setSocketsLayerVersion2-boolean-) | Sets value indicating whether Sockets Layer version 2 is used. |
| [setSocketsLayerVersion2DisableSSLCertificateValidation(boolean value)](#setSocketsLayerVersion2DisableSSLCertificateValidation-boolean-) | Disable SSL certificate validation for Sockets Layer version 2 |
| [setSocketsLayerVersion2SSLSocketFactory(SSLSocketFactory value)](#setSocketsLayerVersion2SSLSocketFactory-javax.net.ssl.SSLSocketFactory-) | Set SSL Socket Factory for Sockets Layer version 2 |
| [setSucceededSending(System.EventHandler<MailMessageEventArgs> handler)](#setSucceededSending-com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--) | Adds or removes subscriber for notifications about succeeded sending of mail messages. |
| [setSupportedEncryption(int value)](#setSupportedEncryption-int-) | Defines the versions of SSL/TLS encryption protocols to be used. |
| [setSupportedEncryptionUnsafe(int value)](#setSupportedEncryptionUnsafe-int-) | Defines the versions of SSL/TLS encryption protocols to be used. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the timeout for mail operations |
| [setTokenProvider(ITokenProvider value)](#setTokenProvider-com.aspose.email.ITokenProvider-) | Gets or sets TokenProvider allowing to retrieve access token. |
| [setUseAuthentication(boolean value)](#setUseAuthentication-boolean-) | Indicates whether authentication is used. |
| [setUseDateInLogFileName(boolean value)](#setUseDateInLogFileName-boolean-) | Gets or sets value which indicates if date has to be used in log file name. |
| [setUseDefaultCredentials(boolean value)](#setUseDefaultCredentials-boolean-) | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [setUseMultiConnection(int value)](#setUseMultiConnection-int-) | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. |
| [setUsePipelining(PipeliningStatus value)](#setUsePipelining-com.aspose.email.PipeliningStatus-) | Gets or sets object which indicates whether the pipelining mode is enabled. |
| [setUseTnef(boolean value)](#setUseTnef-boolean-) | Gets or sets a boolean value that controls whether the messages are sent in TNEF format. |
| [setUsername(String value)](#setUsername-java.lang.String-) | Gets or sets the username. |
| [toString()](#toString--) |  |
| [usePasswordQuotes(boolean value)](#usePasswordQuotes-boolean-) | Sets a value indicating whether Quotes should be used in login password syntax with special characters. |
| [validateCredentials()](#validateCredentials--) | Executes credentials validation |
| [validateCredentials(IConnection connection)](#validateCredentials-com.aspose.email.IConnection-) | Executes credentials validation |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmtpClient() {#SmtpClient--}
```
public SmtpClient()
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

### SmtpClient(String host) {#SmtpClient-java.lang.String-}
```
public SmtpClient(String host)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |

### SmtpClient(String host, short securityOptions) {#SmtpClient-java.lang.String-short-}
```
public SmtpClient(String host, short securityOptions)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| securityOptions | short | Security mode for a mail client |

### SmtpClient(String host, int port) {#SmtpClient-java.lang.String-int-}
```
public SmtpClient(String host, int port)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| port | int | The port used for SMTP. |

### SmtpClient(String host, int port, int securityOptions) {#SmtpClient-java.lang.String-int-int-}
```
public SmtpClient(String host, int port, int securityOptions)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| port | int | The port used for SMTP. |
| securityOptions | int | Security mode for a mail client |

### SmtpClient(String host, String username, String password) {#SmtpClient-java.lang.String-java.lang.String-java.lang.String-}
```
public SmtpClient(String host, String username, String password)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| username | java.lang.String | The username. |
| password | java.lang.String | The password. |

### SmtpClient(String host, String username, String password, int securityOptions) {#SmtpClient-java.lang.String-java.lang.String-java.lang.String-int-}
```
public SmtpClient(String host, String username, String password, int securityOptions)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| username | java.lang.String | The username. |
| password | java.lang.String | The password. |
| securityOptions | int | Security mode for a mail client |

### SmtpClient(String host, int port, String username, String password) {#SmtpClient-java.lang.String-int-java.lang.String-java.lang.String-}
```
public SmtpClient(String host, int port, String username, String password)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| port | int | The port used for SMTP. |
| username | java.lang.String | The username. |
| password | java.lang.String | The password. |

### SmtpClient(String host, int port, String username, String password, int securityOptions) {#SmtpClient-java.lang.String-int-java.lang.String-java.lang.String-int-}
```
public SmtpClient(String host, int port, String username, String password, int securityOptions)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| port | int | The port used for SMTP. |
| username | java.lang.String | The username. |
| password | java.lang.String | The password. |
| securityOptions | int | Security mode for a mail client |

### SmtpClient(String host, String username, String authInfo, boolean useOAuth) {#SmtpClient-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public SmtpClient(String host, String username, String authInfo, boolean useOAuth)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| username | java.lang.String | The username. |
| authInfo | java.lang.String | The user password or XOAUTH2 access token |
| useOAuth | boolean | Defines whether SASL XOAUTH2 mechanism is used to login to the server |

### SmtpClient(String host, String username, String authInfo, boolean useOAuth, int securityOptions) {#SmtpClient-java.lang.String-java.lang.String-java.lang.String-boolean-int-}
```
public SmtpClient(String host, String username, String authInfo, boolean useOAuth, int securityOptions)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| username | java.lang.String | The username. |
| authInfo | java.lang.String | The user password or XOAUTH2 access token |
| useOAuth | boolean | Defines whether SASL XOAUTH2 mechanism is used to login to the server |
| securityOptions | int | Security mode for a mail client |

### SmtpClient(String host, int port, String username, String authInfo, boolean useOAuth) {#SmtpClient-java.lang.String-int-java.lang.String-java.lang.String-boolean-}
```
public SmtpClient(String host, int port, String username, String authInfo, boolean useOAuth)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| port | int | The port used for SMTP. |
| username | java.lang.String | The username. |
| authInfo | java.lang.String | The user password or XOAUTH2 access token |
| useOAuth | boolean | Defines whether SASL XOAUTH2 mechanism is used to login to the server |

### SmtpClient(String host, int port, String username, String authInfo, boolean useOAuth, int securityOptions) {#SmtpClient-java.lang.String-int-java.lang.String-java.lang.String-boolean-int-}
```
public SmtpClient(String host, int port, String username, String authInfo, boolean useOAuth, int securityOptions)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| port | int | The port used for SMTP. |
| username | java.lang.String | The username. |
| authInfo | java.lang.String | The user password or XOAUTH2 access token |
| useOAuth | boolean | Defines whether SASL XOAUTH2 mechanism is used to login to the server |
| securityOptions | int | Security mode for a mail client |

### SmtpClient(String host, String username, ITokenProvider tokenProvider) {#SmtpClient-java.lang.String-java.lang.String-com.aspose.email.ITokenProvider-}
```
public SmtpClient(String host, String username, ITokenProvider tokenProvider)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| username | java.lang.String | The username. |
| tokenProvider | [ITokenProvider](../../com.aspose.email/itokenprovider) | TokenProvider allowing to retrieve access token. |

### SmtpClient(String host, String username, ITokenProvider tokenProvider, int securityOptions) {#SmtpClient-java.lang.String-java.lang.String-com.aspose.email.ITokenProvider-int-}
```
public SmtpClient(String host, String username, ITokenProvider tokenProvider, int securityOptions)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| username | java.lang.String | The username. |
| tokenProvider | [ITokenProvider](../../com.aspose.email/itokenprovider) | TokenProvider allowing to retrieve access token. |
| securityOptions | int | Security mode for a mail client |

### SmtpClient(String host, int port, String username, ITokenProvider tokenProvider) {#SmtpClient-java.lang.String-int-java.lang.String-com.aspose.email.ITokenProvider-}
```
public SmtpClient(String host, int port, String username, ITokenProvider tokenProvider)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| port | int | The port used for SMTP. |
| username | java.lang.String | The username. |
| tokenProvider | [ITokenProvider](../../com.aspose.email/itokenprovider) | TokenProvider allowing to retrieve access token. |

### SmtpClient(String host, int port, String username, ITokenProvider tokenProvider, int securityOptions) {#SmtpClient-java.lang.String-int-java.lang.String-com.aspose.email.ITokenProvider-int-}
```
public SmtpClient(String host, int port, String username, ITokenProvider tokenProvider, int securityOptions)
```


Initializes a new instance of the [SmtpClient](../../com.aspose.email/smtpclient) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The name of the host used for SMTP. |
| port | int | The port used for SMTP. |
| username | java.lang.String | The username. |
| tokenProvider | [ITokenProvider](../../com.aspose.email/itokenprovider) | TokenProvider allowing to retrieve access token. |
| securityOptions | int | Security mode for a mail client |

### beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message) {#beginForward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-}
```
public final System.IAsyncResult beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sender | java.lang.String | Sender of the forwarded message. |
| recipients | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback) {#beginForward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sender | java.lang.String | Sender of the forwarded message. |
| recipients | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback, Object state) {#beginForward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback, Object state)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sender | java.lang.String | Sender of the forwarded message. |
| recipients | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(IConnection connection, String sender, String recipient, MailMessage message) {#beginForward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-}
```
public final System.IAsyncResult beginForward(IConnection connection, String sender, String recipient, MailMessage message)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sender | java.lang.String | Sender of the forwarded message. |
| recipient | java.lang.String | Recipient of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(IConnection connection, String sender, String recipient, MailMessage message, System.AsyncCallback callback) {#beginForward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginForward(IConnection connection, String sender, String recipient, MailMessage message, System.AsyncCallback callback)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sender | java.lang.String | Sender of the forwarded message. |
| recipient | java.lang.String | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(IConnection connection, String sender, String recipient, MailMessage message, System.AsyncCallback callback, Object state) {#beginForward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginForward(IConnection connection, String sender, String recipient, MailMessage message, System.AsyncCallback callback, Object state)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sender | java.lang.String | Sender of the forwarded message. |
| recipient | java.lang.String | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(String sender, MailAddressCollection recipients, MailMessage message) {#beginForward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-}
```
public final System.IAsyncResult beginForward(String sender, MailAddressCollection recipients, MailMessage message)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.String | Sender of the forwarded message. |
| recipients | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback) {#beginForward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginForward(String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.String | Sender of the forwarded message. |
| recipients | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback, Object state) {#beginForward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginForward(String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback, Object state)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.String | Sender of the forwarded message. |
| recipients | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(String sender, String recipient, MailMessage message) {#beginForward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-}
```
public final System.IAsyncResult beginForward(String sender, String recipient, MailMessage message)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.String | Sender of the forwarded message. |
| recipient | java.lang.String | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(String sender, String recipient, MailMessage message, System.AsyncCallback callback) {#beginForward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginForward(String sender, String recipient, MailMessage message, System.AsyncCallback callback)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.String | Sender of the forwarded message. |
| recipient | java.lang.String | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginForward(String sender, String recipient, MailMessage message, System.AsyncCallback callback, Object state) {#beginForward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginForward(String sender, String recipient, MailMessage message, System.AsyncCallback callback, Object state)
```


Begins forward email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.String | Sender of the forwarded message. |
| recipient | java.lang.String | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop() {#beginNoop--}
```
public final System.IAsyncResult beginNoop()
```


Begins to execute 'No operation' command

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop(IConnection connection) {#beginNoop-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginNoop(IConnection connection)
```


Begins to execute 'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop(IConnection connection, System.AsyncCallback callback) {#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginNoop(IConnection connection, System.AsyncCallback callback)
```


Begins to execute 'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop(IConnection connection, System.AsyncCallback callback, Object state) {#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginNoop(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins to execute 'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop(System.AsyncCallback callback) {#beginNoop-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginNoop(System.AsyncCallback callback)
```


Begins to execute 'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop(System.AsyncCallback callback, Object state) {#beginNoop-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginNoop(System.AsyncCallback callback, Object state)
```


Begins to execute 'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, MailMessage message) {#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage-}
```
public final System.IAsyncResult beginSend(IConnection connection, MailMessage message)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Represents an e-mail message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, MailMessage message, System.AsyncCallback callback) {#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSend(IConnection connection, MailMessage message, System.AsyncCallback callback)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Represents an e-mail message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, MailMessage message, System.AsyncCallback callback, Object state) {#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSend(IConnection connection, MailMessage message, System.AsyncCallback callback, Object state)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Represents an e-mail message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, MailMessage[] messages) {#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage...-}
```
public final System.IAsyncResult beginSend(IConnection connection, MailMessage[] messages)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messages | [MailMessage\[\]](../../com.aspose.email/mailmessage) | The array of MailMessage that represents an email-messages to send. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, Iterable<MailMessage> messages) {#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--}
```
public final System.IAsyncResult beginSend(IConnection connection, Iterable<MailMessage> messages)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, Iterable<MailMessage> messages, System.AsyncCallback callback) {#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSend(IConnection connection, Iterable<MailMessage> messages, System.AsyncCallback callback)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, Iterable<MailMessage> messages, System.AsyncCallback callback, Object state) {#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSend(IConnection connection, Iterable<MailMessage> messages, System.AsyncCallback callback, Object state)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate) {#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--}
```
public final System.IAsyncResult beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | com.aspose.ms.System.EventHandler<com.aspose.email.MailMessageEventArgs> | References a method to be called when a message has been sent. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback) {#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | com.aspose.ms.System.EventHandler<com.aspose.email.MailMessageEventArgs> | References a method to be called when a message has been sent. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback, Object state) {#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback, Object state)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | com.aspose.ms.System.EventHandler<com.aspose.email.MailMessageEventArgs> | References a method to be called when a message has been sent. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, String from, String recipients, String subject, String body) {#beginSend-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public final System.IAsyncResult beginSend(IConnection connection, String from, String recipients, String subject, String body)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| from | java.lang.String | A String that contains the address of message sender. |
| recipients | java.lang.String | A String that contains the address of recipients. |
| subject | java.lang.String | A subject of message. |
| body | java.lang.String | A body of message. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, String from, String recipients, String subject, String body, System.AsyncCallback callback) {#beginSend-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSend(IConnection connection, String from, String recipients, String subject, String body, System.AsyncCallback callback)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| from | java.lang.String | A String that contains the address of message sender. |
| recipients | java.lang.String | A String that contains the address of recipients. |
| subject | java.lang.String | A subject of message. |
| body | java.lang.String | A body of message. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(IConnection connection, String from, String recipients, String subject, String body, System.AsyncCallback callback, Object state) {#beginSend-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSend(IConnection connection, String from, String recipients, String subject, String body, System.AsyncCallback callback, Object state)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| from | java.lang.String | A String that contains the address of message sender. |
| recipients | java.lang.String | A String that contains the address of recipients. |
| subject | java.lang.String | A subject of message. |
| body | java.lang.String | A body of message. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(MailMessage message) {#beginSend-com.aspose.email.MailMessage-}
```
public final System.IAsyncResult beginSend(MailMessage message)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Represents an e-mail message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(MailMessage message, System.AsyncCallback callback) {#beginSend-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSend(MailMessage message, System.AsyncCallback callback)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Represents an e-mail message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(MailMessage message, System.AsyncCallback callback, Object state) {#beginSend-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSend(MailMessage message, System.AsyncCallback callback, Object state)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Represents an e-mail message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(MailMessage[] messages) {#beginSend-com.aspose.email.MailMessage...-}
```
public final System.IAsyncResult beginSend(MailMessage[] messages)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | [MailMessage\[\]](../../com.aspose.email/mailmessage) | The array of MailMessage that represents an email-messages to send. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(Iterable<MailMessage> messages) {#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--}
```
public final System.IAsyncResult beginSend(Iterable<MailMessage> messages)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(Iterable<MailMessage> messages, System.AsyncCallback callback) {#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSend(Iterable<MailMessage> messages, System.AsyncCallback callback)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(Iterable<MailMessage> messages, System.AsyncCallback callback, Object state) {#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSend(Iterable<MailMessage> messages, System.AsyncCallback callback, Object state)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate) {#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--}
```
public final System.IAsyncResult beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | com.aspose.ms.System.EventHandler<com.aspose.email.MailMessageEventArgs> | References a method to be called when a message has been sent. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback) {#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | com.aspose.ms.System.EventHandler<com.aspose.email.MailMessageEventArgs> | References a method to be called when a message has been sent. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback, Object state) {#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback, Object state)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | com.aspose.ms.System.EventHandler<com.aspose.email.MailMessageEventArgs> | References a method to be called when a message has been sent. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(String from, String recipients, String subject, String body) {#beginSend-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public final System.IAsyncResult beginSend(String from, String recipients, String subject, String body)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | A String that contains the address of message sender. |
| recipients | java.lang.String | A String that contains the address of recipients. |
| subject | java.lang.String | A subject of message. |
| body | java.lang.String | A body of message. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(String from, String recipients, String subject, String body, System.AsyncCallback callback) {#beginSend-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSend(String from, String recipients, String subject, String body, System.AsyncCallback callback)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | A String that contains the address of message sender. |
| recipients | java.lang.String | A String that contains the address of recipients. |
| subject | java.lang.String | A subject of message. |
| body | java.lang.String | A body of message. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSend(String from, String recipients, String subject, String body, System.AsyncCallback callback, Object state) {#beginSend-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSend(String from, String recipients, String subject, String body, System.AsyncCallback callback, Object state)
```


Begins sending email asynchronously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | A String that contains the address of message sender. |
| recipients | java.lang.String | A String that contains the address of recipients. |
| subject | java.lang.String | A subject of message. |
| body | java.lang.String | A body of message. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSendQueue() {#beginSendQueue--}
```
public final System.IAsyncResult beginSendQueue()
```


Begins to execute 'No operation' command

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSendQueue(System.AsyncCallback callback) {#beginSendQueue-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSendQueue(System.AsyncCallback callback)
```


Begins to execute 'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSendQueue(System.AsyncCallback callback, Object state) {#beginSendQueue-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSendQueue(System.AsyncCallback callback, Object state)
```


Begins to execute 'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials() {#beginValidateCredentials--}
```
public final System.IAsyncResult beginValidateCredentials()
```


Begins to execute credentials validation

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials(IConnection connection) {#beginValidateCredentials-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginValidateCredentials(IConnection connection)
```


Begins to execute credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials(IConnection connection, System.AsyncCallback callback) {#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginValidateCredentials(IConnection connection, System.AsyncCallback callback)
```


Begins to execute credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials(IConnection connection, System.AsyncCallback callback, Object state) {#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginValidateCredentials(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins to execute credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials(System.AsyncCallback callback) {#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginValidateCredentials(System.AsyncCallback callback)
```


Begins to execute credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials(System.AsyncCallback callback, Object state) {#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginValidateCredentials(System.AsyncCallback callback, Object state)
```


Begins to execute credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### bindIPEndPoint(BindIPEndPointHandler handler) {#bindIPEndPoint-com.aspose.email.BindIPEndPointHandler-}
```
public void bindIPEndPoint(BindIPEndPointHandler handler)
```


Associates a Socket with a local endpoint.

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

### close() {#close--}
```
public void close()
```




### connectIPEndPoint(BindIPEndPointHandler handler) {#connectIPEndPoint-com.aspose.email.BindIPEndPointHandler-}
```
public void connectIPEndPoint(BindIPEndPointHandler handler)
```


Associates a Socket with a remote endpoint.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| handler | [BindIPEndPointHandler](../../com.aspose.email/bindipendpointhandler) |  |

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
### dispose() {#dispose--}
```
public void dispose()
```


Finalizes all operations with a server.

### endBeginSendQueue(System.IAsyncResult asyncResult) {#endBeginSendQueue-com.aspose.ms.System.IAsyncResult-}
```
public final void endBeginSendQueue(System.IAsyncResult asyncResult)
```


Waits for the pending asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### endForward(System.IAsyncResult asyncResult) {#endForward-com.aspose.ms.System.IAsyncResult-}
```
public final void endForward(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### endNoop(System.IAsyncResult asyncResult) {#endNoop-com.aspose.ms.System.IAsyncResult-}
```
public final void endNoop(System.IAsyncResult asyncResult)
```


Waits for the pending asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### endSend(System.IAsyncResult asyncResult) {#endSend-com.aspose.ms.System.IAsyncResult-}
```
public final void endSend(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### endValidateCredentials(System.IAsyncResult asyncResult) {#endValidateCredentials-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endValidateCredentials(System.IAsyncResult asyncResult)
```


Waits for the pending asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
boolean - True if authentication was successful, otherwise false.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### forward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message) {#forward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-}
```
public final void forward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message)
```


Forwards specified message to recipient

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sender | java.lang.String | Sender of the forwarded message. |
| recipients | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |

### forward(IConnection connection, String sender, MailAddressCollection recipients, InputStream messageStream) {#forward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-java.io.InputStream-}
```
public final void forward(IConnection connection, String sender, MailAddressCollection recipients, InputStream messageStream)
```


Forwards specified message to recipient

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sender | java.lang.String | Sender of the forwarded message. |
| recipients | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Recipients of the forwarded message. |
| messageStream | java.io.InputStream | The stream that represents message in eml format. |

### forward(IConnection connection, String sender, String recipient, MailMessage message) {#forward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-}
```
public final void forward(IConnection connection, String sender, String recipient, MailMessage message)
```


Forwards specified message to recipient

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sender | java.lang.String | Sender of the forwarded message. |
| recipient | java.lang.String | Recipient of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |

### forward(String sender, MailAddressCollection recipients, MailMessage message) {#forward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-}
```
public final void forward(String sender, MailAddressCollection recipients, MailMessage message)
```


Forwards specified message to recipient

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.String | Sender of the forwarded message. |
| recipients | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Recipients of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |

### forward(String sender, MailAddressCollection recipients, InputStream messageStream) {#forward-java.lang.String-com.aspose.email.MailAddressCollection-java.io.InputStream-}
```
public final void forward(String sender, MailAddressCollection recipients, InputStream messageStream)
```


Forwards specified message to recipient

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.String | Sender of the forwarded message. |
| recipients | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Recipients of the forwarded message. |
| messageStream | java.io.InputStream | The stream that represents message in eml format. |

### forward(String sender, String recipient, MailMessage message) {#forward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-}
```
public final void forward(String sender, String recipient, MailMessage message)
```


Forwards specified message to recipient

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.String | Sender of the forwarded message. |
| recipient | java.lang.String | Recipient of the forwarded message. |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message for a forwarding. |

### getAccessToken() {#getAccessToken--}
```
public String getAccessToken()
```


Gets or sets the access token.

Value: The string that represents access token.

**Returns:**
java.lang.String
### getAllowedAuthentication() {#getAllowedAuthentication--}
```
public final long getAllowedAuthentication()
```


Gets or sets enumeration of allowed by user authentication types

**Returns:**
long
### getCapabilities() {#getCapabilities--}
```
public String[] getCapabilities()
```


Get Capabilities.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClientCertificates() {#getClientCertificates--}
```
public System.Security.Cryptography.X509Certificates.X509CertificateCollection getClientCertificates()
```


Contains collection of clients certificates

**Returns:**
com.aspose.ms.System.Security.Cryptography.X509Certificates.X509CertificateCollection
### getConnectionAsgmtMode() {#getConnectionAsgmtMode--}
```
public int getConnectionAsgmtMode()
```


Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread.

**Returns:**
int
### getConnectionCheckupPeriod() {#getConnectionCheckupPeriod--}
```
public int getConnectionCheckupPeriod()
```


Period of connection checking up in milliseconds. Default value is 5 min.

**Returns:**
int
### getConnectionState() {#getConnectionState--}
```
public final int getConnectionState()
```


Gets the current state of the connection.

**Returns:**
int
### getConnectionsQuantity() {#getConnectionsQuantity--}
```
public int getConnectionsQuantity()
```


Gets or sets quantity of connections in multy-connection mode

**Returns:**
int
### getCurrentConnection() {#getCurrentConnection--}
```
public IConnection getCurrentConnection()
```


Gets current connection according to ConnectionAsgmtMode option

**Returns:**
[IConnection](../../com.aspose.email/iconnection)
### getDefaultPort() {#getDefaultPort--}
```
public int getDefaultPort()
```


Gets default port for client

**Returns:**
int
### getDeliveryMethod() {#getDeliveryMethod--}
```
public final int getDeliveryMethod()
```


Gets or sets the delivery method.

Value: An SmtpDeliveryMethod that indicates how messages are delivered.

**Returns:**
int
### getEnableLogger() {#getEnableLogger--}
```
public final boolean getEnableLogger()
```


Gets or sets value which allows enable/disable logger

**Returns:**
boolean
### getGreetingTimeout() {#getGreetingTimeout--}
```
public final int getGreetingTimeout()
```


Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use  EmailClient.Timeout (\#getTimeout.getTimeout/\#setTimeout(int).setTimeout(int)) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment.

Value: The greeting timeout in milliseconds

**Returns:**
int
### getHelloMessage() {#getHelloMessage--}
```
public final String getHelloMessage()
```


Gets or sets a HELO/EHLO string.

**Returns:**
java.lang.String
### getHost() {#getHost--}
```
public String getHost()
```


Gets or sets the host name.

Value: The host name.

**Returns:**
java.lang.String
### getLogFileName() {#getLogFileName--}
```
public final String getLogFileName()
```


Gets or sets log file name

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public String getPassword()
```


Gets or sets the password. Password limitations are defined by server implementation, which client connects.

Value: The string that represents the password.

**Returns:**
java.lang.String
### getPickupDirectoryLocation() {#getPickupDirectoryLocation--}
```
public final String getPickupDirectoryLocation()
```


Gets or sets the directory where applications save mail messages to be processed by the local SMTP server. Please note: only absolute path is allowed.

Value: A String that represents the pickup directory

**Returns:**
java.lang.String
### getPort() {#getPort--}
```
public int getPort()
```


Gets or sets the port.

Value: The port number.

**Returns:**
int
### getProxy() {#getProxy--}
```
public Proxy getProxy()
```


Gets or sets proxy for the client

**Returns:**
[Proxy](../../com.aspose.email/proxy)
### getSecurityOptions() {#getSecurityOptions--}
```
public int getSecurityOptions()
```


Security mode for a mail client

**Returns:**
int
### getSmtpQueueLocation() {#getSmtpQueueLocation--}
```
public final String getSmtpQueueLocation()
```


Gets or sets the directory where applications save mail messages to be processed by sending in SMTP queue. Please note: only absolute path is allowed.

Value: A String that represents the pickup directory

**Returns:**
java.lang.String
### getSupportedAuthentication() {#getSupportedAuthentication--}
```
public final long getSupportedAuthentication()
```


Gets enumeration of supported by server authentication types

**Returns:**
long
### getSupportedEncryption() {#getSupportedEncryption--}
```
public int getSupportedEncryption()
```


Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [EncryptionProtocols](../../com.aspose.email/encryptionprotocols) documentation for more details. Please use \#setSupportedEncryptionUnsafe(int).setSupportedEncryptionUnsafe(int) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls | Tls11 | Tls12 | Tls13 (in case if your current version of .net framework supports these versions of TLS)

**Returns:**
int
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Gets or sets the timeout for mail operations

Value: The timeout in milliseconds

**Returns:**
int
### getTokenProvider() {#getTokenProvider--}
```
public final ITokenProvider getTokenProvider()
```


Gets or sets TokenProvider allowing to retrieve access token.

**Returns:**
[ITokenProvider](../../com.aspose.email/itokenprovider)
### getUseAuthentication() {#getUseAuthentication--}
```
public boolean getUseAuthentication()
```


Indicates whether authentication is used.

**Returns:**
boolean
### getUseDateInLogFileName() {#getUseDateInLogFileName--}
```
public final boolean getUseDateInLogFileName()
```


Gets or sets value which indicates if date has to be used in log file name.

**Returns:**
boolean
### getUseDefaultCredentials() {#getUseDefaultCredentials--}
```
public boolean getUseDefaultCredentials()
```


Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests.

**Returns:**
boolean
### getUseMultiConnection() {#getUseMultiConnection--}
```
public int getUseMultiConnection()
```


Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing.

**Returns:**
int
### getUsePipelining() {#getUsePipelining--}
```
public PipeliningStatus getUsePipelining()
```


Gets or sets object which indicates whether the pipelining mode is enabled.

**Returns:**
[PipeliningStatus](../../com.aspose.email/pipeliningstatus)
### getUseTnef() {#getUseTnef--}
```
public final boolean getUseTnef()
```


Gets or sets a boolean value that controls whether the messages are sent in TNEF format. Note, that now message is sent in TNEF format when being loaded a message contains tnef.

**Returns:**
boolean
### getUsername() {#getUsername--}
```
public String getUsername()
```


Gets or sets the username.

Value: The username string.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### noop() {#noop--}
```
public void noop()
```


'No operation' command

### noop(IConnection connection) {#noop-com.aspose.email.IConnection-}
```
public void noop(IConnection connection)
```


'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetLogSettings() {#resetLogSettings--}
```
public final void resetLogSettings()
```


Resets logging settings to default.

### send(IConnection connection, MailMessage message) {#send-com.aspose.email.IConnection-com.aspose.email.MailMessage-}
```
public final void send(IConnection connection, MailMessage message)
```


Send the specified message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The MailMessage that represents an email-message. |

### send(IConnection connection, MailMessage[] messages) {#send-com.aspose.email.IConnection-com.aspose.email.MailMessage...-}
```
public final void send(IConnection connection, MailMessage[] messages)
```


Send the specified message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messages | [MailMessage\[\]](../../com.aspose.email/mailmessage) | The array of MailMessage that represents an email-messages to send. |

### send(IConnection connection, MailMessageCollection messages) {#send-com.aspose.email.IConnection-com.aspose.email.MailMessageCollection-}
```
public final void send(IConnection connection, MailMessageCollection messages)
```


Send the specified message collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messages | [MailMessageCollection](../../com.aspose.email/mailmessagecollection) | The collection of messages. |

### send(IConnection connection, Iterable<MailMessage> messages) {#send-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--}
```
public final void send(IConnection connection, Iterable<MailMessage> messages)
```


Send the specified messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The IEnumerator that supports a message iteration. |

### send(IConnection connection, String from, String recipients, String subject, String body) {#send-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public final void send(IConnection connection, String from, String recipients, String subject, String body)
```


Creates and sends the specified message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| from | java.lang.String | A String that contains the address of message sender. |
| recipients | java.lang.String | A String that contains the address of recipients. |
| subject | java.lang.String | A subject of message. |
| body | java.lang.String | A body of message. |

### send(MailMessage message) {#send-com.aspose.email.MailMessage-}
```
public final void send(MailMessage message)
```


Send the specified message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The MailMessage that represents an email-message. |

### send(MailMessage[] messages) {#send-com.aspose.email.MailMessage...-}
```
public final void send(MailMessage[] messages)
```


Send the specified message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | [MailMessage\[\]](../../com.aspose.email/mailmessage) | The array of MailMessage that represents an email-messages to send. |

### send(MailMessageCollection messages) {#send-com.aspose.email.MailMessageCollection-}
```
public final void send(MailMessageCollection messages)
```


Send the specified message collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | [MailMessageCollection](../../com.aspose.email/mailmessagecollection) | The collection of messages. |

### send(Iterable<MailMessage> messages) {#send-java.lang.Iterable-com.aspose.email.MailMessage--}
```
public final void send(Iterable<MailMessage> messages)
```


Send the specified messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | The IEnumerator that supports a message iteration. |

### send(String from, String recipients, String subject, String body) {#send-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public final void send(String from, String recipients, String subject, String body)
```


Creates and sends the specified message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | A String that contains the address of message sender. |
| recipients | java.lang.String | A String that contains the address of recipients. |
| subject | java.lang.String | A subject of message. |
| body | java.lang.String | A body of message. |

### sendToQueue(Iterable<MailMessage> messages) {#sendToQueue-java.lang.Iterable-com.aspose.email.MailMessage--}
```
public final void sendToQueue(Iterable<MailMessage> messages)
```


Append messages to queue

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | MailMessages to send |

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

### setAllowedAuthentication(long value) {#setAllowedAuthentication-long-}
```
public final void setAllowedAuthentication(long value)
```


Gets or sets enumeration of allowed by user authentication types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setConnectionAsgmtMode(int value) {#setConnectionAsgmtMode-int-}
```
public void setConnectionAsgmtMode(int value)
```


Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setConnectionCheckupPeriod(int value) {#setConnectionCheckupPeriod-int-}
```
public void setConnectionCheckupPeriod(int value)
```


Period of connection checking up in milliseconds. Default value is 5 min.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setConnectionsQuantity(int value) {#setConnectionsQuantity-int-}
```
public void setConnectionsQuantity(int value)
```


Gets or sets quantity of connections in multy-connection mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDeliveryMethod(int value) {#setDeliveryMethod-int-}
```
public final void setDeliveryMethod(int value)
```


Gets or sets the delivery method.

Value: An SmtpDeliveryMethod that indicates how messages are delivered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEnableLogger(boolean value) {#setEnableLogger-boolean-}
```
public final void setEnableLogger(boolean value)
```


Gets or sets value which allows enable/disable logger

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFailedSending(System.EventHandler<FailedMailMessageEventArgs> handler) {#setFailedSending-com.aspose.ms.System.EventHandler-com.aspose.email.FailedMailMessageEventArgs--}
```
public void setFailedSending(System.EventHandler<FailedMailMessageEventArgs> handler)
```


Adds or removes subscriber for notifications about failed sending operations in smtp queue

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| handler | com.aspose.ms.System.EventHandler<com.aspose.email.FailedMailMessageEventArgs> |  |

### setGreetingTimeout(int value) {#setGreetingTimeout-int-}
```
public final void setGreetingTimeout(int value)
```


Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use  EmailClient.Timeout (\#getTimeout.getTimeout/\#setTimeout(int).setTimeout(int)) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment.

Value: The greeting timeout in milliseconds

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHelloMessage(String value) {#setHelloMessage-java.lang.String-}
```
public final void setHelloMessage(String value)
```


Gets or sets a HELO/EHLO string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public final void setLogFileName(String value)
```


Gets or sets log file name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setPickupDirectoryLocation(String value) {#setPickupDirectoryLocation-java.lang.String-}
```
public final void setPickupDirectoryLocation(String value)
```


Gets or sets the directory where applications save mail messages to be processed by the local SMTP server. Please note: only absolute path is allowed.

Value: A String that represents the pickup directory

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setProxy(Proxy value) {#setProxy-com.aspose.email.Proxy-}
```
public void setProxy(Proxy value)
```


Gets or sets proxy for the client

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Proxy](../../com.aspose.email/proxy) |  |

### setSecurityOptions(int value) {#setSecurityOptions-int-}
```
public void setSecurityOptions(int value)
```


Security mode for a mail client

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShowCredentialsInLog(boolean value) {#setShowCredentialsInLog-boolean-}
```
public static void setShowCredentialsInLog(boolean value)
```


Sets value indicating whether Credentials should be displayed in the log. By default, is False.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | True if Credentials should be displayed in the log. |

### setSmtpQueueLocation(String value) {#setSmtpQueueLocation-java.lang.String-}
```
public final void setSmtpQueueLocation(String value)
```


Gets or sets the directory where applications save mail messages to be processed by sending in SMTP queue. Please note: only absolute path is allowed.

Value: A String that represents the pickup directory

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setSucceededSending(System.EventHandler<MailMessageEventArgs> handler) {#setSucceededSending-com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--}
```
public void setSucceededSending(System.EventHandler<MailMessageEventArgs> handler)
```


Adds or removes subscriber for notifications about succeeded sending of mail messages. Please note, notifications will be invoked from other threads, so you should to implement thread safe event handler. Also note that this event is common to the mail client instance, in case if the client is running in multi-connection mode, messages from all connections will be processed through this event. So the customer has to analyze in his code message from events to understand which message relates to which operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| handler | com.aspose.ms.System.EventHandler<com.aspose.email.MailMessageEventArgs> |  |

### setSupportedEncryption(int value) {#setSupportedEncryption-int-}
```
public void setSupportedEncryption(int value)
```


Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [EncryptionProtocols](../../com.aspose.email/encryptionprotocols) documentation for more details. Please use \#setSupportedEncryptionUnsafe(int).setSupportedEncryptionUnsafe(int) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls | Tls11 | Tls12 | Tls13 (in case if your current version of .net framework supports these versions of TLS)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSupportedEncryptionUnsafe(int value) {#setSupportedEncryptionUnsafe-int-}
```
public final void setSupportedEncryptionUnsafe(int value)
```


Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use  SupportedEncryption (\#getSupportedEncryption.getSupportedEncryption/\#setSupportedEncryption(int).setSupportedEncryption(int)) property to safely set only protocols that definitely supported by framework. Please note, if your current framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

### setTokenProvider(ITokenProvider value) {#setTokenProvider-com.aspose.email.ITokenProvider-}
```
public final void setTokenProvider(ITokenProvider value)
```


Gets or sets TokenProvider allowing to retrieve access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITokenProvider](../../com.aspose.email/itokenprovider) |  |

### setUseAuthentication(boolean value) {#setUseAuthentication-boolean-}
```
public void setUseAuthentication(boolean value)
```


Indicates whether authentication is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseDateInLogFileName(boolean value) {#setUseDateInLogFileName-boolean-}
```
public final void setUseDateInLogFileName(boolean value)
```


Gets or sets value which indicates if date has to be used in log file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseDefaultCredentials(boolean value) {#setUseDefaultCredentials-boolean-}
```
public void setUseDefaultCredentials(boolean value)
```


Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseMultiConnection(int value) {#setUseMultiConnection-int-}
```
public void setUseMultiConnection(int value)
```


Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUsePipelining(PipeliningStatus value) {#setUsePipelining-com.aspose.email.PipeliningStatus-}
```
public void setUsePipelining(PipeliningStatus value)
```


Gets or sets object which indicates whether the pipelining mode is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PipeliningStatus](../../com.aspose.email/pipeliningstatus) |  |

### setUseTnef(boolean value) {#setUseTnef-boolean-}
```
public final void setUseTnef(boolean value)
```


Gets or sets a boolean value that controls whether the messages are sent in TNEF format. Note, that now message is sent in TNEF format when being loaded a message contains tnef.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### usePasswordQuotes(boolean value) {#usePasswordQuotes-boolean-}
```
public static void usePasswordQuotes(boolean value)
```


Sets a value indicating whether Quotes should be used in login password syntax with special characters. By default, is True.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | False if Quotes should not be used in login password syntax. |

### validateCredentials() {#validateCredentials--}
```
public boolean validateCredentials()
```


Executes credentials validation

**Returns:**
boolean - True if authentication was successful, otherwise false.
### validateCredentials(IConnection connection) {#validateCredentials-com.aspose.email.IConnection-}
```
public final boolean validateCredentials(IConnection connection)
```


Executes credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
boolean - True if authentication was successful, otherwise false.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

