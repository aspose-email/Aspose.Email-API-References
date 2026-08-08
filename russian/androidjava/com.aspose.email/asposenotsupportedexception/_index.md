---
title: AsposeNotSupportedException
second_title: Aspose.Email for Android via Java API Reference
description: Исключение, которое выбрасывается, когда вызываемый метод или параметр не поддерживается, или когда происходит попытка чтения, перемещения или записи в поток, который не поддерживает вызываемую функциональность.
type: docs
weight: 48
url: /ru/androidjava/com.aspose.email/asposenotsupportedexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class AsposeNotSupportedException extends AsposeException
```

Исключение, которое выбрасывается, когда вызываемый метод или параметр не поддерживается, либо когда происходит попытка чтения, перемещения или записи в поток, не поддерживающий вызываемую функциональность.

1
## Constructors

| Constructor | Описание |
| --- | --- |
| [AsposeNotSupportedException()](#AsposeNotSupportedException--) | Инициализирует новый экземпляр класса [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception). |
| [AsposeNotSupportedException(String message)](#AsposeNotSupportedException-java.lang.String-) | Инициализирует новый экземпляр класса [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) с указанным сообщением об ошибке. |
| [AsposeNotSupportedException(String format, String parameter)](#AsposeNotSupportedException-java.lang.String-java.lang.String-) |  |
| [AsposeNotSupportedException(String format, Object[] parameters)](#AsposeNotSupportedException-java.lang.String-java.lang.Object...-) | Инициализирует новый экземпляр класса [AsposeArgumentOutOfRangeException](../../com.aspose.email/asposeargumentoutofrangeexception) с указанным сообщением об ошибке. |
| [AsposeNotSupportedException(String message, System.Exception innerException)](#AsposeNotSupportedException-java.lang.String-com.aspose.ms.System.Exception-) | Инициализирует новый экземпляр класса [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной данного исключения. |
| [AsposeNotSupportedException(System.Exception innerException)](#AsposeNotSupportedException-com.aspose.ms.System.Exception-) | Инициализирует новый экземпляр класса [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) со ссылкой на внутреннее исключение, являющееся причиной данного исключения. |
## Methods

| Method | Описание |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getErrorDetails()](#getErrorDetails--) | Получает дополнительную информацию об ошибке |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) | Получает сообщение, описывающее текущее исключение. |
| [getStackTrace()](#getStackTrace--) |  |
| [getSuppressed()](#getSuppressed--) |  |
| [getType()](#getType--) |  |
| [hashCode()](#hashCode--) |  |
| [initCause(Throwable arg0)](#initCause-java.lang.Throwable-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [printStackTrace()](#printStackTrace--) |  |
| [printStackTrace(PrintStream arg0)](#printStackTrace-java.io.PrintStream-) |  |
| [printStackTrace(PrintWriter arg0)](#printStackTrace-java.io.PrintWriter-) |  |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AsposeNotSupportedException() {#AsposeNotSupportedException--}
```
public AsposeNotSupportedException()
```


Инициализирует новый экземпляр класса [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception).

### AsposeNotSupportedException(String message) {#AsposeNotSupportedException-java.lang.String-}
```
public AsposeNotSupportedException(String message)
```


Инициализирует новый экземпляр класса [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) с указанным сообщением об ошибке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение, описывающее ошибку. |

### AsposeNotSupportedException(String format, String parameter) {#AsposeNotSupportedException-java.lang.String-java.lang.String-}
```
public AsposeNotSupportedException(String format, String parameter)
```


**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| формат | java.lang.String |  |
| параметр | java.lang.String |  |

### AsposeNotSupportedException(String format, Object[] parameters) {#AsposeNotSupportedException-java.lang.String-java.lang.Object...-}
```
public AsposeNotSupportedException(String format, Object[] parameters)
```


Инициализирует новый экземпляр класса [AsposeArgumentOutOfRangeException](../../com.aspose.email/asposeargumentoutofrangeexception) с указанным сообщением об ошибке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| формат | java.lang.String | Формат сообщения |
| параметры | java.lang.Object[] | Параметры формата |

### AsposeNotSupportedException(String message, System.Exception innerException) {#AsposeNotSupportedException-java.lang.String-com.aspose.ms.System.Exception-}
```
public AsposeNotSupportedException(String message, System.Exception innerException)
```


Инициализирует новый экземпляр класса [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной данного исключения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение об ошибке, объясняющее причину исключения. |
| innerException | com.aspose.ms.System.Exception | Исключение, являющееся причиной текущего исключения, или ссылка null (Nothing в Visual Basic), если внутренняя ошибка не указана. |

### AsposeNotSupportedException(System.Exception innerException) {#AsposeNotSupportedException-com.aspose.ms.System.Exception-}
```
public AsposeNotSupportedException(System.Exception innerException)
```


Инициализирует новый экземпляр класса [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) со ссылкой на внутреннее исключение, являющееся причиной данного исключения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| innerException | com.aspose.ms.System.Exception | Исключение, являющееся причиной текущего исключения, или ссылка null (Nothing в Visual Basic), если внутренняя ошибка не указана. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

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
### fillInStackTrace() {#fillInStackTrace--}
```
public synchronized Throwable fillInStackTrace()
```




**Returns:**
java.lang.Throwable
### getCause() {#getCause--}
```
public synchronized Throwable getCause()
```




**Returns:**
java.lang.Throwable
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorDetails() {#getErrorDetails--}
```
public final Object getErrorDetails()
```


Получает дополнительную информацию об ошибке

**Returns:**
java.lang.Object
### getInnerException() {#getInnerException--}
```
public Throwable getInnerException()
```




**Returns:**
java.lang.Throwable
### getLocalizedMessage() {#getLocalizedMessage--}
```
public String getLocalizedMessage()
```




**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public String getMessage()
```


Получает сообщение, описывающее текущее исключение.

**Returns:**
java.lang.String
### getStackTrace() {#getStackTrace--}
```
public StackTraceElement[] getStackTrace()
```




**Returns:**
java.lang.StackTraceElement[]
### getSuppressed() {#getSuppressed--}
```
public final synchronized Throwable[] getSuppressed()
```




**Returns:**
java.lang.Throwable[]
### getType() {#getType--}
```
public System.Type getType()
```




**Returns:**
com.aspose.ms.System.Type
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initCause(Throwable arg0) {#initCause-java.lang.Throwable-}
```
public synchronized Throwable initCause(Throwable arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

**Returns:**
java.lang.Throwable
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### printStackTrace() {#printStackTrace--}
```
public void printStackTrace()
```




### printStackTrace(PrintStream arg0) {#printStackTrace-java.io.PrintStream-}
```
public void printStackTrace(PrintStream arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.

**Returns:**
java.lang.String — строка, представляющая текущий объект.
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

