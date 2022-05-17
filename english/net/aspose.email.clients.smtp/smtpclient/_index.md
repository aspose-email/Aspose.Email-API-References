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
| [AllowedAuthentication](allowedauthentication) { get; set; } | Gets or sets enumeration of allowed by user authentication types |
| override [DefaultPort](defaultport) { get; } | Gets default port for client |
| [DeliveryMethod](deliverymethod) { get; set; } | Gets or sets the delivery method. |
| [HelloMessage](hellomessage) { get; set; } | Gets or sets a HELO/EHLO string. |
| [PickupDirectoryLocation](pickupdirectorylocation) { get; set; } | Gets or sets the directory where applications save mail messages to be processed by the local SMTP server. Please note: only absolute path is allowed. |
| [SmtpQueueLocation](smtpqueuelocation) { get; set; } | Gets or sets the directory where applications save mail messages to be processed by sending in SMTP queue. Please note: only absolute path is allowed. |
| [SupportedAuthentication](supportedauthentication) { get; } | Gets enumeration of supported by server authentication types |
| override [UseDefaultCredentials](usedefaultcredentials) { get; set; } | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [UseTnef](usetnef) { get; set; } | Gets or sets a boolean value that controls whether the messages are sent in TNEF format. Note, that now message is sent in TNEF format when being loaded a message contains tnef. |

## Methods

| Name | Description |
| --- | --- |
| [Forward](forward)(string, MailAddressCollection, MailMessage) | Forwards specified message to recipient |
| [Forward](forward)(string, MailAddressCollection, Stream) | Forwards specified message to recipient |
| [Forward](forward)(string, string, MailMessage) | Forwards specified message to recipient |
| [Forward](forward)(IConnection, string, MailAddressCollection, MailMessage) | Forwards specified message to recipient |
| [Forward](forward)(IConnection, string, MailAddressCollection, Stream) | Forwards specified message to recipient |
| [Forward](forward)(IConnection, string, string, MailMessage) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(string, MailAddressCollection, MailMessage) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(string, MailAddressCollection, Stream) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(string, string, MailMessage) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(IConnection, string, MailAddressCollection, MailMessage) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(IConnection, string, MailAddressCollection, Stream) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(IConnection, string, string, MailMessage) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(string, MailAddressCollection, MailMessage, CancellationToken) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(string, MailAddressCollection, Stream, CancellationToken) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(string, string, MailMessage, CancellationToken) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(IConnection, string, MailAddressCollection, Stream, CancellationToken) | Forwards specified message to recipient |
| [ForwardAsync](forwardasync)(IConnection, string, string, MailMessage, CancellationToken) | Forwards specified message to recipient |
| override [Noop](noop)() | 'No operation' command |
| override [Noop](noop)(IConnection) | 'No operation' command |
| [NoopAsync](noopasync)() | 'No operation' command |
| [NoopAsync](noopasync)(CancellationToken) | 'No operation' command |
| [NoopAsync](noopasync)(IConnection) | 'No operation' command |
| [NoopAsync](noopasync)(IConnection, CancellationToken) | 'No operation' command |
| [Send](send)(IEnumerable&lt;MailMessage&gt;) | Send the specified messages. |
| [Send](send)(MailMessage) | Send the specified message. |
| [Send](send)(MailMessageCollection) | Send the specified message collection. |
| [Send](send)(params MailMessage[]) | Send the specified message. |
| [Send](send)(IConnection, IEnumerable&lt;MailMessage&gt;) | Send the specified messages. |
| [Send](send)(IConnection, MailMessage) | Send the specified message. |
| [Send](send)(IConnection, MailMessageCollection) | Send the specified message collection. |
| [Send](send)(IConnection, params MailMessage[]) | Send the specified message. |
| [Send](send)(string, string, string, string) | Creates and sends the specified message. |
| [Send](send)(IConnection, string, string, string, string) | Creates and sends the specified message. |
| [SendAsync](sendasync)(IEnumerable&lt;MailMessage&gt;) | Send the specified messages. |
| [SendAsync](sendasync)(MailMessage) | Send the specified message. |
| [SendAsync](sendasync)(MailMessageCollection) | Send the specified message collection. |
| [SendAsync](sendasync)(params MailMessage[]) | Send the specified message. |
| [SendAsync](sendasync)(CancellationToken, params MailMessage[]) | Send the specified message. |
| [SendAsync](sendasync)(IConnection, IEnumerable&lt;MailMessage&gt;) | Send the specified messages. |
| [SendAsync](sendasync)(IConnection, MailMessage) | Send the specified message. |
| [SendAsync](sendasync)(IConnection, MailMessageCollection) | Send the specified message collection. |
| [SendAsync](sendasync)(IConnection, params MailMessage[]) | Send the specified message. |
| [SendAsync](sendasync)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Send the specified messages. |
| [SendAsync](sendasync)(MailMessage, CancellationToken) | Send the specified message. |
| [SendAsync](sendasync)(MailMessageCollection, CancellationToken) | Send the specified message collection. |
| [SendAsync](sendasync)(IConnection, CancellationToken, params MailMessage[]) | Send the specified message. |
| [SendAsync](sendasync)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Send the specified messages. |
| [SendAsync](sendasync)(IConnection, MailMessage, CancellationToken) | Send the specified message. |
| [SendAsync](sendasync)(IConnection, MailMessageCollection, CancellationToken) | Send the specified message collection. |
| [SendAsync](sendasync)(string, string, string, string) | Creates and sends the specified message. |
| [SendAsync](sendasync)(IConnection, string, string, string, string) | Creates and sends the specified message. |
| [SendAsync](sendasync)(string, string, string, string, CancellationToken) | Creates and sends the specified message. |
| [SendAsync](sendasync)(IConnection, string, string, string, string, CancellationToken) | Creates and sends the specified message. |
| [SendToQueue](sendtoqueue)(IEnumerable&lt;MailMessage&gt;) | Append messages to queue |
| override [ValidateCredentials](validatecredentials)() | Executes credentials validation |
| [ValidateCredentials](validatecredentials)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)() | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)(CancellationToken) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)(IConnection, CancellationToken) | Executes credentials validation |

## Other Members

| Name | Description |
| --- | --- |
| event [FailedSending](failedsending) | Adds or removes subscriber for notifications about failed sending operations in smtp queue |
| event [SucceededSending](succeededsending) | Adds or removes subscriber for notifications about succeeded sending of mail messages. Please note, notifications will be invoked from other threads, so you should to implement thread safe event handler. Also note that this event is common to the mail client instance, in case if the client is running in multi-connection mode, messages from all connections will be processed through this event. So the customer has to analyze in his code message from events to understand which message relates to which operation. |

### See Also

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IMailTransferAgent](../imailtransferagent)
* namespace [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
