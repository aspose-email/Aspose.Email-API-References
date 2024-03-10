---
title: StorageProcessedEventArgs
second_title: Aspose.Email for Java API Reference
description: Provides data for the  event
type: docs
weight: 667
url: /java/com.aspose.email/storageprocessedeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class StorageProcessedEventArgs extends System.EventArgs
```

Provides data for the [PersonalStorage.StorageProcessedDelegate](../../com.aspose.email/personalstorage\#StorageProcessedDelegate) event
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChunk()](#getChunk--) | Gets the pst that represents the chunk. |
| [getClass()](#getClass--) |  |
| [getFileName()](#getFileName--) | Gets the name of the pst file, that represents the chunk. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Empty {#Empty}
```
public static final System.EventArgs Empty
```


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
### getChunk() {#getChunk--}
```
public final PersonalStorage getChunk()
```


Gets the pst that represents the chunk.

Value: The chunk.

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gets the name of the pst file, that represents the chunk.

Value: The name of the file.

**Returns:**
java.lang.String
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

