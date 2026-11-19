---
title: PersonalStorageLoadOptions
second_title: Aspose.Email for Java API Reference
description: Options for opening a PST or OST file or stream.
type: docs
weight: 590
url: /java/com.aspose.email/personalstorageloadoptions/
---

**Inheritance:**
java.lang.Object
```
public class PersonalStorageLoadOptions
```

Options for opening a PST or OST file or stream.
## Constructors

| Constructor | Description |
| --- | --- |
| [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Initializes a new instance of the [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) class with the default settings: read-only access, and the stream is closed when the storage is disposed. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLeaveStreamOpen()](#getLeaveStreamOpen--) | Gets whether to leave the stream open when the [PersonalStorage](../../com.aspose.email/personalstorage) is disposed. |
| [getWritable()](#getWritable--) | Gets whether the PST is opened for writing. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeaveStreamOpen(boolean value)](#setLeaveStreamOpen-boolean-) | Sets whether to leave the stream open when the [PersonalStorage](../../com.aspose.email/personalstorage) is disposed. |
| [setWritable(boolean value)](#setWritable-boolean-) | Sets whether the PST is opened for writing. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Initializes a new instance of the [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) class with the default settings: read-only access, and the stream is closed when the storage is disposed.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeaveStreamOpen() {#getLeaveStreamOpen--}
```
public final boolean getLeaveStreamOpen()
```


Gets whether to leave the stream open when the [PersonalStorage](../../com.aspose.email/personalstorage) is disposed. It must be  false  when opening a file with [PersonalStorage.fromFile(String, PersonalStorageLoadOptions)](../../com.aspose.email/personalstorage\#fromFile-String--PersonalStorageLoadOptions-). The default is  false .

**Returns:**
boolean
### getWritable() {#getWritable--}
```
public final boolean getWritable()
```


Gets whether the PST is opened for writing. The default is  false .

**Returns:**
boolean -  true  if writable; otherwise,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLeaveStreamOpen(boolean value) {#setLeaveStreamOpen-boolean-}
```
public final void setLeaveStreamOpen(boolean value)
```


Sets whether to leave the stream open when the [PersonalStorage](../../com.aspose.email/personalstorage) is disposed. It must be  false  when opening a file with [PersonalStorage.fromFile(String, PersonalStorageLoadOptions)](../../com.aspose.email/personalstorage\#fromFile-String--PersonalStorageLoadOptions-). The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setWritable(boolean value) {#setWritable-boolean-}
```
public final void setWritable(boolean value)
```


Sets whether the PST is opened for writing. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if writable; otherwise,  false . |

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

