---
title: CustomerEvent
second_title: Aspose.Email for Java API Reference
description: Represents an event.
type: docs
weight: 130
url: /java/com.aspose.email/customerevent/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.ms.System.IEquatable
```
public class CustomerEvent implements Comparable<CustomerEvent>, System.IEquatable<CustomerEvent>
```

Represents an event.
## Constructors

| Constructor | Description |
| --- | --- |
| [CustomerEvent()](#CustomerEvent--) |  |
## Methods

| Method | Description |
| --- | --- |
| [compareTo(CustomerEvent obj)](#compareTo-com.aspose.email.CustomerEvent-) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| [equals(CustomerEvent obj)](#equals-com.aspose.email.CustomerEvent-) | Determines whether the specified Object is equal to the current Object. |
| [equals(CustomerEvent x, CustomerEvent y)](#equals-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-) | Determines whether the specified object instances are considered equal. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [getCategory()](#getCategory--) | Gets or sets an object category |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | Gets or sets a date and time for an event. |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
| [hashCode(CustomerEvent obj)](#hashCode-com.aspose.email.CustomerEvent-) | GetHashCode returns a hash function for specified object. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(CustomerEvent a, CustomerEvent b)](#op-Equality-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-) | Determines whether the specified objects are equal. |
| [op_Inequality(CustomerEvent a, CustomerEvent b)](#op-Inequality-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-) | Determines whether the specified objects are not equal. |
| [setCategory(EventCategory value)](#setCategory-com.aspose.email.EventCategory-) | Gets or sets an object category |
| [setDate(Date value)](#setDate-java.util.Date-) | Gets or sets a date and time for an event. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomerEvent() {#CustomerEvent--}
```
public CustomerEvent()
```


### compareTo(CustomerEvent obj) {#compareTo-com.aspose.email.CustomerEvent-}
```
public int compareTo(CustomerEvent obj)
```


Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [CustomerEvent](../../com.aspose.email/customerevent) | An object to compare with this instance, or null. |

**Returns:**
int - This method returns: a value less than 0 if this is less than value 0 if this is equal to value a value greater than 0 if this is greater than value
### equals(CustomerEvent obj) {#equals-com.aspose.email.CustomerEvent-}
```
public final boolean equals(CustomerEvent obj)
```


Determines whether the specified Object is equal to the current Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [CustomerEvent](../../com.aspose.email/customerevent) | The Object to compare with the current Object. |

**Returns:**
boolean - Returns a boolean indicating if the passed in object obj is Equal to this.
### equals(CustomerEvent x, CustomerEvent y) {#equals-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-}
```
public final boolean equals(CustomerEvent x, CustomerEvent y)
```


Determines whether the specified object instances are considered equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | [CustomerEvent](../../com.aspose.email/customerevent) | The first object to compare. |
| y | [CustomerEvent](../../com.aspose.email/customerevent) | The second object to compare. |

**Returns:**
boolean - true if the objects are considered equal; otherwise, false. If both objA and objB are null, the method returns true.
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
### getCategory() {#getCategory--}
```
public final EventCategory getCategory()
```


Gets or sets an object category

**Returns:**
[EventCategory](../../com.aspose.email/eventcategory)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDate() {#getDate--}
```
public final Date getDate()
```


Gets or sets a date and time for an event.

**Returns:**
java.util.Date
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode returns a hash function for this object.

**Returns:**
int - Returns a hash function for this object.
### hashCode(CustomerEvent obj) {#hashCode-com.aspose.email.CustomerEvent-}
```
public final int hashCode(CustomerEvent obj)
```


GetHashCode returns a hash function for specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [CustomerEvent](../../com.aspose.email/customerevent) | The Object for which a hash code is to be returned. |

**Returns:**
int - Returns a hash function for specified object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(CustomerEvent a, CustomerEvent b) {#op-Equality-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-}
```
public static boolean op_Equality(CustomerEvent a, CustomerEvent b)
```


Determines whether the specified objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [CustomerEvent](../../com.aspose.email/customerevent) | First object to compare |
| b | [CustomerEvent](../../com.aspose.email/customerevent) | Second object to compare |

**Returns:**
boolean - Returns true if objects are equal, otherwise false.
### op_Inequality(CustomerEvent a, CustomerEvent b) {#op-Inequality-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-}
```
public static boolean op_Inequality(CustomerEvent a, CustomerEvent b)
```


Determines whether the specified objects are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [CustomerEvent](../../com.aspose.email/customerevent) | First object to compare |
| b | [CustomerEvent](../../com.aspose.email/customerevent) | Second object to compare |

**Returns:**
boolean - Returns true if objects are not equal, otherwise false.
### setCategory(EventCategory value) {#setCategory-com.aspose.email.EventCategory-}
```
public final void setCategory(EventCategory value)
```


Gets or sets an object category

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EventCategory](../../com.aspose.email/eventcategory) |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


Gets or sets a date and time for an event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - Returns a string that represents the current object.
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

