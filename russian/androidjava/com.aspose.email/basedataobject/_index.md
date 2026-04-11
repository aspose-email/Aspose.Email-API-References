---
title: BaseDataObject
second_title: Aspose.Email for Android via Java API Reference
description: Базовый класс для объектов данных Google.
type: docs
weight: 57
url: /ru/androidjava/com.aspose.email/basedataobject/
---

**Inheritance:**
java.lang.Object
```
public abstract class BaseDataObject
```

Базовый класс для объектов данных Google.
## Constructors

| Constructor | Описание |
| --- | --- |
| [BaseDataObject(String kind)](#BaseDataObject-java.lang.String-) | Инициализирует новый экземпляр класса. |
| [BaseDataObject(String kind, String id)](#BaseDataObject-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса. |
| [BaseDataObject(String kind, String id, String eTag)](#BaseDataObject-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getETag()](#getETag--) | ETag или entity tag — один из нескольких механизмов, которые HTTP предоставляет для проверки веб‑кэша, и который позволяет клиенту выполнять условные запросы. |
| [getId()](#getId--) | Идентификатор ресурса. |
| [getKind()](#getKind--) | Тип ресурса |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setETag(String value)](#setETag-java.lang.String-) | ETag или entity tag — один из нескольких механизмов, которые HTTP предоставляет для проверки веб‑кэша, и который позволяет клиенту выполнять условные запросы. |
| [setId(String value)](#setId-java.lang.String-) | Идентификатор ресурса. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseDataObject(String kind) {#BaseDataObject-java.lang.String-}
```
public BaseDataObject(String kind)
```


Инициализирует новый экземпляр класса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| вид | java.lang.String | Тип ресурса |

### BaseDataObject(String kind, String id) {#BaseDataObject-java.lang.String-java.lang.String-}
```
public BaseDataObject(String kind, String id)
```


Инициализирует новый экземпляр класса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| вид | java.lang.String | Тип ресурса |
| id | java.lang.String | Идентификатор ресурса. |

### BaseDataObject(String kind, String id, String eTag) {#BaseDataObject-java.lang.String-java.lang.String-java.lang.String-}
```
public BaseDataObject(String kind, String id, String eTag)
```


Инициализирует новый экземпляр класса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| вид | java.lang.String | Тип ресурса |
| id | java.lang.String | Идентификатор ресурса. |
| eTag | java.lang.String | Тег сущности |

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
### getETag() {#getETag--}
```
public String getETag()
```


ETag или entity tag — один из нескольких механизмов, которые HTTP предоставляет для проверки веб‑кэша, и который позволяет клиенту выполнять условные запросы. Это делает кэши более эффективными и экономит пропускную способность, поскольку веб‑серверу не нужно отправлять полный ответ, если содержимое не изменилось. ETag также могут использоваться для оптимистичного контроля конкурентности, как способ помочь предотвратить перезапись друг друга при одновременных обновлениях ресурса.

**Returns:**
java.lang.String
### getId() {#getId--}
```
public String getId()
```


Идентификатор ресурса.

**Returns:**
java.lang.String
### getKind() {#getKind--}
```
public String getKind()
```


Тип ресурса

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




### setETag(String value) {#setETag-java.lang.String-}
```
public void setETag(String value)
```


ETag или entity tag — один из нескольких механизмов, которые HTTP предоставляет для проверки веб‑кэша, и который позволяет клиенту выполнять условные запросы. Это делает кэши более эффективными и экономит пропускную способность, поскольку веб‑серверу не нужно отправлять полный ответ, если содержимое не изменилось. ETag также могут использоваться для оптимистичного контроля конкурентности, как способ помочь предотвратить перезапись друг друга при одновременных обновлениях ресурса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setId(String value) {#setId-java.lang.String-}
```
public void setId(String value)
```


Идентификатор ресурса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

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

