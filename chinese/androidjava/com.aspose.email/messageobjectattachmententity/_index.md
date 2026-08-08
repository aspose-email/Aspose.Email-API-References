---
title: MessageObjectAttachmentEntity
second_title: Aspose.Email for Android via Java API 参考
description: 表示附件实体。
type: docs
weight: 310
url: /zh/androidjava/com.aspose.email/messageobjectattachmententity/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMessageObjectPropertyContainer](../../com.aspose.email/imessageobjectpropertycontainer)
```
public final class MessageObjectAttachmentEntity implements IMessageObjectPropertyContainer
```

表示附件实体。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MessageObjectAttachmentEntity()](#MessageObjectAttachmentEntity--) | 初始化 [MessageObjectAttachmentEntity](../../com.aspose.email/messageobjectattachmententity) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomAttachmentStorageData()](#getCustomAttachmentStorageData--) | 获取或设置自定义附件存储数据。可以为 null。 |
| [getEmbeddedMessage()](#getEmbeddedMessage--) | 获取或设置嵌入的消息对象存储（如果存在）。可以为 null。 |
| [getProperties()](#getProperties--) | 获取附件属性。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomAttachmentStorageData(CustomAttachmentStorage value)](#setCustomAttachmentStorageData-com.aspose.email.CustomAttachmentStorage-) | 获取或设置自定义附件存储数据。可以为 null。 |
| [setEmbeddedMessage(MessageObject value)](#setEmbeddedMessage-com.aspose.email.MessageObject-) | 获取或设置嵌入的消息对象存储（如果存在）。可以为 null。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageObjectAttachmentEntity() {#MessageObjectAttachmentEntity--}
```
public MessageObjectAttachmentEntity()
```


初始化 [MessageObjectAttachmentEntity](../../com.aspose.email/messageobjectattachmententity) 类的新实例。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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


获取或设置自定义附件存储数据。可以为 null。

值：自定义附件存储数据。

--------------------

与 MessageObjectAttachmentEntity.EmbeddedMessage (\#getEmbeddedMessage.getEmbeddedMessage/\#setEmbeddedMessage(MessageObject).setEmbeddedMessage(MessageObject)) 互斥，或者两者都可以为 null。

**Returns:**
[CustomAttachmentStorage](../../com.aspose.email/customattachmentstorage)
### getEmbeddedMessage() {#getEmbeddedMessage--}
```
public final MessageObject getEmbeddedMessage()
```


获取或设置嵌入的消息对象存储（如果存在）。可以为 null。

值：嵌入的消息。

--------------------

与 MessageObjectAttachmentEntity.CustomAttachmentStorageData (\#getCustomAttachmentStorageData.getCustomAttachmentStorageData/\#setCustomAttachmentStorageData(CustomAttachmentStorage).setCustomAttachmentStorageData(CustomAttachmentStorage)) 互斥，或者两者都可以为 null。

**Returns:**
[MessageObject](../../com.aspose.email/messageobject)
### getProperties() {#getProperties--}
```
public final MessageObjectPropertiesCollection getProperties()
```


获取附件属性。

值：属性集合。

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


获取或设置自定义附件存储数据。可以为 null。

值：自定义附件存储数据。

--------------------

与 MessageObjectAttachmentEntity.EmbeddedMessage (\#getEmbeddedMessage.getEmbeddedMessage/\#setEmbeddedMessage(MessageObject).setEmbeddedMessage(MessageObject)) 互斥，或者两者都可以为 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CustomAttachmentStorage](../../com.aspose.email/customattachmentstorage) |  |

### setEmbeddedMessage(MessageObject value) {#setEmbeddedMessage-com.aspose.email.MessageObject-}
```
public final void setEmbeddedMessage(MessageObject value)
```


获取或设置嵌入的消息对象存储（如果存在）。可以为 null。

值：嵌入的消息。

--------------------

与 MessageObjectAttachmentEntity.CustomAttachmentStorageData (\#getCustomAttachmentStorageData.getCustomAttachmentStorageData/\#setCustomAttachmentStorageData(CustomAttachmentStorage).setCustomAttachmentStorageData(CustomAttachmentStorage)) 互斥，或者两者都可以为 null。

**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

