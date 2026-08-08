---
title: HeaderCollection
second_title: Aspose.Email for Android via Java API Reference
description: Определяет коллекцию полей заголовка
type: docs
weight: 155
url: /ru/androidjava/com.aspose.email/headercollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public class HeaderCollection implements System.Collections.ICollection<String>
```

Определяет коллекцию полей заголовка
## Constructors

| Constructor | Описание |
| --- | --- |
| [HeaderCollection(HeaderCollection col)](#HeaderCollection-com.aspose.email.HeaderCollection-) | Инициализирует новый экземпляр класса [HeaderCollection](../../com.aspose.email/headercollection). |
| [HeaderCollection()](#HeaderCollection--) | Инициализирует новый экземпляр класса [HeaderCollection](../../com.aspose.email/headercollection). |
## Methods

| Method | Описание |
| --- | --- |
| [add(HeaderCollection c)](#add-com.aspose.email.HeaderCollection-) | Добавляет заголовок в коллекцию. |
| [add(String item)](#add-java.lang.String-) | Добавляет заголовок без значения |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Добавляет заголовок. |
| [add_(String name, String value)](#add--java.lang.String-java.lang.String-) | Добавляет заголовок. |
| [clear()](#clear--) | Очищает все заголовки. |
| [contains(String item)](#contains-java.lang.String-) | Получает значение, указывающее, содержится ли указанный заголовок в коллекции |
| [copyTo(System.Array dest, int index)](#copyTo-com.aspose.ms.System.Array-int-) |  |
| [copyTo(String[] array, int arrayIndex)](#copyTo-java.lang.String---int-) | Копирует все элементы текущей коллекции в указанный массив строк, начиная с указанного индекса назначения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Получает значение по указанному индексу. |
| [get(String name)](#get-java.lang.String-) | Получает значение заголовка по заданному имени заголовка. |
| [getAllKeys()](#getAllKeys--) | Получает массив строк, содержащий все ключи заголовков в коллекциях |
| [getClass()](#getClass--) |  |
| [getDecodedValue(String name)](#getDecodedValue-java.lang.String-) | Получает значение заголовка. |
| [getKey(int index)](#getKey-int-) | Получает ключ по указанному индексу коллекции. |
| [getKeys()](#getKeys--) | Получает  System.Collections.ObjectModel.ReadOnlyCollection\{string\}  содержащий все ключи заголовков в коллекциях |
| [getSyncRoot()](#getSyncRoot--) |  |
| [getValues(String name)](#getValues-java.lang.String-) | Получает значения заголовков. |
| [get_Item(int index)](#get-Item-int-) | Получает значение из коллекции по индексу. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Получает значение из коллекции по имени. |
| [hasKeys()](#hasKeys--) | Получает значение, указывающее, содержит ли коллекция ключи. |
| [hashCode()](#hashCode--) |  |
| [insert(String name, String value)](#insert-java.lang.String-java.lang.String-) | Вставляет заголовок в коллекцию. |
| [isReadOnly()](#isReadOnly--) | Коллекция только для чтения |
| [isSynchronized()](#isSynchronized--) |  |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String item)](#remove-java.lang.String-) | Удаляет заголовок из коллекции по заданному имени заголовка. |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Устанавливает заголовок. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Получает значение из коллекции по имени. |
| [size()](#size--) | Получает количество заголовков |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HeaderCollection(HeaderCollection col) {#HeaderCollection-com.aspose.email.HeaderCollection-}
```
public HeaderCollection(HeaderCollection col)
```


Инициализирует новый экземпляр класса [HeaderCollection](../../com.aspose.email/headercollection).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| col | [HeaderCollection](../../com.aspose.email/headercollection) | Коллекция. |

### HeaderCollection() {#HeaderCollection--}
```
public HeaderCollection()
```


Инициализирует новый экземпляр класса [HeaderCollection](../../com.aspose.email/headercollection).

### add(HeaderCollection c) {#add-com.aspose.email.HeaderCollection-}
```
public final void add(HeaderCollection c)
```


Добавляет заголовок в коллекцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| c | [HeaderCollection](../../com.aspose.email/headercollection) | HeaderCollection для добавления. |

### add(String item) {#add-java.lang.String-}
```
public final void add(String item)
```


Добавляет заголовок без значения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| элемент | java.lang.String |  |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```


Добавляет заголовок.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя заголовка. |
| value | java.lang.String | Значение заголовка. |

### add_(String name, String value) {#add--java.lang.String-java.lang.String-}
```
public void add_(String name, String value)
```


