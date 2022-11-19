---
title: ByDayCollection
second_title: Aspose.Email for Java API Reference
description: Represents a collection of  objects.
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



Corresponds to the BYDAY part of the recurrence rule.

 

The BYDAY rule specifies a list of days of the week for a monthly or yearly recurrence rule.

 

For each day of the week, a specific Nth occurrence or all occurrences can be specified.


## Methods

| Method | Description |
| --- | --- |
| [add(ByDay byDay)](#add-com.aspose.email.ByDay-) | Adds a [ByDay](../../com.aspose.email/byday) to the collection. |
| [add(int dayOfWeek)](#add-int-) | Creates and adds a [ByDay](../../com.aspose.email/byday) that represents all occurrences of the day of the week to the collection. |
| [add(int nthOccurrence, int dayOfWeek)](#add-int-int-) | Creates and adds a [ByDay](../../com.aspose.email/byday) to the collection. |
| [addItem(T arg0)](#addItem-T-) |  |
| [clear()](#clear--) |  |
| [contains(int dayOfWeek)](#contains-int-) | Returns a value indicating whether a specified day of week is present in the collection. |
| [containsItem(T arg0)](#containsItem-T-) |  |
| [copyToTArray(T[] arg0, int arg1)](#copyToTArray-T---int-) |  |
| [equals(ByDayCollection other)](#equals-com.aspose.email.ByDayCollection-) | Determines whether the specified [ByDayCollection](../../com.aspose.email/bydaycollection) is equal to this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [get(int index)](#get-int-) | Gets or sets a  ByDay  from the collection. |
| [getClass()](#getClass--) |  |
| [getICollection()](#getICollection--) |  |
| [getIList()](#getIList--) |  |
| [getSyncRoot()](#getSyncRoot--) |  |
| [get_Item(int arg0)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
| [indexOfItem(T arg0)](#indexOfItem-T-) |  |
| [insertItem(int arg0, T arg1)](#insertItem-int-T-) |  |
| [isReadOnly()](#isReadOnly--) |  |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int arg0)](#removeAt-int-) |  |
| [removeItem(T arg0)](#removeItem-T-) |  |
| [set(int index, ByDay value)](#set-int-com.aspose.email.ByDay-) | Gets or sets a  ByDay  from the collection. |
| [set_Item(int arg0, T arg1)](#set-Item-int-T-) |  |
| [size()](#size--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### addItem(T arg0) {#addItem-T-}
```
public void addItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### clear() {#clear--}
```
public void clear()
```




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
### containsItem(T arg0) {#containsItem-T-}
```
public boolean containsItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### copyToTArray(T[] arg0, int arg1) {#copyToTArray-T---int-}
```
public void copyToTArray(T[] arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T[] |  |
| arg1 | int |  |

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
boolean -  true  if the specified [ByDayCollection](../../com.aspose.email/bydaycollection) is equal to this instance; otherwise,  false .
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
### get(int index) {#get-int-}
```
public ByDay get(int index)
```


Gets or sets a  ByDay  from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | a int. |

**Returns:**
[ByDay](../../com.aspose.email/byday) - a [ByDay](../../com.aspose.email/byday) object.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getICollection() {#getICollection--}
```
public System.Collections.ICollection getICollection()
```




**Returns:**
com.aspose.ms.System.Collections.ICollection
### getIList() {#getIList--}
```
public System.Collections.IList getIList()
```




**Returns:**
com.aspose.ms.System.Collections.IList
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```




**Returns:**
java.lang.Object
### get_Item(int arg0) {#get-Item-int-}
```
public T get_Item(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode returns a hash function for this object.

**Returns:**
int - Returns a hash function for this object.
### indexOfItem(T arg0) {#indexOfItem-T-}
```
public int indexOfItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
int
### insertItem(int arg0, T arg1) {#insertItem-int-T-}
```
public void insertItem(int arg0, T arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**Returns:**
boolean
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<T> iterator()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<T>
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAt(int arg0) {#removeAt-int-}
```
public void removeAt(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### removeItem(T arg0) {#removeItem-T-}
```
public boolean removeItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### set(int index, ByDay value) {#set-int-com.aspose.email.ByDay-}
```
public void set(int index, ByDay value)
```


Gets or sets a  ByDay  from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | a int. |
| value | [ByDay](../../com.aspose.email/byday) | a [ByDay](../../com.aspose.email/byday) object. |

### set_Item(int arg0, T arg1) {#set-Item-int-T-}
```
public void set_Item(int arg0, T arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### size() {#size--}
```
public int size()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

