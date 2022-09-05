---
title: IDeliveryServiceClient
second_title: Aspose.Email for Java API Reference
description:  Represents contract for DeliveryServiceClient
type: docs
weight: 734
url: /java/com.aspose.email/ideliveryserviceclient/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IDeliveryServiceClient extends System.IDisposable
```

Represents contract for DeliveryServiceClient
## Methods

| Method | Description |
| --- | --- |
| [send(MailMessage message)](#send-com.aspose.email.MailMessage-) | Sends email synchronously |
| [send(MailMessage message, List<String> tags, CancellationToken token)](#send-com.aspose.email.MailMessage-java.util.List-java.lang.String--com.aspose.email.CancellationToken-) | Sends email synchronously |
### send(MailMessage message) {#send-com.aspose.email.MailMessage-}
```
public abstract DeliveryServiceResponse send(MailMessage message)
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
public abstract DeliveryServiceResponse send(MailMessage message, List<String> tags, CancellationToken token)
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
