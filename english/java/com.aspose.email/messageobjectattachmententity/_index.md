---
title: MessageObjectAttachmentEntity
second_title: Aspose.Email for Java API Reference
description: Represents an attachment entity.
type: docs
weight: 522
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
| [getCustomAttachmentStorageData()](#getCustomAttachmentStorageData--) | Gets or sets the custom attachment storage data.Can be null. |
| [getEmbeddedMessage()](#getEmbeddedMessage--) | Gets or sets the Embedded Message Object storage if present.Can be null. |
| [getProperties()](#getProperties--) | Gets the attachment properties. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomAttachmentStorageData(CustomAttachmentStorage value)](#setCustomAttachmentStorageData-com.aspose.email.CustomAttachmentStorage-) | Gets or sets the custom attachment storage data.Can be null. |
| [setEmbeddedMessage(MessageObject value)](#setEmbeddedMessage-com.aspose.email.MessageObject-) | Gets or sets the Embedded Message Object storage if present.Can be null. |
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


Gets or sets the custom attachment storage data.Can be null.

Value: The custom attachment storage data.

--------------------

Mutually exclusive with  MessageObjectAttachmentEntity.EmbeddedMessage (\#getEmbeddedMessage.getEmbeddedMessage/\#setEmbeddedMessage(MessageObject).setEmbeddedMessage(MessageObject)) or both can be null.

**Returns:**
[CustomAttachmentStorage](../../com.aspose.email/customattachmentstorage)
### getEmbeddedMessage() {#getEmbeddedMessage--}
```
public final MessageObject getEmbeddedMessage()
```


Gets or sets the Embedded Message Object storage if present.Can be null.

Value: The embedded message.

--------------------

Mutually exclusive with  MessageObjectAttachmentEntity.CustomAttachmentStorageData (\#getCustomAttachmentStorageData.getCustomAttachmentStorageData/\#setCustomAttachmentStorageData(CustomAttachmentStorage).setCustomAttachmentStorageData(CustomAttachmentStorage)) or both can be null.

**Returns:**
[MessageObject](../../com.aspose.email/messageobject)
### getProperties() {#getProperties--}
```
public final MessageObjectPropertiesCollection getProperties()
```


Gets the attachment properties.

Value: The properties collection.

**Returns:**
[MessageObjectPropertiesCollection](../../com.aspose.email/messageobjectpropertiescollection)
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


Gets or sets the custom attachment storage data.Can be null.

Value: The custom attachment storage data.

--------------------

Mutually exclusive with  MessageObjectAttachmentEntity.EmbeddedMessage (\#getEmbeddedMessage.getEmbeddedMessage/\#setEmbeddedMessage(MessageObject).setEmbeddedMessage(MessageObject)) or both can be null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CustomAttachmentStorage](../../com.aspose.email/customattachmentstorage) |  |

### setEmbeddedMessage(MessageObject value) {#setEmbeddedMessage-com.aspose.email.MessageObject-}
```
public final void setEmbeddedMessage(MessageObject value)
```


Gets or sets the Embedded Message Object storage if present.Can be null.

Value: The embedded message.

--------------------

Mutually exclusive with  MessageObjectAttachmentEntity.CustomAttachmentStorageData (\#getCustomAttachmentStorageData.getCustomAttachmentStorageData/\#setCustomAttachmentStorageData(CustomAttachmentStorage).setCustomAttachmentStorageData(CustomAttachmentStorage)) or both can be null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MessageObject](../../com.aspose.email/messageobject) |  |

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

