---
title: ExchangeTask
second_title: Aspose.Email for Java API Reference
description:  Represents the exchange task information.
type: docs
weight: 227
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
| [getStatus()](#getStatus--) | Gets or sets a task status. |
| [setStatus(int value)](#setStatus-int-) | Gets or sets a task status. |
| [getTotalWork()](#getTotalWork--) | Gets or sets a total amount of work that the user expects to work on a task. |
| [setTotalWork(int value)](#setTotalWork-int-) | Gets or sets a total amount of work that the user expects to work on a task. |
| [getActualWork()](#getActualWork--) | Gets or sets an actual amount of time that is spent on a task (minutes). |
| [setActualWork(int value)](#setActualWork-int-) | Gets or sets an actual amount of time that is spent on a task (minutes). |
| [getMileage()](#getMileage--) | Gets or sets a mileage for a task. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Gets or sets a mileage for a task. |
| [getBillingInformation()](#getBillingInformation--) | Gets or sets a billing information for the task. |
| [setBillingInformation(String value)](#setBillingInformation-java.lang.String-) | Gets or sets a billing information for the task. |
| [getCompanies()](#getCompanies--) | Gets or sets a collection of companies that are associated with a task. |
| [setCompanies(System.Collections.Specialized.StringCollection value)](#setCompanies-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets a collection of companies that are associated with a task. |
| [getRecurrencePattern()](#getRecurrencePattern--) | Gets or sets a recurrence information for a recurring task. |
| [setRecurrencePattern(RecurrencePattern value)](#setRecurrencePattern-com.aspose.email.RecurrencePattern-) | Gets or sets a recurrence information for a recurring task. |
| [getReminderDate()](#getReminderDate--) | Gets or sets a task reminder date. |
| [setReminderDate(Date value)](#setReminderDate-java.util.Date-) | Gets or sets a task reminder date. |
| [isBodyHtml()](#isBodyHtml--) | Gets or sets a value indicating whether the task body is html-formatted. |
| [setBodyHtml(boolean value)](#setBodyHtml-boolean-) | Gets or sets a value indicating whether the task body is html-formatted. |
| [getCompletionDate()](#getCompletionDate--) | Gets or sets the date when the user completed work on the task. |
| [setCompletionDate(Date value)](#setCompletionDate-java.util.Date-) | Gets or sets the date when the user completed work on the task. |
| [getUniqueUri()](#getUniqueUri--) | Gets or sets an unique uri of the task. |
| [setUniqueUri(String value)](#setUniqueUri-java.lang.String-) | Gets or sets an unique uri of the task. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves current object to the given stream using specified format. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves current object into file using specified format. |
### ExchangeTask() {#ExchangeTask--}
```
public ExchangeTask()
```


Initializes a new instance of the [ExchangeTask](../../com.aspose.email/exchangetask) class.

### getStatus() {#getStatus--}
```
public final int getStatus()
```


Gets or sets a task status.

**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Gets or sets a task status.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTotalWork() {#getTotalWork--}
```
public final int getTotalWork()
```


Gets or sets a total amount of work that the user expects to work on a task.

**Returns:**
int
### setTotalWork(int value) {#setTotalWork-int-}
```
public final void setTotalWork(int value)
```


Gets or sets a total amount of work that the user expects to work on a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualWork() {#getActualWork--}
```
public final int getActualWork()
```


Gets or sets an actual amount of time that is spent on a task (minutes).

**Returns:**
int
### setActualWork(int value) {#setActualWork-int-}
```
public final void setActualWork(int value)
```


Gets or sets an actual amount of time that is spent on a task (minutes).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMileage() {#getMileage--}
```
public final String getMileage()
```


Gets or sets a mileage for a task.

**Returns:**
java.lang.String
### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Gets or sets a mileage for a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBillingInformation() {#getBillingInformation--}
```
public final String getBillingInformation()
```


Gets or sets a billing information for the task.

**Returns:**
java.lang.String
### setBillingInformation(String value) {#setBillingInformation-java.lang.String-}
```
public final void setBillingInformation(String value)
```


Gets or sets a billing information for the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompanies() {#getCompanies--}
```
public final System.Collections.Specialized.StringCollection getCompanies()
```


Gets or sets a collection of companies that are associated with a task.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### setCompanies(System.Collections.Specialized.StringCollection value) {#setCompanies-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setCompanies(System.Collections.Specialized.StringCollection value)
```


Gets or sets a collection of companies that are associated with a task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### getRecurrencePattern() {#getRecurrencePattern--}
```
public final RecurrencePattern getRecurrencePattern()
```


Gets or sets a recurrence information for a recurring task.

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern)
### setRecurrencePattern(RecurrencePattern value) {#setRecurrencePattern-com.aspose.email.RecurrencePattern-}
```
public final void setRecurrencePattern(RecurrencePattern value)
```


Gets or sets a recurrence information for a recurring task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RecurrencePattern](../../com.aspose.email/recurrencepattern) |  |

### getReminderDate() {#getReminderDate--}
```
public final Date getReminderDate()
```


Gets or sets a task reminder date.

**Returns:**
java.util.Date
### setReminderDate(Date value) {#setReminderDate-java.util.Date-}
```
public final void setReminderDate(Date value)
```


Gets or sets a task reminder date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### isBodyHtml() {#isBodyHtml--}
```
public final boolean isBodyHtml()
```


Gets or sets a value indicating whether the task body is html-formatted.

**Returns:**
boolean
### setBodyHtml(boolean value) {#setBodyHtml-boolean-}
```
public final void setBodyHtml(boolean value)
```


Gets or sets a value indicating whether the task body is html-formatted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompletionDate() {#getCompletionDate--}
```
public final Date getCompletionDate()
```


Gets or sets the date when the user completed work on the task.

**Returns:**
java.util.Date
### setCompletionDate(Date value) {#setCompletionDate-java.util.Date-}
```
public final void setCompletionDate(Date value)
```


Gets or sets the date when the user completed work on the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getUniqueUri() {#getUniqueUri--}
```
public final String getUniqueUri()
```


Gets or sets an unique uri of the task.

**Returns:**
java.lang.String
### setUniqueUri(String value) {#setUniqueUri-java.lang.String-}
```
public final void setUniqueUri(String value)
```


Gets or sets an unique uri of the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

