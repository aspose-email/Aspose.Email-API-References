---
title: Task
second_title: Aspose.Email for Java API Reference
description: Represents a task an iCalendar VTODO component that can be read from iCalendar and saved to iCalendar or Outlook MSG.
type: docs
weight: 705
url: /java/com.aspose.email/task/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Task implements System.IDisposable, Closeable
```

Represents a task (an iCalendar VTODO component) that can be read from iCalendar and saved to iCalendar or Outlook MSG.
## Constructors

| Constructor | Description |
| --- | --- |
| [Task()](#Task--) |  |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Releases the resources used by the task, including its attachments. |
| [dispose()](#dispose--) | Release all resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | Gets the files attached to the task. |
| [getAttendees()](#getAttendees--) | Gets the attendees (assignees) of the task. |
| [getBody()](#getBody--) | Gets the plain-text body of the task. |
| [getClass()](#getClass--) |  |
| [getDueDate()](#getDueDate--) | Gets the date by which the user expects work on the task to be complete. |
| [getHtmlBody()](#getHtmlBody--) | Gets the HTML body of the task. |
| [getLocation()](#getLocation--) | Gets the location of the task. |
| [getMethod()](#getMethod--) | Gets the iTIP method of the task, such as a request or a publication. |
| [getOrganizer()](#getOrganizer--) | Gets the organizer of the task. |
| [getPercentComplete()](#getPercentComplete--) | Gets how much of the task is complete, in percent. |
| [getPriority()](#getPriority--) | Gets the priority of the task. |
| [getRelatedTo()](#getRelatedTo--) | Gets the unique identifier of a related calendar item (the iCalendar RELATED-TO property). |
| [getSequenceId()](#getSequenceId--) | Gets the revision sequence number of the task (the iCalendar SEQUENCE property). |
| [getStartDate()](#getStartDate--) | Gets the start date of the task. |
| [getStatus()](#getStatus--) | Gets the status of the user's progress on the task. |
| [getSubject()](#getSubject--) | Gets the subject of the task. |
| [getUniqueId()](#getUniqueId--) | Gets the unique identifier of the task (the iCalendar UID property). |
| [hashCode()](#hashCode--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads a task from a stream of iCalendar (ICS) data. |
| [load(String filePath)](#load-java.lang.String-) | Loads a task from an iCalendar (ICS) file. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [request()](#request--) | Creates a task request to send by email. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the task to a stream in iCalendar (ICS) format. |
| [save(OutputStream stream, TaskSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.TaskSaveOptions-) | Saves the task to a stream with the specified options. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves current object to the given stream using specified format. |
| [save(String filePath)](#save-java.lang.String-) | Saves the task to an iCalendar (ICS) file. |
| [save(String filePath, TaskSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.TaskSaveOptions-) | Saves the task to a file with the specified options. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves current object into file using specified format. |
| [setAttachments(AttachmentCollection value)](#setAttachments-com.aspose.email.AttachmentCollection-) | Sets the files attached to the task. |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | Sets the attendees (assignees) of the task. |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the plain-text body of the task. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Sets the date by which the user expects work on the task to be complete. |
| [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Sets the HTML body of the task. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Sets the location of the task. |
| [setMethod(int value)](#setMethod-int-) | Sets the iTIP method of the task, such as a request or a publication. |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | Sets the organizer of the task. |
| [setPercentComplete(float value)](#setPercentComplete-float-) | Sets how much of the task is complete, in percent. |
| [setPriority(int value)](#setPriority-int-) | Sets the priority of the task. |
| [setRelatedTo(String value)](#setRelatedTo-java.lang.String-) | Sets the unique identifier of a related calendar item (the iCalendar RELATED-TO property). |
| [setSequenceId(int value)](#setSequenceId-int-) | Sets the revision sequence number of the task (the iCalendar SEQUENCE property). |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Sets the start date of the task. |
| [setStatus(int value)](#setStatus-int-) | Sets the status of the user's progress on the task. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the task. |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | Sets the unique identifier of the task (the iCalendar UID property). |
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


Releases the resources used by the task, including its attachments.

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


Gets the files attached to the task.

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getAttendees() {#getAttendees--}
```
public final MailAddressCollection getAttendees()
```


Gets the attendees (assignees) of the task.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getBody() {#getBody--}
```
public final String getBody()
```


Gets the plain-text body of the task.

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


Gets the date by which the user expects work on the task to be complete.

**Returns:**
java.util.Date
### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


Gets the HTML body of the task.

**Returns:**
java.lang.String
### getLocation() {#getLocation--}
```
public final String getLocation()
```


Gets the location of the task.

**Returns:**
java.lang.String
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Gets the iTIP method of the task, such as a request or a publication.

**Returns:**
int
### getOrganizer() {#getOrganizer--}
```
public final MailAddress getOrganizer()
```


Gets the organizer of the task.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getPercentComplete() {#getPercentComplete--}
```
public final float getPercentComplete()
```


Gets how much of the task is complete, in percent.

**Returns:**
float
### getPriority() {#getPriority--}
```
public final int getPriority()
```


Gets the priority of the task.

**Returns:**
int
### getRelatedTo() {#getRelatedTo--}
```
public final String getRelatedTo()
```


Gets the unique identifier of a related calendar item (the iCalendar RELATED-TO property).

**Returns:**
java.lang.String
### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


Gets the revision sequence number of the task (the iCalendar SEQUENCE property).

**Returns:**
int - The sequence id.
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets the start date of the task.

**Returns:**
java.util.Date
### getStatus() {#getStatus--}
```
public int getStatus()
```


Gets the status of the user's progress on the task.

**Returns:**
int
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the task.

**Returns:**
java.lang.String
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Gets the unique identifier of the task (the iCalendar UID property).

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Task load(InputStream stream)
```


