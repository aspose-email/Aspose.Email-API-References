---
title: ByDayCollection
second_title: Aspose.Email for Android via Java API Reference
description: Представляет коллекцию объектов.
type: docs
weight: 63
url: /ru/androidjava/com.aspose.email/bydaycollection/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection
```
public class ByDayCollection extends System.Collections.ObjectModel.Collection<ByDay>
```

Представляет коллекцию объектов [ByDay](../../com.aspose.email/byday).

--------------------



Соответствует части BYDAY правила повторения.

 

Правило BYDAY задаёт список дней недели для ежемесячного или ежегодного правила повторения.

 

Для каждого дня недели можно указать конкретное N‑ое появление или все появления.


## Methods

| Method | Описание |
| --- | --- |
| [add(ByDay byDay)](#add-com.aspose.email.ByDay-) | Добавляет [ByDay](../../com.aspose.email/byday) в коллекцию. |
| [add(int dayOfWeek)](#add-int-) | Создаёт и добавляет [ByDay](../../com.aspose.email/byday), представляющий все вхождения дня недели, в коллекцию. |
| [add(int nthOccurrence, int dayOfWeek)](#add-int-int-) | Создаёт и добавляет [ByDay](../../com.aspose.email/byday) в коллекцию. |
| [addItem(T arg0)](#addItem-T-) |  |
| [clear()](#clear--) |  |
| [contains(int dayOfWeek)](#contains-int-) | Возвращает значение, указывающее, присутствует ли указанный день недели в коллекции. |
| [containsItem(T arg0)](#containsItem-T-) |  |
| [copyToTArray(T[] arg0, int arg1)](#copyToTArray-T---int-) |  |
| [equals(ByDayCollection other)](#equals-com.aspose.email.ByDayCollection-) | Определяет, равен ли указанный [ByDayCollection](../../com.aspose.email/bydaycollection) этому экземпляру. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный Object текущему Object. |
| [get(int index)](#get-int-) | Получает или задаёт объект ByDay из коллекции. |
| [getClass()](#getClass--) |  |
| [getICollection()](#getICollection--) |  |
| [getIList()](#getIList--) |  |
| [getSyncRoot()](#getSyncRoot--) |  |
| [get_Item(int arg0)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) | GetHashCode возвращает хеш‑функцию для этого объекта. |
| [indexOfItem(T arg0)](#indexOfItem-T-) |  |
| [insertItem(int arg0, T arg1)](#insertItem-int-T-) |  |
| [isReadOnly()](#isReadOnly--) |  |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int arg0)](#removeAt-int-) |  |
| [removeItem(T arg0)](#removeItem-T-) |  |
| [set(int index, ByDay value)](#set-int-com.aspose.email.ByDay-) | Получает или задаёт объект ByDay из коллекции. |
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


Добавляет [ByDay](../../com.aspose.email/byday) в коллекцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| byDay | [ByDay](../../com.aspose.email/byday) | Элемент, который нужно добавить в коллекцию. |

**Returns:**
int - Индекс, начинающийся с нуля, для только что добавленного элемента.
### add(int dayOfWeek) {#add-int-}
```
public final int add(int dayOfWeek)
```


Создаёт и добавляет [ByDay](../../com.aspose.email/byday), представляющий все вхождения дня недели, в коллекцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| dayOfWeek | int | День недели. |

**Returns:**
int - Индекс, начинающийся с нуля, для только что добавленного элемента.
### add(int nthOccurrence, int dayOfWeek) {#add-int-int-}
```
public final int add(int nthOccurrence, int dayOfWeek)
```


Создаёт и добавляет [ByDay](../../com.aspose.email/byday) в коллекцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| nthOccurrence | int | N‑й случай дня недели. |
| dayOfWeek | int | День недели. |

**Returns:**
int - Индекс, начинающийся с нуля, для только что добавленного элемента.
### addItem(T arg0) {#addItem-T-}
```
public void addItem(T arg0)
```




**Parameters:**
| Parameter | Type | Описание |
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


Возвращает значение, указывающее, присутствует ли указанный день недели в коллекции.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| dayOfWeek | int | День недели[DayOfWeek](../../com.aspose.email/dayofweek). |

**Returns:**
boolean - True если параметр value существует в этой коллекции, иначе false.
### containsItem(T arg0) {#containsItem-T-}
```
public boolean containsItem(T arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### copyToTArray(T[] arg0, int arg1) {#copyToTArray-T---int-}
```
public void copyToTArray(T[] arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | T[] |  |
| arg1 | int |  |

### equals(ByDayCollection other) {#equals-com.aspose.email.ByDayCollection-}
```
public boolean equals(ByDayCollection other)
```


Определяет, равен ли указанный [ByDayCollection](../../com.aspose.email/bydaycollection) этому экземпляру.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| other | [ByDayCollection](../../com.aspose.email/bydaycollection) | Коллекция [ByDayCollection](../../com.aspose.email/bydaycollection) для сравнения с этим экземпляром. |

**Returns:**
boolean — true, если указанный [ByDayCollection](../../com.aspose.email/bydaycollection) равен этому экземпляру; иначе false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный Object текущему Object.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с текущим объектом. |

**Returns:**
boolean - Возвращает логическое значение, указывающее, равен ли переданный объект obj этому.
### get(int index) {#get-int-}
```
public ByDay get(int index)
```


Получает или задаёт объект ByDay из коллекции.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | целое число int. |

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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode возвращает хеш‑функцию для этого объекта.

**Returns:**
int - Возвращает хеш-функцию для этого объекта.
### indexOfItem(T arg0) {#indexOfItem-T-}
```
public int indexOfItem(T arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
int
### insertItem(int arg0, T arg1) {#insertItem-int-T-}
```
public void insertItem(int arg0, T arg1)
```




**Parameters:**
| Parameter | Type | Описание |
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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | int |  |

### removeItem(T arg0) {#removeItem-T-}
```
public boolean removeItem(T arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### set(int index, ByDay value) {#set-int-com.aspose.email.ByDay-}
```
public void set(int index, ByDay value)
```


Получает или задаёт объект ByDay из коллекции.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | целое число int. |
| value | [ByDay](../../com.aspose.email/byday) | Объект [ByDay](../../com.aspose.email/byday). |

### set_Item(int arg0, T arg1) {#set-Item-int-T-}
```
public void set_Item(int arg0, T arg1)
```




**Parameters:**
| Parameter | Type | Описание |
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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

