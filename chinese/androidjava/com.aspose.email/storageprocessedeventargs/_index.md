---
title: StorageProcessedEventArgs
second_title: Aspose.Email for Android via Java API 参考
description: 提供事件的数据。
type: docs
weight: 391
url: /zh/androidjava/com.aspose.email/storageprocessedeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class StorageProcessedEventArgs extends System.EventArgs
```

提供 [PersonalStorage.StorageProcessedDelegate](../../com.aspose.email/personalstorage\#StorageProcessedDelegate) 事件的数据。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Empty](#Empty) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChunk()](#getChunk--) | 获取表示该块的 pst。 |
| [getClass()](#getClass--) |  |
| [getFileName()](#getFileName--) | 获取表示该块的 pst 文件的名称。 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChunk() {#getChunk--}
```
public final PersonalStorage getChunk()
```


获取表示该块的 pst。

值：该块。

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


获取表示该块的 pst 文件的名称。

值：文件的名称。

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

