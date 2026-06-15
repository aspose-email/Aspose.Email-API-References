---
title: LogEntry
second_title: Aspose.Email for Android via Java API Reference
description: Представляет сообщение журнала.
type: docs
weight: 182
url: /ru/androidjava/com.aspose.email/logentry/
---

**Inheritance:**
java.lang.Object
```
public class LogEntry
```

Представляет сообщение журнала. Содержит общие свойства, необходимые для всех сообщений журнала.
## Constructors

| Constructor | Описание |
| --- | --- |
| [LogEntry()](#LogEntry--) | Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry). |
| [LogEntry(String message)](#LogEntry-java.lang.String-) | Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry). |
| [LogEntry(String message, Date time)](#LogEntry-java.lang.String-java.util.Date-) | Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry). |
| [LogEntry(String message, Throwable innerException)](#LogEntry-java.lang.String-java.lang.Throwable-) | Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry). |
| [LogEntry(String message, LogLevel severity)](#LogEntry-java.lang.String-com.aspose.email.LogLevel-) | Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry). |
| [LogEntry(String message, Throwable innerException, LogLevel severity)](#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-) | Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry). |
| [LogEntry(String message, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора |
| [LogEntry(byte[] binaryDataMessage)](#LogEntry-byte---) | Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора |
| [LogEntry(byte[] binaryDataMessage, Charset messageEncoding)](#LogEntry-byte---java.nio.charset.Charset-) | Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора |
| [LogEntry(byte[] binaryDataMessage, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-byte---com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора |
| [LogEntry(byte[] binaryDataMessage, Charset messageEncoding, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-byte---java.nio.charset.Charset-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора |
| [LogEntry(String message, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-java.lang.String-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора |
| [LogEntry(String message, Throwable innerException, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора |
## Methods

| Method | Описание |
| --- | --- |
| [addErrorMessage(String message)](#addErrorMessage-java.lang.String-) | Добавьте сообщение об ошибке или предупреждение в начало строкового билдера сообщений. |
| [deepClone()](#deepClone--) | Создаёт новый [LogEntry](../../com.aspose.email/logentry), являющийся копией текущего экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppDomainName()](#getAppDomainName--) | AppDomain, в котором мы работаем |
| [getBinaryDataMessage()](#getBinaryDataMessage--) | Бинарное тело сообщения для журналирования. |
| [getCategory()](#getCategory--) | Имя категории, используемое для маршрутизации записи журнала к одному или нескольким приемникам. |
| [getClass()](#getClass--) |  |
| [getContextualProperties()](#getContextualProperties--) | Словарь пар ключ/значение для записи. |
| [getErrorMessages()](#getErrorMessages--) | Получает сообщение об ошибке с помощью [LogEntry](../../com.aspose.email/logentry) |
| [getEventId()](#getEventId--) | Номер события или идентификатор. |
| [getInnerException()](#getInnerException--) | Получает или задает объект внутреннего исключения. |
| [getMachineName()](#getMachineName--) | Имя компьютера. |
| [getMessage()](#getMessage--) | Тело сообщения для записи в журнал. |
| [getMessageEncoding()](#getMessageEncoding--) | Кодировка для двоичного тела сообщения |
| [getSequenceId()](#getSequenceId--) | Уникальный идентификатор события журнала, который автоматически генерируется и монотонно увеличивается. |
| [getSeverity()](#getSeverity--) | Уровень серьезности записи журнала как перечисление Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)). |
| [getThreadName()](#getThreadName--) | Имя потока. |
| [getTimeStamp()](#getTimeStamp--) | Дата и время сообщения записи журнала. |
| [getTitle()](#getTitle--) | Дополнительное описание сообщения записи журнала. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAppDomainName(String value)](#setAppDomainName-java.lang.String-) | AppDomain, в котором мы работаем |
| [setBinaryDataMessage(byte[] value)](#setBinaryDataMessage-byte---) | Бинарное тело сообщения для журналирования. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Имя категории, используемое для маршрутизации записи журнала к одному или нескольким приемникам. |
| [setContextualProperties(System.Collections.Generic.IGenericDictionary<String,String> value)](#setContextualProperties-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Словарь пар ключ/значение для записи. |
| [setEventId(int value)](#setEventId-int-) | Номер события или идентификатор. |
| [setInnerException(Throwable value)](#setInnerException-java.lang.Throwable-) | Получает или задает объект внутреннего исключения. |
| [setMachineName(String value)](#setMachineName-java.lang.String-) | Имя компьютера. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Тело сообщения для записи в журнал. |
| [setMessageEncoding(Charset value)](#setMessageEncoding-java.nio.charset.Charset-) | Кодировка для двоичного тела сообщения |
| [setSeverity(LogLevel value)](#setSeverity-com.aspose.email.LogLevel-) | Уровень серьезности записи журнала как перечисление Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)). |
| [setThreadName(String value)](#setThreadName-java.lang.String-) | Имя потока. |
| [setTimeStamp(Date value)](#setTimeStamp-java.util.Date-) | Дата и время сообщения записи журнала. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Дополнительное описание сообщения записи журнала. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LogEntry() {#LogEntry--}
```
public LogEntry()
```


Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry).

### LogEntry(String message) {#LogEntry-java.lang.String-}
```
public LogEntry(String message)
```


Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение. |

### LogEntry(String message, Date time) {#LogEntry-java.lang.String-java.util.Date-}
```
public LogEntry(String message, Date time)
```


Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение. |
| время | java.util.Date | Время. |

### LogEntry(String message, Throwable innerException) {#LogEntry-java.lang.String-java.lang.Throwable-}
```
public LogEntry(String message, Throwable innerException)
```


Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Тело сообщения для записи в журнал. Значение, полученное из метода ToString() объекта сообщения. |
| innerException | java.lang.Throwable | Внутреннее исключение для записи в журнал. |

### LogEntry(String message, LogLevel severity) {#LogEntry-java.lang.String-com.aspose.email.LogLevel-}
```
public LogEntry(String message, LogLevel severity)
```


Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Тело сообщения для записи в журнал. Значение, полученное из метода ToString() объекта сообщения. |
| severity | [LogLevel](../../com.aspose.email/loglevel) | Уровень серьезности записи журнала как перечисление Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)). (Неуказано, Информация, Предупреждение или Ошибка). |

### LogEntry(String message, Throwable innerException, LogLevel severity) {#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-}
```
public LogEntry(String message, Throwable innerException, LogLevel severity)
```


Создайте новый экземпляр класса [LogEntry](../../com.aspose.email/logentry).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Тело сообщения для записи в журнал. Значение, полученное из метода ToString() объекта сообщения. |
| innerException | java.lang.Throwable | Внутреннее исключение для записи в журнал. |
| severity | [LogLevel](../../com.aspose.email/loglevel) | Уровень серьезности записи журнала как перечисление Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)). (Неуказано, Информация, Предупреждение или Ошибка). |

### LogEntry(String message, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(String message, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Тело сообщения для записи в журнал. Значение, полученное из метода ToString() объекта сообщения. |
| свойства | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | Словарь пар ключ/значение для записи. |

### LogEntry(byte[] binaryDataMessage) {#LogEntry-byte---}
```
public LogEntry(byte[] binaryDataMessage)
```


Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| binaryDataMessage | byte[] | Бинарное тело сообщения для журналирования. |

### LogEntry(byte[] binaryDataMessage, Charset messageEncoding) {#LogEntry-byte---java.nio.charset.Charset-}
```
public LogEntry(byte[] binaryDataMessage, Charset messageEncoding)
```


Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| binaryDataMessage | byte[] | Бинарное тело сообщения для журналирования. |
| messageEncoding | java.nio.charset.Charset | Кодировка для двоичного сообщения |

### LogEntry(byte[] binaryDataMessage, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-byte---com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(byte[] binaryDataMessage, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| binaryDataMessage | byte[] | Бинарное тело сообщения для журналирования. |
| свойства | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | Словарь пар ключ/значение для записи. |

### LogEntry(byte[] binaryDataMessage, Charset messageEncoding, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-byte---java.nio.charset.Charset-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(byte[] binaryDataMessage, Charset messageEncoding, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| binaryDataMessage | byte[] | Бинарное тело сообщения для журналирования. |
| messageEncoding | java.nio.charset.Charset | Кодировка для двоичного сообщения |
| свойства | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | Словарь пар ключ/значение для записи. |

### LogEntry(String message, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-java.lang.String-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(String message, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Тело сообщения для записи в журнал. Значение, полученное из метода ToString() объекта сообщения. |
| severity | [LogLevel](../../com.aspose.email/loglevel) | Уровень серьезности записи журнала как перечисление Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)). (Неуказано, Информация, Предупреждение или Ошибка). |
| категория | java.lang.String | Имя категории, используемое для маршрутизации записи журнала к одному или нескольким приемникам. |
| eventId | int | Номер события или идентификатор. |
| заголовок | java.lang.String | Дополнительное описание сообщения записи журнала. |
| свойства | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | Словарь пар ключ/значение для записи. |

### LogEntry(String message, Throwable innerException, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(String message, Throwable innerException, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


Создайте новый экземпляр [LogEntry](../../com.aspose.email/logentry) с полным набором параметров конструктора

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Тело сообщения для записи в журнал. Значение, полученное из метода ToString() объекта сообщения. |
| innerException | java.lang.Throwable | Внутреннее исключение для записи в журнал. |
| severity | [LogLevel](../../com.aspose.email/loglevel) | Уровень серьезности записи журнала как перечисление Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)). (Неуказано, Информация, Предупреждение или Ошибка). |
| категория | java.lang.String | Имя категории, используемое для маршрутизации записи журнала к одному или нескольким приемникам. |
| eventId | int | Номер события или идентификатор. |
| заголовок | java.lang.String | Дополнительное описание сообщения записи журнала. |
| свойства | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | Словарь пар ключ/значение для записи. |

### addErrorMessage(String message) {#addErrorMessage-java.lang.String-}
```
public void addErrorMessage(String message)
```


Добавить сообщение об ошибке или предупреждении в начало строкового построителя сообщений. Используется распределителем для записи проблем.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение, которое будет добавлено к этому экземпляру |

### deepClone() {#deepClone--}
```
public final LogEntry deepClone()
```


Создаёт новый [LogEntry](../../com.aspose.email/logentry), являющийся копией текущего экземпляра.

**Returns:**
[LogEntry](../../com.aspose.email/logentry) - A new  LogEntry  that is a copy of the current instance.
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
### getAppDomainName() {#getAppDomainName--}
```
public final String getAppDomainName()
```


AppDomain, в котором мы работаем

**Returns:**
java.lang.String
### getBinaryDataMessage() {#getBinaryDataMessage--}
```
public final byte[] getBinaryDataMessage()
```


Бинарное тело сообщения для журналирования.

**Returns:**
byte[]
### getCategory() {#getCategory--}
```
public final String getCategory()
```


Имя категории, используемое для маршрутизации записи журнала к одному или нескольким приемникам.

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


Словарь пар ключ/значение для записи.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String>
### getErrorMessages() {#getErrorMessages--}
```
public final String getErrorMessages()
```


Получает сообщение об ошибке с помощью [LogEntry](../../com.aspose.email/logentry)

**Returns:**
java.lang.String
### getEventId() {#getEventId--}
```
public final int getEventId()
```


Номер события или идентификатор.

**Returns:**
int
### getInnerException() {#getInnerException--}
```
public final Throwable getInnerException()
```


Получает или задает объект внутреннего исключения.

**Returns:**
java.lang.Throwable
### getMachineName() {#getMachineName--}
```
public final String getMachineName()
```


Имя компьютера.

**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Тело сообщения для записи в журнал. Значение, полученное из метода ToString() объекта сообщения.

**Returns:**
java.lang.String
### getMessageEncoding() {#getMessageEncoding--}
```
public final Charset getMessageEncoding()
```


Кодировка для двоичного тела сообщения

**Returns:**
java.nio.charset.Charset
### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


Уникальный идентификатор события журнала, который автоматически генерируется и монотонно увеличивается.

**Returns:**
int
### getSeverity() {#getSeverity--}
```
public final LogLevel getSeverity()
```


Уровень серьезности записи журнала как перечисление Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)). (Неуказано, Информация, Предупреждение или Ошибка).

**Returns:**
[LogLevel](../../com.aspose.email/loglevel)
### getThreadName() {#getThreadName--}
```
public final String getThreadName()
```


Имя потока.

**Returns:**
java.lang.String
### getTimeStamp() {#getTimeStamp--}
```
public final Date getTimeStamp()
```


Дата и время сообщения записи журнала.

**Returns:**
java.util.Date
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Дополнительное описание сообщения записи журнала.

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


AppDomain, в котором мы работаем

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBinaryDataMessage(byte[] value) {#setBinaryDataMessage-byte---}
```
public final void setBinaryDataMessage(byte[] value)
```


Бинарное тело сообщения для журналирования.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | byte[] |  |

### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Имя категории, используемое для маршрутизации записи журнала к одному или нескольким приемникам.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setContextualProperties(System.Collections.Generic.IGenericDictionary<String,String> value) {#setContextualProperties-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public final void setContextualProperties(System.Collections.Generic.IGenericDictionary<String,String> value)
```


Словарь пар ключ/значение для записи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> |  |

### setEventId(int value) {#setEventId-int-}
```
public final void setEventId(int value)
```


Номер события или идентификатор.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setInnerException(Throwable value) {#setInnerException-java.lang.Throwable-}
```
public final void setInnerException(Throwable value)
```


Получает или задает объект внутреннего исключения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.Throwable |  |

### setMachineName(String value) {#setMachineName-java.lang.String-}
```
public final void setMachineName(String value)
```


Имя компьютера.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Тело сообщения для записи в журнал. Значение, полученное из метода ToString() объекта сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessageEncoding(Charset value) {#setMessageEncoding-java.nio.charset.Charset-}
```
public final void setMessageEncoding(Charset value)
```


Кодировка для двоичного тела сообщения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setSeverity(LogLevel value) {#setSeverity-com.aspose.email.LogLevel-}
```
public final void setSeverity(LogLevel value)
```


Уровень серьезности записи журнала как перечисление Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)). (Неуказано, Информация, Предупреждение или Ошибка).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [LogLevel](../../com.aspose.email/loglevel) |  |

### setThreadName(String value) {#setThreadName-java.lang.String-}
```
public final void setThreadName(String value)
```


Имя потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setTimeStamp(Date value) {#setTimeStamp-java.util.Date-}
```
public final void setTimeStamp(Date value)
```


Дата и время сообщения записи журнала.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Дополнительное описание сообщения записи журнала.

**Parameters:**
| Parameter | Type | Описание |
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

