---
title: Logger
second_title: Aspose.Email for Java API Reference
description:  Provides the logging functionality.
type: docs
weight: 357
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
| [getDebug()](#getDebug--) | Gets the debug logger. |
| [getSeverity()](#getSeverity--) | Gets or sets severity. |
| [setSeverity(LogLevel value)](#setSeverity-com.aspose.email.LogLevel-) | Gets or sets severity. |
| [getName()](#getName--) | Gets or sets name. |
| [getAppenders()](#getAppenders--) | Gets or sets the appender list. |
| [setAppenders(AppenderCollection value)](#setAppenders-com.aspose.email.AppenderCollection-) | Gets or sets the appender list. |
| [isEnabled(LogLevel level)](#isEnabled-com.aspose.email.LogLevel-) | Determines if logging is enabled for the specified level. |
| [writeLine()](#writeLine--) | Writes the empty line to appenders. |
| [writeLine(String message)](#writeLine-java.lang.String-) | Writes the specified message to appenders. |
| [writeLine(Object message)](#writeLine-java.lang.Object-) | Writes the specified message to appenders. |
| [writeFormat(String format, Object[] arguments)](#writeFormat-java.lang.String-java.lang.Object...-) | Writes the message with specified format to appenders. |
| [write(String message)](#write-java.lang.String-) | Writes the specified message to appenders. |
| [write(String message, Exception exception)](#write-java.lang.String-java.lang.Exception-) | Writes the specified message and exception to appenders. |
| [write(String message, Exception ex, LogLevel level)](#write-java.lang.String-java.lang.Exception-com.aspose.email.LogLevel-) | Writes the specified message and exception to appenders. |
| [write(Object message)](#write-java.lang.Object-) | Writes the specified message to appenders. |
| [writeIf(boolean condition, String message)](#writeIf-boolean-java.lang.String-) | Writes the specified message to appenders if condition is true. |
| [writeIf(boolean condition, Object message)](#writeIf-boolean-java.lang.Object-) | Writes the specified message to appenders if condition is true. |
| [writeIf(boolean condition, Object message, Exception exception)](#writeIf-boolean-java.lang.Object-java.lang.Exception-) | Writes the specified message and exception to appenders if condition is true. |
| [writeIf(LogLevel condition, String message)](#writeIf-com.aspose.email.LogLevel-java.lang.String-) | Writes the specified message if the log level is enabled. |
| [writeIf(LogLevel condition, String message, Exception exception)](#writeIf-com.aspose.email.LogLevel-java.lang.String-java.lang.Exception-) | Writes the specified message and exception if the log level is enabled. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
### getDebug() {#getDebug--}
```
public static Logger getDebug()
```


Gets the debug logger.

**Returns:**
[Logger](../../com.aspose.email/logger)
### getSeverity() {#getSeverity--}
```
public final LogLevel getSeverity()
```


Gets or sets severity.

**Returns:**
[LogLevel](../../com.aspose.email/loglevel)
### setSeverity(LogLevel value) {#setSeverity-com.aspose.email.LogLevel-}
```
public final void setSeverity(LogLevel value)
```


Gets or sets severity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [LogLevel](../../com.aspose.email/loglevel) |  |

### getName() {#getName--}
```
public final String getName()
```


Gets or sets name.

**Returns:**
java.lang.String
### getAppenders() {#getAppenders--}
```
public final AppenderCollection getAppenders()
```


Gets or sets the appender list.

**Returns:**
[AppenderCollection](../../com.aspose.email/appendercollection)
### setAppenders(AppenderCollection value) {#setAppenders-com.aspose.email.AppenderCollection-}
```
public final void setAppenders(AppenderCollection value)
```


Gets or sets the appender list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AppenderCollection](../../com.aspose.email/appendercollection) |  |

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
boolean - \`\`\` \`\`\` if logging is enabled for the specified level, otherwise it returns \`\`\` \`\`\`.
### writeLine() {#writeLine--}
```
public final void writeLine()
```


Writes the empty line to appenders.

### writeLine(String message) {#writeLine-java.lang.String-}
```
public final void writeLine(String message)
```


Writes the specified message to appenders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message to write. |

### writeLine(Object message) {#writeLine-java.lang.Object-}
```
public final void writeLine(Object message)
```


Writes the specified message to appenders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.Object | The message to write. |

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

### write(Object message) {#write-java.lang.Object-}
```
public final void write(Object message)
```


Writes the specified message to appenders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.Object | The message to write. |

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

### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

