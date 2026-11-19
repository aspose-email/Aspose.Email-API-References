---
title: AsposeException
second_title: Aspose.Email for Java API Reference
description: The base class of the exceptions thrown by Aspose.Email.
type: docs
weight: 56
url: /java/com.aspose.email/asposeexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class AsposeException extends System.Exception
```

The base class of the exceptions thrown by Aspose.Email.

Catch this type to handle any error that the library reports with its own exception types, such as [FormatNotSupportedException](../../com.aspose.email/formatnotsupportedexception), [SmtpException](../../com.aspose.email/smtpexception) or [ImapException](../../com.aspose.email/imapexception).
## Constructors

| Constructor | Description |
| --- | --- |
| [AsposeException()](#AsposeException--) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class. |
| [AsposeException(String message)](#AsposeException-java.lang.String-) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with the specified error message. |
| [AsposeException(String format, Object[] parameters)](#AsposeException-java.lang.String-java.lang.Object...-) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with an error message built from a composite format string. |
| [AsposeException(String format, String parameter)](#AsposeException-java.lang.String-java.lang.String-) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with an error message built from a format string with one argument. |
| [AsposeException(String message, Throwable innerException)](#AsposeException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with the specified error message and a reference to the exception that caused it. |
| [AsposeException(Throwable innerException)](#AsposeException-java.lang.Throwable-) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with a reference to the exception that caused it. |
## Methods

| Method | Description |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getErrorDetails()](#getErrorDetails--) | Gets additional information about the error, if the operation provides any. |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) | Gets the message that describes the error. |
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
| [toString()](#toString--) | Returns the type, the message and the stack trace of the exception. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AsposeException() {#AsposeException--}
```
public AsposeException()
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class.

### AsposeException(String message) {#AsposeException-java.lang.String-}
```
public AsposeException(String message)
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with the specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message that describes the error. |

### AsposeException(String format, Object[] parameters) {#AsposeException-java.lang.String-java.lang.Object...-}
```
public AsposeException(String format, Object[] parameters)
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with an error message built from a composite format string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | A composite format string with placeholders such as  \{0\} . |
| parameters | java.lang.Object[] | The objects to insert into  format . |

### AsposeException(String format, String parameter) {#AsposeException-java.lang.String-java.lang.String-}
```
public AsposeException(String format, String parameter)
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with an error message built from a format string with one argument.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | A composite format string with one placeholder,  \{0\} . |
| parameter | java.lang.String | The value inserted into  format . |

### AsposeException(String message, Throwable innerException) {#AsposeException-java.lang.String-java.lang.Throwable-}
```
public AsposeException(String message, Throwable innerException)
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with the specified error message and a reference to the exception that caused it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message that describes the error. |
| innerException | java.lang.Throwable | The exception that caused this exception, or  null . |

### AsposeException(Throwable innerException) {#AsposeException-java.lang.Throwable-}
```
public AsposeException(Throwable innerException)
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with a reference to the exception that caused it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| innerException | java.lang.Throwable | The exception that caused this exception, or  null . |

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


Gets additional information about the error, if the operation provides any.

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


Gets the message that describes the error.

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


Returns the type, the message and the stack trace of the exception.

**Returns:**
java.lang.String - A string that represents the exception.
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

