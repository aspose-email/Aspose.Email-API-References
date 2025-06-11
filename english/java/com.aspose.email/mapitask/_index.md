---
title: MapiTask
second_title: Aspose.Email for Java API Reference
description: Represents a MAPI task item.
type: docs
weight: 490
url: /java/com.aspose.email/mapitask/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public class MapiTask extends MapiMessageItemBase
```

Represents a MAPI task item.

This class serves as a wrapper for [MapiMessage](../../com.aspose.email/mapimessage) to simplify the process of handling task information from MAPI properties. It provides a more intuitive interface for accessing and manipulating task data within the MAPI message.

Example:

```

 // Load the MAPI message from a file
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
| [MapiTask(String subject, String body, Date startDate, Date dueDate)](#MapiTask-java.lang.String-java.lang.String-java.util.Date-java.util.Date-) | Initializes a new instance of the [MapiTask](../../com.aspose.email/mapitask) class. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromVTodo(InputStream stream)](#fromVTodo-java.io.InputStream-) | Creates an instance of MapiTask from the specified stream. |
| [fromVTodo(InputStream stream, boolean detectEncoding)](#fromVTodo-java.io.InputStream-boolean-) | Creates an instance of MapiTask from the specified stream. |
| [fromVTodo(String filePath)](#fromVTodo-java.lang.String-) | Creates an instance of MapiTask from the specified .ics file. |
| [fromVTodo(String filePath, boolean detectEncoding)](#fromVTodo-java.lang.String-boolean-) | Creates an instance of MapiTask from the specified .ics file. |
| [getAcceptanceState()](#getAcceptanceState--) | Gets or sets the acceptance state of the task. |
| [getActualEffort()](#getActualEffort--) | Gets or sets the number of minutes that the user actually spent working on a task. |
| [getAttachments()](#getAttachments--) | Gets the attachments in the message. |
| [getBilling()](#getBilling--) | Contains the billing information associated with an item. |
| [getBody()](#getBody--) | Gets the message text. |
| [getBodyHtml()](#getBodyHtml--) | Gets the  BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) of the message converted to HTML, if present, otherwise an empty string. |
| [getBodyRtf()](#getBodyRtf--) | Gets or sets the RTF formatted message text. |
| [getBodyType()](#getBodyType--) | Gets the type of the body. |
| [getCategories()](#getCategories--) | Contains keywords or categories for the message object. |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Gets the code page. |
| [getCompanies()](#getCompanies--) | Contains the names of the companies that are associated with an item. |
| [getDateCompleted()](#getDateCompleted--) | Gets or sets the date when the user completed work on the task. |
| [getDueDate()](#getDueDate--) | Gets or sets the date by which the user expects work on the task to be complete. |
| [getEstimatedEffort()](#getEstimatedEffort--) | Gets or sets the number of minutes that the user expects to work on a task. |
| [getFlags()](#getFlags--) | Gets the indication flags of the Task object. |
| [getHistory()](#getHistory--) | Gets or sets the type of change that was last made to the Task object. |
| [getItemId()](#getItemId--) | The item id, uses with a server |
| [getLastUpdate()](#getLastUpdate--) | Gets or sets the date and time of the most recent change made to the Task object. |
| [getMessageClass()](#getMessageClass--) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. |
| [getMileage()](#getMileage--) | Contains the mileage information that is associated with an item. |
| [getMode()](#getMode--) | Gets or sets the assignment status of the Task object. |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of message. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Gets the named property mapping. |
| [getPercentComplete()](#getPercentComplete--) | Gets or sets the progress the user has made on a task. |
| [getPriority()](#getPriority--) | Gets or sets the current Priority of the Task object. |
| [getProperties()](#getProperties--) | Gets the collection of properties. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets MAPI property by property descriptor. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Gets the value of the property specified by tag as Boolean type. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Gets the string value of the property specified by tag. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Gets the value of the property specified by tag as DateTime type. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Gets the int32 value of the property specified by tag. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Gets the value of the property specified by tag as Long (int64) type. |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Gets the value of the property specified by tag as Short type. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Gets the string value of the property specified by tag. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Gets the string value of the property specified by tag. |
| [getRecipients()](#getRecipients--) | Gets the recipients of the message. |
| [getRecurrence()](#getRecurrence--) | Gets or sets the recurrence properties. |
| [getReminderFileParameter()](#getReminderFileParameter--) | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [getReminderSet()](#getReminderSet--) | Gets or sets a value indicating whether a reminder is set on the object |
| [getReminderTime()](#getReminderTime--) | Gets or sets the initial signal time for a reminder |
| [getSensitivity()](#getSensitivity--) | Gets the Sensitivity. |
| [getStartDate()](#getStartDate--) | Gets or sets the date on which the user expects work on the task to begin. |
| [getState()](#getState--) | Gets or sets the current assignment state of the Task object. |
| [getStatus()](#getStatus--) | Gets or sets the status of the user's progress on the task. |
| [getSubStorages()](#getSubStorages--) | Gets the sub storages. |
| [getSubject()](#getSubject--) | Gets or sets the subject of the message. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [getSupportedType()](#getSupportedType--) | Gets the supported item type. |
| [getUnderlyingMessage()](#getUnderlyingMessage--) | Retrieves the underlying MapiMessage object. |
| [getUsers()](#getUsers--) | Gets or sets information about task users. |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Determines if string properties are Unicode encoded or not. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(long tag)](#removeProperty-long-) | Provides correctly removing property from all collections. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves this [MapiTask](../../com.aspose.email/mapitask) to the given stream using specified format. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves this [MapiTask](../../com.aspose.email/mapitask) into file using specified format. |
| [setAcceptanceState(int value)](#setAcceptanceState-int-) | Gets or sets the acceptance state of the task. |
| [setActualEffort(int value)](#setActualEffort-int-) | Gets or sets the number of minutes that the user actually spent working on a task. |
| [setBilling(String value)](#setBilling-java.lang.String-) | Contains the billing information associated with an item. |
| [setBody(String value)](#setBody-java.lang.String-) | Gets the message text. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Sets the content of the body. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Sets the content of the body. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Gets or sets the RTF formatted message text. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Gets or sets the RTF formatted message text. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Contains keywords or categories for the message object. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Contains the names of the companies that are associated with an item. |
| [setDateCompleted(Date value)](#setDateCompleted-java.util.Date-) | Gets or sets the date when the user completed work on the task. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Gets or sets the date by which the user expects work on the task to be complete. |
| [setEstimatedEffort(int value)](#setEstimatedEffort-int-) | Gets or sets the number of minutes that the user expects to work on a task. |
| [setHistory(int value)](#setHistory-int-) | Gets or sets the type of change that was last made to the Task object. |
| [setLastUpdate(Date value)](#setLastUpdate-java.util.Date-) | Gets or sets the date and time of the most recent change made to the Task object. |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Sets the message flags. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Contains the mileage information that is associated with an item. |
| [setMode(int value)](#setMode-int-) | Gets or sets the assignment status of the Task object. |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Sets the named property mapping. |
| [setPercentComplete(int value)](#setPercentComplete-int-) | Gets or sets the progress the user has made on a task. |
| [setPriority(int value)](#setPriority-int-) | Gets or sets the current Priority of the Task object. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Sets the property. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets MAPI property. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Gets the recipients of the message. |
| [setRecurrence(MapiCalendarRecurrencePattern value)](#setRecurrence-com.aspose.email.MapiCalendarRecurrencePattern-) | Gets or sets the recurrence properties. |
| [setReminderFileParameter(String value)](#setReminderFileParameter-java.lang.String-) | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [setReminderSet(boolean value)](#setReminderSet-boolean-) | Gets or sets a value indicating whether a reminder is set on the object |
| [setReminderTime(Date value)](#setReminderTime-java.util.Date-) | Gets or sets the initial signal time for a reminder |
| [setSensitivity(int value)](#setSensitivity-int-) | Gets the Sensitivity. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets the date on which the user expects work on the task to begin. |
| [setState(int value)](#setState-int-) | Gets or sets the current assignment state of the Task object. |
| [setStatus(int value)](#setStatus-int-) | Gets or sets the status of the user's progress on the task. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets the subject of the message. |
| [setUsers(MapiTaskUsers value)](#setUsers-com.aspose.email.MapiTaskUsers-) | Gets or sets information about task users. |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | Try to get the property data with specified tag key. |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | Gets the value of the specified property as DateTime type. |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | Gets the value of the specified property as Int32 type. |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | Gets the value of the specified property as Long type. |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | Try to get a property data as string with specified tag. |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | Try to get a property data as string with specified tag and code page. |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | Gets the value of the specified property as String type. |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | Gets the value of the specified property as String type. |
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


Initializes a new instance of the [MapiTask](../../com.aspose.email/mapitask) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subject | java.lang.String | The subject. |
| body | java.lang.String | The message body. |
| startDate | java.util.Date | The start date. |
| dueDate | java.util.Date | The due date. |

### close() {#close--}
```
public void close()
```




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


Creates an instance of MapiTask from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to be loaded. |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - Returns a MapiTask instance which is loaded from the specified stream.
### fromVTodo(InputStream stream, boolean detectEncoding) {#fromVTodo-java.io.InputStream-boolean-}
```
public static MapiTask fromVTodo(InputStream stream, boolean detectEncoding)
```


Creates an instance of MapiTask from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to be loaded. |
| detectEncoding | boolean | Determines a data encoding by analyzing its byte order mark (BOM) |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - Returns a MapiTask instance which is loaded from the specified stream.
### fromVTodo(String filePath) {#fromVTodo-java.lang.String-}
```
public static MapiTask fromVTodo(String filePath)
```


Creates an instance of MapiTask from the specified .ics file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to be loaded. |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - Returns a MapiTask instance which is loaded from the specified file.
### fromVTodo(String filePath, boolean detectEncoding) {#fromVTodo-java.lang.String-boolean-}
```
public static MapiTask fromVTodo(String filePath, boolean detectEncoding)
```


Creates an instance of MapiTask from the specified .ics file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to be loaded. |
| detectEncoding | boolean | Determines a data encoding by analyzing its byte order mark (BOM) |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - Returns a MapiTask instance which is loaded from the specified file.
### getAcceptanceState() {#getAcceptanceState--}
```
public final int getAcceptanceState()
```


Gets or sets the acceptance state of the task.

**Returns:**
int
### getActualEffort() {#getActualEffort--}
```
public final int getActualEffort()
```


Gets or sets the number of minutes that the user actually spent working on a task.

**Returns:**
int
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Gets the attachments in the message.

Value: The attachment collection.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection)
### getBilling() {#getBilling--}
```
public final String getBilling()
```


Contains the billing information associated with an item.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public String getBody()
```


Gets the message text.

Value: The string that represents message body.

**Returns:**
java.lang.String
### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Gets the  BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) of the message converted to HTML, if present, otherwise an empty string.

**Returns:**
java.lang.String
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the type of the body.

Value: The type of the body.

**Returns:**
int
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Contains keywords or categories for the message object.

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


Gets the code page.

Value: The code page.

**Returns:**
int
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Contains the names of the companies that are associated with an item.

**Returns:**
java.lang.String[]
### getDateCompleted() {#getDateCompleted--}
```
public final Date getDateCompleted()
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
### getEstimatedEffort() {#getEstimatedEffort--}
```
public final int getEstimatedEffort()
```


Gets or sets the number of minutes that the user expects to work on a task.

**Returns:**
int
### getFlags() {#getFlags--}
```
public final int getFlags()
```


Gets the indication flags of the Task object.

**Returns:**
int
### getHistory() {#getHistory--}
```
public final int getHistory()
```


Gets or sets the type of change that was last made to the Task object.

**Returns:**
int
### getItemId() {#getItemId--}
```
public String getItemId()
```


The item id, uses with a server

**Returns:**
java.lang.String
### getLastUpdate() {#getLastUpdate--}
```
public final Date getLastUpdate()
```


Gets or sets the date and time of the most recent change made to the Task object.

**Returns:**
java.util.Date
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message.

Value: The string that represents message class.

**Returns:**
java.lang.String
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Contains the mileage information that is associated with an item.

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public final int getMode()
```


Gets or sets the assignment status of the Task object.

**Returns:**
int
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of message.

Value: The collection of named properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


Gets the named property mapping.

Value: The named property mapping.

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage)
### getPercentComplete() {#getPercentComplete--}
```
public final int getPercentComplete()
```


Gets or sets the progress the user has made on a task.

**Returns:**
int
### getPriority() {#getPriority--}
```
public final int getPriority()
```


Gets or sets the current Priority of the Task object.

**Returns:**
int
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets the collection of properties.

Value: The properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Gets MAPI property by property descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Property descriptor for looked property |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


Gets the value of the property specified by tag as Boolean type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Boolean - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


Gets the string value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
byte[] - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


Gets the value of the property specified by tag as DateTime type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The MAPI property tag. |

**Returns:**
java.util.Date - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


Gets the int32 value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Integer - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


Gets the value of the property specified by tag as Long (int64) type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Long - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


Gets the value of the property specified by tag as Short type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Short - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream.

Value: The property stream.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream)
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


Gets the string value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.String - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


Gets the string value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| codepage | int | The specified codepage used to get string value. |

**Returns:**
java.lang.String - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Gets the recipients of the message.

Value: The collection of recipients.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### getRecurrence() {#getRecurrence--}
```
public final MapiCalendarRecurrencePattern getRecurrence()
```


Gets or sets the recurrence properties.

**Returns:**
[MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern)
### getReminderFileParameter() {#getReminderFileParameter--}
```
public final String getReminderFileParameter()
```


Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue.

**Returns:**
java.lang.String
### getReminderSet() {#getReminderSet--}
```
public final boolean getReminderSet()
```


Gets or sets a value indicating whether a reminder is set on the object

**Returns:**
boolean
### getReminderTime() {#getReminderTime--}
```
public final Date getReminderTime()
```


Gets or sets the initial signal time for a reminder

**Returns:**
java.util.Date
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the Sensitivity.

Value: The sensitivity.

**Returns:**
int
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets the date on which the user expects work on the task to begin.

**Returns:**
java.util.Date
### getState() {#getState--}
```
public final int getState()
```


Gets or sets the current assignment state of the Task object.

**Returns:**
int
### getStatus() {#getStatus--}
```
public final int getStatus()
```


Gets or sets the status of the user's progress on the task.

**Returns:**
int
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub storages.

Value: The sub storages.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets the subject of the message.

Value: The string that represents message subject.

--------------------

When setting a value, the values of SubjectPrefix(PR\_SUBJECT\_PREFIX) and NormalizedSubject(PR\_NORMALIZED\_SUBJECT) properties are updated as well. If Subject has no prefix, the value of SubjectPrefix property is set null. When setting a null value or empty string, the values of Subject, SubjectPrefix, NormalizedSubject properties are set null.

**Returns:**
java.lang.String
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding.

Value: The string that represents subject prefix.

**Returns:**
java.lang.String
### getSupportedType() {#getSupportedType--}
```
public final int getSupportedType()
```


Gets the supported item type.

Value: The [MapiItemType](../../com.aspose.email/mapiitemtype).

**Returns:**
int
### getUnderlyingMessage() {#getUnderlyingMessage--}
```
public final MapiMessage getUnderlyingMessage()
```


Retrieves the underlying MapiMessage object.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The [MapiMessage](../../com.aspose.email/mapimessage) object.

Retrieves the underlying MAPI message from a MapiTask object and prints out its message class.

```

 // Retrieve the underlying MAPI message from the MapiTask object
 MapiMessage msg = mapiTask.getUnderlyingMessage();

 // Print out the message class of the MAPI message
 // Will output "IPM.Task"
 System.out.println(msg.getMessageClass());
 
```
### getUsers() {#getUsers--}
```
public final MapiTaskUsers getUsers()
```


Gets or sets information about task users.

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


Determines if string properties are Unicode encoded or not.

**Returns:**
boolean - True, if string properties are Unicode encoded.
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


Provides correctly removing property from all collections.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of MapiProperty. |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Saves this [MapiTask](../../com.aspose.email/mapitask) to the given stream using specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveFormat | int |  |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Saves this [MapiTask](../../com.aspose.email/mapitask) into file using specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveFormat | int |  |

### setAcceptanceState(int value) {#setAcceptanceState-int-}
```
public final void setAcceptanceState(int value)
```


Gets or sets the acceptance state of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setActualEffort(int value) {#setActualEffort-int-}
```
public final void setActualEffort(int value)
```


Gets or sets the number of minutes that the user actually spent working on a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Contains the billing information associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Gets the message text.

Value: The string that represents message body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


Sets the content of the body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content. |
| contentType | int | Type of the content.

--------------------

It is provided for setting of the content of the body message in RTF, HTML or Plain Text formats. When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated as well. Note, after the value in HTML format is set, BodyRtf property returns the value which is encoded within RTF. |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


Sets the content of the body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content. |
| contentType | int | Type of the content. |
| compression | boolean | Specify that the content should be compressed.

--------------------

It is provided for setting of the content of the body message in RTF, HTML or Plain Text formats. When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated as well. Note, after the value in HTML format is set, BodyRtf property returns the value which is encoded within RTF. |

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
| compression | boolean | Specify that the content should be compressed. |

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Contains keywords or categories for the message object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Contains the names of the companies that are associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setDateCompleted(Date value) {#setDateCompleted-java.util.Date-}
```
public final void setDateCompleted(Date value)
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

### setEstimatedEffort(int value) {#setEstimatedEffort-int-}
```
public final void setEstimatedEffort(int value)
```


Gets or sets the number of minutes that the user expects to work on a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHistory(int value) {#setHistory-int-}
```
public final void setHistory(int value)
```


Gets or sets the type of change that was last made to the Task object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLastUpdate(Date value) {#setLastUpdate-java.util.Date-}
```
public final void setLastUpdate(Date value)
```


Gets or sets the date and time of the most recent change made to the Task object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message.

Value: The string that represents message class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


Sets the message flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The message flags. |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Contains the mileage information that is associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Gets or sets the assignment status of the Task object.

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


Gets or sets the progress the user has made on a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPriority(int value) {#setPriority-int-}
```
public final void setPriority(int value)
```


Gets or sets the current Priority of the Task object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Sets the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property. |

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


Sets MAPI property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The property descriptor. |
| value | java.lang.Object | The property data. |

### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


Gets the recipients of the message.

Value: The collection of recipients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) |  |

### setRecurrence(MapiCalendarRecurrencePattern value) {#setRecurrence-com.aspose.email.MapiCalendarRecurrencePattern-}
```
public final void setRecurrence(MapiCalendarRecurrencePattern value)
```


Gets or sets the recurrence properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern) |  |

### setReminderFileParameter(String value) {#setReminderFileParameter-java.lang.String-}
```
public final void setReminderFileParameter(String value)
```


Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setReminderSet(boolean value) {#setReminderSet-boolean-}
```
public final void setReminderSet(boolean value)
```


Gets or sets a value indicating whether a reminder is set on the object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setReminderTime(Date value) {#setReminderTime-java.util.Date-}
```
public final void setReminderTime(Date value)
```


Gets or sets the initial signal time for a reminder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Gets the Sensitivity.

Value: The sensitivity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets the date on which the user expects work on the task to begin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setState(int value) {#setState-int-}
```
public final void setState(int value)
```


Gets or sets the current assignment state of the Task object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Gets or sets the status of the user's progress on the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets the subject of the message.

Value: The string that represents message subject.

--------------------

When setting a value, the values of SubjectPrefix(PR\_SUBJECT\_PREFIX) and NormalizedSubject(PR\_NORMALIZED\_SUBJECT) properties are updated as well. If Subject has no prefix, the value of SubjectPrefix property is set null. When setting a null value or empty string, the values of Subject, SubjectPrefix, NormalizedSubject properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUsers(MapiTaskUsers value) {#setUsers-com.aspose.email.MapiTaskUsers-}
```
public final void setUsers(MapiTaskUsers value)
```


Gets or sets information about task users.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiTaskUsers](../../com.aspose.email/mapitaskusers) |  |

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


Try to get the property data with specified tag key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag key. |

**Returns:**
byte[] - The property data.
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


Gets the value of the specified property as DateTime type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | java.util.Date[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


Gets the value of the specified property as Int32 type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | int[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


Gets the value of the specified property as Long type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | long[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


Try to get a property data as string with specified tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The property tag key. |

**Returns:**
java.lang.String - String that contains the contents of property data.
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


Try to get a property data as string with specified tag and code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The property tag key. |
| codepage | int | The code page. |

**Returns:**
java.lang.String - String that contains the contents of property data.
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


Gets the value of the specified property as String type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | java.lang.String[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


Gets the value of the specified property as String type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | java.lang.String[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |
| codepage | int | The specified codepage used to get string value. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
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

