---
title: FileAppender
second_title: Aspose.Email for Android via Java API Reference
description:  Reprensents a file appender.
type: docs
weight: 132
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
| [getFileName()](#getFileName--) | Gets or sets file name. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Gets or sets file name. |
| [getUseDate()](#getUseDate--) | Gets or sets value which indicates whether date is used for logging. |
| [setUseDate(boolean value)](#setUseDate-boolean-) | Gets or sets value which indicates whether date is used for logging. |
| [getEncoding()](#getEncoding--) | Gets or sets the encoding. |
| [setEncoding(String value)](#setEncoding-java.lang.String-) | Gets or sets the encoding. |
| [append(LogEntry logEntry)](#append-com.aspose.email.LogEntry-) | Appends the log entry information to the appender. |
| [appendHeader()](#appendHeader--) | Starts log file with specific header. |
| [append(LogEntry[] logEntries)](#append-com.aspose.email.LogEntry---) | Appends a set of log entries to the appender. |
| [close()](#close--) | Closes the appender. |
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

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gets or sets file name.

**Returns:**
java.lang.String
### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Gets or sets file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getUseDate() {#getUseDate--}
```
public final boolean getUseDate()
```


Gets or sets value which indicates whether date is used for logging.

**Returns:**
boolean
### setUseDate(boolean value) {#setUseDate-boolean-}
```
public final void setUseDate(boolean value)
```


Gets or sets value which indicates whether date is used for logging.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEncoding() {#getEncoding--}
```
public final String getEncoding()
```


Gets or sets the encoding.

**Returns:**
java.lang.String
### setEncoding(String value) {#setEncoding-java.lang.String-}
```
public final void setEncoding(String value)
```


Gets or sets the encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### append(LogEntry logEntry) {#append-com.aspose.email.LogEntry-}
```
public void append(LogEntry logEntry)
```


Appends the log entry information to the appender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logEntry | [LogEntry](../../com.aspose.email/logentry) | The log entry. |

### appendHeader() {#appendHeader--}
```
public void appendHeader()
```


Starts log file with specific header.

### append(LogEntry[] logEntries) {#append-com.aspose.email.LogEntry---}
```
public final void append(LogEntry[] logEntries)
```


Appends a set of log entries to the appender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logEntries | com.aspose.email.LogEntry[] | A set of log entries to log. |

### close() {#close--}
```
public void close()
```


Closes the appender.

