---
title: OlmMessageInfo
second_title: Aspose.Email for Android via Java API 参考
description: 表示 OLM 存储中关于消息的信息。
type: docs
weight: 338
url: /zh/androidjava/com.aspose.email/olmmessageinfo/
---

**Inheritance:**
java.lang.Object
```
public class OlmMessageInfo
```

表示 OLM 存储中关于消息的信息。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | 获取消息的日期。 |
| [getFrom()](#getFrom--) | 获取发件人地址。 |
| [getMessageClass()](#getMessageClass--) | 获取区分大小写的字符串，以标识发送者定义的消息类，例如 IPM.Note。 |
| [getModifiedDate()](#getModifiedDate--) | 获取消息的日期。 |
| [getSubject()](#getSubject--) | 获取消息主题。 |
| [getTo()](#getTo--) | 获取包含消息收件人的地址集合。 |
| [hasAttachments()](#hasAttachments--) | 获取或设置一个值，指示消息是否有附件。 |
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
### getDate() {#getDate--}
```
public final Date getDate()
```


获取消息的日期。

**Returns:**
java.util.Date
### getFrom() {#getFrom--}
```
public final MapiElectronicAddress getFrom()
```


获取发件人地址。

**Returns:**
[MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress)
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


获取区分大小写的字符串，用于标识发送者自定义的消息类，例如 IPM.Note。消息类指定消息的类型、目的或内容。

**Returns:**
java.lang.String
### getModifiedDate() {#getModifiedDate--}
```
public final Date getModifiedDate()
```


获取消息的日期。

**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public final String getSubject()
```


获取消息主题。

**Returns:**
java.lang.String
### getTo() {#getTo--}
```
public final List<MapiElectronicAddress> getTo()
```


获取包含消息收件人的地址集合。

**Returns:**
java.util.List<com.aspose.email.MapiElectronicAddress>
### hasAttachments() {#hasAttachments--}
```
public final boolean hasAttachments()
```


获取或设置一个值，指示消息是否有附件。

值： true 如果此实例有附件；否则， false。

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

