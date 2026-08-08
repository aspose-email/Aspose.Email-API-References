---
title: ContentType
second_title: Aspose.Email for Android via Java API 参考
description: 表示 Content-Type 头部。
type: docs
weight: 86
url: /zh/androidjava/com.aspose.email/contenttype/
---

**Inheritance:**
java.lang.Object
```
public class ContentType
```

表示 Content-Type 头部。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ContentType()](#ContentType--) | 初始化 [ContentType](../../com.aspose.email/contenttype) 类的新实例。 |
| [ContentType(String contentType)](#ContentType-java.lang.String-) | 初始化 [ContentType](../../com.aspose.email/contenttype) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于此实例。 |
| [getBoundary()](#getBoundary--) | 获取或设置包含在 Content-Type 标头中的 boundary 参数的值。 |
| [getCharSet()](#getCharSet--) | 获取或设置 charset 参数的值。 |
| [getClass()](#getClass--) |  |
| [getMediaType()](#getMediaType--) | 获取或设置互联网媒体类型。 |
| [getName()](#getName--) | 获取或设置 name 参数的值。 |
| [getParameters()](#getParameters--) | 获取包含这些参数的字典。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBoundary(String value)](#setBoundary-java.lang.String-) | 获取或设置包含在 Content-Type 标头中的 boundary 参数的值。 |
| [setCharSet(String value)](#setCharSet-java.lang.String-) | 获取或设置 charset 参数的值。 |
| [setMediaType(String value)](#setMediaType-java.lang.String-) | 获取或设置互联网媒体类型。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置 name 参数的值。 |
| [toString()](#toString--) | 返回表示此实例的 String。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContentType() {#ContentType--}
```
public ContentType()
```


初始化 [ContentType](../../com.aspose.email/contenttype) 类的新实例。

### ContentType(String contentType) {#ContentType-java.lang.String-}
```
public ContentType(String contentType)
```


初始化 [ContentType](../../com.aspose.email/contenttype) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentType | java.lang.String | 内容的类型。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 Object 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Object。 |

**Returns:**
boolean - 如果指定的 Object 等于此实例则为 true；否则为 false。
### getBoundary() {#getBoundary--}
```
public final String getBoundary()
```


获取或设置包含在 Content-Type 标头中的 boundary 参数的值。

值：包含 boundary 参数值的字符串。

**Returns:**
java.lang.String
### getCharSet() {#getCharSet--}
```
public final String getCharSet()
```


获取或设置 charset 参数的值。

值：包含 charset 参数值的字符串。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


获取或设置互联网媒体类型。

值：包含媒体类型的字符串。

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


获取或设置 name 参数的值。

值：包含名称的字符串。

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public final TrackingStringDictionary getParameters()
```


获取包含这些参数的字典。

值：包含名称和值对的 StringDictionary。

**Returns:**
[TrackingStringDictionary](../../com.aspose.email/trackingstringdictionary)
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBoundary(String value) {#setBoundary-java.lang.String-}
```
public final void setBoundary(String value)
```


获取或设置包含在 Content-Type 标头中的 boundary 参数的值。

值：包含 boundary 参数值的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCharSet(String value) {#setCharSet-java.lang.String-}
```
public final void setCharSet(String value)
```


获取或设置 charset 参数的值。

值：包含 charset 参数值的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMediaType(String value) {#setMediaType-java.lang.String-}
```
public final void setMediaType(String value)
```


获取或设置互联网媒体类型。

值：包含媒体类型的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


获取或设置 name 参数的值。

值：包含名称的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的 String。

**Returns:**
java.lang.String - 表示此实例的 String。
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

