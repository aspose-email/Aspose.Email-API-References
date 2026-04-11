---
title: MailboxConverter
second_title: Aspose.Email for Android via Java API 参考
description: 提供邮箱转换例程。
type: docs
weight: 201
url: /zh/androidjava/com.aspose.email/mailboxconverter/
---

**Inheritance:**
java.lang.Object
```
public class MailboxConverter
```

提供邮箱转换例程。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MailboxConverter()](#MailboxConverter--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [convertPersonalStorageToMbox(PersonalStorage personalStorage, MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)](#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-com.aspose.email.MboxStorageWriter-com.aspose.email.MessageAcceptanceCallback-) | 使用给定的 [MboxStorageWriter](../../com.aspose.email/mboxstoragewriter) 将 [PersonalStorage](../../com.aspose.email/personalstorage) 转换为 mbox 格式。 |
| [convertPersonalStorageToMbox(PersonalStorage personalStorage, String storagePath, MessageAcceptanceCallback acceptanceCallback)](#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MessageAcceptanceCallback-) | 使用给定的路径将 [PersonalStorage](../../com.aspose.email/personalstorage) 转换为 mbox 格式。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailboxConverter() {#MailboxConverter--}
```
public MailboxConverter()
```


### convertPersonalStorageToMbox(PersonalStorage personalStorage, MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback) {#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-com.aspose.email.MboxStorageWriter-com.aspose.email.MessageAcceptanceCallback-}
```
public static void convertPersonalStorageToMbox(PersonalStorage personalStorage, MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)
```


使用给定的 [MboxStorageWriter](../../com.aspose.email/mboxstoragewriter) 将 [PersonalStorage](../../com.aspose.email/personalstorage) 转换为 mbox 格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| personalStorage | [PersonalStorage](../../com.aspose.email/personalstorage) | 个人存储。 |
| mboxStorageWriter | [MboxStorageWriter](../../com.aspose.email/mboxstoragewriter) | mbox 存储写入器。 |
|  | acceptanceCallback | [MessageAcceptanceCallback](../../com.aspose.email/messageacceptancecallback) | 接受回调，可为 null。 |

--------------------

生成的 mbox 存储将仅包含一个包含所有消息的普通收件箱文件夹；如果需要保留存储的原始结构，请改用 XXX\_method。 |

### convertPersonalStorageToMbox(PersonalStorage personalStorage, String storagePath, MessageAcceptanceCallback acceptanceCallback) {#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MessageAcceptanceCallback-}
```
public static void convertPersonalStorageToMbox(PersonalStorage personalStorage, String storagePath, MessageAcceptanceCallback acceptanceCallback)
```


使用给定的路径将 [PersonalStorage](../../com.aspose.email/personalstorage) 转换为 mbox 格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| personalStorage | [PersonalStorage](../../com.aspose.email/personalstorage) | 个人存储。 |
| storagePath | java.lang.String | 保存 personalStorage 结构的路径。 |
|  | acceptanceCallback | [MessageAcceptanceCallback](../../com.aspose.email/messageacceptancecallback) | 接受回调，可为 null。 |

--------------------

生成的文件夹将包含 personalStorage 的完整副本，例如目录树将在磁盘上重新创建。 |

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