Добавляет заголовок.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя заголовка. |
| value | java.lang.String | Значение заголовка. |

### clear() {#clear--}
```
public void clear()
```


Очищает все заголовки.

### contains(String item) {#contains-java.lang.String-}
```
public final boolean contains(String item)
```


Получает значение, указывающее, содержится ли указанный заголовок в коллекции

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| элемент | java.lang.String | Заголовок для поиска |

**Returns:**
boolean -  True  если коллекция содержит указанный элемент ; иначе,  false
### copyTo(System.Array dest, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array dest, int index)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| dest | com.aspose.ms.System.Array |  |
| индекс | int |  |

### copyTo(String[] array, int arrayIndex) {#copyTo-java.lang.String---int-}
```
public final void copyTo(String[] array, int arrayIndex)
```


Копирует все элементы текущей коллекции в указанный массив строк, начиная с указанного индекса назначения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| массив | java.lang.String[] | Назначение элементов, скопированных из текущей коллекции. |
| arrayIndex | int | Целое число, представляющее индекс в массиве, с которого начинается копирование. |

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
### get(int index) {#get-int-}
```
public String get(int index)
```


Получает значение по указанному индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Целое число, представляющее позицию элемента для получения. |

**Returns:**
java.lang.String - Значение в указанной позиции текущей коллекции.
### get(String name) {#get-java.lang.String-}
```
public final String get(String name)
```


Получает значение заголовка по заданному имени заголовка.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя заголовка. |

**Returns:**
java.lang.String - Значение заголовка.
### getAllKeys() {#getAllKeys--}
```
public String[] getAllKeys()
```


Получает массив строк, содержащий все ключи заголовков в коллекциях

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecodedValue(String name) {#getDecodedValue-java.lang.String-}
```
public final String getDecodedValue(String name)
```


Получает значение заголовка.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя текстового заголовка. |

**Returns:**
java.lang.String - Декодированное текстовое значение
### getKey(int index) {#getKey-int-}
```
public String getKey(int index)
```


Получает ключ по указанному индексу коллекции.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Индекс ключа. |

**Returns:**
java.lang.String - Ключ в указанном индексе.
### getKeys() {#getKeys--}
```
public List<String> getKeys()
```


Получает  System.Collections.ObjectModel.ReadOnlyCollection\{string\}  содержащий все ключи заголовков в коллекциях

**Returns:**
java.util.List<java.lang.String>
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```




**Returns:**
java.lang.Object
### getValues(String name) {#getValues-java.lang.String-}
```
public final String[] getValues(String name)
```


Получает значения заголовков.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя заголовка. |

**Returns:**
java.lang.String[] - Коллекция значений заголовков.
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Получает значение из коллекции по индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Индекс в коллекции для элемента. |

**Returns:**
java.lang.String - Возвращает указанный элемент
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Получает значение из коллекции по имени.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя (ключ) в коллекции для элемента. |

**Returns:**
java.lang.String - Возвращает указанный элемент
### hasKeys() {#hasKeys--}
```
public final boolean hasKeys()
```


Получает значение, указывающее, содержит ли коллекция ключи.

**Returns:**
boolean - Возвращает true, если в коллекции есть элементы, иначе возвращает false.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### insert(String name, String value) {#insert-java.lang.String-java.lang.String-}
```
public final void insert(String name, String value)
```


Вставляет заголовок в коллекцию. Если коллекция содержит заголовки с тем же именем, этот заголовок будет вставлен перед другими заголовками с тем же именем.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя заголовка. |
| value | java.lang.String | Значение заголовка. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Коллекция только для чтения

**Returns:**
boolean
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```




**Returns:**
boolean
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<String> iterator()
```


Возвращает перечислитель, который перебирает коллекцию.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<java.lang.String> - Объект System.Collections.Generic.IEnumerator\{string\}, который можно использовать для перебора элементов коллекции.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String item) {#remove-java.lang.String-}
```
public final boolean remove(String item)
```


Удаляет заголовок из коллекции по заданному имени заголовка.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| элемент | java.lang.String | Имя заголовка. |

**Returns:**
boolean - true, если элемент был успешно удалён из коллекции.
### set(String name, String value) {#set-java.lang.String-java.lang.String-}
```
public final void set(String name, String value)
```


Устанавливает заголовок.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя заголовка. |
| value | java.lang.String | Значение заголовка. |

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Получает значение из коллекции по имени.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя (ключ) в коллекции для элемента. |
| value | java.lang.String |  |

### size() {#size--}
```
public int size()
```


Получает количество заголовков

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

