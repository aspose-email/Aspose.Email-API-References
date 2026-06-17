---
title: 日历
second_title: Aspose.Email for Android via Java API 参考
description: 单个日历的描述等元数据集合。
type: docs
weight: 65
url: /zh/androidjava/com.aspose.email/calendar/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.BaseDataObject](../../com.aspose.email/basedataobject)
```
public class Calendar extends BaseDataObject
```

单个日历的元数据集合，例如描述。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Calendar()](#Calendar--) | 初始化 Calendar 类的新实例。 |
| [Calendar(String summary)](#Calendar-java.lang.String-) | 初始化 Calendar 类的新实例。 |
| [Calendar(String id, String summary)](#Calendar-java.lang.String-java.lang.String-) | 初始化 Calendar 类的新实例。 |
| [Calendar(String summary, String description, String location, String timeZone)](#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 初始化 Calendar 类的新实例。 |
| [Calendar(String id, String summary, String description, String location, String timeZone)](#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 初始化 Calendar 类的新实例。 |
| [Calendar(String id, String eTag, String summary, String description, String location, String timeZone)](#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 初始化 Calendar 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [CALENDAR_KIND](#CALENDAR-KIND) | 资源 'calendar\#calendar' 的类型。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConferenceProperties()](#getConferenceProperties--) | 获取此日历的会议属性。 |
| [getDescription()](#getDescription--) | 日历的描述。 |
| [getETag()](#getETag--) | ETag（实体标签）是 HTTP 提供的用于网页缓存验证的多种机制之一，能够让客户端发起条件请求。 |
| [getId()](#getId--) | 资源的标识符。 |
| [getKind()](#getKind--) | 资源的类型 |
| [getLocation()](#getLocation--) | 日历的地理位置（自由文本）。 |
| [getSummary()](#getSummary--) | 日历的标题。 |
| [getTimeZone()](#getTimeZone--) | 日历的时区。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | 日历的描述。 |
| [setETag(String value)](#setETag-java.lang.String-) | ETag（实体标签）是 HTTP 提供的用于网页缓存验证的多种机制之一，能够让客户端发起条件请求。 |
| [setId(String value)](#setId-java.lang.String-) | 资源的标识符。 |
| [setLocation(String value)](#setLocation-java.lang.String-) | 日历的地理位置（自由文本）。 |
| [setSummary(String value)](#setSummary-java.lang.String-) | 日历的标题。 |
| [setTimeZone(String value)](#setTimeZone-java.lang.String-) | 日历的时区。 |
| [toString()](#toString--) | 返回表示对象实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Calendar() {#Calendar--}
```
public Calendar()
```


初始化 Calendar 类的新实例。

### Calendar(String summary) {#Calendar-java.lang.String-}
```
public Calendar(String summary)
```


初始化 Calendar 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 摘要 | java.lang.String | 日历的标题。 |

### Calendar(String id, String summary) {#Calendar-java.lang.String-java.lang.String-}
```
public Calendar(String id, String summary)
```


初始化 Calendar 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 资源的标识符。 |
| 摘要 | java.lang.String | 日历的标题。 |

### Calendar(String summary, String description, String location, String timeZone) {#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public Calendar(String summary, String description, String location, String timeZone)
```


初始化 Calendar 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 摘要 | java.lang.String | 日历的标题。 |
| description | java.lang.String | 日历的描述。 |
| 位置 | java.lang.String | 日历的地理位置（自由文本）。 |
| 时区 | java.lang.String | 日历的时区。 |

### Calendar(String id, String summary, String description, String location, String timeZone) {#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public Calendar(String id, String summary, String description, String location, String timeZone)
```


初始化 Calendar 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 资源的标识符。 |
| 摘要 | java.lang.String | 日历的标题。 |
| description | java.lang.String | 日历的描述。 |
| 位置 | java.lang.String | 日历的地理位置（自由文本）。 |
| 时区 | java.lang.String | 日历的时区。 |

### Calendar(String id, String eTag, String summary, String description, String location, String timeZone) {#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public Calendar(String id, String eTag, String summary, String description, String location, String timeZone)
```


初始化 Calendar 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 资源的标识符。 |
| eTag | java.lang.String | 实体标签 |
| 摘要 | java.lang.String | 日历的标题。 |
| description | java.lang.String | 日历的描述。 |
| 位置 | java.lang.String | 日历的地理位置（自由文本）。 |
| 时区 | java.lang.String | 日历的时区。 |

### CALENDAR_KIND {#CALENDAR-KIND}
```
public static final String CALENDAR_KIND
```


资源 'calendar\#calendar' 的类型。

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
### getConferenceProperties() {#getConferenceProperties--}
```
public ConferenceProperties getConferenceProperties()
```


获取此日历的会议属性。

**Returns:**
[ConferenceProperties](../../com.aspose.email/conferenceproperties)
### getDescription() {#getDescription--}
```
public String getDescription()
```


日历的描述。

**Returns:**
java.lang.String
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
### getLocation() {#getLocation--}
```
public String getLocation()
```


日历的地理位置（自由文本）。

**Returns:**
java.lang.String
### getSummary() {#getSummary--}
```
public String getSummary()
```


日历的标题。

**Returns:**
java.lang.String
### getTimeZone() {#getTimeZone--}
```
public String getTimeZone()
```


日历的时区。

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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


日历的描述。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setLocation(String value) {#setLocation-java.lang.String-}
```
public void setLocation(String value)
```


日历的地理位置（自由文本）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSummary(String value) {#setSummary-java.lang.String-}
```
public void setSummary(String value)
```


日历的标题。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setTimeZone(String value) {#setTimeZone-java.lang.String-}
```
public void setTimeZone(String value)
```


日历的时区。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


返回表示对象实例的字符串。

**Returns:**
java.lang.String - 返回表示对象实例的字符串。
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

