---
title: MessageObject
second_title: Aspose.Email for Android via Java API 参考
description: 表示 Outlook 消息对象。
type: docs
weight: 309
url: /zh/androidjava/com.aspose.email/messageobject/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMessageObjectPropertyContainer](../../com.aspose.email/imessageobjectpropertycontainer)
```
public final class MessageObject implements IMessageObjectPropertyContainer
```

表示 Outlook 邮件对象。评估限制：加载消息时仅读取 1 个附件和 1 个收件人，保存消息时将添加水印。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MessageObject(InputStream stream, int loadFormat)](#MessageObject-java.io.InputStream-int-) | 初始化 [MessageObject](../../com.aspose.email/messageobject) 类的新实例。 |
| [MessageObject(String fileName, int loadFormat)](#MessageObject-java.lang.String-int-) | 初始化 [MessageObject](../../com.aspose.email/messageobject) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | 获取 [MessageObject](../../com.aspose.email/messageobject) 的附件。 |
| [getClass()](#getClass--) |  |
| [getCodepage()](#getCodepage--) | 获取在使用 [MapiType.PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8) 类型时用于对字符串属性进行编码/解码的代码页。 |
| [getIdForNamedProperty()](#getIdForNamedProperty--) | 获取用于命名属性的 ID，命名属性是特殊属性，其 ID 应在范围 [0x8000,0xfffe] 内，且从 0x8000 开始顺序对齐。 |
| [getProperties()](#getProperties--) | 获取 [MessageObject](../../com.aspose.email/messageobject) 的属性。 |
| [getRecipients()](#getRecipients--) | 获取 [MessageObject](../../com.aspose.email/messageobject) 的收件人。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 将当前消息对象保存到指定的流中。 |
| [save(String fileName, int format)](#save-java.lang.String-int-) | 将当前消息对象保存到指定的文件中。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageObject(InputStream stream, int loadFormat) {#MessageObject-java.io.InputStream-int-}
```
public MessageObject(InputStream stream, int loadFormat)
```


初始化 [MessageObject](../../com.aspose.email/messageobject) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于初始化此对象的流。 |
| loadFormat | int | 消息对象存储的源格式。 |

### MessageObject(String fileName, int loadFormat) {#MessageObject-java.lang.String-int-}
```
public MessageObject(String fileName, int loadFormat)
```


初始化 [MessageObject](../../com.aspose.email/messageobject) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 要读取的文件名。 |
|  | loadFormat | int | 消息对象存储的源格式。 |

--------------------

此外，可能会抛出与 File\#open(String,int).open(String,int) 调用相同的一组异常。 |

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
### getAttachments() {#getAttachments--}
```
public final MessageObjectAttachmentsCollection getAttachments()
```


获取 [MessageObject](../../com.aspose.email/messageobject) 的附件。

值：附件。

**Returns:**
[MessageObjectAttachmentsCollection](../../com.aspose.email/messageobjectattachmentscollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodepage() {#getCodepage--}
```
public final int getCodepage()
```


获取在使用 [MapiType.PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8) 类型时用于对字符串属性进行编码/解码的代码页。

值：代码页。

**Returns:**
int
### getIdForNamedProperty() {#getIdForNamedProperty--}
```
public final int getIdForNamedProperty()
```


获取用于命名属性的 ID，命名属性是特殊属性，其 ID 应在范围 [0x8000,0xfffe] 内，从 0x8000 开始顺序对齐。使用此方法查找可用的 ID，因为自行计算可能很困难。

**Returns:**
int - 命名属性的可用 ID。
### getProperties() {#getProperties--}
```
public final MessageObjectPropertiesCollection getProperties()
```


获取 [MessageObject](../../com.aspose.email/messageobject) 的属性。

值：属性。

**Returns:**
[MessageObjectPropertiesCollection](../../com.aspose.email/messageobjectpropertiescollection)
### getRecipients() {#getRecipients--}
```
public final MessageObjectRecipientsCollection getRecipients()
```


获取 [MessageObject](../../com.aspose.email/messageobject) 的收件人。

值：收件人。

**Returns:**
[MessageObjectRecipientsCollection](../../com.aspose.email/messageobjectrecipientscollection)
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




### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


将当前消息对象保存到指定的流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 要写入的流。 |
| 格式 | int | 输出数据的格式。 |

### save(String fileName, int format) {#save-java.lang.String-int-}
```
public final void save(String fileName, int format)
```


将当前消息对象保存到指定的文件中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
|  | 格式 | int | 输出数据的格式。 |

--------------------

此外，可能会抛出与 File\#openWrite(String).openWrite(String) 调用相同的一组异常。 |

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

