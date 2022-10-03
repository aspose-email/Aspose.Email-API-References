---
title: ByNumberCollection
second_title: Aspose.Email for Java API Reference
description: Represents a set of months weeks days hours minutes or seconds in a recurrence rule.
type: docs
weight: 88
url: /java/com.aspose.email/bynumbercollection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.List
```
public class ByNumberCollection extends System.Collections.Generic.List<Integer>
```

Represents a set of months, weeks, days, hours, minutes or seconds in a recurrence rule.

--------------------



Corresponds to various BYXXX parts such as BYDAY, BYMONTH of a recurrence rule.

 

Most of the ByXXX properties of \{@link RecurrenceRule\} are implemented as ByNumberCollection.


## Methods

| Method | Description |
| --- | --- |
| [add(int value)](#add-int-) | Adds a month, week, day, hour, minute or second to the collection. |
| [add(int[] values)](#add-int---) | Adds an array of month, week, day, hour, minute or second to the collection. |
| [equals(ByNumberCollection other)](#equals-com.aspose.email.ByNumberCollection-) | Determines whether the specified [ByNumberCollection](../../com.aspose.email/bynumbercollection) is equal to this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
### add(int value) {#add-int-}
```
public final int add(int value)
```


Adds a month, week, day, hour, minute or second to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value to add.

--------------------



Throws an exception if the value is outside of the valid range for the time unit of this collection.

 |

**Returns:**
int - The zero-based index of the newly added item.
### add(int[] values) {#add-int---}
```
public final void add(int[] values)
```


Adds an array of month, week, day, hour, minute or second to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | int[] | The values. |

### equals(ByNumberCollection other) {#equals-com.aspose.email.ByNumberCollection-}
```
public boolean equals(ByNumberCollection other)
```


Determines whether the specified [ByNumberCollection](../../com.aspose.email/bynumbercollection) is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ByNumberCollection](../../com.aspose.email/bynumbercollection) | The [ByNumberCollection](../../com.aspose.email/bynumbercollection) to compare with this instance. |

**Returns:**
boolean -  true  if the specified [ByNumberCollection](../../com.aspose.email/bynumbercollection) is equal to this instance; otherwise,  false .
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
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode returns a hash function for this object.

**Returns:**
int - Returns a hash function for this object.
