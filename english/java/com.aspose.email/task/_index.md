---
title: Task
second_title: Aspose.Email for Java API Reference
description: Represents the exchange task information.
type: docs
weight: 672
url: /java/com.aspose.email/task/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Task implements System.IDisposable, Closeable
```

Represents the exchange task information.
## Constructors

| Constructor | Description |
| --- | --- |
| [Task()](#Task--) |  |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Release all resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | Gets or sets a collection of file attached to the task. |
| [getAttendees()](#getAttendees--) | Gets or sets the attendees. |
| [getBody()](#getBody--) | Gets or sets a task body. |
| [getClass()](#getClass--) |  |
| [getDueDate()](#getDueDate--) | Gets or sets the date by which the user expects work on the task to be complete. |
| [getMethod()](#getMethod--) | Gets or sets iTIP methods associated with an task. |
| [getOrganizer()](#getOrganizer--) | Gets or sets the organizer. |
| [getPercentComplete()](#getPercentComplete--) | Gets or sets a pecent of task completion. |
| [getPriority()](#getPriority--) | Gets or sets a task priority. |
| [getRelatedTo()](#getRelatedTo--) | Gets or sets a related UID |
| [getSequenceId()](#getSequenceId--) | Gets or sets the sequence id. |
| [getStartDate()](#getStartDate--) | Gets or sets a start date of task. |
| [getSubject()](#getSubject--) | Gets or sets a task subject. |
| [getUniqueId()](#getUniqueId--) | Gets or sets unique identifier |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [request()](#request--) | Requests the object. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves current object to the given stream using MSG format. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves current object to the given stream using specified format. |
| [save(String filePath)](#save-java.lang.String-) | Saves current object into file using MSG format. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves current object into file using specified format. |
| [setAttachments(AttachmentCollection value)](#setAttachments-com.aspose.email.AttachmentCollection-) | Gets or sets a collection of file attached to the task. |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | Gets or sets the attendees. |
| [setBody(String value)](#setBody-java.lang.String-) | Gets or sets a task body. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Gets or sets the date by which the user expects work on the task to be complete. |
| [setMethod(int value)](#setMethod-int-) | Gets or sets iTIP methods associated with an task. |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | Gets or sets the organizer. |
| [setPercentComplete(float value)](#setPercentComplete-float-) | Gets or sets a pecent of task completion. |
| [setPriority(int value)](#setPriority-int-) | Gets or sets a task priority. |
| [setRelatedTo(String value)](#setRelatedTo-java.lang.String-) | Gets or sets a related UID |
| [setSequenceId(int value)](#setSequenceId-int-) | Gets or sets the sequence id. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets a start date of task. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets a task subject. |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | Gets or sets unique identifier |
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
### getRelatedTo() {#getRelatedTo--}
```
public final String getRelatedTo()
```


Gets or sets a related UID

**Returns:**
java.lang.String
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
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets a task subject.

**Returns:**
java.lang.String
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Gets or sets unique identifier

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

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Gets or sets a task body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setRelatedTo(String value) {#setRelatedTo-java.lang.String-}
```
public final void setRelatedTo(String value)
```


Gets or sets a related UID

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets a task subject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


Gets or sets unique identifier

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

