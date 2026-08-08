---
title: MapiPropertyCollection
second_title: Aspose.Email for Android via Java API 参考
description: 表示 MapiProperty 项的集合。
type: docs
weight: 272
url: /zh/androidjava/com.aspose.email/mapipropertycollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary, [com.aspose.email.INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider)
```
public class MapiPropertyCollection implements System.Collections.Generic.IGenericDictionary<Long,MapiProperty>, INamedPropertyTagProvider
```

表示 MapiProperty 项的集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiPropertyCollection()](#MapiPropertyCollection--) | 创建 MapiProperty 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(MapiProperty value)](#add-com.aspose.email.MapiProperty-) | 添加具有指定标签的 MapiProperty 项目。 |
| [add(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [add(long key, MapiProperty value)](#add-long-com.aspose.email.MapiProperty-) | 添加具有指定标签的 MapiProperty 项目。 |
| [addItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [addItem(Long arg0, MapiProperty arg1)](#addItem-java.lang.Long-com.aspose.email.MapiProperty-) |  |
| [clear()](#clear--) | 从集合中移除所有元素。 |
| [contains(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [containsItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [containsKey(Long arg0)](#containsKey-java.lang.Long-) |  |
| [containsKey(long key)](#containsKey-long-) | 确定集合是否包含具有指定标签的属性。 |
| [copyTo(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] array, int arrayIndex)](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-) |  |
| [copyToTArray(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] arg0, int arg1)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNamedPropertyTag(long dataType)](#generateNamedPropertyTag-long-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | 获取一个 System.Collections.Generic.ICollection<long>，其中包含集合中的键。 |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | 通过属性描述符获取 MAPI 属性。 |
| [getTagFromNamedProperty(String name)](#getTagFromNamedProperty-java.lang.String-) | 获取已命名属性的标签。 |
| [getTagFromNamedProperty(long LId)](#getTagFromNamedProperty-long-) | 获取已命名属性的标签。 |
| [getValues()](#getValues--) | 获取一个 System.Collections.Generic.ICollection<MapiProperty>，其中包含集合中的值。 |
| [get_Item(PropertyDescriptor pd)](#get-Item-com.aspose.email.PropertyDescriptor-) | 获取或设置与指定键关联的值。 |
| [get_Item(Long arg0)](#get-Item-java.lang.Long-) |  |
| [get_Item(long tag)](#get-Item-long-) | 获取或设置与指定键关联的值。 |
| [get_Keys()](#get-Keys--) | 获取一个 System.Collections.Generic.ICollection<long>，其中包含集合中的键。 |
| [get_Values()](#get-Values--) | 获取一个 System.Collections.Generic.ICollection<MapiProperty>，其中包含集合中的值。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个指示集合是否只读的值。 |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(PropertyDescriptor pd)](#remove-com.aspose.email.PropertyDescriptor-) | 从集合中移除具有指定属性描述符的属性。 |
| [remove(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [remove(long key)](#remove-long-) | 从集合中移除具有指定标签的属性。 |
| [removeItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [removeItemByKey(Long arg0)](#removeItemByKey-java.lang.Long-) |  |
| [set_Item(PropertyDescriptor pd, MapiProperty value)](#set-Item-com.aspose.email.PropertyDescriptor-com.aspose.email.MapiProperty-) | 获取或设置与指定键关联的值。 |
| [set_Item(Long arg0, MapiProperty arg1)](#set-Item-java.lang.Long-com.aspose.email.MapiProperty-) |  |
| [set_Item(long tag, MapiProperty value)](#set-Item-long-com.aspose.email.MapiProperty-) | 获取或设置与指定键关联的值。 |
| [size()](#size--) | 获取集合中包含的元素数量。 |
| [toString()](#toString--) |  |
| [tryGetValue(Long arg0, Object[] arg1)](#tryGetValue-java.lang.Long-java.lang.Object---) |  |
| [tryGetValue(long key, MapiProperty[] value)](#tryGetValue-long-com.aspose.email.MapiProperty---) | 获取与指定标签关联的属性。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiPropertyCollection() {#MapiPropertyCollection--}
```
public MapiPropertyCollection()
```


创建 MapiProperty 类的新实例。

### add(MapiProperty value) {#add-com.aspose.email.MapiProperty-}
```
public void add(MapiProperty value)
```


添加具有指定标签的 MapiProperty 项目。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | 属性值。 |

### add(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item) {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public final void add(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 项 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

### add(long key, MapiProperty value) {#add-long-com.aspose.email.MapiProperty-}
```
public void add(long key, MapiProperty value)
```


添加具有指定标签的 MapiProperty 项目。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | long | 属性标签。 |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | 属性值。 |

### addItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public void addItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

### addItem(Long arg0, MapiProperty arg1) {#addItem-java.lang.Long-com.aspose.email.MapiProperty-}
```
public void addItem(Long arg0, MapiProperty arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Long |  |
| arg1 | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### clear() {#clear--}
```
public final void clear()
```


从集合中移除所有元素。

### contains(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item) {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public final boolean contains(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 项 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### containsItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### containsKey(Long arg0) {#containsKey-java.lang.Long-}
```
public boolean containsKey(Long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Long |  |

**Returns:**
boolean
### containsKey(long key) {#containsKey-long-}
```
public final boolean containsKey(long key)
```


确定集合是否包含具有指定标签的属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | long | 属性标签。 |

**Returns:**
boolean - 如果集合包含具有该标签的属性，则为 true；否则为 false
### copyTo(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] array, int arrayIndex) {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-}
```
public final void copyTo(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] array, int arrayIndex)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数组 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty>[] |  |
| arrayIndex | int |  |

### copyToTArray(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] arg0, int arg1) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty>[] |  |
| arg1 | int |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNamedPropertyTag(long dataType) {#generateNamedPropertyTag-long-}
```
public final long generateNamedPropertyTag(long dataType)
```


生成命名属性标签

**Parameters:**
| 参数 | 类型 | 描述 |
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


获取一个 System.Collections.Generic.ICollection<long>，其中包含集合中的键。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


通过属性描述符获取 MAPI 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 已查找属性的属性描述符 |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### getTagFromNamedProperty(String name) {#getTagFromNamedProperty-java.lang.String-}
```
public final long getTagFromNamedProperty(String name)
```


获取已命名属性的标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 属性名称 |

**Returns:**
long - 属性标签值。
### getTagFromNamedProperty(long LId) {#getTagFromNamedProperty-long-}
```
public final long getTagFromNamedProperty(long LId)
```


获取已命名属性的标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| LId | long | 属性 ID。 |

**Returns:**
long - 属性标签值。
### getValues() {#getValues--}
```
public final System.Collections.Generic.IGenericCollection getValues()
```


获取一个 System.Collections.Generic.ICollection<MapiProperty>，其中包含集合中的值。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
### get_Item(PropertyDescriptor pd) {#get-Item-com.aspose.email.PropertyDescriptor-}
```
public final MapiProperty get_Item(PropertyDescriptor pd)
```


获取或设置与指定键关联的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 要获取或设置其值的 [PropertyDescriptor](../../com.aspose.email/propertydescriptor) 键。 |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The value associated with the specified key.
### get_Item(Long arg0) {#get-Item-java.lang.Long-}
```
public MapiProperty get_Item(Long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Long |  |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty)
### get_Item(long tag) {#get-Item-long-}
```
public final MapiProperty get_Item(long tag)
```


获取或设置与指定键关联的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 要获取或设置其值的标签键。 |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The value associated with the specified key.
### get_Keys() {#get-Keys--}
```
public final System.Collections.Generic.IGenericCollection<Long> get_Keys()
```


获取一个 System.Collections.Generic.ICollection<long>，其中包含集合中的键。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.Long>
### get_Values() {#get-Values--}
```
public final System.Collections.Generic.IGenericCollection<? extends MapiProperty> get_Values()
```


获取一个 System.Collections.Generic.ICollection<MapiProperty>，其中包含集合中的值。

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


获取一个指示集合是否只读的值。

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


从集合中移除具有指定属性描述符的属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 要删除的属性的属性描述符。 |

**Returns:**
布尔型 - 如果属性成功删除则为 true；否则为 false。
### remove(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item) {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public final boolean remove(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 项 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### remove(long key) {#remove-long-}
```
public final boolean remove(long key)
```


从集合中移除具有指定标签的属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | long | 要删除的属性的标签。 |

**Returns:**
布尔型 - 如果属性成功删除则为 true；否则为 false。
### removeItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### removeItemByKey(Long arg0) {#removeItemByKey-java.lang.Long-}
```
public boolean removeItemByKey(Long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Long |  |

**Returns:**
boolean
### set_Item(PropertyDescriptor pd, MapiProperty value) {#set-Item-com.aspose.email.PropertyDescriptor-com.aspose.email.MapiProperty-}
```
public final void set_Item(PropertyDescriptor pd, MapiProperty value)
```


获取或设置与指定键关联的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 要获取或设置其值的 [PropertyDescriptor](../../com.aspose.email/propertydescriptor) 键。 |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### set_Item(Long arg0, MapiProperty arg1) {#set-Item-java.lang.Long-com.aspose.email.MapiProperty-}
```
public void set_Item(Long arg0, MapiProperty arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Long |  |
| arg1 | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### set_Item(long tag, MapiProperty value) {#set-Item-long-com.aspose.email.MapiProperty-}
```
public final void set_Item(long tag, MapiProperty value)
```


获取或设置与指定键关联的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 要获取或设置其值的标签键。 |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### size() {#size--}
```
public final int size()
```


获取集合中包含的元素数量。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Long |  |
| arg1 | java.lang.Object[] |  |

**Returns:**
boolean
### tryGetValue(long key, MapiProperty[] value) {#tryGetValue-long-com.aspose.email.MapiProperty---}
```
public final boolean tryGetValue(long key, MapiProperty[] value)
```


获取与指定标签关联的属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | long | 属性标签。 |
| value | [MapiProperty\[\]](../../com.aspose.email/mapiproperty) |  |

**Returns:**
布尔 -
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

