---
title: SmtpFailedRecipientException
second_title: Aspose.Email for Java API Reference
description: Represents the exception which arises when the specified recipient is wrong
type: docs
weight: 677
url: /java/com.aspose.email/smtpfailedrecipientexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception), [com.aspose.email.SmtpException](../../com.aspose.email/smtpexception)
```
public class SmtpFailedRecipientException extends SmtpException
```

Represents the exception which arises when the specified recipient is wrong
## Constructors

| Constructor | Description |
| --- | --- |
| [SmtpFailedRecipientException()](#SmtpFailedRecipientException--) | Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class |
| [SmtpFailedRecipientException(String message)](#SmtpFailedRecipientException-java.lang.String-) | Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class |
| [SmtpFailedRecipientException(String message, Throwable innerException)](#SmtpFailedRecipientException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class |
| [SmtpFailedRecipientException(int statusCode, String failedRecipient)](#SmtpFailedRecipientException-int-java.lang.String-) | Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class |
| [SmtpFailedRecipientException(int statusCode, String failedRecipient, String serverResponse)](#SmtpFailedRecipientException-int-java.lang.String-java.lang.String-) | Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class |
| [SmtpFailedRecipientException(String message, String failedRecipient, System.Exception innerException)](#SmtpFailedRecipientException-java.lang.String-java.lang.String-com.aspose.ms.System.Exception-) | Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class |
## Methods

| Method | Description |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getErrorDetails()](#getErrorDetails--) | Gets extra information aboout error |
| [getFailedRecipient()](#getFailedRecipient--) | Failed recipient |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) | Gets a message that describes the current exception. |
| [getOperationDetails()](#getOperationDetails--) | Gets extra information aboout error |
| [getStackTrace()](#getStackTrace--) |  |
| [getStatusCode()](#getStatusCode--) | Smtp status code |
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
| [setStatusCode(int value)](#setStatusCode-int-) | Smtp status code |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmtpFailedRecipientException() {#SmtpFailedRecipientException--}
```
public SmtpFailedRecipientException()
```


Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class

### SmtpFailedRecipientException(String message) {#SmtpFailedRecipientException-java.lang.String-}
```
public SmtpFailedRecipientException(String message)
```


Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |

### SmtpFailedRecipientException(String message, Throwable innerException) {#SmtpFailedRecipientException-java.lang.String-java.lang.Throwable-}
```
public SmtpFailedRecipientException(String message, Throwable innerException)
```


Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |
| innerException | java.lang.Throwable | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### SmtpFailedRecipientException(int statusCode, String failedRecipient) {#SmtpFailedRecipientException-int-java.lang.String-}
```
public SmtpFailedRecipientException(int statusCode, String failedRecipient)
```


Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| statusCode | int | Status code |
| failedRecipient | java.lang.String | Failed recipient |

### SmtpFailedRecipientException(int statusCode, String failedRecipient, String serverResponse) {#SmtpFailedRecipientException-int-java.lang.String-java.lang.String-}
```
public SmtpFailedRecipientException(int statusCode, String failedRecipient, String serverResponse)
```


Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| statusCode | int | Status code |
| failedRecipient | java.lang.String | Failed recipient |
| serverResponse | java.lang.String | Server response |

### SmtpFailedRecipientException(String message, String failedRecipient, System.Exception innerException) {#SmtpFailedRecipientException-java.lang.String-java.lang.String-com.aspose.ms.System.Exception-}
```
public SmtpFailedRecipientException(String message, String failedRecipient, System.Exception innerException)
```


Initializes a new instance of the [SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |
| failedRecipient | java.lang.String | Failed recipient |
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
### getFailedRecipient() {#getFailedRecipient--}
```
public final String getFailedRecipient()
```


Failed recipient

**Returns:**
java.lang.String
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
### getOperationDetails() {#getOperationDetails--}
```
public final SendMessagesResult getOperationDetails()
```


Gets extra information aboout error

**Returns:**
[SendMessagesResult](../../com.aspose.email/sendmessagesresult)
### getStackTrace() {#getStackTrace--}
```
public StackTraceElement[] getStackTrace()
```




**Returns:**
java.lang.StackTraceElement[]
### getStatusCode() {#getStatusCode--}
```
public final int getStatusCode()
```


Smtp status code

**Returns:**
int
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

### setStatusCode(int value) {#setStatusCode-int-}
```
public final void setStatusCode(int value)
```


Smtp status code

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

