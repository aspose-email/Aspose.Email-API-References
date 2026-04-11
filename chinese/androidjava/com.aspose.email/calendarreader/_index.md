---
title: CalendarReader
second_title: Aspose.Email for Android via Java API 参考
description: 允许从文件或流读取包含多个事件的日历到 Appointment 对象。
type: docs
weight: 68
url: /zh/androidjava/com.aspose.email/calendarreader/
---

**Inheritance:**
java.lang.Object
```
public class CalendarReader
```

允许从文件或流读取包含多个事件的日历到 Appointment 对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CalendarReader(String path)](#CalendarReader-java.lang.String-) | 使用源文件和默认的 Appointment LoadOptions 初始化 CalendarReader 的新实例。 |
| [CalendarReader(String path, AppointmentLoadOptions options)](#CalendarReader-java.lang.String-com.aspose.email.AppointmentLoadOptions-) | 使用源文件和 Appointment LoadOptions 初始化 CalendarReader 的新实例。 |
| [CalendarReader(InputStream stream)](#CalendarReader-java.io.InputStream-) | 使用源流和默认的 Appointment LoadOptions 初始化 CalendarReader 的新实例。 |
| [CalendarReader(InputStream stream, AppointmentLoadOptions options)](#CalendarReader-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-) | 使用源流和 Appointment LoadOptions 初始化 CalendarReader 的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCurrent()](#getCurrent--) | 当前读取的事件。 |
| [hashCode()](#hashCode--) |  |
| [nextEvent()](#nextEvent--) | 从源读取下一个 Event 并将其保存到 Current。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CalendarReader(String path) {#CalendarReader-java.lang.String-}
```
public CalendarReader(String path)
```


使用源文件和默认的 Appointment LoadOptions 初始化 CalendarReader 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 源文件的路径。 |

### CalendarReader(String path, AppointmentLoadOptions options) {#CalendarReader-java.lang.String-com.aspose.email.AppointmentLoadOptions-}
```
public CalendarReader(String path, AppointmentLoadOptions options)
```


使用源文件和 Appointment LoadOptions 初始化 CalendarReader 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 源文件的路径。 |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | 附加的 LoadOptions。 |

### CalendarReader(InputStream stream) {#CalendarReader-java.io.InputStream-}
```
public CalendarReader(InputStream stream)
```


使用源流和默认的 Appointment LoadOptions 初始化 CalendarReader 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 源流。 |

### CalendarReader(InputStream stream, AppointmentLoadOptions options) {#CalendarReader-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-}
```
public CalendarReader(InputStream stream, AppointmentLoadOptions options)
```


使用源流和 Appointment LoadOptions 初始化 CalendarReader 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 源流。 |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | 附加的 LoadOptions。 |

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
### getCurrent() {#getCurrent--}
```
public final Appointment getCurrent()
```


当前读取的事件。

**Returns:**
[Appointment](../../com.aspose.email/appointment)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### nextEvent() {#nextEvent--}
```
public final boolean nextEvent()
```


从源读取下一个 Event 并将其保存到 Current。

**Returns:**
boolean - 成功则为 True，否则为 false。
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

