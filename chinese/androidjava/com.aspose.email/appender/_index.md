---
title: Appender
second_title: Aspose.Email for Android via Java API 参考
description: 表示 Appender 的基类。
type: docs
weight: 24
url: /zh/androidjava/com.aspose.email/appender/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IAppender](../../com.aspose.email/iappender), com.aspose.ms.System.IDisposable
```
public abstract class Appender implements IAppender, System.IDisposable
```

表示 Appender 的基类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [append(LogEntry entry)](#append-com.aspose.email.LogEntry-) | 将指定的日志条目追加到 appender。 |
| [appendHeader()](#appendHeader--) | 使用特定标题启动日志文件。 |
| [close()](#close--) | 关闭 appender。 |
| [dispose()](#dispose--) | 释放 Appender 使用的非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormatter()](#getFormatter--) | 获取或设置格式化程序。 |
| [hashCode()](#hashCode--) |  |
| [initialize()](#initialize--) | 初始化 appender 实例。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFormatter(IFormatter value)](#setFormatter-com.aspose.email.IFormatter-) | 获取或设置格式化程序。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### append(LogEntry entry) {#append-com.aspose.email.LogEntry-}
```
public abstract void append(LogEntry entry)
```


将指定的日志条目追加到 appender。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | 日志条目。 |

### appendHeader() {#appendHeader--}
```
public void appendHeader()
```


使用特定标题启动日志文件。

### close() {#close--}
```
public void close()
```


关闭 appender。

### dispose() {#dispose--}
```
public final void dispose()
```


释放 Appender 使用的非托管资源。

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
### getFormatter() {#getFormatter--}
```
public final IFormatter getFormatter()
```


获取或设置格式化程序。

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initialize() {#initialize--}
```
public void initialize()
```


初始化 appender 实例。

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFormatter(IFormatter value) {#setFormatter-com.aspose.email.IFormatter-}
```
public final void setFormatter(IFormatter value)
```


获取或设置格式化程序。

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

