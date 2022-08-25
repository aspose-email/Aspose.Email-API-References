---
title: ByDayCollection
second_title: Aspose.Email for Java API Reference
description:  Represents a collection of  objects.
type: docs
weight: 87
url: /java/com.aspose.email/bydaycollection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection
```
public class ByDayCollection extends System.Collections.ObjectModel.Collection<ByDay>
```

Represents a collection of [ByDay](../../com.aspose.email/byday) objects.

--------------------

\`\`\`

Corresponds to the BYDAY part of the recurrence rule.

\`\`\` \`\`\`

The BYDAY rule specifies a list of days of the week for a monthly or yearly recurrence rule.

\`\`\` \`\`\`

For each day of the week, a specific Nth occurrence or all occurrences can be specified.

\`\`\`
## Methods

| Method | Description |
| --- | --- |
| [add(ByDay byDay)](#add-com.aspose.email.ByDay-) | Adds a [ByDay](../../com.aspose.email/byday) to the collection. |
| [add(int dayOfWeek)](#add-int-) | Creates and adds a [ByDay](../../com.aspose.email/byday) that represents all occurrences of the day of the week to the collection. |
| [add(int nthOccurrence, int dayOfWeek)](#add-int-int-) | Creates and adds a [ByDay](../../com.aspose.email/byday) to the collection. |
| [get(int index)](#get-int-) | Gets or sets a \`\`\` ByDay \`\`\` from the collection. |
| [set(int index, ByDay value)](#set-int-com.aspose.email.ByDay-) | Gets or sets a \`\`\` ByDay \`\`\` from the collection. |
| [contains(int dayOfWeek)](#contains-int-) | Returns a value indicating whether a specified day of week is present in the collection. |
| [equals(ByDayCollection other)](#equals-com.aspose.email.ByDayCollection-) | Determines whether the specified [ByDayCollection](../../com.aspose.email/bydaycollection) is equal to this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
### add(ByDay byDay) {#add-com.aspose.email.ByDay-}
```
public final int add(ByDay byDay)
```


Adds a [ByDay](../../com.aspose.email/byday) to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byDay | [ByDay](../../com.aspose.email/byday) | The item to add to the collection. |

**Returns:**
int - The zero-based index of the newly added item.
### add(int dayOfWeek) {#add-int-}
```
public final int add(int dayOfWeek)
```


Creates and adds a [ByDay](../../com.aspose.email/byday) that represents all occurrences of the day of the week to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dayOfWeek | int | A day of the week. |

**Returns:**
int - The zero-based index of the newly added item.
### add(int nthOccurrence, int dayOfWeek) {#add-int-int-}
```
public final int add(int nthOccurrence, int dayOfWeek)
```


Creates and adds a [ByDay](../../com.aspose.email/byday) to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nthOccurrence | int | The nth occurrence of the day of the week. |
| dayOfWeek | int | A day of the week. |

**Returns:**
int - The zero-based index of the newly added item.
### get(int index) {#get-int-}
```
public ByDay get(int index)
```


Gets or sets a \`\`\` ByDay \`\`\` from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | a int. |

**Returns:**
[ByDay](../../com.aspose.email/byday) - a com.aspose.email.ByDay object.
### set(int index, ByDay value) {#set-int-com.aspose.email.ByDay-}
```
public void set(int index, ByDay value)
```


Gets or sets a \`\`\` ByDay \`\`\` from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | a int. |
| value | [ByDay](../../com.aspose.email/byday) | a com.aspose.email.ByDay object. |

### contains(int dayOfWeek) {#contains-int-}
```
public final boolean contains(int dayOfWeek)
```


Returns a value indicating whether a specified day of week is present in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dayOfWeek | int | Day of week[DayOfWeek](../../com.aspose.email/dayofweek). |

**Returns:**
boolean - True if the value parameter exists within this collection, otherwise false.
### equals(ByDayCollection other) {#equals-com.aspose.email.ByDayCollection-}
```
public boolean equals(ByDayCollection other)
```


Determines whether the specified [ByDayCollection](../../com.aspose.email/bydaycollection) is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ByDayCollection](../../com.aspose.email/bydaycollection) | The [ByDayCollection](../../com.aspose.email/bydaycollection) to compare with this instance. |

**Returns:**
boolean - \`\`\` true \`\`\` if the specified [ByDayCollection](../../com.aspose.email/bydaycollection) is equal to this instance; otherwise, \`\`\` false \`\`\`.
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
