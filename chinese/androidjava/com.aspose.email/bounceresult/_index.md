---
title: BounceResult
second_title: Aspose.Email for Android via Java API 参考
description: 表示消息检查的结果为退回消息。
type: docs
weight: 60
url: /zh/androidjava/com.aspose.email/bounceresult/
---

**Inheritance:**
java.lang.Object
```
public class BounceResult
```

表示消息检查的结果为退回消息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BounceResult()](#BounceResult--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | 指示尝试投递消息后执行的操作。 |
| [getClass()](#getClass--) |  |
| [getOriginalMessage()](#getOriginalMessage--) | 包含原始消息。 |
| [getReason()](#getReason--) | 对于“失败”或“延迟”的收件人，包含邮件传输系统发出的实际诊断代码。 |
| [getRecipient()](#getRecipient--) | 指示发送方在发出投递失败报告的消息中指定的原始收件人地址。 |
| [getStatus()](#getStatus--) | 包含一个与传输方式无关的状态码，用于指示该收件人的消息投递状态。 |
| [hashCode()](#hashCode--) |  |
| [isBounced()](#isBounced--) | 如果电子邮件是投递失败或投递延迟报告，则为 True。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BounceResult() {#BounceResult--}
```
public BounceResult()
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
### getAction() {#getAction--}
```
public final int getAction()
```


指示尝试投递消息后执行的操作。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOriginalMessage() {#getOriginalMessage--}
```
public final MailMessage getOriginalMessage()
```


包含原始消息。

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### getReason() {#getReason--}
```
public final String getReason()
```


对于“失败”或“延迟”的收件人，包含邮件传输系统发出的实际诊断代码。

**Returns:**
java.lang.String
### getRecipient() {#getRecipient--}
```
public final String getRecipient()
```


指示发送方在发出投递失败报告的消息中指定的原始收件人地址。

**Returns:**
java.lang.String
### getStatus() {#getStatus--}
```
public final String getStatus()
```


包含一个与传输方式无关的状态码，用于指示该收件人的消息投递状态。

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBounced() {#isBounced--}
```
public final boolean isBounced()
```


如果电子邮件是投递失败或投递延迟报告，则为 True。

**Returns:**
boolean
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

