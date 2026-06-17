---
title: FileAppender
second_title: Aspose.Email for Android via Java API 参考
description: 表示一个文件追加器。
type: docs
weight: 132
url: /zh/androidjava/com.aspose.email/fileappender/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.Appender](../../com.aspose.email/appender)
```
public final class FileAppender extends Appender
```

表示一个文件追加器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileAppender()](#FileAppender--) | 初始化一个新的 FileAppender 类实例。 |
| [FileAppender(String fileName)](#FileAppender-java.lang.String-) | 初始化一个新的 FileAppender 类实例。 |
| [FileAppender(String fileName, boolean useDate)](#FileAppender-java.lang.String-boolean-) | 初始化一个新的 FileAppender 类实例。 |
| [FileAppender(String fileName, IFormatter formatter)](#FileAppender-java.lang.String-com.aspose.email.IFormatter-) | 初始化一个新的 FileAppender 类实例。 |
| [FileAppender(String fileName, boolean useDate, IFormatter formatter)](#FileAppender-java.lang.String-boolean-com.aspose.email.IFormatter-) | 初始化一个新的 FileAppender 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [append(LogEntry logEntry)](#append-com.aspose.email.LogEntry-) | 将日志条目信息追加到附加器。 |
| [append(LogEntry[] logEntries)](#append-com.aspose.email.LogEntry---) | 将一组日志条目追加到附加器。 |
| [appendHeader()](#appendHeader--) | 使用特定标题启动日志文件。 |
| [close()](#close--) | 关闭 appender。 |
| [dispose()](#dispose--) | 释放 Appender 使用的非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | 获取或设置编码。 |
| [getFileName()](#getFileName--) | 获取或设置文件名。 |
| [getFormatter()](#getFormatter--) | 获取或设置格式化程序。 |
| [getUseDate()](#getUseDate--) | 获取或设置指示是否在日志中使用日期的值。 |
| [hashCode()](#hashCode--) |  |
| [initialize()](#initialize--) | 初始化 appender 实例。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncoding(String value)](#setEncoding-java.lang.String-) | 获取或设置编码。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 获取或设置文件名。 |
| [setFormatter(IFormatter value)](#setFormatter-com.aspose.email.IFormatter-) | 获取或设置格式化程序。 |
| [setUseDate(boolean value)](#setUseDate-boolean-) | 获取或设置指示是否在日志中使用日期的值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileAppender() {#FileAppender--}
```
public FileAppender()
```


初始化一个新的 FileAppender 类实例。

### FileAppender(String fileName) {#FileAppender-java.lang.String-}
```
public FileAppender(String fileName)
```


初始化一个新的 FileAppender 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |

### FileAppender(String fileName, boolean useDate) {#FileAppender-java.lang.String-boolean-}
```
public FileAppender(String fileName, boolean useDate)
```


初始化一个新的 FileAppender 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| useDate | boolean | 指示文件名中是否使用日期 |

### FileAppender(String fileName, IFormatter formatter) {#FileAppender-java.lang.String-com.aspose.email.IFormatter-}
```
public FileAppender(String fileName, IFormatter formatter)
```


初始化一个新的 FileAppender 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| formatter | [IFormatter](../../com.aspose.email/iformatter) | 日志格式化器 |

### FileAppender(String fileName, boolean useDate, IFormatter formatter) {#FileAppender-java.lang.String-boolean-com.aspose.email.IFormatter-}
```
public FileAppender(String fileName, boolean useDate, IFormatter formatter)
```


初始化一个新的 FileAppender 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| useDate | boolean | 指示文件名中是否使用日期 |
| formatter | [IFormatter](../../com.aspose.email/iformatter) | 日志格式化器 |

### append(LogEntry logEntry) {#append-com.aspose.email.LogEntry-}
```
public void append(LogEntry logEntry)
```


将日志条目信息追加到附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| logEntry | [LogEntry](../../com.aspose.email/logentry) | 日志条目。 |

### append(LogEntry[] logEntries) {#append-com.aspose.email.LogEntry---}
```
public final void append(LogEntry[] logEntries)
```


将一组日志条目追加到附加器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| logEntries | [LogEntry\[\]](../../com.aspose.email/logentry) | 要记录的一组日志条目。 |

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
### getEncoding() {#getEncoding--}
```
public final String getEncoding()
```


获取或设置编码。

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


获取或设置文件名。

**Returns:**
java.lang.String
### getFormatter() {#getFormatter--}
```
public final IFormatter getFormatter()
```


获取或设置格式化程序。

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### getUseDate() {#getUseDate--}
```
public final boolean getUseDate()
```


获取或设置指示是否在日志中使用日期的值。

**Returns:**
boolean
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




### setEncoding(String value) {#setEncoding-java.lang.String-}
```
public final void setEncoding(String value)
```


获取或设置编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


获取或设置文件名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFormatter(IFormatter value) {#setFormatter-com.aspose.email.IFormatter-}
```
public final void setFormatter(IFormatter value)
```


获取或设置格式化程序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

### setUseDate(boolean value) {#setUseDate-boolean-}
```
public final void setUseDate(boolean value)
```


获取或设置指示是否在日志中使用日期的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

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

