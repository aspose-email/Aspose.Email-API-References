---
title: IcsSaveOptions
second_title: Aspose.Email for Java API Reference
description:  Represents iCalendar save options
type: docs
weight: 299
url: /java/com.aspose.email/icssaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions)
```
public final class IcsSaveOptions extends AppointmentSaveOptions
```

Represents iCalendar save options
## Constructors

| Constructor | Description |
| --- | --- |
| [IcsSaveOptions()](#IcsSaveOptions--) | Initializes a new instance of the [IcsSaveOptions](../../com.aspose.email/icssaveoptions) class |
| [IcsSaveOptions(int method)](#IcsSaveOptions-int-) | Initializes a new instance of the [IcsSaveOptions](../../com.aspose.email/icssaveoptions) class |
## Methods

| Method | Description |
| --- | --- |
| [getDefault()](#getDefault--) | Gets the default Ics save options |
| [getAction()](#getAction--) | Gets or sets appointment Action |
| [setAction(int value)](#setAction-int-) | Gets or sets appointment Action |
| [getProductId()](#getProductId--) | Gets or sets the product identifier that created iCalendar object. |
| [setProductId(String value)](#setProductId-java.lang.String-) | Gets or sets the product identifier that created iCalendar object. |
| [getSequenceId()](#getSequenceId--) | Gets or sets the sequence id. |
| [setSequenceId(int value)](#setSequenceId-int-) | Gets or sets the sequence id. |
| [getMethodType()](#getMethodType--) | Gets or sets the iCalendar object method type associated with the calendar object. |
| [setMethodType(int value)](#setMethodType-int-) | Gets or sets the iCalendar object method type associated with the calendar object. |
| [getStartTimeZone()](#getStartTimeZone--) | Gets or sets the Start time zone. |
| [setStartTimeZone(String value)](#setStartTimeZone-java.lang.String-) | Gets or sets the Start time zone. |
| [getEndTimeZone()](#getEndTimeZone--) | Gets or sets the End time zone. |
| [setEndTimeZone(String value)](#setEndTimeZone-java.lang.String-) | Gets or sets the End time zone. |
| [getCreateNew()](#getCreateNew--) | Gets or sets value indicating whether need create new calendar or append events in existing calendar. |
| [setCreateNew(boolean value)](#setCreateNew-boolean-) | Gets or sets value indicating whether need create new calendar or append events in existing calendar. |
### IcsSaveOptions() {#IcsSaveOptions--}
```
public IcsSaveOptions()
```


Initializes a new instance of the [IcsSaveOptions](../../com.aspose.email/icssaveoptions) class

### IcsSaveOptions(int method) {#IcsSaveOptions-int-}
```
public IcsSaveOptions(int method)
```


Initializes a new instance of the [IcsSaveOptions](../../com.aspose.email/icssaveoptions) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| method | int | An appointment method |

### getDefault() {#getDefault--}
```
public static IcsSaveOptions getDefault()
```


Gets the default Ics save options

**Returns:**
[IcsSaveOptions](../../com.aspose.email/icssaveoptions)
### getAction() {#getAction--}
```
public final int getAction()
```


Gets or sets appointment Action

**Returns:**
int
### setAction(int value) {#setAction-int-}
```
public final void setAction(int value)
```


Gets or sets appointment Action

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getProductId() {#getProductId--}
```
public final String getProductId()
```


Gets or sets the product identifier that created iCalendar object.

Value: The product identifier.

**Returns:**
java.lang.String
### setProductId(String value) {#setProductId-java.lang.String-}
```
public final void setProductId(String value)
```


Gets or sets the product identifier that created iCalendar object.

Value: The product identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


Gets or sets the sequence id.

Value: The sequence id.

**Returns:**
int
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

### getMethodType() {#getMethodType--}
```
public final int getMethodType()
```


Gets or sets the iCalendar object method type associated with the calendar object.

**Returns:**
int
### setMethodType(int value) {#setMethodType-int-}
```
public final void setMethodType(int value)
```


Gets or sets the iCalendar object method type associated with the calendar object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStartTimeZone() {#getStartTimeZone--}
```
public final String getStartTimeZone()
```


Gets or sets the Start time zone.

**Returns:**
java.lang.String
### setStartTimeZone(String value) {#setStartTimeZone-java.lang.String-}
```
public final void setStartTimeZone(String value)
```


Gets or sets the Start time zone.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEndTimeZone() {#getEndTimeZone--}
```
public final String getEndTimeZone()
```


Gets or sets the End time zone.

**Returns:**
java.lang.String
### setEndTimeZone(String value) {#setEndTimeZone-java.lang.String-}
```
public final void setEndTimeZone(String value)
```


Gets or sets the End time zone.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreateNew() {#getCreateNew--}
```
public final boolean getCreateNew()
```


Gets or sets value indicating whether need create new calendar or append events in existing calendar. Default value is true.

**Returns:**
boolean
### setCreateNew(boolean value) {#setCreateNew-boolean-}
```
public final void setCreateNew(boolean value)
```


Gets or sets value indicating whether need create new calendar or append events in existing calendar. Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

