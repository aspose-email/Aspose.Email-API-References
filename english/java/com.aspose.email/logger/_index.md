---
title: Logger
second_title: Aspose.Email for Java API Reference
description: Provides the logging functionality.
type: docs
weight: 358
url: /java/com.aspose.email/logger/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Logger implements System.IDisposable
```

Provides the logging functionality.
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppenders()](#getAppenders--) | Gets or sets the appender list. |
| [getClass()](#getClass--) |  |
| [getDebug()](#getDebug--) | Gets the debug logger. |
| [getName()](#getName--) | Gets or sets name. |
| [getSeverity()](#getSeverity--) | Gets or sets severity. |
| [hashCode()](#hashCode--) |  |
| [isEnabled(LogLevel level)](#isEnabled-com.aspose.email.LogLevel-) | Determines if logging is enabled for the specified level. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAppenders(AppenderCollection value)](#setAppenders-com.aspose.email.AppenderCollection-) | Gets or sets the appender list. |
| [setSeverity(LogLevel value)](#setSeverity-com.aspose.email.LogLevel-) | Gets or sets severity. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(Object message)](#write-java.lang.Object-) | Writes the specified message to appenders. |
| [write(String message)](#write-java.lang.String-) | Writes the specified message to appenders. |
| [write(String message, Exception exception)](#write-java.lang.String-java.lang.Exception-) | Writes the specified message and exception to appenders. |
| [write(String message, Exception ex, LogLevel level)](#write-java.lang.String-java.lang.Exception-com.aspose.email.LogLevel-) | Writes the specified message and exception to appenders. |
| [writeFormat(String format, Object[] arguments)](#writeFormat-java.lang.String-java.lang.Object...-) | Writes the message with specified format to appenders. |
| [writeIf(boolean condition, Object message)](#writeIf-boolean-java.lang.Object-) | Writes the specified message to appenders if condition is true. |
| [writeIf(boolean condition, Object message, Exception exception)](#writeIf-boolean-java.lang.Object-java.lang.Exception-) | Writes the specified message and exception to appenders if condition is true. |
| [writeIf(boolean condition, String message)](#writeIf-boolean-java.lang.String-) | Writes the specified message to appenders if condition is true. |
| [writeIf(LogLevel condition, String message)](#writeIf-com.aspose.email.LogLevel-java.lang.String-) | Writes the specified message if the log level is enabled. |
| [writeIf(LogLevel condition, String message, Exception exception)](#writeIf-com.aspose.email.LogLevel-java.lang.String-java.lang.Exception-) | Writes the specified message and exception if the log level is enabled. |
| [writeLine()](#writeLine--) | Writes the empty line to appenders. |
| [writeLine(Object message)](#writeLine-java.lang.Object-) | Writes the specified message to appenders. |
| [writeLine(String message)](#writeLine-java.lang.String-) | Writes the specified message to appenders. |
### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### getAppenders() {#getAppenders--}
```
public final AppenderCollection getAppenders()
```


Gets or sets the appender list.

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


Gets the debug logger.

**Returns:**
[Logger](../../com.aspose.email/logger)
### getName() {#getName--}
```
public final String getName()
```


Gets or sets name.

**Returns:**
java.lang.String
### getSeverity() {#getSeverity--}
```
public final LogLevel getSeverity()
```


Gets or sets severity.

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


Determines if logging is enabled for the specified level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | [LogLevel](../../com.aspose.email/loglevel) | level to be checked |

**Returns:**
boolean -   if logging is enabled for the specified level, otherwise it returns  .
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


Gets or sets the appender list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AppenderCollection](../../com.aspose.email/appendercollection) |  |

### setSeverity(LogLevel value) {#setSeverity-com.aspose.email.LogLevel-}
```
public final void setSeverity(LogLevel value)
```


Gets or sets severity.

**Parameters:**
| Parameter | Type | Description |
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

### write(Object message) {#write-java.lang.Object-}
```
public final void write(Object message)
```


Writes the specified message to appenders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.Object | The message to write. |

### write(String message) {#write-java.lang.String-}
```
public final void write(String message)
```


Writes the specified message to appenders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message to write. |

### write(String message, Exception exception) {#write-java.lang.String-java.lang.Exception-}
```
public final void write(String message, Exception exception)
```


Writes the specified message and exception to appenders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message to write. |
| exception | java.lang.Exception | The exception to write. |

### write(String message, Exception ex, LogLevel level) {#write-java.lang.String-java.lang.Exception-com.aspose.email.LogLevel-}
```
public final void write(String message, Exception ex, LogLevel level)
```


Writes the specified message and exception to appenders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message to write. |
| ex | java.lang.Exception | The exception to write. |
| level | [LogLevel](../../com.aspose.email/loglevel) | The log level. |

### writeFormat(String format, Object[] arguments) {#writeFormat-java.lang.String-java.lang.Object...-}
```
public final void writeFormat(String format, Object[] arguments)
```


Writes the message with specified format to appenders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String |  |
| arguments | java.lang.Object[] |  |

### writeIf(boolean condition, Object message) {#writeIf-boolean-java.lang.Object-}
```
public final void writeIf(boolean condition, Object message)
```


Writes the specified message to appenders if condition is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| condition | boolean | The condition to test. |
| message | java.lang.Object | The message to write. |

### writeIf(boolean condition, Object message, Exception exception) {#writeIf-boolean-java.lang.Object-java.lang.Exception-}
```
public final void writeIf(boolean condition, Object message, Exception exception)
```


Writes the specified message and exception to appenders if condition is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| condition | boolean | The condition to test. |
| message | java.lang.Object | The message to write. |
| exception | java.lang.Exception | The exception to write. |

### writeIf(boolean condition, String message) {#writeIf-boolean-java.lang.String-}
```
public final void writeIf(boolean condition, String message)
```


Writes the specified message to appenders if condition is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| condition | boolean | The condition to test. |
| message | java.lang.String | The message to write. |

### writeIf(LogLevel condition, String message) {#writeIf-com.aspose.email.LogLevel-java.lang.String-}
```
public final void writeIf(LogLevel condition, String message)
```


Writes the specified message if the log level is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| condition | [LogLevel](../../com.aspose.email/loglevel) | The log level. |
| message | java.lang.String | The message to log. |

### writeIf(LogLevel condition, String message, Exception exception) {#writeIf-com.aspose.email.LogLevel-java.lang.String-java.lang.Exception-}
```
public final void writeIf(LogLevel condition, String message, Exception exception)
```


Writes the specified message and exception if the log level is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| condition | [LogLevel](../../com.aspose.email/loglevel) | The log level. |
| message | java.lang.String | The message to log. |
| exception | java.lang.Exception | The exception to log. |

### writeLine() {#writeLine--}
```
public final void writeLine()
```


Writes the empty line to appenders.

### writeLine(Object message) {#writeLine-java.lang.Object-}
```
public final void writeLine(Object message)
```


Writes the specified message to appenders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.Object | The message to write. |

### writeLine(String message) {#writeLine-java.lang.String-}
```
public final void writeLine(String message)
```


Writes the specified message to appenders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message to write. |

