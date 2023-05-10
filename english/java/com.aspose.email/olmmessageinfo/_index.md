---
title: OlmMessageInfo
second_title: Aspose.Email for Java API Reference
description: Represents an information about message in the OLM storage.
type: docs
weight: 543
url: /java/com.aspose.email/olmmessageinfo/
---

**Inheritance:**
java.lang.Object
```
public class OlmMessageInfo
```

Represents an information about message in the OLM storage.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | Gets the date of message. |
| [getEntryId()](#getEntryId--) | Gets the message entry identifier. |
| [getFrom()](#getFrom--) | Gets the from address. |
| [getMessageClass()](#getMessageClass--) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. |
| [getModifiedDate()](#getModifiedDate--) | Gets the date of message. |
| [getSubject()](#getSubject--) | Gets the message subject. |
| [getTo()](#getTo--) | Gets the address collection that contains the recipients of message. |
| [hasAttachments()](#hasAttachments--) | Gets or sets a value indicating whether the message has attachments. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getDate() {#getDate--}
```
public final Date getDate()
```


Gets the date of message.

**Returns:**
java.util.Date
### getEntryId() {#getEntryId--}
```
public final String getEntryId()
```


Gets the message entry identifier.

Value: The entry identifier.

**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public final MapiElectronicAddress getFrom()
```


Gets the from address.

**Returns:**
[MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress)
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message.

**Returns:**
java.lang.String
### getModifiedDate() {#getModifiedDate--}
```
public final Date getModifiedDate()
```


Gets the date of message.

**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the message subject.

**Returns:**
java.lang.String
### getTo() {#getTo--}
```
public final List<MapiElectronicAddress> getTo()
```


Gets the address collection that contains the recipients of message.

**Returns:**
java.util.List<com.aspose.email.MapiElectronicAddress>
### hasAttachments() {#hasAttachments--}
```
public final boolean hasAttachments()
```


Gets or sets a value indicating whether the message has attachments.

Value:  true  if this instance has attachments; otherwise,  false .

**Returns:**
boolean
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