Loads a task from a stream of iCalendar (ICS) data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read from. |

**Returns:**
[Task](../../com.aspose.email/task) - The task read from the stream.
### load(String filePath) {#load-java.lang.String-}
```
public static Task load(String filePath)
```


Loads a task from an iCalendar (ICS) file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the ICS file. |

**Returns:**
[Task](../../com.aspose.email/task) - The task read from the file.
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


Creates a task request to send by email.

The METHOD is PUBLISH when \#getMethod().getMethod() is [TIPMethod.Publish](../../com.aspose.email/tipmethod\#Publish), and REQUEST otherwise.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An [AlternateView](../../com.aspose.email/alternateview) with the iCalendar data (text/calendar) to add to a [MailMessage](../../com.aspose.email/mailmessage).
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves the task to a stream in iCalendar (ICS) format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### save(OutputStream stream, TaskSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.TaskSaveOptions-}
```
public void save(OutputStream stream, TaskSaveOptions saveOptions)
```


Saves the task to a stream with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| saveOptions | [TaskSaveOptions](../../com.aspose.email/tasksaveoptions) | The save options. Their type, [TaskIcsSaveOptions](../../com.aspose.email/taskicssaveoptions) or [TaskMsgSaveOptions](../../com.aspose.email/taskmsgsaveoptions), selects the format;  null  saves in iCalendar format. |

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


Saves the task to an iCalendar (ICS) file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to create. An existing file is overwritten. |

### save(String filePath, TaskSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.TaskSaveOptions-}
```
public void save(String filePath, TaskSaveOptions saveOptions)
```


Saves the task to a file with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to create. An existing file is overwritten. |
| saveOptions | [TaskSaveOptions](../../com.aspose.email/tasksaveoptions) | The save options. Their type, [TaskIcsSaveOptions](../../com.aspose.email/taskicssaveoptions) or [TaskMsgSaveOptions](../../com.aspose.email/taskmsgsaveoptions), selects the format;  null  saves in iCalendar format. |

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


Sets the files attached to the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AttachmentCollection](../../com.aspose.email/attachmentcollection) |  |

### setAttendees(MailAddressCollection value) {#setAttendees-com.aspose.email.MailAddressCollection-}
```
public final void setAttendees(MailAddressCollection value)
```


Sets the attendees (assignees) of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Sets the plain-text body of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


Sets the date by which the user expects work on the task to be complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


Sets the HTML body of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Sets the location of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Sets the iTIP method of the task, such as a request or a publication.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOrganizer(MailAddress value) {#setOrganizer-com.aspose.email.MailAddress-}
```
public final void setOrganizer(MailAddress value)
```


Sets the organizer of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setPercentComplete(float value) {#setPercentComplete-float-}
```
public final void setPercentComplete(float value)
```


Sets how much of the task is complete, in percent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setPriority(int value) {#setPriority-int-}
```
public final void setPriority(int value)
```


Sets the priority of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRelatedTo(String value) {#setRelatedTo-java.lang.String-}
```
public final void setRelatedTo(String value)
```


Sets the unique identifier of a related calendar item (the iCalendar RELATED-TO property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSequenceId(int value) {#setSequenceId-int-}
```
public final void setSequenceId(int value)
```


Sets the revision sequence number of the task (the iCalendar SEQUENCE property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The sequence id. |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Sets the start date of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setStatus(int value) {#setStatus-int-}
```
public void setStatus(int value)
```


Sets the status of the user's progress on the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets the subject of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


Sets the unique identifier of the task (the iCalendar UID property).

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

