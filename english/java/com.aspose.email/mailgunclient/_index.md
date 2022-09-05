---
title: MailgunClient
second_title: Aspose.Email for Java API Reference
description:  Represents the Mailgun client
type: docs
weight: 381
url: /java/com.aspose.email/mailgunclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IDeliveryServiceClient](../../com.aspose.email/ideliveryserviceclient)
```
public class MailgunClient implements IDeliveryServiceClient
```

Represents the Mailgun client
## Constructors

| Constructor | Description |
| --- | --- |
| [MailgunClient(String domainName, String apiKey)](#MailgunClient-java.lang.String-java.lang.String-) | Initializes a new instance of the [MailgunClient](../../com.aspose.email/mailgunclient) class |
| [MailgunClient(String domainName, String apiKey, int mailGunRegion)](#MailgunClient-java.lang.String-java.lang.String-int-) | Initializes a new instance of the [MailgunClient](../../com.aspose.email/mailgunclient) class |
## Methods

| Method | Description |
| --- | --- |
| [send(MailMessage message)](#send-com.aspose.email.MailMessage-) | Sends email synchronously |
| [send(MailMessage message, List<String> tags, CancellationToken token)](#send-com.aspose.email.MailMessage-java.util.List-java.lang.String--com.aspose.email.CancellationToken-) | Sends email synchronously |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
### MailgunClient(String domainName, String apiKey) {#MailgunClient-java.lang.String-java.lang.String-}
```
public MailgunClient(String domainName, String apiKey)
```


Initializes a new instance of the [MailgunClient](../../com.aspose.email/mailgunclient) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| domainName | java.lang.String |  |
| apiKey | java.lang.String |  |

### MailgunClient(String domainName, String apiKey, int mailGunRegion) {#MailgunClient-java.lang.String-java.lang.String-int-}
```
public MailgunClient(String domainName, String apiKey, int mailGunRegion)
```


Initializes a new instance of the [MailgunClient](../../com.aspose.email/mailgunclient) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| domainName | java.lang.String |  |
| apiKey | java.lang.String |  |
| mailGunRegion | int |  |

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

