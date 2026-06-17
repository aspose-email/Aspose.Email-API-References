---
title: PersonalStorageLoadOptions
second_title: Aspose.Email for Android via Java API 参考
description: 指定加载 PST 存储时的附加选项。
type: docs
weight: 345
url: /zh/androidjava/com.aspose.email/personalstorageloadoptions/
---

**Inheritance:**
java.lang.Object
```
public class PersonalStorageLoadOptions
```

指定加载 PST 存储时的附加选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLeaveStreamOpen()](#getLeaveStreamOpen--) | 在释放 PersonalStorage 时保持流打开。 |
| [getWritable()](#getWritable--) | 获取或设置指示 pst 是否可写的值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeaveStreamOpen(boolean value)](#setLeaveStreamOpen-boolean-) | 在释放 PersonalStorage 时保持流打开。 |
| [setWritable(boolean value)](#setWritable-boolean-) | 获取或设置指示 pst 是否可写的值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
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


在释放 PersonalStorage 时保持流打开。当使用 [PersonalStorage.fromFile(String,PersonalStorageLoadOptions)](../../com.aspose.email/personalstorage\\#fromFile-String-PersonalStorageLoadOptions-) 方法时应始终为 false。默认情况下该值为 false。

**Returns:**
boolean
### getWritable() {#getWritable--}
```
public final boolean getWritable()
```


获取或设置指示 pst 是否可写的值。默认情况下该值为 true。

值：如果可写则为 true；否则为 false。

**Returns:**
boolean
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


在释放 PersonalStorage 时保持流打开。当使用 [PersonalStorage.fromFile(String,PersonalStorageLoadOptions)](../../com.aspose.email/personalstorage\\#fromFile-String-PersonalStorageLoadOptions-) 方法时应始终为 false。默认情况下该值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setWritable(boolean value) {#setWritable-boolean-}
```
public final void setWritable(boolean value)
```


获取或设置指示 pst 是否可写的值。默认情况下该值为 true。

值：如果可写则为 true；否则为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

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

