---
title: ResponseMessageBuilder
second_title: Aspose.Email for Java API Reference
description: Provides creation and formatting the forwarding and replying messages.
type: docs
weight: 609
url: /java/com.aspose.email/responsemessagebuilder/
---

**Inheritance:**
java.lang.Object
```
public abstract class ResponseMessageBuilder
```

Provides creation and formatting the forwarding and replying messages.
## Constructors

| Constructor | Description |
| --- | --- |
| [ResponseMessageBuilder()](#ResponseMessageBuilder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [buildResponse(MailMessage msg)](#buildResponse-com.aspose.email.MailMessage-) | Builds the forwarding and replying messages. |
| [buildResponse(MapiMessage msg)](#buildResponse-com.aspose.email.MapiMessage-) | Builds the forwarding and replying messages. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdditionMode()](#getAdditionMode--) | Gets or sets the format of response message. |
| [getClass()](#getClass--) |  |
| [getResponseText()](#getResponseText--) | Gets or sets the body of response message. |
| [getSender()](#getSender--) | Gets or sets the addres from which the response message will be sent. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdditionMode(int value)](#setAdditionMode-int-) | Gets or sets the format of response message. |
| [setResponseText(String value)](#setResponseText-java.lang.String-) | Gets or sets the body of response message. |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | Gets or sets the addres from which the response message will be sent. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResponseMessageBuilder() {#ResponseMessageBuilder--}
```
public ResponseMessageBuilder()
```


### buildResponse(MailMessage msg) {#buildResponse-com.aspose.email.MailMessage-}
```
public abstract MailMessage buildResponse(MailMessage msg)
```


Builds the forwarding and replying messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MailMessage](../../com.aspose.email/mailmessage) | Original message [MailMessage](../../com.aspose.email/mailmessage). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Resultant message [MailMessage](../../com.aspose.email/mailmessage).
### buildResponse(MapiMessage msg) {#buildResponse-com.aspose.email.MapiMessage-}
```
public abstract MapiMessage buildResponse(MapiMessage msg)
```


Builds the forwarding and replying messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | Original message [MapiMessage](../../com.aspose.email/mapimessage). |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Resultant message [MapiMessage](../../com.aspose.email/mapimessage).
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
### getAdditionMode() {#getAdditionMode--}
```
public final int getAdditionMode()
```


Gets or sets the format of response message.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getResponseText() {#getResponseText--}
```
public final String getResponseText()
```


Gets or sets the body of response message.

--------------------

Can contain html tags or rtf keywords if type of body of original message is HTML or RTF respectively.

**Returns:**
java.lang.String
### getSender() {#getSender--}
```
public final MailAddress getSender()
```


Gets or sets the addres from which the response message will be sent.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
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




### setAdditionMode(int value) {#setAdditionMode-int-}
```
public final void setAdditionMode(int value)
```


Gets or sets the format of response message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setResponseText(String value) {#setResponseText-java.lang.String-}
```
public final void setResponseText(String value)
```


Gets or sets the body of response message.

--------------------

Can contain html tags or rtf keywords if type of body of original message is HTML or RTF respectively.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public final void setSender(MailAddress value)
```


Gets or sets the addres from which the response message will be sent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

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

