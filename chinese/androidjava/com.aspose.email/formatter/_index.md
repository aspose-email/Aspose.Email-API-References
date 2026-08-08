---
title: 格式化程序
second_title: Aspose.Email for Android via Java API 参考
description: 表示用于格式化日志条目消息的接口。
type: docs
weight: 150
url: /zh/androidjava/com.aspose.email/formatter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IFormatter](../../com.aspose.email/iformatter)
```
public abstract class Formatter implements IFormatter
```

表示用于格式化日志条目消息的接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(LogEntry entry)](#format-com.aspose.email.LogEntry-) | 格式化日志条目并返回要输出的字符串。 |
| [format(Date datatime)](#format-java.util.Date-) | 格式化日期时间并返回要输出的字符串。 |
| [getClass()](#getClass--) |  |
| [getDefaultFormatter()](#getDefaultFormatter--) | 获取或设置默认格式化程序 |
| [getFooter()](#getFooter--) | 获取或设置页脚。 |
| [getHeader()](#getHeader--) | 获取或设置页眉。 |
| [getLogHeader()](#getLogHeader--) | 获取或设置日志页眉 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFormatter(IFormatter value)](#setDefaultFormatter-com.aspose.email.IFormatter-) | 获取或设置默认格式化程序 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### format(LogEntry entry) {#format-com.aspose.email.LogEntry-}
```
public String format(LogEntry entry)
```


格式化日志条目并返回要输出的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | 要格式化的日志条目。 |

**Returns:**
java.lang.String - 表示日志条目的字符串。
### format(Date datatime) {#format-java.util.Date-}
```
public String format(Date datatime)
```


格式化日期时间并返回要输出的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 日期时间 | java.util.Date | 用于格式化为字符串的日期时间值 |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFormatter() {#getDefaultFormatter--}
```
public static IFormatter getDefaultFormatter()
```


获取或设置默认格式化程序

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### getFooter() {#getFooter--}
```
public String getFooter()
```


获取或设置页脚。

**Returns:**
java.lang.String
### getHeader() {#getHeader--}
```
public String getHeader()
```


获取或设置页眉。

**Returns:**
java.lang.String
### getLogHeader() {#getLogHeader--}
```
public String getLogHeader()
```


获取或设置日志页眉

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




### setDefaultFormatter(IFormatter value) {#setDefaultFormatter-com.aspose.email.IFormatter-}
```
public static void setDefaultFormatter(IFormatter value)
```


获取或设置默认格式化程序

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

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

