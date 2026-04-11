---
title: Logger
second_title: Aspose.Email for Android via Java API Reference
description: Обеспечивает функциональность журналирования.
type: docs
weight: 184
url: /ru/androidjava/com.aspose.email/logger/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Logger implements System.IDisposable
```

Обеспечивает функциональность журналирования.
## Methods

| Method | Описание |
| --- | --- |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppenders()](#getAppenders--) | Получает или задает список аппендеров. |
| [getClass()](#getClass--) |  |
| [getDebug()](#getDebug--) | Получает отладочный логгер. |
| [getName()](#getName--) | Получает или задает имя. |
| [getSeverity()](#getSeverity--) | Получает или задает степень важности. |
| [hashCode()](#hashCode--) |  |
| [isEnabled(LogLevel level)](#isEnabled-com.aspose.email.LogLevel-) | Определяет, включено ли журналирование для указанного уровня. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAppenders(AppenderCollection value)](#setAppenders-com.aspose.email.AppenderCollection-) | Получает или задает список аппендеров. |
| [setSeverity(LogLevel value)](#setSeverity-com.aspose.email.LogLevel-) | Получает или задает степень важности. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(Object message)](#write-java.lang.Object-) | Записывает указанное сообщение в аппендеры. |
| [write(String message)](#write-java.lang.String-) | Записывает указанное сообщение в аппендеры. |
| [write(String message, Exception exception)](#write-java.lang.String-java.lang.Exception-) | Записывает указанное сообщение и исключение в аппендеры. |
| [write(String message, Exception ex, LogLevel level)](#write-java.lang.String-java.lang.Exception-com.aspose.email.LogLevel-) | Записывает указанное сообщение и исключение в аппендеры. |
| [writeFormat(String format, Object[] arguments)](#writeFormat-java.lang.String-java.lang.Object...-) | Записывает сообщение с указанным форматом в аппендеры. |
| [writeIf(boolean condition, Object message)](#writeIf-boolean-java.lang.Object-) | Записывает указанное сообщение в аппендеры, если условие истинно. |
| [writeIf(boolean condition, Object message, Exception exception)](#writeIf-boolean-java.lang.Object-java.lang.Exception-) | Записывает указанное сообщение и исключение в аппендеры, если условие истинно. |
| [writeIf(boolean condition, String message)](#writeIf-boolean-java.lang.String-) | Записывает указанное сообщение в аппендеры, если условие истинно. |
| [writeIf(LogLevel condition, String message)](#writeIf-com.aspose.email.LogLevel-java.lang.String-) | Записывает указанное сообщение, если уровень журнала включен. |
| [writeIf(LogLevel condition, String message, Exception exception)](#writeIf-com.aspose.email.LogLevel-java.lang.String-java.lang.Exception-) | Записывает указанное сообщение и исключение, если уровень журнала включен. |
| [writeLine()](#writeLine--) | Записывает пустую строку в аппендеры. |
| [writeLine(Object message)](#writeLine-java.lang.Object-) | Записывает указанное сообщение в аппендеры. |
| [writeLine(String message)](#writeLine-java.lang.String-) | Записывает указанное сообщение в аппендеры. |
### dispose() {#dispose--}
```
public final void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов.

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
### getAppenders() {#getAppenders--}
```
public final AppenderCollection getAppenders()
```


Получает или задает список аппендеров.

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


Получает отладочный логгер.

**Returns:**
[Logger](../../com.aspose.email/logger)
### getName() {#getName--}
```
public final String getName()
```


Получает или задает имя.

**Returns:**
java.lang.String
### getSeverity() {#getSeverity--}
```
public final LogLevel getSeverity()
```


Получает или задает степень важности.

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


Определяет, включено ли журналирование для указанного уровня.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| level | [LogLevel](../../com.aspose.email/loglevel) | уровень для проверки |

**Returns:**
boolean -   если журналирование включено для указанного уровня, иначе возвращает  .
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


Получает или задает список аппендеров.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [AppenderCollection](../../com.aspose.email/appendercollection) |  |

