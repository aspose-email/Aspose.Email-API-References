---
title: StorageProcessedEventArgs
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет данные для события
type: docs
weight: 391
url: /ru/androidjava/com.aspose.email/storageprocessedeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class StorageProcessedEventArgs extends System.EventArgs
```

Предоставляет данные для события [PersonalStorage.StorageProcessedDelegate](../../com.aspose.email/personalstorage\#StorageProcessedDelegate)
## Поля

| Поле | Описание |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChunk()](#getChunk--) | Получает pst, представляющий фрагмент. |
| [getClass()](#getClass--) |  |
| [getFileName()](#getFileName--) | Получает имя файла pst, представляющего фрагмент. |
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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChunk() {#getChunk--}
```
public final PersonalStorage getChunk()
```


Получает pst, представляющий фрагмент.

Значение: Фрагмент.

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


Получает имя файла pst, представляющего фрагмент.

Значение: Имя файла.

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

