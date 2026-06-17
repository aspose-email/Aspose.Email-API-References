---
title: LogEntry
second_title: Aspose.Email for Android via Java API 参考
description: 表示日志消息。
type: docs
weight: 182
url: /zh/androidjava/com.aspose.email/logentry/
---

**Inheritance:**
java.lang.Object
```
public class LogEntry
```

表示一条日志消息。包含所有日志消息所需的通用属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LogEntry()](#LogEntry--) | 初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。 |
| [LogEntry(String message)](#LogEntry-java.lang.String-) | 初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。 |
| [LogEntry(String message, Date time)](#LogEntry-java.lang.String-java.util.Date-) | 初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。 |
| [LogEntry(String message, Throwable innerException)](#LogEntry-java.lang.String-java.lang.Throwable-) | 初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。 |
| [LogEntry(String message, LogLevel severity)](#LogEntry-java.lang.String-com.aspose.email.LogLevel-) | 初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。 |
| [LogEntry(String message, Throwable innerException, LogLevel severity)](#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-) | 初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。 |
| [LogEntry(String message, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | 使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例 |
| [LogEntry(byte[] binaryDataMessage)](#LogEntry-byte---) | 使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例 |
| [LogEntry(byte[] binaryDataMessage, Charset messageEncoding)](#LogEntry-byte---java.nio.charset.Charset-) | 使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例 |
| [LogEntry(byte[] binaryDataMessage, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-byte---com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | 使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例 |
| [LogEntry(byte[] binaryDataMessage, Charset messageEncoding, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-byte---java.nio.charset.Charset-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | 使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例 |
| [LogEntry(String message, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-java.lang.String-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | 使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例 |
| [LogEntry(String message, Throwable innerException, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | 使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addErrorMessage(String message)](#addErrorMessage-java.lang.String-) | 在 messages 字符串生成器的开头添加错误或警告消息。 |
| [deepClone()](#deepClone--) | 创建一个新的 [LogEntry](../../com.aspose.email/logentry)，它是当前实例的副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppDomainName()](#getAppDomainName--) | 我们运行所在的 AppDomain |
| [getBinaryDataMessage()](#getBinaryDataMessage--) | 要记录的二进制消息体。 |
| [getCategory()](#getCategory--) | 用于将日志条目路由到一个或多个接收器的类别名称。 |
| [getClass()](#getClass--) |  |
| [getContextualProperties()](#getContextualProperties--) | 要记录的键/值对字典。 |
| [getErrorMessages()](#getErrorMessages--) | 获取带有 [LogEntry](../../com.aspose.email/logentry) 的错误消息 |
| [getEventId()](#getEventId--) | 事件编号或标识符。 |
| [getInnerException()](#getInnerException--) | 获取或设置内部异常对象。 |
| [getMachineName()](#getMachineName--) | 计算机名称。 |
| [getMessage()](#getMessage--) | 要记录的消息正文。 |
| [getMessageEncoding()](#getMessageEncoding--) | 二进制消息正文的编码 |
| [getSequenceId()](#getSequenceId--) | 日志事件的唯一标识符，自动生成且单调递增。 |
| [getSeverity()](#getSeverity--) | 日志条目严重性，作为 Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) 枚举。 |
| [getThreadName()](#getThreadName--) | 线程的名称。 |
| [getTimeStamp()](#getTimeStamp--) | 日志条目消息的日期和时间。 |
| [getTitle()](#getTitle--) | 日志条目消息的附加描述。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAppDomainName(String value)](#setAppDomainName-java.lang.String-) | 我们运行所在的 AppDomain |
| [setBinaryDataMessage(byte[] value)](#setBinaryDataMessage-byte---) | 要记录的二进制消息体。 |
| [setCategory(String value)](#setCategory-java.lang.String-) | 用于将日志条目路由到一个或多个接收器的类别名称。 |
| [setContextualProperties(System.Collections.Generic.IGenericDictionary<String,String> value)](#setContextualProperties-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | 要记录的键/值对字典。 |
| [setEventId(int value)](#setEventId-int-) | 事件编号或标识符。 |
| [setInnerException(Throwable value)](#setInnerException-java.lang.Throwable-) | 获取或设置内部异常对象。 |
| [setMachineName(String value)](#setMachineName-java.lang.String-) | 计算机名称。 |
| [setMessage(String value)](#setMessage-java.lang.String-) | 要记录的消息正文。 |
| [setMessageEncoding(Charset value)](#setMessageEncoding-java.nio.charset.Charset-) | 二进制消息正文的编码 |
| [setSeverity(LogLevel value)](#setSeverity-com.aspose.email.LogLevel-) | 日志条目严重性，作为 Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) 枚举。 |
| [setThreadName(String value)](#setThreadName-java.lang.String-) | 线程的名称。 |
| [setTimeStamp(Date value)](#setTimeStamp-java.util.Date-) | 日志条目消息的日期和时间。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 日志条目消息的附加描述。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LogEntry() {#LogEntry--}
```
public LogEntry()
```


初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。

### LogEntry(String message) {#LogEntry-java.lang.String-}
```
public LogEntry(String message)
```


初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 消息。 |

### LogEntry(String message, Date time) {#LogEntry-java.lang.String-java.util.Date-}
```
public LogEntry(String message, Date time)
```


初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 消息。 |
| 时间 | java.util.Date | 时间。 |

### LogEntry(String message, Throwable innerException) {#LogEntry-java.lang.String-java.lang.Throwable-}
```
public LogEntry(String message, Throwable innerException)
```


初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| innerException | java.lang.Throwable | 要记录的内部异常。 |

### LogEntry(String message, LogLevel severity) {#LogEntry-java.lang.String-com.aspose.email.LogLevel-}
```
public LogEntry(String message, LogLevel severity)
```


初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| severity | [LogLevel](../../com.aspose.email/loglevel) | 日志条目严重性，作为 Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) 枚举。（未指定、信息、警告或错误） |

### LogEntry(String message, Throwable innerException, LogLevel severity) {#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-}
```
public LogEntry(String message, Throwable innerException, LogLevel severity)
```


初始化 [LogEntry](../../com.aspose.email/logentry) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| innerException | java.lang.Throwable | 要记录的内部异常。 |
| severity | [LogLevel](../../com.aspose.email/loglevel) | 日志条目严重性，作为 Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) 枚举。（未指定、信息、警告或错误） |

### LogEntry(String message, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(String message, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| 属性 | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | 要记录的键/值对字典。 |

### LogEntry(byte[] binaryDataMessage) {#LogEntry-byte---}
```
public LogEntry(byte[] binaryDataMessage)
```


使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| binaryDataMessage | byte[] | 要记录的二进制消息体。 |

### LogEntry(byte[] binaryDataMessage, Charset messageEncoding) {#LogEntry-byte---java.nio.charset.Charset-}
```
public LogEntry(byte[] binaryDataMessage, Charset messageEncoding)
```


使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| binaryDataMessage | byte[] | 要记录的二进制消息体。 |
| messageEncoding | java.nio.charset.Charset | 二进制消息的编码 |

### LogEntry(byte[] binaryDataMessage, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-byte---com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(byte[] binaryDataMessage, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| binaryDataMessage | byte[] | 要记录的二进制消息体。 |
| 属性 | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | 要记录的键/值对字典。 |

### LogEntry(byte[] binaryDataMessage, Charset messageEncoding, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-byte---java.nio.charset.Charset-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(byte[] binaryDataMessage, Charset messageEncoding, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| binaryDataMessage | byte[] | 要记录的二进制消息体。 |
| messageEncoding | java.nio.charset.Charset | 二进制消息的编码 |
| 属性 | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | 要记录的键/值对字典。 |

### LogEntry(String message, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-java.lang.String-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(String message, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| severity | [LogLevel](../../com.aspose.email/loglevel) | 日志条目严重性，作为 Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) 枚举。（未指定、信息、警告或错误） |
| 类别 | java.lang.String | 用于将日志条目路由到一个或多个接收器的类别名称。 |
| eventId | int | 事件编号或标识符。 |
| 标题 | java.lang.String | 日志条目消息的附加描述。 |
| 属性 | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | 要记录的键/值对字典。 |

### LogEntry(String message, Throwable innerException, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(String message, Throwable innerException, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


使用完整的构造函数参数集创建 [LogEntry](../../com.aspose.email/logentry) 的新实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| innerException | java.lang.Throwable | 要记录的内部异常。 |
| severity | [LogLevel](../../com.aspose.email/loglevel) | 日志条目严重性，作为 Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) 枚举。（未指定、信息、警告或错误） |
| 类别 | java.lang.String | 用于将日志条目路由到一个或多个接收器的类别名称。 |
| eventId | int | 事件编号或标识符。 |
| 标题 | java.lang.String | 日志条目消息的附加描述。 |
| 属性 | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | 要记录的键/值对字典。 |

### addErrorMessage(String message) {#addErrorMessage-java.lang.String-}
```
public void addErrorMessage(String message)
```


在 messages 字符串生成器的开头添加错误或警告消息。由分发器用于记录问题。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 要添加到此实例的消息 |

### deepClone() {#deepClone--}
```
public final LogEntry deepClone()
```


创建一个新的 [LogEntry](../../com.aspose.email/logentry)，它是当前实例的副本。

**Returns:**
[LogEntry](../../com.aspose.email/logentry) - A new  LogEntry  that is a copy of the current instance.
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
### getAppDomainName() {#getAppDomainName--}
```
public final String getAppDomainName()
```


我们运行所在的 AppDomain

**Returns:**
java.lang.String
### getBinaryDataMessage() {#getBinaryDataMessage--}
```
public final byte[] getBinaryDataMessage()
```


要记录的二进制消息体。

**Returns:**
byte[]
### getCategory() {#getCategory--}
```
public final String getCategory()
```


用于将日志条目路由到一个或多个接收器的类别名称。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContextualProperties() {#getContextualProperties--}
```
public final System.Collections.Generic.IGenericDictionary<String,String> getContextualProperties()
```


要记录的键/值对字典。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String>
### getErrorMessages() {#getErrorMessages--}
```
public final String getErrorMessages()
```


获取带有 [LogEntry](../../com.aspose.email/logentry) 的错误消息

**Returns:**
java.lang.String
### getEventId() {#getEventId--}
```
public final int getEventId()
```


事件编号或标识符。

**Returns:**
int
### getInnerException() {#getInnerException--}
```
public final Throwable getInnerException()
```


获取或设置内部异常对象。

**Returns:**
java.lang.Throwable
### getMachineName() {#getMachineName--}
```
public final String getMachineName()
```


计算机名称。

**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public final String getMessage()
```


要记录的消息正文。来自消息对象的 ToString() 方法的值。

**Returns:**
java.lang.String
### getMessageEncoding() {#getMessageEncoding--}
```
public final Charset getMessageEncoding()
```


二进制消息正文的编码

**Returns:**
java.nio.charset.Charset
### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


日志事件的唯一标识符，自动生成且单调递增。

**Returns:**
int
### getSeverity() {#getSeverity--}
```
public final LogLevel getSeverity()
```


日志条目严重性，作为 Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) 枚举。（未指定、信息、警告或错误）

**Returns:**
[LogLevel](../../com.aspose.email/loglevel)
### getThreadName() {#getThreadName--}
```
public final String getThreadName()
```


线程的名称。

**Returns:**
java.lang.String
### getTimeStamp() {#getTimeStamp--}
```
public final Date getTimeStamp()
```


日志条目消息的日期和时间。

**Returns:**
java.util.Date
### getTitle() {#getTitle--}
```
public final String getTitle()
```


日志条目消息的附加描述。

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




### setAppDomainName(String value) {#setAppDomainName-java.lang.String-}
```
public final void setAppDomainName(String value)
```


我们运行所在的 AppDomain

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBinaryDataMessage(byte[] value) {#setBinaryDataMessage-byte---}
```
public final void setBinaryDataMessage(byte[] value)
```


要记录的二进制消息体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


用于将日志条目路由到一个或多个接收器的类别名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setContextualProperties(System.Collections.Generic.IGenericDictionary<String,String> value) {#setContextualProperties-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public final void setContextualProperties(System.Collections.Generic.IGenericDictionary<String,String> value)
```


要记录的键/值对字典。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> |  |

### setEventId(int value) {#setEventId-int-}
```
public final void setEventId(int value)
```


事件编号或标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setInnerException(Throwable value) {#setInnerException-java.lang.Throwable-}
```
public final void setInnerException(Throwable value)
```


获取或设置内部异常对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Throwable |  |

### setMachineName(String value) {#setMachineName-java.lang.String-}
```
public final void setMachineName(String value)
```


计算机名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


要记录的消息正文。来自消息对象的 ToString() 方法的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessageEncoding(Charset value) {#setMessageEncoding-java.nio.charset.Charset-}
```
public final void setMessageEncoding(Charset value)
```


二进制消息正文的编码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setSeverity(LogLevel value) {#setSeverity-com.aspose.email.LogLevel-}
```
public final void setSeverity(LogLevel value)
```


日志条目严重性，作为 Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) 枚举。（未指定、信息、警告或错误）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [LogLevel](../../com.aspose.email/loglevel) |  |

### setThreadName(String value) {#setThreadName-java.lang.String-}
```
public final void setThreadName(String value)
```


线程的名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setTimeStamp(Date value) {#setTimeStamp-java.util.Date-}
```
public final void setTimeStamp(Date value)
```


日志条目消息的日期和时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


日志条目消息的附加描述。

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

