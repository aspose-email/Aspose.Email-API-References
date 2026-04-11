---
title: ReplyMessageBuilder
second_title: Aspose.Email for Android via Java API 参考
description: 提供创建和格式化回复消息的功能。
type: docs
weight: 373
url: /zh/androidjava/com.aspose.email/replymessagebuilder/
---

**Inheritance:**
java.lang.Object，[com.aspose.email.ResponseMessageBuilder](../../com.aspose.email/responsemessagebuilder)
```
public class ReplyMessageBuilder extends ResponseMessageBuilder
```

提供创建和格式化回复消息的功能。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ReplyMessageBuilder()](#ReplyMessageBuilder--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [buildResponse(MailMessage msg)](#buildResponse-com.aspose.email.MailMessage-) | 构建回复消息。 |
| [buildResponse(MapiMessage msg)](#buildResponse-com.aspose.email.MapiMessage-) | 构建回复消息。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdditionMode()](#getAdditionMode--) | 获取或设置响应消息的格式。 |
| [getClass()](#getClass--) |  |
| [getReplyAll()](#getReplyAll--) | 在回复消息中提供自动添加收件人的功能。 |
| [getResponseText()](#getResponseText--) | 获取或设置响应消息的正文。 |
| [getSender()](#getSender--) | 获取或设置发送响应消息的地址。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdditionMode(int value)](#setAdditionMode-int-) | 获取或设置响应消息的格式。 |
| [setReplyAll(boolean value)](#setReplyAll-boolean-) | 在回复消息中提供自动添加收件人的功能。 |
| [setResponseText(String value)](#setResponseText-java.lang.String-) | 获取或设置响应消息的正文。 |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | 获取或设置发送响应消息的地址。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReplyMessageBuilder() {#ReplyMessageBuilder--}
```
public ReplyMessageBuilder()
```


### buildResponse(MailMessage msg) {#buildResponse-com.aspose.email.MailMessage-}
```
public MailMessage buildResponse(MailMessage msg)
```


构建回复消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| msg | [MailMessage](../../com.aspose.email/mailmessage) | 原始消息 [MailMessage](../../com.aspose.email/mailmessage)。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Resultant message [MailMessage](../../com.aspose.email/mailmessage).
### buildResponse(MapiMessage msg) {#buildResponse-com.aspose.email.MapiMessage-}
```
public MapiMessage buildResponse(MapiMessage msg)
```


构建回复消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | 原始消息 [MapiMessage](../../com.aspose.email/mapimessage)。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Resultant message [MapiMessage](../../com.aspose.email/mapimessage).
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
### getAdditionMode() {#getAdditionMode--}
```
public final int getAdditionMode()
```


获取或设置响应消息的格式。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getReplyAll() {#getReplyAll--}
```
public final boolean getReplyAll()
```


在回复消息中提供自动添加收件人的功能。

**Returns:**
boolean
### getResponseText() {#getResponseText--}
```
public final String getResponseText()
```


获取或设置响应消息的正文。

--------------------

如果原始消息正文的类型分别为 HTML 或 RTF，则可以包含 html 标签或 rtf 关键字。

**Returns:**
java.lang.String
### getSender() {#getSender--}
```
public final MailAddress getSender()
```


获取或设置发送响应消息的地址。

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


获取或设置响应消息的格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setReplyAll(boolean value) {#setReplyAll-boolean-}
```
public final void setReplyAll(boolean value)
```


在回复消息中提供自动添加收件人的功能。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setResponseText(String value) {#setResponseText-java.lang.String-}
```
public final void setResponseText(String value)
```


获取或设置响应消息的正文。

--------------------

如果原始消息正文的类型分别为 HTML 或 RTF，则可以包含 html 标签或 rtf 关键字。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public final void setSender(MailAddress value)
```


获取或设置发送响应消息的地址。

**Parameters:**
| 参数 | 类型 | 描述 |
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

