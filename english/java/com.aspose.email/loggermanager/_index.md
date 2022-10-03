---
title: LoggerManager
second_title: Aspose.Email for Java API Reference
description: Static manager that controls the creation of loggers.
type: docs
weight: 358
url: /java/com.aspose.email/loggermanager/
---
**Inheritance:**
java.lang.Object
```
public class LoggerManager
```

Static manager that controls the creation of loggers.
## Constructors

| Constructor | Description |
| --- | --- |
| [LoggerManager()](#LoggerManager--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLogger(String name)](#getLogger-java.lang.String-) | Gets a logger by the specified name. |
| [addLogger(String name, Logger logger)](#addLogger-java.lang.String-com.aspose.email.Logger-) | Adds a logger to the LoggerManager with specified name. |
| [removeLogger(String name)](#removeLogger-java.lang.String-) | Removes a logger with the specified name. |
| [containsLogger(String name)](#containsLogger-java.lang.String-) | Determines whether the logger cache contains an object with the specified logger name. |
| [createLogger(String name, Appender appender)](#createLogger-java.lang.String-com.aspose.email.Appender-) | Creates a logger with specified name and appender. |
| [createLogger(String name, Appender[] appenders)](#createLogger-java.lang.String-com.aspose.email.Appender...-) | Creates a logger with specified name and appender. |
| [createLogger(String name, LogLevel severity, Appender appender)](#createLogger-java.lang.String-com.aspose.email.LogLevel-com.aspose.email.Appender-) | Creates a logger with specified name and appender. |
| [createLogger(String name, LogLevel severity, Appender[] appenders)](#createLogger-java.lang.String-com.aspose.email.LogLevel-com.aspose.email.Appender...-) | Creates a logger with specified name and appender. |
### LoggerManager() {#LoggerManager--}
```
public LoggerManager()
```


### getLogger(String name) {#getLogger-java.lang.String-}
```
public static Logger getLogger(String name)
```


Gets a logger by the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The logger name. |

**Returns:**
[Logger](../../com.aspose.email/logger) - The logger.
### addLogger(String name, Logger logger) {#addLogger-java.lang.String-com.aspose.email.Logger-}
```
public static void addLogger(String name, Logger logger)
```


Adds a logger to the LoggerManager with specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The logger name. |
| logger | [Logger](../../com.aspose.email/logger) | The logger. |

### removeLogger(String name) {#removeLogger-java.lang.String-}
```
public static void removeLogger(String name)
```


Removes a logger with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The logger name. |

### containsLogger(String name) {#containsLogger-java.lang.String-}
```
public static boolean containsLogger(String name)
```


Determines whether the logger cache contains an object with the specified logger name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The logger name. |

**Returns:**
boolean - true if the logger cache contains an element with the key; otherwise, false.
### createLogger(String name, Appender appender) {#createLogger-java.lang.String-com.aspose.email.Appender-}
```
public static Logger createLogger(String name, Appender appender)
```


Creates a logger with specified name and appender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The logger name. |
| appender | [Appender](../../com.aspose.email/appender) | The appender. |

**Returns:**
[Logger](../../com.aspose.email/logger) - The created logger.
### createLogger(String name, Appender[] appenders) {#createLogger-java.lang.String-com.aspose.email.Appender...-}
```
public static Logger createLogger(String name, Appender[] appenders)
```


Creates a logger with specified name and appender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The logger name. |
| appenders | [Appender\[\]](../../com.aspose.email/appender) | The appender. |

**Returns:**
[Logger](../../com.aspose.email/logger) - The created logger.
### createLogger(String name, LogLevel severity, Appender appender) {#createLogger-java.lang.String-com.aspose.email.LogLevel-com.aspose.email.Appender-}
```
public static Logger createLogger(String name, LogLevel severity, Appender appender)
```


Creates a logger with specified name and appender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The logger name. |
| severity | [LogLevel](../../com.aspose.email/loglevel) | The severity. |
| appender | [Appender](../../com.aspose.email/appender) | The appender. |

**Returns:**
[Logger](../../com.aspose.email/logger) - The created logger.
### createLogger(String name, LogLevel severity, Appender[] appenders) {#createLogger-java.lang.String-com.aspose.email.LogLevel-com.aspose.email.Appender...-}
```
public static Logger createLogger(String name, LogLevel severity, Appender[] appenders)
```


Creates a logger with specified name and appender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The logger name. |
| severity | [LogLevel](../../com.aspose.email/loglevel) | The severity. |
| appenders | [Appender\[\]](../../com.aspose.email/appender) | The appenders array. |

**Returns:**
[Logger](../../com.aspose.email/logger) - The created logger.
