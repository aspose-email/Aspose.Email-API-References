---
title: AsposeInvalidOperationException
second_title: Aspose.Email for Java API Reference
description: Exception class for denoting an object was in a state that made calling a method illegal.
type: docs
weight: 59
url: /java/com.aspose.email/asposeinvalidoperationexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class AsposeInvalidOperationException extends AsposeException
```

Exception class for denoting an object was in a state that made calling a method illegal.
## Constructors

| Constructor | Description |
| --- | --- |
| [AsposeInvalidOperationException()](#AsposeInvalidOperationException--) | Initializes a new instance of the [AsposeInvalidOperationException](../../com.aspose.email/asposeinvalidoperationexception) class. |
| [AsposeInvalidOperationException(String message)](#AsposeInvalidOperationException-java.lang.String-) | Initializes a new instance of the [AsposeInvalidOperationException](../../com.aspose.email/asposeinvalidoperationexception) class with a specified error message. |
| [AsposeInvalidOperationException(String format, String parameter)](#AsposeInvalidOperationException-java.lang.String-java.lang.String-) |  |
| [AsposeInvalidOperationException(String format, Object[] parameters)](#AsposeInvalidOperationException-java.lang.String-java.lang.Object...-) | Initializes a new instance of the [AsposeInvalidOperationException](../../com.aspose.email/asposeinvalidoperationexception) class with a specified error message. |
| [AsposeInvalidOperationException(String message, Throwable inner)](#AsposeInvalidOperationException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the [AsposeInvalidOperationException](../../com.aspose.email/asposeinvalidoperationexception) class with a specified error message. |
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
### AsposeInvalidOperationException() {#AsposeInvalidOperationException--}
```
public AsposeInvalidOperationException()
```


Initializes a new instance of the [AsposeInvalidOperationException](../../com.aspose.email/asposeinvalidoperationexception) class.

### AsposeInvalidOperationException(String message) {#AsposeInvalidOperationException-java.lang.String-}
```
public AsposeInvalidOperationException(String message)
```


Initializes a new instance of the [AsposeInvalidOperationException](../../com.aspose.email/asposeinvalidoperationexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A message that describes the error. |

### AsposeInvalidOperationException(String format, String parameter) {#AsposeInvalidOperationException-java.lang.String-java.lang.String-}
```
public AsposeInvalidOperationException(String format, String parameter)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String |  |
| parameter | java.lang.String |  |

### AsposeInvalidOperationException(String format, Object[] parameters) {#AsposeInvalidOperationException-java.lang.String-java.lang.Object...-}
```
public AsposeInvalidOperationException(String format, Object[] parameters)
```


Initializes a new instance of the [AsposeInvalidOperationException](../../com.aspose.email/asposeinvalidoperationexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | Message format |
| parameters | java.lang.Object[] | Format parameters |

### AsposeInvalidOperationException(String message, Throwable inner) {#AsposeInvalidOperationException-java.lang.String-java.lang.Throwable-}
```
public AsposeInvalidOperationException(String message, Throwable inner)
```


Initializes a new instance of the [AsposeInvalidOperationException](../../com.aspose.email/asposeinvalidoperationexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A message that describes the error. |
| inner | java.lang.Throwable | The exception causing the current exception. |

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

