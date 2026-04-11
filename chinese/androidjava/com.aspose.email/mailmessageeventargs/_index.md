---
title: MailMessageEventArgs
second_title: Aspose.Email for Android via Java API 参考
description: 提供 MessageSending 和 MessageSent 事件的数据。
type: docs
weight: 194
url: /zh/androidjava/com.aspose.email/mailmessageeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class MailMessageEventArgs extends System.EventArgs
```

提供 MessageSending 和 MessageSent 事件的数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MailMessageEventArgs(MailMessage message)](#MailMessageEventArgs-com.aspose.email.MailMessage-) | 初始化一个新的 [MailMessageEventArgs](../../com.aspose.email/mailmessageeventargs) 类的实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Empty](#Empty) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessage()](#getMessage--) | 获取发送的邮件。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailMessageEventArgs(MailMessage message) {#MailMessageEventArgs-com.aspose.email.MailMessage-}
```
public MailMessageEventArgs(MailMessage message)
```


初始化一个新的 [MailMessageEventArgs](../../com.aspose.email/mailmessageeventargs) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | 消息。 |

### Empty {#Empty}
```
public static final System.EventArgs Empty
```


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
### getMessage() {#getMessage--}
```
public final MailMessage getMessage()
```


获取发送的邮件。

值：MailMessage。

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
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

