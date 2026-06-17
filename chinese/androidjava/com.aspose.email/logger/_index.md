---
title: Logger
second_title: Aspose.Email for Android via Java API 参考
description: 提供日志功能。
type: docs
weight: 184
url: /zh/androidjava/com.aspose.email/logger/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Logger implements System.IDisposable
```

提供日志功能。
## 方法

| 方法 | 描述 |
| --- | --- |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppenders()](#getAppenders--) | 获取或设置附加器列表。 |
| [getClass()](#getClass--) |  |
| [getDebug()](#getDebug--) | 获取调试日志记录器。 |
| [getName()](#getName--) | 获取或设置名称。 |
| [getSeverity()](#getSeverity--) | 获取或设置严重性。 |
| [hashCode()](#hashCode--) |  |
| [isEnabled(LogLevel level)](#isEnabled-com.aspose.email.LogLevel-) | 确定是否为指定级别启用了日志记录。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAppenders(AppenderCollection value)](#setAppenders-com.aspose.email.AppenderCollection-) | 获取或设置附加器列表。 |
| [setSeverity(LogLevel value)](#setSeverity-com.aspose.email.LogLevel-) | 获取或设置严重性。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(Object message)](#write-java.lang.Object-) | 将指定的消息写入附加器。 |
| [write(String message)](#write-java.lang.String-) | 将指定的消息写入附加器。 |
| [write(String message, Exception exception)](#write-java.lang.String-java.lang.Exception-) | 将指定的消息和异常写入附加器。 |
| [write(String message, Exception ex, LogLevel level)](#write-java.lang.String-java.lang.Exception-com.aspose.email.LogLevel-) | 将指定的消息和异常写入附加器。 |
| [writeFormat(String format, Object[] arguments)](#writeFormat-java.lang.String-java.lang.Object...-) | 将带有指定格式的消息写入附加器。 |
| [writeIf(boolean condition, Object message)](#writeIf-boolean-java.lang.Object-) | 如果条件为真，则将指定的消息写入附加器。 |
| [writeIf(boolean condition, Object message, Exception exception)](#writeIf-boolean-java.lang.Object-java.lang.Exception-) | 如果条件为真，则将指定的消息和异常写入附加器。 |
| [writeIf(boolean condition, String message)](#writeIf-boolean-java.lang.String-) | 如果条件为真，则将指定的消息写入附加器。 |
| [writeIf(LogLevel condition, String message)](#writeIf-com.aspose.email.LogLevel-java.lang.String-) | 如果已启用日志级别，则写入指定的消息。 |
| [writeIf(LogLevel condition, String message, Exception exception)](#writeIf-com.aspose.email.LogLevel-java.lang.String-java.lang.Exception-) | 如果已启用日志级别，则写入指定的消息和异常。 |
| [writeLine()](#writeLine--) | 将空行写入附加器。 |
| [writeLine(Object message)](#writeLine-java.lang.Object-) | 将指定的消息写入附加器。 |
| [writeLine(String message)](#writeLine-java.lang.String-) | 将指定的消息写入附加器。 |
### dispose() {#dispose--}
```
public final void dispose()
```


执行应用程序定义的任务，以释放、释放或重置非托管资源。

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
### getAppenders() {#getAppenders--}
```
public final AppenderCollection getAppenders()
```


获取或设置附加器列表。

**Returns:**
[AppenderCollection](../../com.aspose.email/appendercollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDebug() {#getDebug--}
```
public static Logger getDebug()
```


获取调试日志记录器。

**Returns:**
[Logger](../../com.aspose.email/logger)
### getName() {#getName--}
```
public final String getName()
```


获取或设置名称。

**Returns:**
java.lang.String
### getSeverity() {#getSeverity--}
```
public final LogLevel getSeverity()
```


获取或设置严重性。

**Returns:**
[LogLevel](../../com.aspose.email/loglevel)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled(LogLevel level) {#isEnabled-com.aspose.email.LogLevel-}
```
public final boolean isEnabled(LogLevel level)
```


确定是否为指定级别启用了日志记录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | [LogLevel](../../com.aspose.email/loglevel) | 要检查的级别 |

**Returns:**
布尔值 -   如果为指定级别启用了日志记录，否则返回  。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAppenders(AppenderCollection value) {#setAppenders-com.aspose.email.AppenderCollection-}
```
public final void setAppenders(AppenderCollection value)
```


获取或设置附加器列表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AppenderCollection](../../com.aspose.email/appendercollection) |  |

### setSeverity(LogLevel value) {#setSeverity-com.aspose.email.LogLevel-}
```
public final void setSeverity(LogLevel value)
```


获取或设置严重性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [LogLevel](../../com.aspose.email/loglevel) |  |

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

### write(Object message) {#write-java.lang.Object-}
```
public final void write(Object message)
```


将指定的消息写入附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.Object | 要写入的消息。 |

### write(String message) {#write-java.lang.String-}
```
public final void write(String message)
```


将指定的消息写入附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要写入的消息。 |

### write(String message, Exception exception) {#write-java.lang.String-java.lang.Exception-}
```
public final void write(String message, Exception exception)
```


将指定的消息和异常写入附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要写入的消息。 |
| 异常 | java.lang.Exception | 要写入的异常。 |

### write(String message, Exception ex, LogLevel level) {#write-java.lang.String-java.lang.Exception-com.aspose.email.LogLevel-}
```
public final void write(String message, Exception ex, LogLevel level)
```


将指定的消息和异常写入附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要写入的消息。 |
| ex | java.lang.Exception | 要写入的异常。 |
| level | [LogLevel](../../com.aspose.email/loglevel) | 日志级别。 |

### writeFormat(String format, Object[] arguments) {#writeFormat-java.lang.String-java.lang.Object...-}
```
public final void writeFormat(String format, Object[] arguments)
```


将带有指定格式的消息写入附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 格式 | java.lang.String |  |
| 参数 | java.lang.Object[] |  |

### writeIf(boolean condition, Object message) {#writeIf-boolean-java.lang.Object-}
```
public final void writeIf(boolean condition, Object message)
```


如果条件为真，则将指定的消息写入附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 条件 | boolean | 要测试的条件。 |
| 消息 | java.lang.Object | 要写入的消息。 |

### writeIf(boolean condition, Object message, Exception exception) {#writeIf-boolean-java.lang.Object-java.lang.Exception-}
```
public final void writeIf(boolean condition, Object message, Exception exception)
```


如果条件为真，则将指定的消息和异常写入附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 条件 | boolean | 要测试的条件。 |
| 消息 | java.lang.Object | 要写入的消息。 |
| 异常 | java.lang.Exception | 要写入的异常。 |

### writeIf(boolean condition, String message) {#writeIf-boolean-java.lang.String-}
```
public final void writeIf(boolean condition, String message)
```


如果条件为真，则将指定的消息写入附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 条件 | boolean | 要测试的条件。 |
| 消息 | java.lang.String | 要写入的消息。 |

### writeIf(LogLevel condition, String message) {#writeIf-com.aspose.email.LogLevel-java.lang.String-}
```
public final void writeIf(LogLevel condition, String message)
```


如果已启用日志级别，则写入指定的消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| condition | [LogLevel](../../com.aspose.email/loglevel) | 日志级别。 |
| 消息 | java.lang.String | 要记录的消息。 |

### writeIf(LogLevel condition, String message, Exception exception) {#writeIf-com.aspose.email.LogLevel-java.lang.String-java.lang.Exception-}
```
public final void writeIf(LogLevel condition, String message, Exception exception)
```


如果已启用日志级别，则写入指定的消息和异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| condition | [LogLevel](../../com.aspose.email/loglevel) | 日志级别。 |
| 消息 | java.lang.String | 要记录的消息。 |
| 异常 | java.lang.Exception | 要记录的异常。 |

### writeLine() {#writeLine--}
```
public final void writeLine()
```


将空行写入附加器。

### writeLine(Object message) {#writeLine-java.lang.Object-}
```
public final void writeLine(Object message)
```


将指定的消息写入附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.Object | 要写入的消息。 |

### writeLine(String message) {#writeLine-java.lang.String-}
```
public final void writeLine(String message)
```


将指定的消息写入附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要写入的消息。 |

