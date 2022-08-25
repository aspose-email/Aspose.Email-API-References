---
title: SendGridClient
second_title: Aspose.Email for Java API Reference
description:  Represents the SendGrid client
type: docs
weight: 621
url: /java/com.aspose.email/sendgridclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IDeliveryServiceClient](../../com.aspose.email/ideliveryserviceclient)
```
public class SendGridClient implements IDeliveryServiceClient
```

Represents the SendGrid client
## Constructors

| Constructor | Description |
| --- | --- |
| [SendGridClient(String apiKey)](#SendGridClient-java.lang.String-) | Initializes a new instance of the [SendGridClient](../../com.aspose.email/sendgridclient) class |
| [SendGridClient(String apiKey, boolean sandBoxMode)](#SendGridClient-java.lang.String-boolean-) | Initializes a new instance of the [SendGridClient](../../com.aspose.email/sendgridclient) class |
## Methods

| Method | Description |
| --- | --- |
| [send(MailMessage message)](#send-com.aspose.email.MailMessage-) | Sends email synchronously |
| [send(MailMessage message, List<String> tags, CancellationToken token)](#send-com.aspose.email.MailMessage-java.util.List-java.lang.String--com.aspose.email.CancellationToken-) | Sends email synchronously |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
### SendGridClient(String apiKey) {#SendGridClient-java.lang.String-}
```
public SendGridClient(String apiKey)
```


Initializes a new instance of the [SendGridClient](../../com.aspose.email/sendgridclient) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| apiKey | java.lang.String |  |

### SendGridClient(String apiKey, boolean sandBoxMode) {#SendGridClient-java.lang.String-boolean-}
```
public SendGridClient(String apiKey, boolean sandBoxMode)
```


Initializes a new instance of the [SendGridClient](../../com.aspose.email/sendgridclient) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| apiKey | java.lang.String |  |
| sandBoxMode | boolean |  |

### send(MailMessage message) {#send-com.aspose.email.MailMessage-}
```
public final DeliveryServiceResponse send(MailMessage message)
```


Sends email synchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The MailMessage that represents an email-message. |

**Returns:**
[DeliveryServiceResponse](../../com.aspose.email/deliveryserviceresponse) - 
### send(MailMessage message, List<String> tags, CancellationToken token) {#send-com.aspose.email.MailMessage-java.util.List-java.lang.String--com.aspose.email.CancellationToken-}
```
public final DeliveryServiceResponse send(MailMessage message, List<String> tags, CancellationToken token)
```


Sends email synchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The MailMessage that represents an email-message. |
| tags | java.util.List<java.lang.String> |  |
| token | com.aspose.email.CancellationToken |  |

**Returns:**
[DeliveryServiceResponse](../../com.aspose.email/deliveryserviceresponse) - 
### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

