---
title: SmtpClient
second_title: Aspose.Email for Java API Reference
description: Allows applications to send messages by using the Simple Mail Transfer Protocol SMTP.
type: docs
weight: 633
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
| [getDefaultPort()](#getDefaultPort--) | Gets default port for client |
| [getHelloMessage()](#getHelloMessage--) | Gets or sets a HELO/EHLO string. |
| [setHelloMessage(String value)](#setHelloMessage-java.lang.String-) | Gets or sets a HELO/EHLO string. |
| [getDeliveryMethod()](#getDeliveryMethod--) | Gets or sets the delivery method. |
| [setDeliveryMethod(int value)](#setDeliveryMethod-int-) | Gets or sets the delivery method. |
| [getPickupDirectoryLocation()](#getPickupDirectoryLocation--) | Gets or sets the directory where applications save mail messages to be processed by the local SMTP server. |
| [setPickupDirectoryLocation(String value)](#setPickupDirectoryLocation-java.lang.String-) | Gets or sets the directory where applications save mail messages to be processed by the local SMTP server. |
| [getSmtpQueueLocation()](#getSmtpQueueLocation--) | Gets or sets the directory where applications save mail messages to be processed by sending in SMTP queue. |
| [setSmtpQueueLocation(String value)](#setSmtpQueueLocation-java.lang.String-) | Gets or sets the directory where applications save mail messages to be processed by sending in SMTP queue. |
| [setFailedSending(System.EventHandler<FailedMailMessageEventArgs> handler)](#setFailedSending-com.aspose.ms.System.EventHandler-com.aspose.email.FailedMailMessageEventArgs--) | Adds or removes subscriber for notifications about failed sending operations in smtp queue |
| [setSucceededQueueSending(System.EventHandler<MailMessageEventArgs> handler)](#setSucceededQueueSending-com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--) | Adds or removes subscriber for notifications about succeeded sending operations in smtp queue |
| [setSucceededSending(System.EventHandler<MailMessageEventArgs> handler)](#setSucceededSending-com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--) | Adds or removes subscriber for notifications about succeeded sending of mail messages. |
| [getUseDefaultCredentials()](#getUseDefaultCredentials--) | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [setUseDefaultCredentials(boolean value)](#setUseDefaultCredentials-boolean-) | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [getUseTnef()](#getUseTnef--) | Gets or sets a boolean value that controls whether the messages are sent in TNEF format. |
| [setUseTnef(boolean value)](#setUseTnef-boolean-) | Gets or sets a boolean value that controls whether the messages are sent in TNEF format. |
| [getAllowedAuthentication()](#getAllowedAuthentication--) | Gets or sets enumeration of allowed by user authentication types |
| [setAllowedAuthentication(long value)](#setAllowedAuthentication-long-) | Gets or sets enumeration of allowed by user authentication types |
| [getSupportedAuthentication()](#getSupportedAuthentication--) | Gets enumeration of supported by server authentication types |
| [beginForward(IConnection connection, String sender, String recipient, MailMessage message)](#beginForward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-) | Begins forward email asynchronously. |
| [beginForward(IConnection connection, String sender, String recipient, MailMessage message, System.AsyncCallback callback)](#beginForward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins forward email asynchronously. |
| [beginForward(IConnection connection, String sender, String recipient, MailMessage message, System.AsyncCallback callback, Object state)](#beginForward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins forward email asynchronously. |
| [beginForward(String sender, String recipient, MailMessage message)](#beginForward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-) | Begins forward email asynchronously. |
| [beginForward(String sender, String recipient, MailMessage message, System.AsyncCallback callback)](#beginForward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins forward email asynchronously. |
| [beginForward(String sender, String recipient, MailMessage message, System.AsyncCallback callback, Object state)](#beginForward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins forward email asynchronously. |
| [beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message)](#beginForward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-) | Begins forward email asynchronously. |
| [beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback)](#beginForward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins forward email asynchronously. |
| [beginForward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback, Object state)](#beginForward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins forward email asynchronously. |
| [beginForward(String sender, MailAddressCollection recipients, MailMessage message)](#beginForward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-) | Begins forward email asynchronously. |
| [beginForward(String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback)](#beginForward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins forward email asynchronously. |
| [beginForward(String sender, MailAddressCollection recipients, MailMessage message, System.AsyncCallback callback, Object state)](#beginForward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins forward email asynchronously. |
| [endForward(System.IAsyncResult asyncResult)](#endForward-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [forward(IConnection connection, String sender, String recipient, MailMessage message)](#forward-com.aspose.email.IConnection-java.lang.String-java.lang.String-com.aspose.email.MailMessage-) | Forwards specified message to recipient |
| [forward(IConnection connection, String sender, MailAddressCollection recipients, MailMessage message)](#forward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-) | Forwards specified message to recipient |
| [forward(String sender, String recipient, MailMessage message)](#forward-java.lang.String-java.lang.String-com.aspose.email.MailMessage-) | Forwards specified message to recipient |
| [forward(String sender, MailAddressCollection recipients, MailMessage message)](#forward-java.lang.String-com.aspose.email.MailAddressCollection-com.aspose.email.MailMessage-) | Forwards specified message to recipient |
| [forward(IConnection connection, String sender, MailAddressCollection recipients, InputStream messageStream)](#forward-com.aspose.email.IConnection-java.lang.String-com.aspose.email.MailAddressCollection-java.io.InputStream-) | Forwards specified message to recipient |
| [forward(String sender, MailAddressCollection recipients, InputStream messageStream)](#forward-java.lang.String-com.aspose.email.MailAddressCollection-java.io.InputStream-) | Forwards specified message to recipient |
| [beginNoop(IConnection connection)](#beginNoop-com.aspose.email.IConnection-) | Begins to execute 'No operation' command |
| [beginNoop(IConnection connection, System.AsyncCallback callback)](#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins to execute 'No operation' command |
| [beginNoop(IConnection connection, System.AsyncCallback callback, Object state)](#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute 'No operation' command |
| [beginNoop()](#beginNoop--) | Begins to execute 'No operation' command |
| [beginNoop(System.AsyncCallback callback)](#beginNoop-com.aspose.ms.System.AsyncCallback-) | Begins to execute 'No operation' command |
| [beginNoop(System.AsyncCallback callback, Object state)](#beginNoop-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute 'No operation' command |
| [endNoop(System.IAsyncResult asyncResult)](#endNoop-com.aspose.ms.System.IAsyncResult-) | Waits for the pending asynchronous operation to complete. |
| [noop(IConnection connection)](#noop-com.aspose.email.IConnection-) | 'No operation' command |
| [noop()](#noop--) | 'No operation' command |
| [beginSend(IConnection connection, MailMessage message)](#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, MailMessage message, System.AsyncCallback callback)](#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, MailMessage message, System.AsyncCallback callback, Object state)](#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, String from, String recipients, String subject, String body)](#beginSend-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, String from, String recipients, String subject, String body, System.AsyncCallback callback)](#beginSend-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, String from, String recipients, String subject, String body, System.AsyncCallback callback, Object state)](#beginSend-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, MailMessage[] messages)](#beginSend-com.aspose.email.IConnection-com.aspose.email.MailMessage...-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages, System.AsyncCallback callback)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages, System.AsyncCallback callback, Object state)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(MailMessage message)](#beginSend-com.aspose.email.MailMessage-) | Begins sending email asynchronously. |
| [beginSend(MailMessage message, System.AsyncCallback callback)](#beginSend-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(MailMessage message, System.AsyncCallback callback, Object state)](#beginSend-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(String from, String recipients, String subject, String body)](#beginSend-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Begins sending email asynchronously. |
| [beginSend(String from, String recipients, String subject, String body, System.AsyncCallback callback)](#beginSend-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(String from, String recipients, String subject, String body, System.AsyncCallback callback, Object state)](#beginSend-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(MailMessage[] messages)](#beginSend-com.aspose.email.MailMessage...-) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages, System.AsyncCallback callback)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages, System.AsyncCallback callback, Object state)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(IConnection connection, Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback, Object state)](#beginSend-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-) | Begins sending email asynchronously. |
| [beginSend(Iterable<MailMessage> messages, System.EventHandler<MailMessageEventArgs> messageSentDelegate, System.AsyncCallback callback, Object state)](#beginSend-java.lang.Iterable-com.aspose.email.MailMessage--com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins sending email asynchronously. |
| [endSend(System.IAsyncResult asyncResult)](#endSend-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [send(String from, String recipients, String subject, String body)](#send-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Creates and sends the specified message. |
| [send(MailMessage message)](#send-com.aspose.email.MailMessage-) | Send the specified message. |
| [send(MailMessage[] messages)](#send-com.aspose.email.MailMessage...-) | Send the specified message. |
| [send(MailMessageCollection messages)](#send-com.aspose.email.MailMessageCollection-) | Send the specified message collection. |
| [send(Iterable<MailMessage> messages)](#send-java.lang.Iterable-com.aspose.email.MailMessage--) | Send the specified messages. |
| [send(IConnection connection, String from, String recipients, String subject, String body)](#send-com.aspose.email.IConnection-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Creates and sends the specified message. |
| [send(IConnection connection, MailMessage message)](#send-com.aspose.email.IConnection-com.aspose.email.MailMessage-) | Send the specified message. |
| [send(IConnection connection, MailMessage[] messages)](#send-com.aspose.email.IConnection-com.aspose.email.MailMessage...-) | Send the specified message. |
| [send(IConnection connection, MailMessageCollection messages)](#send-com.aspose.email.IConnection-com.aspose.email.MailMessageCollection-) | Send the specified message collection. |
| [send(IConnection connection, Iterable<MailMessage> messages)](#send-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.MailMessage--) | Send the specified messages. |
| [beginSendQueue()](#beginSendQueue--) | Begins to execute 'No operation' command |
| [beginSendQueue(System.AsyncCallback callback)](#beginSendQueue-com.aspose.ms.System.AsyncCallback-) | Begins to execute 'No operation' command |
| [beginSendQueue(System.AsyncCallback callback, Object state)](#beginSendQueue-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute 'No operation' command |
| [endBeginSendQueue(System.IAsyncResult asyncResult)](#endBeginSendQueue-com.aspose.ms.System.IAsyncResult-) | Waits for the pending asynchronous operation to complete. |
| [sendToQueue(Iterable<MailMessage> messages)](#sendToQueue-java.lang.Iterable-com.aspose.email.MailMessage--) | Append messages to queue |
| [beginValidateCredentials(IConnection connection)](#beginValidateCredentials-com.aspose.email.IConnection-) | Begins to execute credentials validation |
| [beginValidateCredentials(IConnection connection, System.AsyncCallback callback)](#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins to execute credentials validation |
| [beginValidateCredentials(IConnection connection, System.AsyncCallback callback, Object state)](#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute credentials validation |
| [beginValidateCredentials()](#beginValidateCredentials--) | Begins to execute credentials validation |
| [beginValidateCredentials(System.AsyncCallback callback)](#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-) | Begins to execute credentials validation |
| [beginValidateCredentials(System.AsyncCallback callback, Object state)](#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute credentials validation |
| [endValidateCredentials(System.IAsyncResult asyncResult)](#endValidateCredentials-com.aspose.ms.System.IAsyncResult-) | Waits for the pending asynchronous operation to complete. |
| [validateCredentials(IConnection connection)](#validateCredentials-com.aspose.email.IConnection-) | Executes credentials validation |
| [validateCredentials()](#validateCredentials--) | Executes credentials validation |
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

### getDefaultPort() {#getDefaultPort--}
```
public int getDefaultPort()
```


Gets default port for client

**Returns:**
int
### getHelloMessage() {#getHelloMessage--}
```
public final String getHelloMessage()
```


Gets or sets a HELO/EHLO string.

**Returns:**
java.lang.String
### setHelloMessage(String value) {#setHelloMessage-java.lang.String-}
```
public final void setHelloMessage(String value)
```


Gets or sets a HELO/EHLO string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeliveryMethod() {#getDeliveryMethod--}
```
public final int getDeliveryMethod()
```


Gets or sets the delivery method.

Value: An SmtpDeliveryMethod that indicates how messages are delivered.

**Returns:**
int
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

### getPickupDirectoryLocation() {#getPickupDirectoryLocation--}
```
public final String getPickupDirectoryLocation()
```


Gets or sets the directory where applications save mail messages to be processed by the local SMTP server. Please note: only absolute path is allowed.

Value: A String that represents the pickup directory

**Returns:**
java.lang.String
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

### getSmtpQueueLocation() {#getSmtpQueueLocation--}
```
public final String getSmtpQueueLocation()
```


Gets or sets the directory where applications save mail messages to be processed by sending in SMTP queue. Please note: only absolute path is allowed.

Value: A String that represents the pickup directory

**Returns:**
java.lang.String
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

### setFailedSending(System.EventHandler<FailedMailMessageEventArgs> handler) {#setFailedSending-com.aspose.ms.System.EventHandler-com.aspose.email.FailedMailMessageEventArgs--}
```
public void setFailedSending(System.EventHandler<FailedMailMessageEventArgs> handler)
```


Adds or removes subscriber for notifications about failed sending operations in smtp queue

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| handler | com.aspose.ms.System.EventHandler<com.aspose.email.FailedMailMessageEventArgs> |  |

### setSucceededQueueSending(System.EventHandler<MailMessageEventArgs> handler) {#setSucceededQueueSending-com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--}
```
public void setSucceededQueueSending(System.EventHandler<MailMessageEventArgs> handler)
```


Adds or removes subscriber for notifications about succeeded sending operations in smtp queue

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| handler | com.aspose.ms.System.EventHandler<com.aspose.email.MailMessageEventArgs> |  |

### setSucceededSending(System.EventHandler<MailMessageEventArgs> handler) {#setSucceededSending-com.aspose.ms.System.EventHandler-com.aspose.email.MailMessageEventArgs--}
```
public void setSucceededSending(System.EventHandler<MailMessageEventArgs> handler)
```


Adds or removes subscriber for notifications about succeeded sending of mail messages. Please note, notifications will be invoked from other threads, so you should to implement thread safe event handler. Also note that this event is common to the mail client instance, in case if the client is running in multi-connection mode, messages from all connections will be processed through this event. So the customer has to analyze in his code message from events to understand which message relates to which operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| handler | com.aspose.ms.System.EventHandler<com.aspose.email.MailMessageEventArgs> |  |

### getUseDefaultCredentials() {#getUseDefaultCredentials--}
```
public boolean getUseDefaultCredentials()
```


Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests.

**Returns:**
boolean
### setUseDefaultCredentials(boolean value) {#setUseDefaultCredentials-boolean-}
```
public void setUseDefaultCredentials(boolean value)
```


Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseTnef() {#getUseTnef--}
```
public final boolean getUseTnef()
```


Gets or sets a boolean value that controls whether the messages are sent in TNEF format. Note, that now message is sent in TNEF format when being loaded a message contains tnef.

**Returns:**
boolean
### setUseTnef(boolean value) {#setUseTnef-boolean-}
```
public final void setUseTnef(boolean value)
```


Gets or sets a boolean value that controls whether the messages are sent in TNEF format. Note, that now message is sent in TNEF format when being loaded a message contains tnef.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAllowedAuthentication() {#getAllowedAuthentication--}
```
public final long getAllowedAuthentication()
```


Gets or sets enumeration of allowed by user authentication types

**Returns:**
long
### setAllowedAuthentication(long value) {#setAllowedAuthentication-long-}
```
public final void setAllowedAuthentication(long value)
```


Gets or sets enumeration of allowed by user authentication types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSupportedAuthentication() {#getSupportedAuthentication--}
```
public final long getSupportedAuthentication()
```


Gets enumeration of supported by server authentication types

**Returns:**
long
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
### endForward(System.IAsyncResult asyncResult) {#endForward-com.aspose.ms.System.IAsyncResult-}
```
public final void endForward(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

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
### beginNoop() {#beginNoop--}
```
public final System.IAsyncResult beginNoop()
```


Begins to execute 'No operation' command

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
### endNoop(System.IAsyncResult asyncResult) {#endNoop-com.aspose.ms.System.IAsyncResult-}
```
public final void endNoop(System.IAsyncResult asyncResult)
```


Waits for the pending asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### noop(IConnection connection) {#noop-com.aspose.email.IConnection-}
```
public void noop(IConnection connection)
```


'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

### noop() {#noop--}
```
public void noop()
```


'No operation' command

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
### endSend(System.IAsyncResult asyncResult) {#endSend-com.aspose.ms.System.IAsyncResult-}
```
public final void endSend(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

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
### endBeginSendQueue(System.IAsyncResult asyncResult) {#endBeginSendQueue-com.aspose.ms.System.IAsyncResult-}
```
public final void endBeginSendQueue(System.IAsyncResult asyncResult)
```


Waits for the pending asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### sendToQueue(Iterable<MailMessage> messages) {#sendToQueue-java.lang.Iterable-com.aspose.email.MailMessage--}
```
public final void sendToQueue(Iterable<MailMessage> messages)
```


Append messages to queue

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | MailMessages to send |

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
### beginValidateCredentials() {#beginValidateCredentials--}
```
public final System.IAsyncResult beginValidateCredentials()
```


Begins to execute credentials validation

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
### validateCredentials() {#validateCredentials--}
```
public boolean validateCredentials()
```


Executes credentials validation

**Returns:**
boolean - True if authentication was successful, otherwise false.
