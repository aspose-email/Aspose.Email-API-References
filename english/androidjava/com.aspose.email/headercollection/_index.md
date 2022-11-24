---
title: HeaderCollection
second_title: Aspose.Email for Android via Java API Reference
description: Defines the collection of header fields
type: docs
weight: 155
url: /androidjava/com.aspose.email/headercollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public class HeaderCollection implements System.Collections.ICollection<String>
```

Defines the collection of header fields
## Constructors

| Constructor | Description |
| --- | --- |
| [HeaderCollection(HeaderCollection col)](#HeaderCollection-com.aspose.email.HeaderCollection-) | Initializes a new instance of the [HeaderCollection](../../com.aspose.email/headercollection) class. |
| [HeaderCollection()](#HeaderCollection--) | Initializes a new instance of the [HeaderCollection](../../com.aspose.email/headercollection) class. |
## Methods

| Method | Description |
| --- | --- |
| [add(HeaderCollection c)](#add-com.aspose.email.HeaderCollection-) | Adds a header to collection. |
| [add(String item)](#add-java.lang.String-) | Adds the header without value |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adds the header. |
| [add_(String name, String value)](#add--java.lang.String-java.lang.String-) | Adds the header. |
| [clear()](#clear--) | Clears all headers. |
| [contains(String item)](#contains-java.lang.String-) | Gets a value indicating whether the specified header is contained in the collection |
| [copyTo(System.Array dest, int index)](#copyTo-com.aspose.ms.System.Array-int-) |  |
| [copyTo(String[] array, int arrayIndex)](#copyTo-java.lang.String---int-) | Copies all the elements of the current collection to the specified string array starting at the specified destination index. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Gets the value at the specified index. |
| [get(String name)](#get-java.lang.String-) | Gets the header value by a given header name. |
| [getAllKeys()](#getAllKeys--) | Gets an array of strings containing all header keys in collections |
| [getClass()](#getClass--) |  |
| [getDecodedValue(String name)](#getDecodedValue-java.lang.String-) | Gets the header value. |
| [getKey(int index)](#getKey-int-) | Gets the key at the specified index of the collection. |
| [getKeys()](#getKeys--) | Gets a  System.Collections.ObjectModel.ReadOnlyCollection\{string\}  containing all header keys in collections |
| [getSyncRoot()](#getSyncRoot--) |  |
| [getValues(String name)](#getValues-java.lang.String-) | Gets the header values. |
| [get_Item(int index)](#get-Item-int-) | Gets a value from collection by the index. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets a value from collection by the name. |
| [hasKeys()](#hasKeys--) | Gets a value indicating whether the collection contains keys. |
| [hashCode()](#hashCode--) |  |
| [insert(String name, String value)](#insert-java.lang.String-java.lang.String-) | Inserts the header in collection. |
| [isReadOnly()](#isReadOnly--) | Is collection readonly |
| [isSynchronized()](#isSynchronized--) |  |
| [iterator()](#iterator--) | Returns an enumerator that iterates through a collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String item)](#remove-java.lang.String-) | Removes the header from collection by a given header name. |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Sets the header. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Gets a value from collection by the name. |
| [size()](#size--) | Gets a count of headers |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HeaderCollection(HeaderCollection col) {#HeaderCollection-com.aspose.email.HeaderCollection-}
```
public HeaderCollection(HeaderCollection col)
```


Initializes a new instance of the [HeaderCollection](../../com.aspose.email/headercollection) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| col | [HeaderCollection](../../com.aspose.email/headercollection) | The collection. |

### HeaderCollection() {#HeaderCollection--}
```
public HeaderCollection()
```


Initializes a new instance of the [HeaderCollection](../../com.aspose.email/headercollection) class.

### add(HeaderCollection c) {#add-com.aspose.email.HeaderCollection-}
```
public final void add(HeaderCollection c)
```


Adds a header to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | [HeaderCollection](../../com.aspose.email/headercollection) | HeaderCollection for adding. |

### add(String item) {#add-java.lang.String-}
```
public final void add(String item)
```


Adds the header without value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | java.lang.String |  |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```


Adds the header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The header name. |
| value | java.lang.String | The header value. |

### add_(String name, String value) {#add--java.lang.String-java.lang.String-}
```
public void add_(String name, String value)
```


Adds the header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The header name. |
| value | java.lang.String | The header value. |

### clear() {#clear--}
```
public void clear()
```


Clears all headers.

### contains(String item) {#contains-java.lang.String-}
```
public final boolean contains(String item)
```


Gets a value indicating whether the specified header is contained in the collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | java.lang.String | A header to search |

**Returns:**
boolean -  True  if collection contains specified  item ; otherwise,  false 
### copyTo(System.Array dest, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array dest, int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dest | com.aspose.ms.System.Array |  |
| index | int |  |

### copyTo(String[] array, int arrayIndex) {#copyTo-java.lang.String---int-}
```
public final void copyTo(String[] array, int arrayIndex)
```


Copies all the elements of the current collection to the specified string array starting at the specified destination index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | java.lang.String[] | The destination of the elements copied from the current collection. |
| arrayIndex | int | An integer that represents the index in array at which copying begins. |

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
### get(int index) {#get-int-}
```
public String get(int index)
```


Gets the value at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | An integer that represents the position of the element to get. |

**Returns:**
java.lang.String - The value at the specified position in current collection.
### get(String name) {#get-java.lang.String-}
```
public final String get(String name)
```


Gets the header value by a given header name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The haeader name. |

**Returns:**
java.lang.String - The header value.
### getAllKeys() {#getAllKeys--}
```
public String[] getAllKeys()
```


Gets an array of strings containing all header keys in collections

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


Gets the header value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The text header name. |

**Returns:**
java.lang.String - Decoded text value
### getKey(int index) {#getKey-int-}
```
public String getKey(int index)
```


Gets the key at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the key. |

**Returns:**
java.lang.String - The key at the specified index.
### getKeys() {#getKeys--}
```
public List<String> getKeys()
```


Gets a  System.Collections.ObjectModel.ReadOnlyCollection\{string\}  containing all header keys in collections

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


Gets the header values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The header name. |

**Returns:**
java.lang.String[] - The collection of header values.
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Gets a value from collection by the index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index in collection for an item. |

**Returns:**
java.lang.String - Returns specified item
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Gets a value from collection by the name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name (key) in collection for an item. |

**Returns:**
java.lang.String - Returns specified item
### hasKeys() {#hasKeys--}
```
public final boolean hasKeys()
```


Gets a value indicating whether the collection contains keys.

**Returns:**
boolean - Returns true if collection has an items, otherwise returns false.
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


Inserts the header in collection. If collection contains headers with the same name this header will be inserted before other headers with the same name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The header name. |
| value | java.lang.String | The header value. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Is collection readonly

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


Returns an enumerator that iterates through a collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<java.lang.String> - An  System.Collections.Generic.IEnumerator\{string\}  object that can be used to iterate through the collection.
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


Removes the header from collection by a given header name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | java.lang.String | The header name. |

**Returns:**
boolean - true if item was successfully removed from the collection.
### set(String name, String value) {#set-java.lang.String-java.lang.String-}
```
public final void set(String name, String value)
```


Sets the header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The header name. |
| value | java.lang.String | The header value. |

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Gets a value from collection by the name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name (key) in collection for an item. |
| value | java.lang.String |  |

### size() {#size--}
```
public int size()
```


Gets a count of headers

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

