---
title: ExchangeTask
second_title: Aspose.Email for Java API Reference
description: Represents the exchange task information.
type: docs
weight: 229
url: /java/com.aspose.email/exchangetask/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.Task](../../com.aspose.email/task)
```
public final class ExchangeTask extends Task
```

Represents the exchange task information.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExchangeTask()](#ExchangeTask--) | Initializes a new instance of the [ExchangeTask](../../com.aspose.email/exchangetask) class. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Release all resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActualWork()](#getActualWork--) | Gets or sets an actual amount of time that is spent on a task (minutes). |
| [getAttachments()](#getAttachments--) | Gets or sets a collection of file attached to the task. |
| [getAttendees()](#getAttendees--) | Gets or sets the attendees. |
| [getBillingInformation()](#getBillingInformation--) | Gets or sets a billing information for the task. |
| [getBody()](#getBody--) | Gets or sets a task body. |
| [getClass()](#getClass--) |  |
| [getCompanies()](#getCompanies--) | Gets or sets a collection of companies that are associated with a task. |
| [getCompletionDate()](#getCompletionDate--) | Gets or sets the date when the user completed work on the task. |
| [getDueDate()](#getDueDate--) | Gets or sets the date by which the user expects work on the task to be complete. |
| [getMethod()](#getMethod--) | Gets or sets iTIP methods associated with an task. |
| [getMileage()](#getMileage--) | Gets or sets a mileage for a task. |
| [getOrganizer()](#getOrganizer--) | Gets or sets the organizer. |
| [getPercentComplete()](#getPercentComplete--) | Gets or sets a pecent of task completion. |
| [getPriority()](#getPriority--) | Gets or sets a task priority. |
| [getRecurrencePattern()](#getRecurrencePattern--) | Gets or sets a recurrence information for a recurring task. |
| [getRelatedTo()](#getRelatedTo--) | Gets or sets a related UID |
| [getReminderDate()](#getReminderDate--) | Gets or sets a task reminder date. |
| [getSequenceId()](#getSequenceId--) | Gets or sets the sequence id. |
| [getStartDate()](#getStartDate--) | Gets or sets a start date of task. |
| [getStatus()](#getStatus--) | Gets or sets a task status. |
| [getSubject()](#getSubject--) | Gets or sets a task subject. |
| [getTotalWork()](#getTotalWork--) | Gets or sets a total amount of work that the user expects to work on a task. |
| [getUniqueId()](#getUniqueId--) | Gets or sets unique identifier |
| [getUniqueUri()](#getUniqueUri--) | Gets or sets an unique uri of the task. |
| [hashCode()](#hashCode--) |  |
| [isBodyHtml()](#isBodyHtml--) | Gets or sets a value indicating whether the task body is html-formatted. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [request()](#request--) | Requests the object. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves current object to the given stream using MSG format. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves current object to the given stream using specified format. |
| [save(String filePath)](#save-java.lang.String-) | Saves current object into file using MSG format. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves current object into file using specified format. |
| [setActualWork(int value)](#setActualWork-int-) | Gets or sets an actual amount of time that is spent on a task (minutes). |
| [setAttachments(AttachmentCollection value)](#setAttachments-com.aspose.email.AttachmentCollection-) | Gets or sets a collection of file attached to the task. |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | Gets or sets the attendees. |
| [setBillingInformation(String value)](#setBillingInformation-java.lang.String-) | Gets or sets a billing information for the task. |
| [setBody(String value)](#setBody-java.lang.String-) | Gets or sets a task body. |
| [setBodyHtml(boolean value)](#setBodyHtml-boolean-) | Gets or sets a value indicating whether the task body is html-formatted. |
| [setCompanies(System.Collections.Specialized.StringCollection value)](#setCompanies-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets a collection of companies that are associated with a task. |
| [setCompletionDate(Date value)](#setCompletionDate-java.util.Date-) | Gets or sets the date when the user completed work on the task. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Gets or sets the date by which the user expects work on the task to be complete. |
| [setMethod(int value)](#setMethod-int-) | Gets or sets iTIP methods associated with an task. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Gets or sets a mileage for a task. |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | Gets or sets the organizer. |
| [setPercentComplete(float value)](#setPercentComplete-float-) | Gets or sets a pecent of task completion. |
| [setPriority(int value)](#setPriority-int-) | Gets or sets a task priority. |
| [setRecurrencePattern(RecurrencePattern value)](#setRecurrencePattern-com.aspose.email.RecurrencePattern-) | Gets or sets a recurrence information for a recurring task. |
| [setRelatedTo(String value)](#setRelatedTo-java.lang.String-) | Gets or sets a related UID |
| [setReminderDate(Date value)](#setReminderDate-java.util.Date-) | Gets or sets a task reminder date. |
| [setSequenceId(int value)](#setSequenceId-int-) | Gets or sets the sequence id. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets a start date of task. |
| [setStatus(int value)](#setStatus-int-) | Gets or sets a task status. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets a task subject. |
| [setTotalWork(int value)](#setTotalWork-int-) | Gets or sets a total amount of work that the user expects to work on a task. |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | Gets or sets unique identifier |
| [setUniqueUri(String value)](#setUniqueUri-java.lang.String-) | Gets or sets an unique uri of the task. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExchangeTask() {#ExchangeTask--}
```
public ExchangeTask()
```


Initializes a new instance of the [ExchangeTask](../../com.aspose.email/exchangetask) class.

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Release all resources.

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
### getActualWork() {#getActualWork--}
```
public final int getActualWork()
```


Gets or sets an actual amount of time that is spent on a task (minutes).

**Returns:**
int
### getAttachments() {#getAttachments--}
```
public final AttachmentCollection getAttachments()
```


Gets or sets a collection of file attached to the task.

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getAttendees() {#getAttendees--}
```
public final MailAddressCollection getAttendees()
```


Gets or sets the attendees.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getBillingInformation() {#getBillingInformation--}
```
public final String getBillingInformation()
```


Gets or sets a billing information for the task.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public final String getBody()
```


Gets or sets a task body.

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


Gets or sets a collection of companies that are associated with a task.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getCompletionDate() {#getCompletionDate--}
```
public final Date getCompletionDate()
```


Gets or sets the date when the user completed work on the task.

**Returns:**
java.util.Date
### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


Gets or sets the date by which the user expects work on the task to be complete.

**Returns:**
java.util.Date
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Gets or sets iTIP methods associated with an task.

**Returns:**
int
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Gets or sets a mileage for a task.

**Returns:**
java.lang.String
### getOrganizer() {#getOrganizer--}
```
public final MailAddress getOrganizer()
```


Gets or sets the organizer.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getPercentComplete() {#getPercentComplete--}
```
public final float getPercentComplete()
```


Gets or sets a pecent of task completion.

**Returns:**
float
### getPriority() {#getPriority--}
```
public final int getPriority()
```


Gets or sets a task priority.

**Returns:**
int
### getRecurrencePattern() {#getRecurrencePattern--}
```
public final RecurrencePattern getRecurrencePattern()
```


Gets or sets a recurrence information for a recurring task.

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern)
### getRelatedTo() {#getRelatedTo--}
```
public final String getRelatedTo()
```


Gets or sets a related UID

**Returns:**
java.lang.String
### getReminderDate() {#getReminderDate--}
```
public final Date getReminderDate()
```


Gets or sets a task reminder date.

**Returns:**
java.util.Date
### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


Gets or sets the sequence id.

Value: The sequence id.

**Returns:**
int
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets a start date of task.

**Returns:**
java.util.Date
### getStatus() {#getStatus--}
```
public final int getStatus()
```


Gets or sets a task status.

**Returns:**
int
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets a task subject.

**Returns:**
java.lang.String
### getTotalWork() {#getTotalWork--}
```
public final int getTotalWork()
```


Gets or sets a total amount of work that the user expects to work on a task.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Gets or sets unique identifier

**Returns:**
java.lang.String
### getUniqueUri() {#getUniqueUri--}
```
public final String getUniqueUri()
```


Gets or sets an unique uri of the task.

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


Gets or sets a value indicating whether the task body is html-formatted.

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


Requests the object.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves current object to the given stream using MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to. |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int saveFormat)
```


Saves current object to the given stream using specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to. |
| saveFormat | int | A save format. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Saves current object into file using MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file name. |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public void save(String filePath, int saveFormat)
```


Saves current object into file using specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file name. |
| saveFormat | int | A save format. |

### setActualWork(int value) {#setActualWork-int-}
```
public final void setActualWork(int value)
```


Gets or sets an actual amount of time that is spent on a task (minutes).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setAttachments(AttachmentCollection value) {#setAttachments-com.aspose.email.AttachmentCollection-}
```
public final void setAttachments(AttachmentCollection value)
```


Gets or sets a collection of file attached to the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AttachmentCollection](../../com.aspose.email/attachmentcollection) |  |

### setAttendees(MailAddressCollection value) {#setAttendees-com.aspose.email.MailAddressCollection-}
```
public final void setAttendees(MailAddressCollection value)
```


Gets or sets the attendees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setBillingInformation(String value) {#setBillingInformation-java.lang.String-}
```
public final void setBillingInformation(String value)
```


Gets or sets a billing information for the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Gets or sets a task body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyHtml(boolean value) {#setBodyHtml-boolean-}
```
public final void setBodyHtml(boolean value)
```


Gets or sets a value indicating whether the task body is html-formatted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setCompanies(System.Collections.Specialized.StringCollection value) {#setCompanies-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setCompanies(System.Collections.Specialized.StringCollection value)
```


Gets or sets a collection of companies that are associated with a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### setCompletionDate(Date value) {#setCompletionDate-java.util.Date-}
```
public final void setCompletionDate(Date value)
```


Gets or sets the date when the user completed work on the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


Gets or sets the date by which the user expects work on the task to be complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Gets or sets iTIP methods associated with an task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Gets or sets a mileage for a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setOrganizer(MailAddress value) {#setOrganizer-com.aspose.email.MailAddress-}
```
public final void setOrganizer(MailAddress value)
```


Gets or sets the organizer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setPercentComplete(float value) {#setPercentComplete-float-}
```
public final void setPercentComplete(float value)
```


Gets or sets a pecent of task completion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setPriority(int value) {#setPriority-int-}
```
public final void setPriority(int value)
```


Gets or sets a task priority.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRecurrencePattern(RecurrencePattern value) {#setRecurrencePattern-com.aspose.email.RecurrencePattern-}
```
public final void setRecurrencePattern(RecurrencePattern value)
```


Gets or sets a recurrence information for a recurring task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RecurrencePattern](../../com.aspose.email/recurrencepattern) |  |

### setRelatedTo(String value) {#setRelatedTo-java.lang.String-}
```
public final void setRelatedTo(String value)
```


Gets or sets a related UID

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setReminderDate(Date value) {#setReminderDate-java.util.Date-}
```
public final void setReminderDate(Date value)
```


Gets or sets a task reminder date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setSequenceId(int value) {#setSequenceId-int-}
```
public final void setSequenceId(int value)
```


Gets or sets the sequence id.

Value: The sequence id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets a start date of task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Gets or sets a task status.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets a task subject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTotalWork(int value) {#setTotalWork-int-}
```
public final void setTotalWork(int value)
```


Gets or sets a total amount of work that the user expects to work on a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


Gets or sets unique identifier

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUniqueUri(String value) {#setUniqueUri-java.lang.String-}
```
public final void setUniqueUri(String value)
```


Gets or sets an unique uri of the task.

**Parameters:**
| Parameter | Type | Description |
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

