---
title: FileAppender
second_title: Aspose.Email for Android via Java API Reference
description: Представляет файловый аппендер.
type: docs
weight: 132
url: /ru/androidjava/com.aspose.email/fileappender/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.Appender](../../com.aspose.email/appender)
```
public final class FileAppender extends Appender
```

Представляет файловый аппендер.
## Constructors

| Constructor | Описание |
| --- | --- |
| [FileAppender()](#FileAppender--) | Инициализирует новый экземпляр класса FileAppender. |
| [FileAppender(String fileName)](#FileAppender-java.lang.String-) | Инициализирует новый экземпляр класса FileAppender. |
| [FileAppender(String fileName, boolean useDate)](#FileAppender-java.lang.String-boolean-) | Инициализирует новый экземпляр класса FileAppender. |
| [FileAppender(String fileName, IFormatter formatter)](#FileAppender-java.lang.String-com.aspose.email.IFormatter-) | Инициализирует новый экземпляр класса FileAppender. |
| [FileAppender(String fileName, boolean useDate, IFormatter formatter)](#FileAppender-java.lang.String-boolean-com.aspose.email.IFormatter-) | Инициализирует новый экземпляр класса FileAppender. |
## Methods

| Method | Описание |
| --- | --- |
| [append(LogEntry logEntry)](#append-com.aspose.email.LogEntry-) | Добавляет информацию о записи журнала в аппендер. |
| [append(LogEntry[] logEntries)](#append-com.aspose.email.LogEntry---) | Добавляет набор записей журнала в аппендер. |
| [appendHeader()](#appendHeader--) | Начинает файл журнала с определённого заголовка. |
| [close()](#close--) | Closes the appender. |
| [dispose()](#dispose--) | Releases the unmanaged resources used by the Appender. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Получает или задает кодировку. |
| [getFileName()](#getFileName--) | Получает или задает имя файла. |
| [getFormatter()](#getFormatter--) | Gets or sets the formatter. |
| [getUseDate()](#getUseDate--) | Получает или задает значение, указывающее, используется ли дата для журналирования. |
| [hashCode()](#hashCode--) |  |
| [initialize()](#initialize--) | Initializes the appender instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncoding(String value)](#setEncoding-java.lang.String-) | Получает или задает кодировку. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Получает или задает имя файла. |
| [setFormatter(IFormatter value)](#setFormatter-com.aspose.email.IFormatter-) | Gets or sets the formatter. |
| [setUseDate(boolean value)](#setUseDate-boolean-) | Получает или задает значение, указывающее, используется ли дата для журналирования. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileAppender() {#FileAppender--}
```
public FileAppender()
```


Инициализирует новый экземпляр класса FileAppender.

### FileAppender(String fileName) {#FileAppender-java.lang.String-}
```
public FileAppender(String fileName)
```


Инициализирует новый экземпляр класса FileAppender.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

### FileAppender(String fileName, boolean useDate) {#FileAppender-java.lang.String-boolean-}
```
public FileAppender(String fileName, boolean useDate)
```


Инициализирует новый экземпляр класса FileAppender.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| useDate | boolean | Указывает, используется ли дата в имени файла |

### FileAppender(String fileName, IFormatter formatter) {#FileAppender-java.lang.String-com.aspose.email.IFormatter-}
```
public FileAppender(String fileName, IFormatter formatter)
```


Инициализирует новый экземпляр класса FileAppender.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| formatter | [IFormatter](../../com.aspose.email/iformatter) | Форматировщик журнала |

### FileAppender(String fileName, boolean useDate, IFormatter formatter) {#FileAppender-java.lang.String-boolean-com.aspose.email.IFormatter-}
```
public FileAppender(String fileName, boolean useDate, IFormatter formatter)
```


Инициализирует новый экземпляр класса FileAppender.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| useDate | boolean | Указывает, используется ли дата в имени файла |
| formatter | [IFormatter](../../com.aspose.email/iformatter) | Форматировщик журнала |

### append(LogEntry logEntry) {#append-com.aspose.email.LogEntry-}
```
public void append(LogEntry logEntry)
```


Добавляет информацию о записи журнала в аппендер.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| logEntry | [LogEntry](../../com.aspose.email/logentry) | The log entry. |

### append(LogEntry[] logEntries) {#append-com.aspose.email.LogEntry---}
```
public final void append(LogEntry[] logEntries)
```


Добавляет набор записей журнала в аппендер.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| logEntries | [LogEntry\[\]](../../com.aspose.email/logentry) | Набор записей журнала для записи. |

### appendHeader() {#appendHeader--}
```
public void appendHeader()
```


Начинает файл журнала с определённого заголовка.

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
| Parameter | Type | Описание |
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


Получает или задает кодировку.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Получает или задает имя файла.

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


Получает или задает значение, указывающее, используется ли дата для журналирования.

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


Получает или задает кодировку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Получает или задает имя файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setFormatter(IFormatter value) {#setFormatter-com.aspose.email.IFormatter-}
```
public final void setFormatter(IFormatter value)
```


Gets or sets the formatter.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

### setUseDate(boolean value) {#setUseDate-boolean-}
```
public final void setUseDate(boolean value)
```


Получает или задает значение, указывающее, используется ли дата для журналирования.

**Parameters:**
| Parameter | Type | Описание |
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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

