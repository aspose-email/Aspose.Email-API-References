---
title: 任务
second_title: Aspose.Email for Android via Java API 参考
description: 表示 Exchange 任务信息。
type: docs
weight: 397
url: /zh/androidjava/com.aspose.email/task/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Task implements System.IDisposable, Closeable
```

表示 Exchange 任务信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Task()](#Task--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | 释放所有资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | 获取或设置附加到任务的文件集合。 |
| [getAttendees()](#getAttendees--) | 获取或设置与会者。 |
| [getBody()](#getBody--) | 获取或设置任务正文。 |
| [getClass()](#getClass--) |  |
| [getDueDate()](#getDueDate--) | 获取或设置用户期望完成任务工作的日期。 |
| [getMethod()](#getMethod--) | 获取或设置与任务关联的 iTIP 方法。 |
| [getOrganizer()](#getOrganizer--) | 获取或设置组织者。 |
| [getPercentComplete()](#getPercentComplete--) | 获取或设置任务完成的百分比。 |
| [getPriority()](#getPriority--) | 获取或设置任务优先级。 |
| [getRelatedTo()](#getRelatedTo--) | 获取或设置相关的 UID |
| [getSequenceId()](#getSequenceId--) | 获取或设置序列 ID。 |
| [getStartDate()](#getStartDate--) | 获取或设置任务的开始日期。 |
| [getSubject()](#getSubject--) | 获取或设置任务主题。 |
| [getUniqueId()](#getUniqueId--) | 获取或设置唯一标识符 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [request()](#request--) | 请求对象。 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 使用 MSG 格式将当前对象保存到给定的流。 |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | 使用指定格式将当前对象保存到给定的流。 |
| [save(String filePath)](#save-java.lang.String-) | 使用 MSG 格式将当前对象保存到文件。 |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | 使用指定格式将当前对象保存到文件。 |
| [setAttachments(AttachmentCollection value)](#setAttachments-com.aspose.email.AttachmentCollection-) | 获取或设置附加到任务的文件集合。 |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | 获取或设置与会者。 |
| [setBody(String value)](#setBody-java.lang.String-) | 获取或设置任务正文。 |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | 获取或设置用户期望完成任务工作的日期。 |
| [setMethod(int value)](#setMethod-int-) | 获取或设置与任务关联的 iTIP 方法。 |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | 获取或设置组织者。 |
| [setPercentComplete(float value)](#setPercentComplete-float-) | 获取或设置任务完成的百分比。 |
| [setPriority(int value)](#setPriority-int-) | 获取或设置任务优先级。 |
| [setRelatedTo(String value)](#setRelatedTo-java.lang.String-) | 获取或设置相关的 UID |
| [setSequenceId(int value)](#setSequenceId-int-) | 获取或设置序列 ID。 |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | 获取或设置任务的开始日期。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 获取或设置任务主题。 |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | 获取或设置唯一标识符 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Task() {#Task--}
```
public Task()
```


### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


释放所有资源。

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
public final AttachmentCollection getAttachments()
```


获取或设置附加到任务的文件集合。

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getAttendees() {#getAttendees--}
```
public final MailAddressCollection getAttendees()
```


获取或设置与会者。

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getBody() {#getBody--}
```
public final String getBody()
```


获取或设置任务正文。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


获取或设置用户期望完成任务工作的日期。

**Returns:**
java.util.Date
### getMethod() {#getMethod--}
```
public final int getMethod()
```


获取或设置与任务关联的 iTIP 方法。

**Returns:**
int
### getOrganizer() {#getOrganizer--}
```
public final MailAddress getOrganizer()
```


获取或设置组织者。

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getPercentComplete() {#getPercentComplete--}
```
public final float getPercentComplete()
```


获取或设置任务完成的百分比。

**Returns:**
float
### getPriority() {#getPriority--}
```
public final int getPriority()
```


获取或设置任务优先级。

**Returns:**
int
### getRelatedTo() {#getRelatedTo--}
```
public final String getRelatedTo()
```


获取或设置相关的 UID

**Returns:**
java.lang.String
### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


获取或设置序列 ID。

值：序列 ID。

**Returns:**
int
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


获取或设置任务的开始日期。

**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public final String getSubject()
```


获取或设置任务主题。

**Returns:**
java.lang.String
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


获取或设置唯一标识符

**Returns:**
java.lang.String
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




### request() {#request--}
```
public final AlternateView request()
```


请求对象。

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


使用 MSG 格式将当前对象保存到给定的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存的流。 |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int saveFormat)
```


使用指定格式将当前对象保存到给定的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存的流。 |
| saveFormat | int | 保存格式。 |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


使用 MSG 格式将当前对象保存到文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件名。 |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public void save(String filePath, int saveFormat)
```


使用指定格式将当前对象保存到文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件名。 |
| saveFormat | int | 保存格式。 |

### setAttachments(AttachmentCollection value) {#setAttachments-com.aspose.email.AttachmentCollection-}
```
public final void setAttachments(AttachmentCollection value)
```


获取或设置附加到任务的文件集合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AttachmentCollection](../../com.aspose.email/attachmentcollection) |  |

### setAttendees(MailAddressCollection value) {#setAttendees-com.aspose.email.MailAddressCollection-}
```
public final void setAttendees(MailAddressCollection value)
```


获取或设置与会者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


获取或设置任务正文。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


获取或设置用户期望完成任务工作的日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


获取或设置与任务关联的 iTIP 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setOrganizer(MailAddress value) {#setOrganizer-com.aspose.email.MailAddress-}
```
public final void setOrganizer(MailAddress value)
```


获取或设置组织者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setPercentComplete(float value) {#setPercentComplete-float-}
```
public final void setPercentComplete(float value)
```


获取或设置任务完成的百分比。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setPriority(int value) {#setPriority-int-}
```
public final void setPriority(int value)
```


获取或设置任务优先级。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setRelatedTo(String value) {#setRelatedTo-java.lang.String-}
```
public final void setRelatedTo(String value)
```


获取或设置相关的 UID

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSequenceId(int value) {#setSequenceId-int-}
```
public final void setSequenceId(int value)
```


获取或设置序列 ID。

值：序列 ID。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


获取或设置任务的开始日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


获取或设置任务主题。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


获取或设置唯一标识符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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

