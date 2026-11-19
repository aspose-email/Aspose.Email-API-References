---
title: MessageObjectAttachmentEntity
second_title: Aspose.Email for Java API Reference
description: Represents an attachment entity.
type: docs
weight: 525
url: /java/com.aspose.email/messageobjectattachmententity/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMessageObjectPropertyContainer](../../com.aspose.email/imessageobjectpropertycontainer)
```
public final class MessageObjectAttachmentEntity implements IMessageObjectPropertyContainer
```

Represents an attachment entity.
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageObjectAttachmentEntity()](#MessageObjectAttachmentEntity--) | Initializes a new instance of the [MessageObjectAttachmentEntity](../../com.aspose.email/messageobjectattachmententity) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomAttachmentStorageData()](#getCustomAttachmentStorageData--) | Gets the custom attachment storage data. |
| [getEmbeddedMessage()](#getEmbeddedMessage--) | Gets the Embedded Message Object storage if present. |
| [getProperties()](#getProperties--) | Gets the attachment properties. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomAttachmentStorageData(CustomAttachmentStorage value)](#setCustomAttachmentStorageData-com.aspose.email.CustomAttachmentStorage-) | Sets the custom attachment storage data. |
| [setEmbeddedMessage(MessageObject value)](#setEmbeddedMessage-com.aspose.email.MessageObject-) | Sets the Embedded Message Object storage if present. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageObjectAttachmentEntity() {#MessageObjectAttachmentEntity--}
```
public MessageObjectAttachmentEntity()
```


Initializes a new instance of the [MessageObjectAttachmentEntity](../../com.aspose.email/messageobjectattachmententity) class.

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
### getCustomAttachmentStorageData() {#getCustomAttachmentStorageData--}
```
public final CustomAttachmentStorage getCustomAttachmentStorageData()
```


Gets the custom attachment storage data. Can be  null .

Mutually exclusive with \#getEmbeddedMessage().getEmbeddedMessage() or both can be  null .

**Returns:**
[CustomAttachmentStorage](../../com.aspose.email/customattachmentstorage) - The custom attachment storage data.
### getEmbeddedMessage() {#getEmbeddedMessage--}
```
public final MessageObject getEmbeddedMessage()
```


Gets the Embedded Message Object storage if present. Can be  null .

Mutually exclusive with \#getCustomAttachmentStorageData().getCustomAttachmentStorageData() or both can be  null .

**Returns:**
[MessageObject](../../com.aspose.email/messageobject) - The embedded message.
### getProperties() {#getProperties--}
```
public final MessageObjectPropertiesCollection getProperties()
```


Gets the attachment properties.

**Returns:**
[MessageObjectPropertiesCollection](../../com.aspose.email/messageobjectpropertiescollection) - The properties collection.
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




### setCustomAttachmentStorageData(CustomAttachmentStorage value) {#setCustomAttachmentStorageData-com.aspose.email.CustomAttachmentStorage-}
```
public final void setCustomAttachmentStorageData(CustomAttachmentStorage value)
```


Sets the custom attachment storage data. Can be  null .

Mutually exclusive with \#getEmbeddedMessage().getEmbeddedMessage() or both can be  null .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CustomAttachmentStorage](../../com.aspose.email/customattachmentstorage) | The custom attachment storage data. |

### setEmbeddedMessage(MessageObject value) {#setEmbeddedMessage-com.aspose.email.MessageObject-}
```
public final void setEmbeddedMessage(MessageObject value)
```


Sets the Embedded Message Object storage if present. Can be  null .

Mutually exclusive with \#getCustomAttachmentStorageData().getCustomAttachmentStorageData() or both can be  null .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MessageObject](../../com.aspose.email/messageobject) | The embedded message. |

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

