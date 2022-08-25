---
title: CalendarDeletionOptions
second_title: Aspose.Email for Java API Reference
description:  Defines parameters for item deletion
type: docs
weight: 92
url: /java/com.aspose.email/calendardeletionoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.DeletionOptions](../../com.aspose.email/deletionoptions)
```
public class CalendarDeletionOptions extends DeletionOptions
```

Defines parameters for item deletion
## Constructors

| Constructor | Description |
| --- | --- |
| [CalendarDeletionOptions()](#CalendarDeletionOptions--) | Initializes a new instance of the [CalendarDeletionOptions](../../com.aspose.email/calendardeletionoptions) class. |
| [CalendarDeletionOptions(int type)](#CalendarDeletionOptions-int-) | Initializes a new instance of the [CalendarDeletionOptions](../../com.aspose.email/calendardeletionoptions) class. |
| [CalendarDeletionOptions(int type, int notyficationType)](#CalendarDeletionOptions-int-int-) | Initializes a new instance of the [CalendarDeletionOptions](../../com.aspose.email/calendardeletionoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getDefault()](#getDefault--) | Gets instance of the [DeletionOptions](../../com.aspose.email/deletionoptions) object with settings uses by default |
| [getDeletePermanently()](#getDeletePermanently--) | Gets instance of the [DeletionOptions](../../com.aspose.email/deletionoptions) object with settings for permanent deletion |
| [getMoveToDeletedItems()](#getMoveToDeletedItems--) | Gets instance of the [DeletionOptions](../../com.aspose.email/deletionoptions) object with settings for moving to deleted items |
| [getNotyficationType()](#getNotyficationType--) | Gets or sets value which indicates how members of event has to be notified |
| [setNotyficationType(int value)](#setNotyficationType-int-) | Gets or sets value which indicates how members of event has to be notified |
### CalendarDeletionOptions() {#CalendarDeletionOptions--}
```
public CalendarDeletionOptions()
```


Initializes a new instance of the [CalendarDeletionOptions](../../com.aspose.email/calendardeletionoptions) class.

### CalendarDeletionOptions(int type) {#CalendarDeletionOptions-int-}
```
public CalendarDeletionOptions(int type)
```


Initializes a new instance of the [CalendarDeletionOptions](../../com.aspose.email/calendardeletionoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of deletion |

### CalendarDeletionOptions(int type, int notyficationType) {#CalendarDeletionOptions-int-int-}
```
public CalendarDeletionOptions(int type, int notyficationType)
```


Initializes a new instance of the [CalendarDeletionOptions](../../com.aspose.email/calendardeletionoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of deletion |
| notyficationType | int | indicates how members of event has to be notified |

### getDefault() {#getDefault--}
```
public static CalendarDeletionOptions getDefault()
```


Gets instance of the [DeletionOptions](../../com.aspose.email/deletionoptions) object with settings uses by default

**Returns:**
[CalendarDeletionOptions](../../com.aspose.email/calendardeletionoptions)
### getDeletePermanently() {#getDeletePermanently--}
```
public static CalendarDeletionOptions getDeletePermanently()
```


Gets instance of the [DeletionOptions](../../com.aspose.email/deletionoptions) object with settings for permanent deletion

**Returns:**
[CalendarDeletionOptions](../../com.aspose.email/calendardeletionoptions)
### getMoveToDeletedItems() {#getMoveToDeletedItems--}
```
public static CalendarDeletionOptions getMoveToDeletedItems()
```


Gets instance of the [DeletionOptions](../../com.aspose.email/deletionoptions) object with settings for moving to deleted items

**Returns:**
[CalendarDeletionOptions](../../com.aspose.email/calendardeletionoptions)
### getNotyficationType() {#getNotyficationType--}
```
public final int getNotyficationType()
```


Gets or sets value which indicates how members of event has to be notified

**Returns:**
int
### setNotyficationType(int value) {#setNotyficationType-int-}
```
public final void setNotyficationType(int value)
```


Gets or sets value which indicates how members of event has to be notified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

