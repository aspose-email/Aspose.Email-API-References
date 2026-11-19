---
title: MapiTask
second_title: Aspose.Email for Java API Reference
description: Represents a MAPI task item.
type: docs
weight: 493
url: /java/com.aspose.email/mapitask/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public class MapiTask extends MapiMessageItemBase
```

Represents a MAPI task item.

This class serves as a wrapper for [MapiMessage](../../com.aspose.email/mapimessage) to simplify the process of handling task information from MAPI properties. It provides a more intuitive interface for accessing and manipulating task data within the MAPI message.

The following example demonstrates how to get a [MapiTask](../../com.aspose.email/mapitask) object from a [MapiMessage](../../com.aspose.email/mapimessage).

```

 MapiMessage msg = MapiMessage.load("task.msg");

 // Check if the loaded message is a supported task type
 if (msg.getSupportedType() == MapiItemType.Task) {
     // Convert the MAPI message to a MapiTask object
     MapiTask mapiTask = (MapiTask) msg.toMapiMessageItem();

     // Display some task info
     System.out.println(mapiTask.getSubject());
     System.out.println(mapiTask.getDueDate());
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiTask()](#MapiTask--) | Initializes a new instance of the [MapiTask](../../com.aspose.email/mapitask) class. |
| [MapiTask(String subject, String body, Date startDate, Date dueDate)](#MapiTask-java.lang.String-java.lang.String-java.util.Date-java.util.Date-) | Initializes a new instance of the [MapiTask](../../com.aspose.email/mapitask) class with a subject, a body and dates. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Releases the resources used by the item. |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromVTodo(InputStream stream)](#fromVTodo-java.io.InputStream-) | Loads a task from a stream that contains an iCalendar VTODO. |
| [fromVTodo(InputStream stream, boolean detectEncoding)](#fromVTodo-java.io.InputStream-boolean-) | Loads a task from a stream that contains an iCalendar VTODO, optionally detecting the encoding. |
| [fromVTodo(String filePath)](#fromVTodo-java.lang.String-) | Loads a task from an iCalendar (.ics) file with a VTODO. |
| [fromVTodo(String filePath, boolean detectEncoding)](#fromVTodo-java.lang.String-boolean-) | Loads a task from an iCalendar (.ics) file with a VTODO, optionally detecting the encoding. |
| [getAcceptanceState()](#getAcceptanceState--) | Gets whether the assignee has accepted or rejected the task. |
| [getActualEffort()](#getActualEffort--) | Gets the time actually spent on the task, in minutes. |
| [getAttachments()](#getAttachments--) | Gets the attachments of the item. |
| [getBilling()](#getBilling--) | Gets the billing information of the item. |
| [getBody()](#getBody--) | Gets the plain-text body of the item. |
| [getBodyHtml()](#getBodyHtml--) | Gets the body of the item as HTML, converted from \#getBodyRtf().getBodyRtf(); an empty string when there is no RTF body. |
| [getBodyRtf()](#getBodyRtf--) | Gets the body of the item in RTF format. |
| [getBodyType()](#getBodyType--) | Gets the format of the body: plain text, HTML or RTF. |
| [getCategories()](#getCategories--) | Gets the categories of the item. |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Gets the code page of the ANSI strings of the object. |
| [getCompanies()](#getCompanies--) | Gets the names of the companies associated with the item. |
| [getDateCompleted()](#getDateCompleted--) | Gets the date the work on the task was completed. |
| [getDueDate()](#getDueDate--) | Gets the date the task is due. |
| [getEstimatedEffort()](#getEstimatedEffort--) | Gets the expected time of work on the task, in minutes. |
| [getFlags()](#getFlags--) | Gets the flags of the task, such as complete or recurring. |
| [getHistory()](#getHistory--) | Gets the last change made to the task. |
| [getItemId()](#getItemId--) | Gets the identifier of the item on the mail server, for items obtained from a server;  null  otherwise. |
| [getLastUpdate()](#getLastUpdate--) | Gets the date and time of the last change made to the task. |
| [getMessageClass()](#getMessageClass--) | Gets the message class of the item, such as  IPM.Note  for an e-mail message. |
| [getMileage()](#getMileage--) | Gets the mileage information of the item. |
| [getMode()](#getMode--) | Gets the assignment status of the task. |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of the item. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Gets the mapping between the named properties and the tags they are stored under. |
| [getPercentComplete()](#getPercentComplete--) | Gets the progress of the task, from 0 to 100 percent. |
| [getPriority()](#getPriority--) | Gets the priority of the task. |
| [getProperties()](#getProperties--) | Gets all properties of the object. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets a MAPI property of the item by its descriptor. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Gets the value of a property as a Boolean. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Gets the value of a property as bytes. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Gets the value of a property as a date and time. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Gets the value of a property as a 32-bit integer. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Gets the value of a property as a 64-bit integer. |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Gets the value of a property as a 16-bit integer. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream of the item. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Gets the value of a property as a string. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [getRecipients()](#getRecipients--) | Gets the recipients of the item. |
| [getRecurrence()](#getRecurrence--) | Gets the recurrence of the task;  null  for a single task. |
| [getReminderFileParameter()](#getReminderFileParameter--) | Gets the full path of the sound file that is played when the reminder is due. |
| [getReminderSet()](#getReminderSet--) | Gets a value indicating whether a reminder is set. |
| [getReminderTime()](#getReminderTime--) | Gets the date and time of the reminder. |
| [getSensitivity()](#getSensitivity--) | Gets the sensitivity of the item: normal, personal, private or confidential. |
| [getStartDate()](#getStartDate--) | Gets the date the work on the task starts. |
| [getState()](#getState--) | Gets the assignment state of the task. |
| [getStatus()](#getStatus--) | Gets the progress status of the task: not started, in progress, complete and so on. |
| [getSubStorages()](#getSubStorages--) | Gets the sub-storages of the item. |
| [getSubject()](#getSubject--) | Gets the subject of the message. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Gets the prefix of the subject, such as  RE:  or  FW: . |
| [getSupportedType()](#getSupportedType--) | Gets the type of the item, as determined by its message class. |
| [getUnderlyingMessage()](#getUnderlyingMessage--) | Retrieves the underlying MapiMessage object. |
| [getUsers()](#getUsers--) | Gets the people involved in the task: owner, assigner, delegator and so on. |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Determines whether the string properties of the object are stored in Unicode. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads a [MapiTask](../../com.aspose.email/mapitask) from the specified stream. |
| [load(String filePath)](#load-java.lang.String-) | Loads a [MapiTask](../../com.aspose.email/mapitask) from the specified file. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(long tag)](#removeProperty-long-) | Removes a property from the item, including its named-property mapping. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves this [MapiTask](../../com.aspose.email/mapitask) to the given stream. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves the task to a stream in the specified format. |
| [save(String filePath)](#save-java.lang.String-) | Saves this [MapiTask](../../com.aspose.email/mapitask) to the given file. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves the task to a file in the specified format. |
| [setAcceptanceState(int value)](#setAcceptanceState-int-) | Sets whether the assignee has accepted or rejected the task. |
| [setActualEffort(int value)](#setActualEffort-int-) | Sets the time actually spent on the task, in minutes. |
| [setBilling(String value)](#setBilling-java.lang.String-) | Sets the billing information of the item. |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the plain-text body of the item. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Sets the body of the item in the specified format. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Sets the body of the item in the specified format, optionally compressing it. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Sets the body of the item in RTF format. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Sets the body of the item in RTF format, optionally compressing it. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Sets the categories of the item. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Sets the names of the companies associated with the item. |
| [setDateCompleted(Date value)](#setDateCompleted-java.util.Date-) | Sets the date the work on the task was completed. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Sets the date the task is due. |
| [setEstimatedEffort(int value)](#setEstimatedEffort-int-) | Sets the expected time of work on the task, in minutes. |
| [setHistory(int value)](#setHistory-int-) | Sets the last change made to the task. |
| [setLastUpdate(Date value)](#setLastUpdate-java.util.Date-) | Sets the date and time of the last change made to the task. |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Sets the message class of the item, such as  IPM.Note  for an e-mail message. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Sets the flags of the message, such as read or unsent. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Sets the mileage information of the item. |
| [setMode(int value)](#setMode-int-) | Sets the assignment status of the task. |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Sets the named property mapping. |
| [setPercentComplete(int value)](#setPercentComplete-int-) | Sets the progress of the task, from 0 to 100 percent. |
| [setPriority(int value)](#setPriority-int-) | Sets the priority of the task. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Adds the property, or replaces the property with the same tag. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets the value of a MAPI property of the item. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Sets the recipients of the item. |
| [setRecurrence(MapiCalendarRecurrencePattern value)](#setRecurrence-com.aspose.email.MapiCalendarRecurrencePattern-) | Sets the recurrence of the task;  null  for a single task. |
| [setReminderFileParameter(String value)](#setReminderFileParameter-java.lang.String-) | Sets the full path of the sound file that is played when the reminder is due. |
| [setReminderSet(boolean value)](#setReminderSet-boolean-) | Sets a value indicating whether a reminder is set. |
| [setReminderTime(Date value)](#setReminderTime-java.util.Date-) | Sets the date and time of the reminder. |
| [setSensitivity(int value)](#setSensitivity-int-) | Sets the sensitivity of the item: normal, personal, private or confidential. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Sets the date the work on the task starts. |
| [setState(int value)](#setState-int-) | Sets the assignment state of the task. |
| [setStatus(int value)](#setStatus-int-) | Sets the progress status of the task: not started, in progress, complete and so on. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the message. |
| [setUsers(MapiTaskUsers value)](#setUsers-com.aspose.email.MapiTaskUsers-) | Sets the people involved in the task: owner, assigner, delegator and so on. |
| [toMvPropertyList(Object obj)](#toMvPropertyList-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | Gets the value of a property as bytes. |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | Gets the value of a property as a date and time, if the property exists. |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | Gets the value of a property as a string. |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | Gets the value of a property as a string, if the property exists. |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiTask() {#MapiTask--}
```
public MapiTask()
```


Initializes a new instance of the [MapiTask](../../com.aspose.email/mapitask) class.

### MapiTask(String subject, String body, Date startDate, Date dueDate) {#MapiTask-java.lang.String-java.lang.String-java.util.Date-java.util.Date-}
```
public MapiTask(String subject, String body, Date startDate, Date dueDate)
```


Initializes a new instance of the [MapiTask](../../com.aspose.email/mapitask) class with a subject, a body and dates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subject | java.lang.String | The subject. |
| body | java.lang.String | The body. |
| startDate | java.util.Date | The date the work starts. |
| dueDate | java.util.Date | The date the task is due. |

### close() {#close--}
```
public void close()
```


Releases the resources used by the item.

### createMapiNode(String key) {#createMapiNode-java.lang.String-}
```
public IMapiNode createMapiNode(String key)
```


Creates the mapi node.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The node key. |

**Returns:**
com.aspose.email.IMapiNode - The IMapiNode interface.
### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### fromVTodo(InputStream stream) {#fromVTodo-java.io.InputStream-}
```
public static MapiTask fromVTodo(InputStream stream)
```


Loads a task from a stream that contains an iCalendar VTODO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - The loaded task.
### fromVTodo(InputStream stream, boolean detectEncoding) {#fromVTodo-java.io.InputStream-boolean-}
```
public static MapiTask fromVTodo(InputStream stream, boolean detectEncoding)
```


Loads a task from a stream that contains an iCalendar VTODO, optionally detecting the encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |
| detectEncoding | boolean |  true  to detect the encoding of the data from its byte order mark (BOM). |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - The loaded task.
### fromVTodo(String filePath) {#fromVTodo-java.lang.String-}
```
public static MapiTask fromVTodo(String filePath)
```


Loads a task from an iCalendar (.ics) file with a VTODO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file. |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - The loaded task.
### fromVTodo(String filePath, boolean detectEncoding) {#fromVTodo-java.lang.String-boolean-}
```
public static MapiTask fromVTodo(String filePath, boolean detectEncoding)
```


Loads a task from an iCalendar (.ics) file with a VTODO, optionally detecting the encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file. |
| detectEncoding | boolean |  true  to detect the encoding of the data from its byte order mark (BOM). |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - The loaded task.
### getAcceptanceState() {#getAcceptanceState--}
```
public final int getAcceptanceState()
```


Gets whether the assignee has accepted or rejected the task.

**Returns:**
int
### getActualEffort() {#getActualEffort--}
```
public final int getActualEffort()
```


Gets the time actually spent on the task, in minutes.

**Returns:**
int
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Gets the attachments of the item.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The attachments.
### getBilling() {#getBilling--}
```
public final String getBilling()
```


Gets the billing information of the item.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public String getBody()
```


Gets the plain-text body of the item.

**Returns:**
java.lang.String - The body.
### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Gets the body of the item as HTML, converted from \#getBodyRtf().getBodyRtf(); an empty string when there is no RTF body.

**Returns:**
java.lang.String
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Gets the body of the item in RTF format.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int), which encapsulates HTML in RTF as Outlook does. Setting  null  or an empty string clears both bodies.

**Returns:**
java.lang.String - The RTF body.
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the format of the body: plain text, HTML or RTF.

**Returns:**
int - The format of the body.
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Gets the categories of the item.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


Gets the code page of the ANSI strings of the object.

**Returns:**
int - The code page.
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Gets the names of the companies associated with the item.

**Returns:**
java.lang.String[]
### getDateCompleted() {#getDateCompleted--}
```
public final Date getDateCompleted()
```


Gets the date the work on the task was completed.

**Returns:**
java.util.Date
### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


Gets the date the task is due.

**Returns:**
java.util.Date
### getEstimatedEffort() {#getEstimatedEffort--}
```
public final int getEstimatedEffort()
```


Gets the expected time of work on the task, in minutes.

**Returns:**
int
### getFlags() {#getFlags--}
```
public final int getFlags()
```


Gets the flags of the task, such as complete or recurring.

**Returns:**
int
### getHistory() {#getHistory--}
```
public final int getHistory()
```


Gets the last change made to the task.

**Returns:**
int
### getItemId() {#getItemId--}
```
public String getItemId()
```


Gets the identifier of the item on the mail server, for items obtained from a server;  null  otherwise.

**Returns:**
java.lang.String
### getLastUpdate() {#getLastUpdate--}
```
public final Date getLastUpdate()
```


Gets the date and time of the last change made to the task.

**Returns:**
java.util.Date
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets the message class of the item, such as  IPM.Note  for an e-mail message. The class determines the type of the item.

**Returns:**
java.lang.String - The message class. It is case-sensitive.
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Gets the mileage information of the item.

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public final int getMode()
```


Gets the assignment status of the task.

**Returns:**
int
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of the item.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The named properties.
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


Gets the mapping between the named properties and the tags they are stored under.

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) - The named property mapping.
### getPercentComplete() {#getPercentComplete--}
```
public final int getPercentComplete()
```


Gets the progress of the task, from 0 to 100 percent.

**Returns:**
int
### getPriority() {#getPriority--}
```
public final int getPriority()
```


Gets the priority of the task.

**Returns:**
int
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets all properties of the object.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The properties.
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Gets a MAPI property of the item by its descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The property, or  null  if the item does not have it.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


Gets the value of a property as a Boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Boolean - The value, or  null  if the property does not exist.
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


Gets the value of a property as bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
byte[] - The value, or  null  if the property does not exist.
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


Gets the value of a property as a date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The tag of the property. |

**Returns:**
java.util.Date - The value, or  null  if the property does not exist.
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


Gets the value of a property as a 32-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Integer - The value, or  null  if the property does not exist.
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


Gets the value of a property as a 64-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Long - The value, or  null  if the property does not exist.
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


Gets the value of a property as a 16-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Short - The value, or  null  if the property does not exist.
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream of the item.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream) - The property stream.
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


Gets the value of a property as a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


Gets the value of a property as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Gets the recipients of the item.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) - The recipients.
### getRecurrence() {#getRecurrence--}
```
public final MapiCalendarRecurrencePattern getRecurrence()
```


Gets the recurrence of the task;  null  for a single task.

**Returns:**
[MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern)
### getReminderFileParameter() {#getReminderFileParameter--}
```
public final String getReminderFileParameter()
```


Gets the full path of the sound file that is played when the reminder is due.

**Returns:**
java.lang.String
### getReminderSet() {#getReminderSet--}
```
public final boolean getReminderSet()
```


Gets a value indicating whether a reminder is set.

**Returns:**
boolean
### getReminderTime() {#getReminderTime--}
```
public final Date getReminderTime()
```


Gets the date and time of the reminder.

**Returns:**
java.util.Date
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the sensitivity of the item: normal, personal, private or confidential.

**Returns:**
int - The sensitivity.
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets the date the work on the task starts.

**Returns:**
java.util.Date
### getState() {#getState--}
```
public final int getState()
```


Gets the assignment state of the task.

**Returns:**
int
### getStatus() {#getStatus--}
```
public final int getStatus()
```


Gets the progress status of the task: not started, in progress, complete and so on.

**Returns:**
int
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub-storages of the item.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The sub-storages.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the message.

Setting the subject also sets the subject prefix (such as  RE: ) and the normalized subject (the subject without the prefix). Setting  null  or an empty string clears all three.

**Returns:**
java.lang.String - The subject.
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Gets the prefix of the subject, such as  RE:  or  FW: .

**Returns:**
java.lang.String - The subject prefix.
### getSupportedType() {#getSupportedType--}
```
public final int getSupportedType()
```


Gets the type of the item, as determined by its message class.

**Returns:**
int - The item type.
### getUnderlyingMessage() {#getUnderlyingMessage--}
```
public final MapiMessage getUnderlyingMessage()
```


Retrieves the underlying MapiMessage object.

Retrieves the underlying MAPI message from a MapiTask object and prints out its message class.

```

 // Retrieve the underlying MAPI message from the MapiTask object
 MapiMessage msg = mapiTask.getUnderlyingMessage();

 // Print out the message class of the MAPI message
 // Will output "IPM.Task"
 System.out.println(msg.getMessageClass());
 
```

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The [MapiMessage](../../com.aspose.email/mapimessage) object.
### getUsers() {#getUsers--}
```
public final MapiTaskUsers getUsers()
```


Gets the people involved in the task: owner, assigner, delegator and so on.

**Returns:**
[MapiTaskUsers](../../com.aspose.email/mapitaskusers)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


Determines whether the string properties of the object are stored in Unicode.

**Returns:**
boolean -  true  if the strings are Unicode;  false  if they are ANSI.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MapiTask load(InputStream stream)
```


Loads a [MapiTask](../../com.aspose.email/mapitask) from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to be loaded. |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - Returns a [MapiTask](../../com.aspose.email/mapitask) instance loaded from the specified stream.
### load(String filePath) {#load-java.lang.String-}
```
public static MapiTask load(String filePath)
```


Loads a [MapiTask](../../com.aspose.email/mapitask) from the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to be loaded. |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - Returns a [MapiTask](../../com.aspose.email/mapitask) instance loaded from the specified file.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Removes a property from the item, including its named-property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property to remove. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves this [MapiTask](../../com.aspose.email/mapitask) to the given stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to. |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Saves the task to a stream in the specified format. Only MSG is supported.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| saveFormat | int | The format. |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves this [MapiTask](../../com.aspose.email/mapitask) to the given file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file name. |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Saves the task to a file in the specified format. Only MSG is supported.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to write. |
| saveFormat | int | The format. |

### setAcceptanceState(int value) {#setAcceptanceState-int-}
```
public final void setAcceptanceState(int value)
```


Sets whether the assignee has accepted or rejected the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setActualEffort(int value) {#setActualEffort-int-}
```
public final void setActualEffort(int value)
```


Sets the time actually spent on the task, in minutes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Sets the billing information of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Sets the plain-text body of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The body. |

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


Sets the body of the item in the specified format.

The plain-text body, the RTF body and the compressed RTF property are all updated. After HTML content is set, \#getBodyRtf().getBodyRtf() returns that HTML encapsulated in RTF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The text of the body. |
| contentType | int | The format of  content . |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


Sets the body of the item in the specified format, optionally compressing it.

The plain-text body, the RTF body and the compressed RTF property are all updated. After HTML content is set, \#getBodyRtf().getBodyRtf() returns that HTML encapsulated in RTF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The text of the body. |
| contentType | int | The format of  content . |
| compression | boolean |  true  to store the RTF body compressed. |

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Sets the body of the item in RTF format.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int), which encapsulates HTML in RTF as Outlook does. Setting  null  or an empty string clears both bodies.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The RTF body. |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


Sets the body of the item in RTF format, optionally compressing it.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int). Setting  null  or an empty string clears both bodies.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The body in RTF. |
| compression | boolean |  true  to store the RTF body compressed. |

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Sets the categories of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Sets the names of the companies associated with the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setDateCompleted(Date value) {#setDateCompleted-java.util.Date-}
```
public final void setDateCompleted(Date value)
```


Sets the date the work on the task was completed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


Sets the date the task is due.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setEstimatedEffort(int value) {#setEstimatedEffort-int-}
```
public final void setEstimatedEffort(int value)
```


Sets the expected time of work on the task, in minutes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHistory(int value) {#setHistory-int-}
```
public final void setHistory(int value)
```


Sets the last change made to the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLastUpdate(Date value) {#setLastUpdate-java.util.Date-}
```
public final void setLastUpdate(Date value)
```


Sets the date and time of the last change made to the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


Sets the message class of the item, such as  IPM.Note  for an e-mail message. The class determines the type of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The message class. It is case-sensitive. |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


Sets the flags of the message, such as read or unsent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The flags to set. |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Sets the mileage information of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Sets the assignment status of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


Sets the named property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | The MapiNamedPropertyMappingStorage. |

### setPercentComplete(int value) {#setPercentComplete-int-}
```
public final void setPercentComplete(int value)
```


Sets the progress of the task, from 0 to 100 percent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPriority(int value) {#setPriority-int-}
```
public final void setPriority(int value)
```


Sets the priority of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Adds the property, or replaces the property with the same tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property to set. |

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


Sets the value of a MAPI property of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |
| value | java.lang.Object | The value, of a Java type that matches the data type of the property. |

### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


Sets the recipients of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) | The recipients. |

### setRecurrence(MapiCalendarRecurrencePattern value) {#setRecurrence-com.aspose.email.MapiCalendarRecurrencePattern-}
```
public final void setRecurrence(MapiCalendarRecurrencePattern value)
```


Sets the recurrence of the task;  null  for a single task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern) |  |

### setReminderFileParameter(String value) {#setReminderFileParameter-java.lang.String-}
```
public final void setReminderFileParameter(String value)
```


Sets the full path of the sound file that is played when the reminder is due.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setReminderSet(boolean value) {#setReminderSet-boolean-}
```
public final void setReminderSet(boolean value)
```


Sets a value indicating whether a reminder is set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setReminderTime(Date value) {#setReminderTime-java.util.Date-}
```
public final void setReminderTime(Date value)
```


Sets the date and time of the reminder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Sets the sensitivity of the item: normal, personal, private or confidential.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The sensitivity. |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Sets the date the work on the task starts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setState(int value) {#setState-int-}
```
public final void setState(int value)
```


Sets the assignment state of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Sets the progress status of the task: not started, in progress, complete and so on.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets the subject of the message.

Setting the subject also sets the subject prefix (such as  RE: ) and the normalized subject (the subject without the prefix). Setting  null  or an empty string clears all three.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The subject. |

### setUsers(MapiTaskUsers value) {#setUsers-com.aspose.email.MapiTaskUsers-}
```
public final void setUsers(MapiTaskUsers value)
```


Sets the people involved in the task: owner, assigner, delegator and so on.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiTaskUsers](../../com.aspose.email/mapitaskusers) |  |

### toMvPropertyList(Object obj) {#toMvPropertyList-java.lang.Object-}
```
public static System.Collections.Generic.IGenericList<Object> toMvPropertyList(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Object>
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetPropertyData(long tag) {#tryGetPropertyData-long-}
```
public final byte[] tryGetPropertyData(long tag)
```


Gets the value of a property as bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
byte[] - The value, or  null  if the property does not exist.
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


Gets the value of a property as a date and time, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.util.Date[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


Gets the value of a property as a 32-bit integer, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | int[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


Gets the value of a property as a 64-bit integer, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | long[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


Gets the value of a property as a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


Gets the value of a property as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


Gets the value of a property as a string, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
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

