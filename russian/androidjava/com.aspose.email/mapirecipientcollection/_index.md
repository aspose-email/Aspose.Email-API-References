---
title: MapiRecipientCollection
second_title: Aspose.Email for Android via Java API Reference
description: Представляет коллекцию объектов MapiRecipient.
type: docs
weight: 279
url: /ru/androidjava/com.aspose.email/mapirecipientcollection/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection
```
public class MapiRecipientCollection extends System.Collections.ObjectModel.Collection<MapiRecipient>
```

Представляет коллекцию объектов MapiRecipient.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiRecipientCollection()](#MapiRecipientCollection--) | Инициализирует новый экземпляр класса [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection). |
## Methods

| Method | Описание |
| --- | --- |
| [add(String address, String displayName, int recipientType)](#add-java.lang.String-java.lang.String-int-) | Добавляет нового получателя. |
| [add(String address, String addressType, String displayName, int recipientType)](#add-java.lang.String-java.lang.String-java.lang.String-int-) | Добавляет нового получателя. |
| [addItem(T arg0)](#addItem-T-) |  |
| [addMapiRecipient(MapiRecipient item)](#addMapiRecipient-com.aspose.email.MapiRecipient-) | Добавляет объект в конец System.Collections.ObjectModel.Collection1. |
| [clear()](#clear--) |  |
| [containsItem(T arg0)](#containsItem-T-) |  |
| [copyToTArray(T[] arg0, int arg1)](#copyToTArray-T---int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getICollection()](#getICollection--) |  |
| [getIList()](#getIList--) |  |
| [getSyncRoot()](#getSyncRoot--) |  |
| [get_Item(int arg0)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) |  |
| [indexOfItem(T arg0)](#indexOfItem-T-) |  |
| [insertItem(int arg0, T arg1)](#insertItem-int-T-) |  |
| [insertMapiRecipient(int index, MapiRecipient item)](#insertMapiRecipient-int-com.aspose.email.MapiRecipient-) | Вставляет элемент в System.Collections.ObjectModel.Collection1 по указанному индексу. |
| [isReadOnly()](#isReadOnly--) |  |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int arg0)](#removeAt-int-) |  |
| [removeItem(T arg0)](#removeItem-T-) |  |
| [set_Item(int arg0, T arg1)](#set-Item-int-T-) |  |
| [size()](#size--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiRecipientCollection() {#MapiRecipientCollection--}
```
public MapiRecipientCollection()
```


Инициализирует новый экземпляр класса [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection).

### add(String address, String displayName, int recipientType) {#add-java.lang.String-java.lang.String-int-}
```
public final void add(String address, String displayName, int recipientType)
```


Добавляет нового получателя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Почтовый адрес получателя. |
| displayName | java.lang.String | Отображаемое имя получателя. |
|  | recipientType | int | Тип получателя. |

--------------------

При добавлении нового получателя значение либо MapiMessage.DisplayTo, либо MapiMessage.DisplayBcc, либо MapiMessage.DisplayCC также обновляется в зависимости от типа получателя. |

### add(String address, String addressType, String displayName, int recipientType) {#add-java.lang.String-java.lang.String-java.lang.String-int-}
```
public final void add(String address, String addressType, String displayName, int recipientType)
```


Добавляет нового получателя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Почтовый адрес получателя. |
| addressType | java.lang.String | Тип адреса. |
| displayName | java.lang.String | Отображаемое имя получателя. |
|  | recipientType | int | Тип получателя. |

--------------------

При добавлении нового получателя значение либо MapiMessage.DisplayTo, либо MapiMessage.DisplayBcc, либо MapiMessage.DisplayCC также обновляется в зависимости от типа получателя. |

### addItem(T arg0) {#addItem-T-}
```
public void addItem(T arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | T |  |

### addMapiRecipient(MapiRecipient item) {#addMapiRecipient-com.aspose.email.MapiRecipient-}
```
public final void addMapiRecipient(MapiRecipient item)
```


Добавляет объект в конец System.Collections.ObjectModel.Collection1.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| item | [MapiRecipient](../../com.aspose.email/mapirecipient) | Объект, который будет добавлен в конец коллекции System.Collections.ObjectModel.Collection1. Значение может быть null для ссылочных типов. |

### clear() {#clear--}
```
public void clear()
```




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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
public native int hashCode()
```




**Returns:**
int
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

### insertMapiRecipient(int index, MapiRecipient item) {#insertMapiRecipient-int-com.aspose.email.MapiRecipient-}
```
public final void insertMapiRecipient(int index, MapiRecipient item)
```


Вставляет элемент в System.Collections.ObjectModel.Collection1 по указанному индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Нулевой индекс, по которому следует вставить элемент item. |
| item | [MapiRecipient](../../com.aspose.email/mapirecipient) | Объект для вставки. Значение может быть null для ссылочных типов. |

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

