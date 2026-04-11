---
title: PersonalStorageLoadOptions
second_title: Aspose.Email for Android via Java API Reference
description: Указывает дополнительные параметры при загрузке хранилища PST.
type: docs
weight: 345
url: /ru/androidjava/com.aspose.email/personalstorageloadoptions/
---

**Inheritance:**
java.lang.Object
```
public class PersonalStorageLoadOptions
```

Указывает дополнительные параметры при загрузке хранилища PST.
## Constructors

| Constructor | Описание |
| --- | --- |
| [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLeaveStreamOpen()](#getLeaveStreamOpen--) | Оставлять поток открытым при освобождении PersonalStorage. |
| [getWritable()](#getWritable--) | Получает или задаёт значение, указывающее, доступен ли pst для записи. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeaveStreamOpen(boolean value)](#setLeaveStreamOpen-boolean-) | Оставлять поток открытым при освобождении PersonalStorage. |
| [setWritable(boolean value)](#setWritable-boolean-) | Получает или задаёт значение, указывающее, доступен ли pst для записи. |
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
### getLeaveStreamOpen() {#getLeaveStreamOpen--}
```
public final boolean getLeaveStreamOpen()
```


Оставлять поток открытым при освобождении PersonalStorage. Должно всегда быть false, когда используется метод [PersonalStorage.fromFile(String,PersonalStorageLoadOptions)](../../com.aspose.email/personalstorage\#fromFile-String-PersonalStorageLoadOptions-). По умолчанию значение — false.

**Returns:**
boolean
### getWritable() {#getWritable--}
```
public final boolean getWritable()
```


Получает или задаёт значение, указывающее, доступен ли pst для записи. По умолчанию значение — true.

Значение: true если доступен для записи; иначе — false.

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


Оставлять поток открытым при освобождении PersonalStorage. Должно всегда быть false, когда используется метод [PersonalStorage.fromFile(String,PersonalStorageLoadOptions)](../../com.aspose.email/personalstorage\#fromFile-String-PersonalStorageLoadOptions-). По умолчанию значение — false.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setWritable(boolean value) {#setWritable-boolean-}
```
public final void setWritable(boolean value)
```


Получает или задаёт значение, указывающее, доступен ли pst для записи. По умолчанию значение — true.

Значение: true если доступен для записи; иначе — false.

**Parameters:**
| Parameter | Type | Описание |
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

