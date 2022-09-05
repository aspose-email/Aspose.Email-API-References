---
title: MapiJournal
second_title: Aspose.Email for Java API Reference
description:  Represents the Outlook Journal object.
type: docs
weight: 440
url: /java/com.aspose.email/mapijournal/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiJournal extends MapiMessageItemBase
```

Represents the Outlook Journal object.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiJournal()](#MapiJournal--) | Initializes a new instance of the [MapiJournal](../../com.aspose.email/mapijournal) class. |
| [MapiJournal(String subject, String body, String description, String briefDescription)](#MapiJournal-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [MapiJournal](../../com.aspose.email/mapijournal) class. |
## Methods

| Method | Description |
| --- | --- |
| [getBriefDescription()](#getBriefDescription--) | Gets or sets the brief description of activity that is being recorded. |
| [setBriefDescription(String value)](#setBriefDescription-java.lang.String-) | Gets or sets the brief description of activity that is being recorded. |
| [getDescription()](#getDescription--) | Gets or sets the description of activity that is being recorded. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Gets or sets the description of activity that is being recorded. |
| [getStartTime()](#getStartTime--) | Gets or sets the time at which the activity began. |
| [setStartTime(Date value)](#setStartTime-java.util.Date-) | Gets or sets the time at which the activity began. |
| [getEndTime()](#getEndTime--) | Gets or sets the time at which the activity ended. |
| [setEndTime(Date value)](#setEndTime-java.util.Date-) | Gets or sets the time at which the activity ended. |
| [getDuration()](#getDuration--) | Gets the duration of the activity. |
| [getDocumentStatus()](#getDocumentStatus--) | Gets or sets the status of document. |
| [setDocumentStatus(int value)](#setDocumentStatus-int-) | Gets or sets the status of document. |
| [getFlags()](#getFlags--) | Gets or sets a flags that contains metadata about the Journal object. |
| [setFlags(int value)](#setFlags-int-) | Gets or sets a flags that contains metadata about the Journal object. |
| [save(String fileName)](#save-java.lang.String-) | Saves the specified file name. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the specified stream. |
### MapiJournal() {#MapiJournal--}
```
public MapiJournal()
```


Initializes a new instance of the [MapiJournal](../../com.aspose.email/mapijournal) class.

### MapiJournal(String subject, String body, String description, String briefDescription) {#MapiJournal-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiJournal(String subject, String body, String description, String briefDescription)
```


Initializes a new instance of the [MapiJournal](../../com.aspose.email/mapijournal) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subject | java.lang.String | The subject. |
| body | java.lang.String | The message body. |
| description | java.lang.String | The description. |
| briefDescription | java.lang.String | The brief description. |

### getBriefDescription() {#getBriefDescription--}
```
public final String getBriefDescription()
```


Gets or sets the brief description of activity that is being recorded.

Value: The string that represents activity.

**Returns:**
java.lang.String
### setBriefDescription(String value) {#setBriefDescription-java.lang.String-}
```
public final void setBriefDescription(String value)
```


Gets or sets the brief description of activity that is being recorded.

Value: The string that represents activity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets or sets the description of activity that is being recorded.

Value: The string that represents activity.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Gets or sets the description of activity that is being recorded.

Value: The string that represents activity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getStartTime() {#getStartTime--}
```
public final Date getStartTime()
```


Gets or sets the time at which the activity began.

**Returns:**
java.util.Date
### setStartTime(Date value) {#setStartTime-java.util.Date-}
```
public final void setStartTime(Date value)
```


Gets or sets the time at which the activity began.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getEndTime() {#getEndTime--}
```
public final Date getEndTime()
```


Gets or sets the time at which the activity ended.

**Returns:**
java.util.Date
### setEndTime(Date value) {#setEndTime-java.util.Date-}
```
public final void setEndTime(Date value)
```


Gets or sets the time at which the activity ended.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getDuration() {#getDuration--}
```
public final double getDuration()
```


Gets the duration of the activity.

Value: The value that represents duration of the activity.

**Returns:**
double
### getDocumentStatus() {#getDocumentStatus--}
```
public final int getDocumentStatus()
```


Gets or sets the status of document.

Value: The document status.

**Returns:**
int
### setDocumentStatus(int value) {#setDocumentStatus-int-}
```
public final void setDocumentStatus(int value)
```


Gets or sets the status of document.

Value: The document status.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public final int getFlags()
```


Gets or sets a flags that contains metadata about the Journal object.

Value: The journal flags.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public final void setFlags(int value)
```


Gets or sets a flags that contains metadata about the Journal object.

Value: The journal flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### save(String fileName) {#save-java.lang.String-}
```
public final void save(String fileName)
```


Saves the specified file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream. |

