---
title: MapiTask
second_title: Aspose.Email for Java API Reference
description:  Represents the Outlook Task object.
type: docs
weight: 467
url: /java/com.aspose.email/mapitask/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public class MapiTask extends MapiMessageItemBase
```

Represents the Outlook Task object.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiTask()](#MapiTask--) | Initializes a new instance of the [MapiTask](../../com.aspose.email/mapitask) class. |
| [MapiTask(String subject, String body, Date startDate, Date dueDate)](#MapiTask-java.lang.String-java.lang.String-java.util.Date-java.util.Date-) | Initializes a new instance of the [MapiTask](../../com.aspose.email/mapitask) class. |
## Methods

| Method | Description |
| --- | --- |
| [getPercentComplete()](#getPercentComplete--) | Gets or sets the progress the user has made on a task. |
| [setPercentComplete(int value)](#setPercentComplete-int-) | Gets or sets the progress the user has made on a task. |
| [getActualEffort()](#getActualEffort--) | Gets or sets the number of minutes that the user actually spent working on a task. |
| [setActualEffort(int value)](#setActualEffort-int-) | Gets or sets the number of minutes that the user actually spent working on a task. |
| [getEstimatedEffort()](#getEstimatedEffort--) | Gets or sets the number of minutes that the user expects to work on a task. |
| [setEstimatedEffort(int value)](#setEstimatedEffort-int-) | Gets or sets the number of minutes that the user expects to work on a task. |
| [getDueDate()](#getDueDate--) | Gets or sets the date by which the user expects work on the task to be complete. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Gets or sets the date by which the user expects work on the task to be complete. |
| [getStartDate()](#getStartDate--) | Gets or sets the date on which the user expects work on the task to begin. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets the date on which the user expects work on the task to begin. |
| [getDateCompleted()](#getDateCompleted--) | Gets or sets the date when the user completed work on the task. |
| [setDateCompleted(Date value)](#setDateCompleted-java.util.Date-) | Gets or sets the date when the user completed work on the task. |
| [getLastUpdate()](#getLastUpdate--) | Gets or sets the date and time of the most recent change made to the Task object. |
| [setLastUpdate(Date value)](#setLastUpdate-java.util.Date-) | Gets or sets the date and time of the most recent change made to the Task object. |
| [getRecurrence()](#getRecurrence--) | Gets or sets the recurrence properties. |
| [setRecurrence(MapiCalendarRecurrencePattern value)](#setRecurrence-com.aspose.email.MapiCalendarRecurrencePattern-) | Gets or sets the recurrence properties. |
| [getHistory()](#getHistory--) | Gets or sets the type of change that was last made to the Task object. |
| [setHistory(int value)](#setHistory-int-) | Gets or sets the type of change that was last made to the Task object. |
| [getUsers()](#getUsers--) | Gets or sets information about task users. |
| [setUsers(MapiTaskUsers value)](#setUsers-com.aspose.email.MapiTaskUsers-) | Gets or sets information about task users. |
| [getStatus()](#getStatus--) | Gets or sets the status of the user's progress on the task. |
| [setStatus(int value)](#setStatus-int-) | Gets or sets the status of the user's progress on the task. |
| [getMode()](#getMode--) | Gets or sets the assignment status of the Task object. |
| [setMode(int value)](#setMode-int-) | Gets or sets the assignment status of the Task object. |
| [getState()](#getState--) | Gets or sets the current assignment state of the Task object. |
| [setState(int value)](#setState-int-) | Gets or sets the current assignment state of the Task object. |
| [getAcceptanceState()](#getAcceptanceState--) | Gets or sets the acceptance state of the task. |
| [setAcceptanceState(int value)](#setAcceptanceState-int-) | Gets or sets the acceptance state of the task. |
| [getFlags()](#getFlags--) | Gets the indication flags of the Task object. |
| [getReminderTime()](#getReminderTime--) | Gets or sets the initial signal time for a reminder |
| [setReminderTime(Date value)](#setReminderTime-java.util.Date-) | Gets or sets the initial signal time for a reminder |
| [getReminderSet()](#getReminderSet--) | Gets or sets a value indicating whether a reminder is set on the object |
| [setReminderSet(boolean value)](#setReminderSet-boolean-) | Gets or sets a value indicating whether a reminder is set on the object |
| [getReminderFileParameter()](#getReminderFileParameter--) | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [setReminderFileParameter(String value)](#setReminderFileParameter-java.lang.String-) | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves this [MapiTask](../../com.aspose.email/mapitask) to the given stream using specified format. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves this [MapiTask](../../com.aspose.email/mapitask) into file using specified format. |
| [fromVTodo(String filePath)](#fromVTodo-java.lang.String-) | Creates an instance of MapiTask from the specified .ics file. |
| [fromVTodo(String filePath, boolean detectEncoding)](#fromVTodo-java.lang.String-boolean-) | Creates an instance of MapiTask from the specified .ics file. |
| [fromVTodo(InputStream stream)](#fromVTodo-java.io.InputStream-) | Creates an instance of MapiTask from the specified stream. |
| [fromVTodo(InputStream stream, boolean detectEncoding)](#fromVTodo-java.io.InputStream-boolean-) | Creates an instance of MapiTask from the specified stream. |
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

### getPercentComplete() {#getPercentComplete--}
```
public final int getPercentComplete()
```


Gets or sets the progress the user has made on a task.

**Returns:**
int
### setPercentComplete(int value) {#setPercentComplete-int-}
```
public final void setPercentComplete(int value)
```


Gets or sets the progress the user has made on a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualEffort() {#getActualEffort--}
```
public final int getActualEffort()
```


Gets or sets the number of minutes that the user actually spent working on a task.

**Returns:**
int
### setActualEffort(int value) {#setActualEffort-int-}
```
public final void setActualEffort(int value)
```


Gets or sets the number of minutes that the user actually spent working on a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEstimatedEffort() {#getEstimatedEffort--}
```
public final int getEstimatedEffort()
```


Gets or sets the number of minutes that the user expects to work on a task.

**Returns:**
int
### setEstimatedEffort(int value) {#setEstimatedEffort-int-}
```
public final void setEstimatedEffort(int value)
```


Gets or sets the number of minutes that the user expects to work on a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


Gets or sets the date by which the user expects work on the task to be complete.

**Returns:**
java.util.Date
### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


Gets or sets the date by which the user expects work on the task to be complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets the date on which the user expects work on the task to begin.

**Returns:**
java.util.Date
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets the date on which the user expects work on the task to begin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getDateCompleted() {#getDateCompleted--}
```
public final Date getDateCompleted()
```


Gets or sets the date when the user completed work on the task.

**Returns:**
java.util.Date
### setDateCompleted(Date value) {#setDateCompleted-java.util.Date-}
```
public final void setDateCompleted(Date value)
```


Gets or sets the date when the user completed work on the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastUpdate() {#getLastUpdate--}
```
public final Date getLastUpdate()
```


Gets or sets the date and time of the most recent change made to the Task object.

**Returns:**
java.util.Date
### setLastUpdate(Date value) {#setLastUpdate-java.util.Date-}
```
public final void setLastUpdate(Date value)
```


Gets or sets the date and time of the most recent change made to the Task object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getRecurrence() {#getRecurrence--}
```
public final MapiCalendarRecurrencePattern getRecurrence()
```


Gets or sets the recurrence properties.

**Returns:**
[MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern)
### setRecurrence(MapiCalendarRecurrencePattern value) {#setRecurrence-com.aspose.email.MapiCalendarRecurrencePattern-}
```
public final void setRecurrence(MapiCalendarRecurrencePattern value)
```


Gets or sets the recurrence properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern) |  |

### getHistory() {#getHistory--}
```
public final int getHistory()
```


Gets or sets the type of change that was last made to the Task object.

**Returns:**
int
### setHistory(int value) {#setHistory-int-}
```
public final void setHistory(int value)
```


Gets or sets the type of change that was last made to the Task object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUsers() {#getUsers--}
```
public final MapiTaskUsers getUsers()
```


Gets or sets information about task users.

**Returns:**
[MapiTaskUsers](../../com.aspose.email/mapitaskusers)
### setUsers(MapiTaskUsers value) {#setUsers-com.aspose.email.MapiTaskUsers-}
```
public final void setUsers(MapiTaskUsers value)
```


Gets or sets information about task users.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiTaskUsers](../../com.aspose.email/mapitaskusers) |  |

### getStatus() {#getStatus--}
```
public final int getStatus()
```


Gets or sets the status of the user's progress on the task.

**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Gets or sets the status of the user's progress on the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Gets or sets the assignment status of the Task object.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Gets or sets the assignment status of the Task object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getState() {#getState--}
```
public final int getState()
```


Gets or sets the current assignment state of the Task object.

**Returns:**
int
### setState(int value) {#setState-int-}
```
public final void setState(int value)
```


Gets or sets the current assignment state of the Task object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAcceptanceState() {#getAcceptanceState--}
```
public final int getAcceptanceState()
```


Gets or sets the acceptance state of the task.

**Returns:**
int
### setAcceptanceState(int value) {#setAcceptanceState-int-}
```
public final void setAcceptanceState(int value)
```


Gets or sets the acceptance state of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public final int getFlags()
```


Gets the indication flags of the Task object.

**Returns:**
int
### getReminderTime() {#getReminderTime--}
```
public final Date getReminderTime()
```


Gets or sets the initial signal time for a reminder

**Returns:**
java.util.Date
### setReminderTime(Date value) {#setReminderTime-java.util.Date-}
```
public final void setReminderTime(Date value)
```


Gets or sets the initial signal time for a reminder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getReminderSet() {#getReminderSet--}
```
public final boolean getReminderSet()
```


Gets or sets a value indicating whether a reminder is set on the object

**Returns:**
boolean
### setReminderSet(boolean value) {#setReminderSet-boolean-}
```
public final void setReminderSet(boolean value)
```


Gets or sets a value indicating whether a reminder is set on the object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getReminderFileParameter() {#getReminderFileParameter--}
```
public final String getReminderFileParameter()
```


Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue.

**Returns:**
java.lang.String
### setReminderFileParameter(String value) {#setReminderFileParameter-java.lang.String-}
```
public final void setReminderFileParameter(String value)
```


Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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
