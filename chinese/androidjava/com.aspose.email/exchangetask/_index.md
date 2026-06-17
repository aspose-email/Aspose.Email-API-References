---
title: ExchangeTask
second_title: Aspose.Email for Android via Java API 参考
description: 表示 Exchange 任务信息。
type: docs
weight: 127
url: /zh/androidjava/com.aspose.email/exchangetask/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.Task](../../com.aspose.email/task)
```
public final class ExchangeTask extends Task
```

表示 Exchange 任务信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExchangeTask()](#ExchangeTask--) | 初始化 [ExchangeTask](../../com.aspose.email/exchangetask) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | 释放所有资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActualWork()](#getActualWork--) | 获取或设置任务实际花费的时间（分钟）。 |
| [getAttachments()](#getAttachments--) | 获取或设置附加到任务的文件集合。 |
| [getAttendees()](#getAttendees--) | 获取或设置与会者。 |
| [getBillingInformation()](#getBillingInformation--) | 获取或设置任务的计费信息。 |
| [getBody()](#getBody--) | 获取或设置任务正文。 |
| [getClass()](#getClass--) |  |
| [getCompanies()](#getCompanies--) | 获取或设置与任务关联的公司集合。 |
| [getCompletionDate()](#getCompletionDate--) | 获取或设置用户完成任务工作的日期。 |
| [getDueDate()](#getDueDate--) | 获取或设置用户期望完成任务工作的日期。 |
| [getMethod()](#getMethod--) | 获取或设置与任务关联的 iTIP 方法。 |
| [getMileage()](#getMileage--) | 获取或设置任务的里程数。 |
| [getOrganizer()](#getOrganizer--) | 获取或设置组织者。 |
| [getPercentComplete()](#getPercentComplete--) | 获取或设置任务完成的百分比。 |
| [getPriority()](#getPriority--) | 获取或设置任务优先级。 |
| [getRecurrencePattern()](#getRecurrencePattern--) | 获取或设置循环任务的重复信息。 |
| [getRelatedTo()](#getRelatedTo--) | 获取或设置相关的 UID |
| [getReminderDate()](#getReminderDate--) | 获取或设置任务提醒日期。 |
| [getSequenceId()](#getSequenceId--) | 获取或设置序列 ID。 |
| [getStartDate()](#getStartDate--) | 获取或设置任务的开始日期。 |
| [getStatus()](#getStatus--) | 获取或设置任务状态。 |
| [getSubject()](#getSubject--) | 获取或设置任务主题。 |
| [getTotalWork()](#getTotalWork--) | 获取或设置用户预计在任务上完成的工作总量。 |
| [getUniqueId()](#getUniqueId--) | 获取或设置唯一标识符 |
| [getUniqueUri()](#getUniqueUri--) | 获取或设置任务的唯一 URI。 |
| [hashCode()](#hashCode--) |  |
| [isBodyHtml()](#isBodyHtml--) | 获取或设置指示任务正文是否为 HTML 格式的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [request()](#request--) | 请求对象。 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 使用 MSG 格式将当前对象保存到给定的流。 |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | 使用指定格式将当前对象保存到给定的流。 |
| [save(String filePath)](#save-java.lang.String-) | 使用 MSG 格式将当前对象保存到文件。 |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | 使用指定格式将当前对象保存到文件。 |
| [setActualWork(int value)](#setActualWork-int-) | 获取或设置任务实际花费的时间（分钟）。 |
| [setAttachments(AttachmentCollection value)](#setAttachments-com.aspose.email.AttachmentCollection-) | 获取或设置附加到任务的文件集合。 |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | 获取或设置与会者。 |
| [setBillingInformation(String value)](#setBillingInformation-java.lang.String-) | 获取或设置任务的计费信息。 |
| [setBody(String value)](#setBody-java.lang.String-) | 获取或设置任务正文。 |
| [setBodyHtml(boolean value)](#setBodyHtml-boolean-) | 获取或设置指示任务正文是否为 HTML 格式的值。 |
| [setCompanies(System.Collections.Specialized.StringCollection value)](#setCompanies-com.aspose.ms.System.Collections.Specialized.StringCollection-) | 获取或设置与任务关联的公司集合。 |
| [setCompletionDate(Date value)](#setCompletionDate-java.util.Date-) | 获取或设置用户完成任务工作的日期。 |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | 获取或设置用户期望完成任务工作的日期。 |
| [setMethod(int value)](#setMethod-int-) | 获取或设置与任务关联的 iTIP 方法。 |
| [setMileage(String value)](#setMileage-java.lang.String-) | 获取或设置任务的里程数。 |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | 获取或设置组织者。 |
| [setPercentComplete(float value)](#setPercentComplete-float-) | 获取或设置任务完成的百分比。 |
| [setPriority(int value)](#setPriority-int-) | 获取或设置任务优先级。 |
| [setRecurrencePattern(RecurrencePattern value)](#setRecurrencePattern-com.aspose.email.RecurrencePattern-) | 获取或设置循环任务的重复信息。 |
| [setRelatedTo(String value)](#setRelatedTo-java.lang.String-) | 获取或设置相关的 UID |
| [setReminderDate(Date value)](#setReminderDate-java.util.Date-) | 获取或设置任务提醒日期。 |
| [setSequenceId(int value)](#setSequenceId-int-) | 获取或设置序列 ID。 |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | 获取或设置任务的开始日期。 |
| [setStatus(int value)](#setStatus-int-) | 获取或设置任务状态。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 获取或设置任务主题。 |
| [setTotalWork(int value)](#setTotalWork-int-) | 获取或设置用户预计在任务上完成的工作总量。 |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | 获取或设置唯一标识符 |
| [setUniqueUri(String value)](#setUniqueUri-java.lang.String-) | 获取或设置任务的唯一 URI。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExchangeTask() {#ExchangeTask--}
```
public ExchangeTask()
```


初始化 [ExchangeTask](../../com.aspose.email/exchangetask) 类的新实例。

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
### getActualWork() {#getActualWork--}
```
public final int getActualWork()
```


获取或设置任务实际花费的时间（分钟）。

**Returns:**
int
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
### getBillingInformation() {#getBillingInformation--}
```
public final String getBillingInformation()
```


获取或设置任务的计费信息。

**Returns:**
java.lang.String
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
### getCompanies() {#getCompanies--}
```
public final System.Collections.Specialized.StringCollection getCompanies()
```


获取或设置与任务关联的公司集合。

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getCompletionDate() {#getCompletionDate--}
```
public final Date getCompletionDate()
```


获取或设置用户完成任务工作的日期。

**Returns:**
java.util.Date
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
### getMileage() {#getMileage--}
```
public final String getMileage()
```


获取或设置任务的里程数。

**Returns:**
java.lang.String
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
### getRecurrencePattern() {#getRecurrencePattern--}
```
public final RecurrencePattern getRecurrencePattern()
```


获取或设置循环任务的重复信息。

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern)
### getRelatedTo() {#getRelatedTo--}
```
public final String getRelatedTo()
```


获取或设置相关的 UID

**Returns:**
java.lang.String
### getReminderDate() {#getReminderDate--}
```
public final Date getReminderDate()
```


获取或设置任务提醒日期。

**Returns:**
java.util.Date
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
### getStatus() {#getStatus--}
```
public final int getStatus()
```


获取或设置任务状态。

**Returns:**
int
### getSubject() {#getSubject--}
```
public final String getSubject()
```


获取或设置任务主题。

**Returns:**
java.lang.String
### getTotalWork() {#getTotalWork--}
```
public final int getTotalWork()
```


获取或设置用户预计在任务上完成的工作总量。

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


获取或设置唯一标识符

**Returns:**
java.lang.String
### getUniqueUri() {#getUniqueUri--}
```
public final String getUniqueUri()
```


获取或设置任务的唯一 URI。

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBodyHtml() {#isBodyHtml--}
```
public final boolean isBodyHtml()
```


获取或设置指示任务正文是否为 HTML 格式的值。

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

### setActualWork(int value) {#setActualWork-int-}
```
public final void setActualWork(int value)
```


获取或设置任务实际花费的时间（分钟）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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

### setBillingInformation(String value) {#setBillingInformation-java.lang.String-}
```
public final void setBillingInformation(String value)
```


获取或设置任务的计费信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


获取或设置任务正文。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyHtml(boolean value) {#setBodyHtml-boolean-}
```
public final void setBodyHtml(boolean value)
```


获取或设置指示任务正文是否为 HTML 格式的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setCompanies(System.Collections.Specialized.StringCollection value) {#setCompanies-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setCompanies(System.Collections.Specialized.StringCollection value)
```


获取或设置与任务关联的公司集合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### setCompletionDate(Date value) {#setCompletionDate-java.util.Date-}
```
public final void setCompletionDate(Date value)
```


获取或设置用户完成任务工作的日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

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

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


获取或设置任务的里程数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setRecurrencePattern(RecurrencePattern value) {#setRecurrencePattern-com.aspose.email.RecurrencePattern-}
```
public final void setRecurrencePattern(RecurrencePattern value)
```


获取或设置循环任务的重复信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RecurrencePattern](../../com.aspose.email/recurrencepattern) |  |

### setRelatedTo(String value) {#setRelatedTo-java.lang.String-}
```
public final void setRelatedTo(String value)
```


获取或设置相关的 UID

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setReminderDate(Date value) {#setReminderDate-java.util.Date-}
```
public final void setReminderDate(Date value)
```


获取或设置任务提醒日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

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

### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


获取或设置任务状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


获取或设置任务主题。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setTotalWork(int value) {#setTotalWork-int-}
```
public final void setTotalWork(int value)
```


获取或设置用户预计在任务上完成的工作总量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


获取或设置唯一标识符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setUniqueUri(String value) {#setUniqueUri-java.lang.String-}
```
public final void setUniqueUri(String value)
```


获取或设置任务的唯一 URI。

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

