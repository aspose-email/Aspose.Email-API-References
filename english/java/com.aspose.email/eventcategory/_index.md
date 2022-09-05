---
title: EventCategory
second_title: Aspose.Email for Java API Reference
description:  Represents category for an event
type: docs
weight: 181
url: /java/com.aspose.email/eventcategory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class EventCategory implements System.IEquatable<EventCategory>
```

Represents category for an event
## Constructors

| Constructor | Description |
| --- | --- |
| [EventCategory(String description)](#EventCategory-java.lang.String-) | Initializes a new instance of the 'Custom' [EventCategory](../../com.aspose.email/eventcategory). |
## Fields

| Field | Description |
| --- | --- |
| [CUSTOM_VALUE](#CUSTOM-VALUE) | String value for 'Custom' category |
| [BIRTHDAY_VALUE](#BIRTHDAY-VALUE) | String value for 'Birthday' category |
| [ANNIVERSARY_VALUE](#ANNIVERSARY-VALUE) | String value for 'Anniversary' category |
## Methods

| Method | Description |
| --- | --- |
| [getBirthday()](#getBirthday--) | Birthday |
| [getAnniversary()](#getAnniversary--) | Anniversary |
| [getCustom()](#getCustom--) | Custom description |
| [getValue()](#getValue--) | Gets string representation of an event category |
| [getDescription()](#getDescription--) | Gets description for the 'Custom' category of an event |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [op_Equality(EventCategory a, EventCategory b)](#op-Equality-com.aspose.email.EventCategory-com.aspose.email.EventCategory-) | Determines whether the specified objects are equal. |
| [op_Inequality(EventCategory a, EventCategory b)](#op-Inequality-com.aspose.email.EventCategory-com.aspose.email.EventCategory-) | Determines whether the specified objects are not equal. |
| [equals(EventCategory other)](#equals-com.aspose.email.EventCategory-) | Determines whether the specified object is equal to the current object. |
### EventCategory(String description) {#EventCategory-java.lang.String-}
```
public EventCategory(String description)
```


Initializes a new instance of the 'Custom' [EventCategory](../../com.aspose.email/eventcategory).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | Description for the 'Custom' category of an event |

### CUSTOM_VALUE {#CUSTOM-VALUE}
```
public static final String CUSTOM_VALUE
```


String value for 'Custom' category

### BIRTHDAY_VALUE {#BIRTHDAY-VALUE}
```
public static final String BIRTHDAY_VALUE
```


String value for 'Birthday' category

### ANNIVERSARY_VALUE {#ANNIVERSARY-VALUE}
```
public static final String ANNIVERSARY_VALUE
```


String value for 'Anniversary' category

### getBirthday() {#getBirthday--}
```
public static EventCategory getBirthday()
```


Birthday

**Returns:**
[EventCategory](../../com.aspose.email/eventcategory)
### getAnniversary() {#getAnniversary--}
```
public static EventCategory getAnniversary()
```


Anniversary

**Returns:**
[EventCategory](../../com.aspose.email/eventcategory)
### getCustom() {#getCustom--}
```
public static EventCategory getCustom()
```


Custom description

**Returns:**
[EventCategory](../../com.aspose.email/eventcategory)
### getValue() {#getValue--}
```
public final String getValue()
```


Gets string representation of an event category

**Returns:**
java.lang.String
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets description for the 'Custom' category of an event

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - Returns a string that represents the current object.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode returns a hash function for this object.

**Returns:**
int - Returns a hash function for this object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object is equal to the current Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with the current Object. |

**Returns:**
boolean - Returns a boolean indicating if the passed in object obj is Equal to this.
### op_Equality(EventCategory a, EventCategory b) {#op-Equality-com.aspose.email.EventCategory-com.aspose.email.EventCategory-}
```
public static boolean op_Equality(EventCategory a, EventCategory b)
```


Determines whether the specified objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [EventCategory](../../com.aspose.email/eventcategory) | First object to compare |
| b | [EventCategory](../../com.aspose.email/eventcategory) | Second object to compare |

**Returns:**
boolean - Returns true if objects are equal, otherwise false.
### op_Inequality(EventCategory a, EventCategory b) {#op-Inequality-com.aspose.email.EventCategory-com.aspose.email.EventCategory-}
```
public static boolean op_Inequality(EventCategory a, EventCategory b)
```


Determines whether the specified objects are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [EventCategory](../../com.aspose.email/eventcategory) | First object to compare |
| b | [EventCategory](../../com.aspose.email/eventcategory) | Second object to compare |

**Returns:**
boolean - Returns true if objects are not equal, otherwise false.
### equals(EventCategory other) {#equals-com.aspose.email.EventCategory-}
```
public boolean equals(EventCategory other)
```


Determines whether the specified object is equal to the current object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [EventCategory](../../com.aspose.email/eventcategory) | The object to compare with the current object. |

**Returns:**
boolean - true if the specified object is equal to the current object; otherwise, false.
