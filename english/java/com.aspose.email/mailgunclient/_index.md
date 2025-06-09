---
title: MailgunClient
second_title: Aspose.Email for Java API Reference
description: Represents the Mailgun client
type: docs
weight: 399
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
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [send(MailMessage message)](#send-com.aspose.email.MailMessage-) | Sends email synchronously |
| [send(MailMessage message, List<String> tags, CancellationToken token)](#send-com.aspose.email.MailMessage-java.util.List-java.lang.String--com.aspose.email.CancellationToken-) | Sends email synchronously |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