### setSeverity(LogLevel value) {#setSeverity-com.aspose.email.LogLevel-}
```
public final void setSeverity(LogLevel value)
```


Получает или задает степень важности.

**Parameters:**
| Parameter | Type | Описание |
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

### write(Object message) {#write-java.lang.Object-}
```
public final void write(Object message)
```


Записывает указанное сообщение в аппендеры.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.Object | Сообщение для записи. |

### write(String message) {#write-java.lang.String-}
```
public final void write(String message)
```


Записывает указанное сообщение в аппендеры.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение для записи. |

### write(String message, Exception exception) {#write-java.lang.String-java.lang.Exception-}
```
public final void write(String message, Exception exception)
```


Записывает указанное сообщение и исключение в аппендеры.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение для записи. |
| исключение | java.lang.Exception | Исключение для записи. |

### write(String message, Exception ex, LogLevel level) {#write-java.lang.String-java.lang.Exception-com.aspose.email.LogLevel-}
```
public final void write(String message, Exception ex, LogLevel level)
```


Записывает указанное сообщение и исключение в аппендеры.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение для записи. |
| ex | java.lang.Exception | Исключение для записи. |
| level | [LogLevel](../../com.aspose.email/loglevel) | Уровень журнала. |

### writeFormat(String format, Object[] arguments) {#writeFormat-java.lang.String-java.lang.Object...-}
```
public final void writeFormat(String format, Object[] arguments)
```


Записывает сообщение с указанным форматом в аппендеры.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| формат | java.lang.String |  |
| аргументы | java.lang.Object[] |  |

### writeIf(boolean condition, Object message) {#writeIf-boolean-java.lang.Object-}
```
public final void writeIf(boolean condition, Object message)
```


Записывает указанное сообщение в аппендеры, если условие истинно.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| условие | boolean | Условие для проверки. |
| сообщение | java.lang.Object | Сообщение для записи. |

### writeIf(boolean condition, Object message, Exception exception) {#writeIf-boolean-java.lang.Object-java.lang.Exception-}
```
public final void writeIf(boolean condition, Object message, Exception exception)
```


Записывает указанное сообщение и исключение в аппендеры, если условие истинно.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| условие | boolean | Условие для проверки. |
| сообщение | java.lang.Object | Сообщение для записи. |
| исключение | java.lang.Exception | Исключение для записи. |

### writeIf(boolean condition, String message) {#writeIf-boolean-java.lang.String-}
```
public final void writeIf(boolean condition, String message)
```


Записывает указанное сообщение в аппендеры, если условие истинно.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| условие | boolean | Условие для проверки. |
| сообщение | java.lang.String | Сообщение для записи. |

### writeIf(LogLevel condition, String message) {#writeIf-com.aspose.email.LogLevel-java.lang.String-}
```
public final void writeIf(LogLevel condition, String message)
```


Записывает указанное сообщение, если уровень журнала включен.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| condition | [LogLevel](../../com.aspose.email/loglevel) | Уровень журнала. |
| сообщение | java.lang.String | Сообщение для журналирования. |

### writeIf(LogLevel condition, String message, Exception exception) {#writeIf-com.aspose.email.LogLevel-java.lang.String-java.lang.Exception-}
```
public final void writeIf(LogLevel condition, String message, Exception exception)
```


Записывает указанное сообщение и исключение, если уровень журнала включен.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| condition | [LogLevel](../../com.aspose.email/loglevel) | Уровень журнала. |
| сообщение | java.lang.String | Сообщение для журналирования. |
| исключение | java.lang.Exception | Исключение для журналирования. |

### writeLine() {#writeLine--}
```
public final void writeLine()
```


Записывает пустую строку в аппендеры.

### writeLine(Object message) {#writeLine-java.lang.Object-}
```
public final void writeLine(Object message)
```


Записывает указанное сообщение в аппендеры.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.Object | Сообщение для записи. |

### writeLine(String message) {#writeLine-java.lang.String-}
```
public final void writeLine(String message)
```


Записывает указанное сообщение в аппендеры.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение для записи. |

