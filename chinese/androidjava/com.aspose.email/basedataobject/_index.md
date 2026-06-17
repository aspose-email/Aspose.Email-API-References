---
title: BaseDataObject
second_title: Aspose.Email for Android via Java API 参考
description: Google 数据对象的基类。
type: docs
weight: 57
url: /zh/androidjava/com.aspose.email/basedataobject/
---

**Inheritance:**
java.lang.Object
```
public abstract class BaseDataObject
```

Google 数据对象的基类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BaseDataObject(String kind)](#BaseDataObject-java.lang.String-) | 初始化该类的新实例。 |
| [BaseDataObject(String kind, String id)](#BaseDataObject-java.lang.String-java.lang.String-) | 初始化该类的新实例。 |
| [BaseDataObject(String kind, String id, String eTag)](#BaseDataObject-java.lang.String-java.lang.String-java.lang.String-) | 初始化该类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getETag()](#getETag--) | ETag（实体标签）是 HTTP 提供的用于网页缓存验证的多种机制之一，能够让客户端发起条件请求。 |
| [getId()](#getId--) | 资源的标识符。 |
| [getKind()](#getKind--) | 资源的类型 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setETag(String value)](#setETag-java.lang.String-) | ETag（实体标签）是 HTTP 提供的用于网页缓存验证的多种机制之一，能够让客户端发起条件请求。 |
| [setId(String value)](#setId-java.lang.String-) | 资源的标识符。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseDataObject(String kind) {#BaseDataObject-java.lang.String-}
```
public BaseDataObject(String kind)
```


初始化该类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 种类 | java.lang.String | 资源的类型 |

### BaseDataObject(String kind, String id) {#BaseDataObject-java.lang.String-java.lang.String-}
```
public BaseDataObject(String kind, String id)
```


初始化该类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 种类 | java.lang.String | 资源的类型 |
| id | java.lang.String | 资源的标识符。 |

### BaseDataObject(String kind, String id, String eTag) {#BaseDataObject-java.lang.String-java.lang.String-java.lang.String-}
```
public BaseDataObject(String kind, String id, String eTag)
```


初始化该类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 种类 | java.lang.String | 资源的类型 |
| id | java.lang.String | 资源的标识符。 |
| eTag | java.lang.String | 实体标签 |

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
### getETag() {#getETag--}
```
public String getETag()
```


ETag（实体标签）是 HTTP 提供的用于网页缓存验证的多种机制之一，能够让客户端发起条件请求。这使得缓存更加高效，并节省带宽，因为如果内容未改变，Web 服务器无需发送完整响应。ETag 还可用于乐观并发控制，以帮助防止对同一资源的同时更新相互覆盖。

**Returns:**
java.lang.String
### getId() {#getId--}
```
public String getId()
```


资源的标识符。

**Returns:**
java.lang.String
### getKind() {#getKind--}
```
public String getKind()
```


资源的类型

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


ETag（实体标签）是 HTTP 提供的用于网页缓存验证的多种机制之一，能够让客户端发起条件请求。这使得缓存更加高效，并节省带宽，因为如果内容未改变，Web 服务器无需发送完整响应。ETag 还可用于乐观并发控制，以帮助防止对同一资源的同时更新相互覆盖。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setId(String value) {#setId-java.lang.String-}
```
public void setId(String value)
```


资源的标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
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

