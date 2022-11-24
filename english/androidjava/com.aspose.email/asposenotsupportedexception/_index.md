---
title: AsposeNotSupportedException
second_title: Aspose.Email for Android via Java API Reference
description: The exception that is thrown when an invoked method or parameter is not supported  or when there is an attempt to read seek or write to a stream that does not support the invoked functionality.
type: docs
weight: 48
url: /androidjava/com.aspose.email/asposenotsupportedexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class AsposeNotSupportedException extends AsposeException
```

The exception that is thrown when an invoked method or parameter is not supported, or when there is an attempt to read, seek, or write to a stream that does not support the invoked functionality.

 1 
## Constructors

| Constructor | Description |
| --- | --- |
| [AsposeNotSupportedException()](#AsposeNotSupportedException--) | Initializes a new instance of the [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) class. |
| [AsposeNotSupportedException(String message)](#AsposeNotSupportedException-java.lang.String-) | Initializes a new instance of the [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) class with a specified error message. |
| [AsposeNotSupportedException(String format, String parameter)](#AsposeNotSupportedException-java.lang.String-java.lang.String-) |  |
| [AsposeNotSupportedException(String format, Object[] parameters)](#AsposeNotSupportedException-java.lang.String-java.lang.Object...-) | Initializes a new instance of the [AsposeArgumentOutOfRangeException](../../com.aspose.email/asposeargumentoutofrangeexception) class with a specified error message. |
| [AsposeNotSupportedException(String message, System.Exception innerException)](#AsposeNotSupportedException-java.lang.String-com.aspose.ms.System.Exception-) | Initializes a new instance of the [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| [AsposeNotSupportedException(System.Exception innerException)](#AsposeNotSupportedException-com.aspose.ms.System.Exception-) | Initializes a new instance of the [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) class with a reference to the inner exception that is the cause of this exception. |
## Methods

| Method | Description |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getErrorDetails()](#getErrorDetails--) | Gets extra information aboout error |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) | Gets a message that describes the current exception. |
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
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AsposeNotSupportedException() {#AsposeNotSupportedException--}
```
public AsposeNotSupportedException()
```


Initializes a new instance of the [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) class.

### AsposeNotSupportedException(String message) {#AsposeNotSupportedException-java.lang.String-}
```
public AsposeNotSupportedException(String message)
```


Initializes a new instance of the [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message that describes the error. |

### AsposeNotSupportedException(String format, String parameter) {#AsposeNotSupportedException-java.lang.String-java.lang.String-}
```
public AsposeNotSupportedException(String format, String parameter)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String |  |
| parameter | java.lang.String |  |

### AsposeNotSupportedException(String format, Object[] parameters) {#AsposeNotSupportedException-java.lang.String-java.lang.Object...-}
```
public AsposeNotSupportedException(String format, Object[] parameters)
```


Initializes a new instance of the [AsposeArgumentOutOfRangeException](../../com.aspose.email/asposeargumentoutofrangeexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | Message format |
| parameters | java.lang.Object[] | Format parameters |

### AsposeNotSupportedException(String message, System.Exception innerException) {#AsposeNotSupportedException-java.lang.String-com.aspose.ms.System.Exception-}
```
public AsposeNotSupportedException(String message, System.Exception innerException)
```


Initializes a new instance of the [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message that explains the reason for the exception. |
| innerException | com.aspose.ms.System.Exception | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### AsposeNotSupportedException(System.Exception innerException) {#AsposeNotSupportedException-com.aspose.ms.System.Exception-}
```
public AsposeNotSupportedException(System.Exception innerException)
```


Initializes a new instance of the [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) class with a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| innerException | com.aspose.ms.System.Exception | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

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


Gets extra information aboout error

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


Gets a message that describes the current exception.

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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
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

