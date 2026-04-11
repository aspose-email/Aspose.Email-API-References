---
title: MapiPropertyCollection
second_title: Aspose.Email for Android via Java API Reference
description: Представляет коллекцию элементов MapiProperty.
type: docs
weight: 272
url: /ru/androidjava/com.aspose.email/mapipropertycollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary, [com.aspose.email.INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider)
```
public class MapiPropertyCollection implements System.Collections.Generic.IGenericDictionary<Long,MapiProperty>, INamedPropertyTagProvider
```

Представляет коллекцию элементов MapiProperty.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiPropertyCollection()](#MapiPropertyCollection--) | Создаёт новый экземпляр класса MapiProperty. |
## Methods

| Method | Описание |
| --- | --- |
| [add(MapiProperty value)](#add-com.aspose.email.MapiProperty-) | Добавляет элемент MapiProperty с указанным тегом. |
| [add(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [add(long key, MapiProperty value)](#add-long-com.aspose.email.MapiProperty-) | Добавляет элемент MapiProperty с указанным тегом. |
| [addItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [addItem(Long arg0, MapiProperty arg1)](#addItem-java.lang.Long-com.aspose.email.MapiProperty-) |  |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [containsItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [containsKey(Long arg0)](#containsKey-java.lang.Long-) |  |
| [containsKey(long key)](#containsKey-long-) | Определяет, содержит ли коллекция свойство с указанным тегом. |
| [copyTo(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] array, int arrayIndex)](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-) |  |
| [copyToTArray(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] arg0, int arg1)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNamedPropertyTag(long dataType)](#generateNamedPropertyTag-long-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Возвращает System.Collections.Generic.ICollection<long>, содержащий ключи в коллекции. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Получает свойство MAPI по дескриптору свойства. |
| [getTagFromNamedProperty(String name)](#getTagFromNamedProperty-java.lang.String-) | Возвращает тег из именованного свойства. |
| [getTagFromNamedProperty(long LId)](#getTagFromNamedProperty-long-) | Возвращает тег из именованного свойства. |
| [getValues()](#getValues--) | Возвращает System.Collections.Generic.ICollection<MapiProperty>, содержащий значения в коллекции. |
| [get_Item(PropertyDescriptor pd)](#get-Item-com.aspose.email.PropertyDescriptor-) | Возвращает или задает значение, связанное с указанным ключом. |
| [get_Item(Long arg0)](#get-Item-java.lang.Long-) |  |
| [get_Item(long tag)](#get-Item-long-) | Возвращает или задает значение, связанное с указанным ключом. |
| [get_Keys()](#get-Keys--) | Возвращает System.Collections.Generic.ICollection<long>, содержащий ключи в коллекции. |
| [get_Values()](#get-Values--) | Возвращает System.Collections.Generic.ICollection<MapiProperty>, содержащий значения в коллекции. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(PropertyDescriptor pd)](#remove-com.aspose.email.PropertyDescriptor-) | Удаляет свойство с указанным дескриптором свойства из коллекции. |
| [remove(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [remove(long key)](#remove-long-) | Удаляет свойство с указанным тегом из коллекции. |
| [removeItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [removeItemByKey(Long arg0)](#removeItemByKey-java.lang.Long-) |  |
| [set_Item(PropertyDescriptor pd, MapiProperty value)](#set-Item-com.aspose.email.PropertyDescriptor-com.aspose.email.MapiProperty-) | Возвращает или задает значение, связанное с указанным ключом. |
| [set_Item(Long arg0, MapiProperty arg1)](#set-Item-java.lang.Long-com.aspose.email.MapiProperty-) |  |
| [set_Item(long tag, MapiProperty value)](#set-Item-long-com.aspose.email.MapiProperty-) | Возвращает или задает значение, связанное с указанным ключом. |
| [size()](#size--) | Возвращает количество элементов, содержащихся в коллекции. |
| [toString()](#toString--) |  |
| [tryGetValue(Long arg0, Object[] arg1)](#tryGetValue-java.lang.Long-java.lang.Object---) |  |
| [tryGetValue(long key, MapiProperty[] value)](#tryGetValue-long-com.aspose.email.MapiProperty---) | Возвращает свойство, связанное с указанным тегом. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiPropertyCollection() {#MapiPropertyCollection--}
```
public MapiPropertyCollection()
```


Создаёт новый экземпляр класса MapiProperty.

### add(MapiProperty value) {#add-com.aspose.email.MapiProperty-}
```
public void add(MapiProperty value)
```


Добавляет элемент MapiProperty с указанным тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | Значение свойства. |

### add(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item) {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public final void add(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| элемент | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

### add(long key, MapiProperty value) {#add-long-com.aspose.email.MapiProperty-}
```
public void add(long key, MapiProperty value)
```


Добавляет элемент MapiProperty с указанным тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ключ | long | Тег свойства. |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | Значение свойства. |

### addItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public void addItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

### addItem(Long arg0, MapiProperty arg1) {#addItem-java.lang.Long-com.aspose.email.MapiProperty-}
```
public void addItem(Long arg0, MapiProperty arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Long |  |
| arg1 | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### clear() {#clear--}
```
public final void clear()
```


Удаляет все элементы из коллекции.

### contains(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item) {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public final boolean contains(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| элемент | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### containsItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### containsKey(Long arg0) {#containsKey-java.lang.Long-}
```
public boolean containsKey(Long arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Long |  |

**Returns:**
boolean
### containsKey(long key) {#containsKey-long-}
```
public final boolean containsKey(long key)
```


Определяет, содержит ли коллекция свойство с указанным тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ключ | long | Тег свойства. |

**Returns:**
boolean - true, если коллекция содержит свойство с тегом; иначе false
### copyTo(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] array, int arrayIndex) {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-}
```
public final void copyTo(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] array, int arrayIndex)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| массив | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty>[] |  |
| arrayIndex | int |  |

### copyToTArray(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] arg0, int arg1) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty>[] |  |
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
### generateNamedPropertyTag(long dataType) {#generateNamedPropertyTag-long-}
```
public final long generateNamedPropertyTag(long dataType)
```


Генерирует тег именованного свойства

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| dataType | long |  |

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeys() {#getKeys--}
```
public final System.Collections.Generic.IGenericCollection getKeys()
```


Возвращает System.Collections.Generic.ICollection<long>, содержащий ключи в коллекции.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Получает свойство MAPI по дескриптору свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Дескриптор свойства для искомого свойства. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### getTagFromNamedProperty(String name) {#getTagFromNamedProperty-java.lang.String-}
```
public final long getTagFromNamedProperty(String name)
```


Возвращает тег из именованного свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |

**Returns:**
long - Значение тега свойства.
### getTagFromNamedProperty(long LId) {#getTagFromNamedProperty-long-}
```
public final long getTagFromNamedProperty(long LId)
```


Возвращает тег из именованного свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| LId | long | Идентификатор свойства. |

**Returns:**
long - Значение тега свойства.
### getValues() {#getValues--}
```
public final System.Collections.Generic.IGenericCollection getValues()
```


Возвращает System.Collections.Generic.ICollection<MapiProperty>, содержащий значения в коллекции.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
### get_Item(PropertyDescriptor pd) {#get-Item-com.aspose.email.PropertyDescriptor-}
```
public final MapiProperty get_Item(PropertyDescriptor pd)
```


Возвращает или задает значение, связанное с указанным ключом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Ключ [PropertyDescriptor](../../com.aspose.email/propertydescriptor), значение которого следует получить или установить. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The value associated with the specified key.
### get_Item(Long arg0) {#get-Item-java.lang.Long-}
```
public MapiProperty get_Item(Long arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Long |  |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty)
### get_Item(long tag) {#get-Item-long-}
```
public final MapiProperty get_Item(long tag)
```


Возвращает или задает значение, связанное с указанным ключом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Ключ тега, значение которого следует получить или установить. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The value associated with the specified key.
### get_Keys() {#get-Keys--}
```
public final System.Collections.Generic.IGenericCollection<Long> get_Keys()
```


Возвращает System.Collections.Generic.ICollection<long>, содержащий ключи в коллекции.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.Long>
### get_Values() {#get-Values--}
```
public final System.Collections.Generic.IGenericCollection<? extends MapiProperty> get_Values()
```


Возвращает System.Collections.Generic.ICollection<MapiProperty>, содержащий значения в коллекции.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<? extends com.aspose.email.MapiProperty>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Возвращает значение, указывающее, является ли коллекция только для чтения.

**Returns:**
boolean
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<Long,MapiProperty>> iterator()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty>>
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(PropertyDescriptor pd) {#remove-com.aspose.email.PropertyDescriptor-}
```
public final boolean remove(PropertyDescriptor pd)
```


Удаляет свойство с указанным дескриптором свойства из коллекции.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Дескриптор свойства, которое нужно удалить. |

**Returns:**
boolean — true, если свойство успешно удалено; иначе — false.
### remove(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item) {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public final boolean remove(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| элемент | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### remove(long key) {#remove-long-}
```
public final boolean remove(long key)
```


Удаляет свойство с указанным тегом из коллекции.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ключ | long | Тег свойства, которое нужно удалить. |

**Returns:**
boolean — true, если свойство успешно удалено; иначе — false.
### removeItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### removeItemByKey(Long arg0) {#removeItemByKey-java.lang.Long-}
```
public boolean removeItemByKey(Long arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Long |  |

**Returns:**
boolean
### set_Item(PropertyDescriptor pd, MapiProperty value) {#set-Item-com.aspose.email.PropertyDescriptor-com.aspose.email.MapiProperty-}
```
public final void set_Item(PropertyDescriptor pd, MapiProperty value)
```


Возвращает или задает значение, связанное с указанным ключом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Ключ [PropertyDescriptor](../../com.aspose.email/propertydescriptor), значение которого следует получить или установить. |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### set_Item(Long arg0, MapiProperty arg1) {#set-Item-java.lang.Long-com.aspose.email.MapiProperty-}
```
public void set_Item(Long arg0, MapiProperty arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Long |  |
| arg1 | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### set_Item(long tag, MapiProperty value) {#set-Item-long-com.aspose.email.MapiProperty-}
```
public final void set_Item(long tag, MapiProperty value)
```


Возвращает или задает значение, связанное с указанным ключом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Ключ тега, значение которого следует получить или установить. |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### size() {#size--}
```
public final int size()
```


Возвращает количество элементов, содержащихся в коллекции.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetValue(Long arg0, Object[] arg1) {#tryGetValue-java.lang.Long-java.lang.Object---}
```
public boolean tryGetValue(Long arg0, Object[] arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Long |  |
| arg1 | java.lang.Object[] |  |

**Returns:**
boolean
### tryGetValue(long key, MapiProperty[] value) {#tryGetValue-long-com.aspose.email.MapiProperty---}
```
public final boolean tryGetValue(long key, MapiProperty[] value)
```


Возвращает свойство, связанное с указанным тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ключ | long | Тег свойства. |
| value | [MapiProperty\[\]](../../com.aspose.email/mapiproperty) |  |

**Returns:**
boolean -
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

