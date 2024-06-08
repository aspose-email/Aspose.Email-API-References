---
title: MapiPropertyCollection
second_title: Aspose.Email for Java API Reference
description: Represents the collection of MapiProperty items.
type: docs
weight: 461
url: /java/com.aspose.email/mapipropertycollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary, [com.aspose.email.INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider)
```
public class MapiPropertyCollection implements System.Collections.Generic.IGenericDictionary<Long,MapiProperty>, INamedPropertyTagProvider
```

Represents the collection of MapiProperty items.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiPropertyCollection()](#MapiPropertyCollection--) | Creates a new instance of class MapiProperty. |
## Methods

| Method | Description |
| --- | --- |
| [add(MapiProperty value)](#add-com.aspose.email.MapiProperty-) | Adds a MapiProperty item with specified tag. |
| [add(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [add(long key, MapiProperty value)](#add-long-com.aspose.email.MapiProperty-) | Adds a MapiProperty item with specified tag. |
| [addItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [addItem(Long arg0, MapiProperty arg1)](#addItem-java.lang.Long-com.aspose.email.MapiProperty-) |  |
| [clear()](#clear--) | Removes all of the elements from the collection. |
| [contains(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [containsItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [containsKey(Long arg0)](#containsKey-java.lang.Long-) |  |
| [containsKey(long key)](#containsKey-long-) | Determines whether the collection contains a property with the specified tag. |
| [copyTo(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] array, int arrayIndex)](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-) |  |
| [copyToTArray(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] arg0, int arg1)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNamedPropertyTag(long dataType)](#generateNamedPropertyTag-long-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Gets a System.Collections.Generic.ICollection<long> containing the keys in the collection. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets MAPI property by property descriptor. |
| [getTagFromNamedProperty(String name)](#getTagFromNamedProperty-java.lang.String-) | Gets the tag from named property. |
| [getTagFromNamedProperty(long LId)](#getTagFromNamedProperty-long-) | Gets the tag from named property. |
| [getValues()](#getValues--) | Gets an System.Collections.Generic.ICollection<MapiProperty> containing the values in the collection. |
| [get_Item(PropertyDescriptor pd)](#get-Item-com.aspose.email.PropertyDescriptor-) | Gets or sets the value associated with the specified key. |
| [get_Item(Long arg0)](#get-Item-java.lang.Long-) |  |
| [get_Item(long tag)](#get-Item-long-) | Gets or sets the value associated with the specified key. |
| [get_Keys()](#get-Keys--) | Gets a System.Collections.Generic.ICollection<long> containing the keys in the collection. |
| [get_Values()](#get-Values--) | Gets an System.Collections.Generic.ICollection<MapiProperty> containing the values in the collection. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read only. |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(PropertyDescriptor pd)](#remove-com.aspose.email.PropertyDescriptor-) | Removes the property with the specified property descriptor from the collection. |
| [remove(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [remove(long key)](#remove-long-) | Removes the property with the specified tag from the collection. |
| [removeItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--) |  |
| [removeItemByKey(Long arg0)](#removeItemByKey-java.lang.Long-) |  |
| [set_Item(PropertyDescriptor pd, MapiProperty value)](#set-Item-com.aspose.email.PropertyDescriptor-com.aspose.email.MapiProperty-) | Gets or sets the value associated with the specified key. |
| [set_Item(Long arg0, MapiProperty arg1)](#set-Item-java.lang.Long-com.aspose.email.MapiProperty-) |  |
| [set_Item(long tag, MapiProperty value)](#set-Item-long-com.aspose.email.MapiProperty-) | Gets or sets the value associated with the specified key. |
| [size()](#size--) | Gets the number of elements contained in the collection. |
| [toString()](#toString--) |  |
| [tryGetValue(Long arg0, Object[] arg1)](#tryGetValue-java.lang.Long-java.lang.Object---) |  |
| [tryGetValue(long key, MapiProperty[] value)](#tryGetValue-long-com.aspose.email.MapiProperty---) | Gets the property associated with the specified tag. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiPropertyCollection() {#MapiPropertyCollection--}
```
public MapiPropertyCollection()
```


Creates a new instance of class MapiProperty.

### add(MapiProperty value) {#add-com.aspose.email.MapiProperty-}
```
public void add(MapiProperty value)
```


Adds a MapiProperty item with specified tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property value. |

### add(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item) {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public final void add(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

### add(long key, MapiProperty value) {#add-long-com.aspose.email.MapiProperty-}
```
public void add(long key, MapiProperty value)
```


Adds a MapiProperty item with specified tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The property tag. |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property value. |

### addItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public void addItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

### addItem(Long arg0, MapiProperty arg1) {#addItem-java.lang.Long-com.aspose.email.MapiProperty-}
```
public void addItem(Long arg0, MapiProperty arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Long |  |
| arg1 | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### clear() {#clear--}
```
public final void clear()
```


Removes all of the elements from the collection.

### contains(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item) {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public final boolean contains(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### containsItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### containsKey(Long arg0) {#containsKey-java.lang.Long-}
```
public boolean containsKey(Long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Long |  |

**Returns:**
boolean
### containsKey(long key) {#containsKey-long-}
```
public final boolean containsKey(long key)
```


Determines whether the collection contains a property with the specified tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The property tag. |

**Returns:**
boolean - true if the collection contains a property with the tag; otherwise, false
### copyTo(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] array, int arrayIndex) {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-}
```
public final void copyTo(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] array, int arrayIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty>[] |  |
| arrayIndex | int |  |

### copyToTArray(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] arg0, int arg1) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<Long,MapiProperty>[] arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty>[] |  |
| arg1 | int |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNamedPropertyTag(long dataType) {#generateNamedPropertyTag-long-}
```
public final long generateNamedPropertyTag(long dataType)
```


Generates named property tag

**Parameters:**
| Parameter | Type | Description |
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


Gets a System.Collections.Generic.ICollection<long> containing the keys in the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Gets MAPI property by property descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Property descriptor for looked property |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### getTagFromNamedProperty(String name) {#getTagFromNamedProperty-java.lang.String-}
```
public final long getTagFromNamedProperty(String name)
```


Gets the tag from named property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The property name |

**Returns:**
long - The property tag value.
### getTagFromNamedProperty(long LId) {#getTagFromNamedProperty-long-}
```
public final long getTagFromNamedProperty(long LId)
```


Gets the tag from named property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| LId | long | The property id. |

**Returns:**
long - The property tag value.
### getValues() {#getValues--}
```
public final System.Collections.Generic.IGenericCollection getValues()
```


Gets an System.Collections.Generic.ICollection<MapiProperty> containing the values in the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
### get_Item(PropertyDescriptor pd) {#get-Item-com.aspose.email.PropertyDescriptor-}
```
public final MapiProperty get_Item(PropertyDescriptor pd)
```


Gets or sets the value associated with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The [PropertyDescriptor](../../com.aspose.email/propertydescriptor) key whose value to get or set. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The value associated with the specified key.
### get_Item(Long arg0) {#get-Item-java.lang.Long-}
```
public MapiProperty get_Item(Long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Long |  |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty)
### get_Item(long tag) {#get-Item-long-}
```
public final MapiProperty get_Item(long tag)
```


Gets or sets the value associated with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag key whose value to get or set. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The value associated with the specified key.
### get_Keys() {#get-Keys--}
```
public final System.Collections.Generic.IGenericCollection<Long> get_Keys()
```


Gets a System.Collections.Generic.ICollection<long> containing the keys in the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.Long>
### get_Values() {#get-Values--}
```
public final System.Collections.Generic.IGenericCollection<? extends MapiProperty> get_Values()
```


Gets an System.Collections.Generic.ICollection<MapiProperty> containing the values in the collection.

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


Gets a value indicating whether the collection is read only.

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


Removes the property with the specified property descriptor from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Property descriptor of the property to remove. |

**Returns:**
boolean - true if the property is successfully removed; otherwise, false.
### remove(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item) {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public final boolean remove(System.Collections.Generic.KeyValuePair<Long,MapiProperty> item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### remove(long key) {#remove-long-}
```
public final boolean remove(long key)
```


Removes the property with the specified tag from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The tag of the property to remove. |

**Returns:**
boolean - true if the property is successfully removed; otherwise, false.
### removeItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Long-com.aspose.email.MapiProperty--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<Long,MapiProperty> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Long,com.aspose.email.MapiProperty> |  |

**Returns:**
boolean
### removeItemByKey(Long arg0) {#removeItemByKey-java.lang.Long-}
```
public boolean removeItemByKey(Long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Long |  |

**Returns:**
boolean
### set_Item(PropertyDescriptor pd, MapiProperty value) {#set-Item-com.aspose.email.PropertyDescriptor-com.aspose.email.MapiProperty-}
```
public final void set_Item(PropertyDescriptor pd, MapiProperty value)
```


Gets or sets the value associated with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The [PropertyDescriptor](../../com.aspose.email/propertydescriptor) key whose value to get or set. |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### set_Item(Long arg0, MapiProperty arg1) {#set-Item-java.lang.Long-com.aspose.email.MapiProperty-}
```
public void set_Item(Long arg0, MapiProperty arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Long |  |
| arg1 | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### set_Item(long tag, MapiProperty value) {#set-Item-long-com.aspose.email.MapiProperty-}
```
public final void set_Item(long tag, MapiProperty value)
```


Gets or sets the value associated with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag key whose value to get or set. |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) |  |

### size() {#size--}
```
public final int size()
```


Gets the number of elements contained in the collection.

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Long |  |
| arg1 | java.lang.Object[] |  |

**Returns:**
boolean
### tryGetValue(long key, MapiProperty[] value) {#tryGetValue-long-com.aspose.email.MapiProperty---}
```
public final boolean tryGetValue(long key, MapiProperty[] value)
```


Gets the property associated with the specified tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The property tag. |
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

