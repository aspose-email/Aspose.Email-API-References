---
title: FileAppender
second_title: Aspose.Email for Java API Reference
description: Reprensents a file appender.
type: docs
weight: 243
url: /java/com.aspose.email/fileappender/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.Appender](../../com.aspose.email/appender)
```
public final class FileAppender extends Appender
```

Reprensents a file appender.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileAppender()](#FileAppender--) | Initializes a new instance of the FileAppender class. |
| [FileAppender(String fileName)](#FileAppender-java.lang.String-) | Initializes a new instance of the FileAppender class. |
| [FileAppender(String fileName, boolean useDate)](#FileAppender-java.lang.String-boolean-) | Initializes a new instance of the FileAppender class. |
| [FileAppender(String fileName, IFormatter formatter)](#FileAppender-java.lang.String-com.aspose.email.IFormatter-) | Initializes a new instance of the FileAppender class. |
| [FileAppender(String fileName, boolean useDate, IFormatter formatter)](#FileAppender-java.lang.String-boolean-com.aspose.email.IFormatter-) | Initializes a new instance of the FileAppender class. |
## Methods

| Method | Description |
| --- | --- |
| [append(LogEntry logEntry)](#append-com.aspose.email.LogEntry-) | Appends the log entry information to the appender. |
| [append(LogEntry[] logEntries)](#append-com.aspose.email.LogEntry---) | Appends a set of log entries to the appender. |
| [appendHeader()](#appendHeader--) | Starts log file with specific header. |
| [close()](#close--) | Closes the appender. |
| [dispose()](#dispose--) | Releases the unmanaged resources used by the Appender. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Gets or sets the encoding. |
| [getFileName()](#getFileName--) | Gets or sets file name. |
| [getFormatter()](#getFormatter--) | Gets or sets the formatter. |
| [getUseDate()](#getUseDate--) | Gets or sets value which indicates whether date is used for logging. |
| [hashCode()](#hashCode--) |  |
| [initialize()](#initialize--) | Initializes the appender instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncoding(String value)](#setEncoding-java.lang.String-) | Gets or sets the encoding. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Gets or sets file name. |
| [setFormatter(IFormatter value)](#setFormatter-com.aspose.email.IFormatter-) | Gets or sets the formatter. |
| [setUseDate(boolean value)](#setUseDate-boolean-) | Gets or sets value which indicates whether date is used for logging. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileAppender() {#FileAppender--}
```
public FileAppender()
```


Initializes a new instance of the FileAppender class.

### FileAppender(String fileName) {#FileAppender-java.lang.String-}
```
public FileAppender(String fileName)
```


Initializes a new instance of the FileAppender class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |

### FileAppender(String fileName, boolean useDate) {#FileAppender-java.lang.String-boolean-}
```
public FileAppender(String fileName, boolean useDate)
```


Initializes a new instance of the FileAppender class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| useDate | boolean | Indicates if date is used in file name |

### FileAppender(String fileName, IFormatter formatter) {#FileAppender-java.lang.String-com.aspose.email.IFormatter-}
```
public FileAppender(String fileName, IFormatter formatter)
```


Initializes a new instance of the FileAppender class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| formatter | [IFormatter](../../com.aspose.email/iformatter) | Log formatter |

### FileAppender(String fileName, boolean useDate, IFormatter formatter) {#FileAppender-java.lang.String-boolean-com.aspose.email.IFormatter-}
```
public FileAppender(String fileName, boolean useDate, IFormatter formatter)
```


Initializes a new instance of the FileAppender class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| useDate | boolean | Indicates if date is used in file name |
| formatter | [IFormatter](../../com.aspose.email/iformatter) | Log formatter |

### append(LogEntry logEntry) {#append-com.aspose.email.LogEntry-}
```
public void append(LogEntry logEntry)
```


Appends the log entry information to the appender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logEntry | [LogEntry](../../com.aspose.email/logentry) | The log entry. |

### append(LogEntry[] logEntries) {#append-com.aspose.email.LogEntry---}
```
public final void append(LogEntry[] logEntries)
```


Appends a set of log entries to the appender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logEntries | [LogEntry\[\]](../../com.aspose.email/logentry) | A set of log entries to log. |

### appendHeader() {#appendHeader--}
```
public void appendHeader()
```


Starts log file with specific header.

### close() {#close--}
```
public void close()
```


Closes the appender.

### dispose() {#dispose--}
```
public final void dispose()
```


Releases the unmanaged resources used by the Appender.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets or sets the encoding.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gets or sets file name.

**Returns:**
java.lang.String
### getFormatter() {#getFormatter--}
```
public final IFormatter getFormatter()
```


Gets or sets the formatter.

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### getUseDate() {#getUseDate--}
```
public final boolean getUseDate()
```


Gets or sets value which indicates whether date is used for logging.

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


Initializes the appender instance.

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


Gets or sets the encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Gets or sets file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFormatter(IFormatter value) {#setFormatter-com.aspose.email.IFormatter-}
```
public final void setFormatter(IFormatter value)
```


Gets or sets the formatter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

### setUseDate(boolean value) {#setUseDate-boolean-}
```
public final void setUseDate(boolean value)
```


Gets or sets value which indicates whether date is used for logging.

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

