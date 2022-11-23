---
title: SmtpException
second_title: Aspose.Email for Java API Reference
description: Represents the exception that is thrown when the SmtpClient is not able to complete an operation.
type: docs
weight: 635
url: /java/com.aspose.email/smtpexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class SmtpException extends AsposeException
```

Represents the exception that is thrown when the SmtpClient is not able to complete an operation.
## Constructors

| Constructor | Description |
| --- | --- |
| [SmtpException(int statusCode)](#SmtpException-int-) | Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class |
| [SmtpException(int statusCode, String message)](#SmtpException-int-java.lang.String-) | Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class |
| [SmtpException()](#SmtpException--) | Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class |
| [SmtpException(String message)](#SmtpException-java.lang.String-) | Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class |
| [SmtpException(String message, SendMessagesResult result)](#SmtpException-java.lang.String-com.aspose.email.SendMessagesResult-) | Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class |
| [SmtpException(String message, Throwable innerException)](#SmtpException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class |
| [SmtpException(String message, Throwable innerException, MailMessage mailMessage)](#SmtpException-java.lang.String-java.lang.Throwable-com.aspose.email.MailMessage-) | Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class |
| [SmtpException(String message, MailMessage mailMessage)](#SmtpException-java.lang.String-com.aspose.email.MailMessage-) | Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class |
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
### SmtpException(int statusCode) {#SmtpException-int-}
```
public SmtpException(int statusCode)
```


Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| statusCode | int | Smtp status code |

### SmtpException(int statusCode, String message) {#SmtpException-int-java.lang.String-}
```
public SmtpException(int statusCode, String message)
```


Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| statusCode | int | Smtp status code |
| message | java.lang.String | Error message |

### SmtpException() {#SmtpException--}
```
public SmtpException()
```


Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class

### SmtpException(String message) {#SmtpException-java.lang.String-}
```
public SmtpException(String message)
```


Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |

### SmtpException(String message, SendMessagesResult result) {#SmtpException-java.lang.String-com.aspose.email.SendMessagesResult-}
```
public SmtpException(String message, SendMessagesResult result)
```


Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |
| result | [SendMessagesResult](../../com.aspose.email/sendmessagesresult) | Operation result |

### SmtpException(String message, Throwable innerException) {#SmtpException-java.lang.String-java.lang.Throwable-}
```
public SmtpException(String message, Throwable innerException)
```


Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |
| innerException | java.lang.Throwable | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### SmtpException(String message, Throwable innerException, MailMessage mailMessage) {#SmtpException-java.lang.String-java.lang.Throwable-com.aspose.email.MailMessage-}
```
public SmtpException(String message, Throwable innerException, MailMessage mailMessage)
```


Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |
| innerException | java.lang.Throwable | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |
| mailMessage | [MailMessage](../../com.aspose.email/mailmessage) |  |

### SmtpException(String message, MailMessage mailMessage) {#SmtpException-java.lang.String-com.aspose.email.MailMessage-}
```
public SmtpException(String message, MailMessage mailMessage)
```


Initializes a new instance of the [SmtpException](../../com.aspose.email/smtpexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |
| mailMessage | [MailMessage](../../com.aspose.email/mailmessage) |  |

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

