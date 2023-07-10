---
title: SmtpFailedRecipientsException
second_title: Aspose.Email for Java API Reference
description: Summary description for SmtpFailedRecipientsException.
type: docs
weight: 645
url: /java/com.aspose.email/smtpfailedrecipientsexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception), [com.aspose.email.SmtpException](../../com.aspose.email/smtpexception), [com.aspose.email.SmtpFailedRecipientException](../../com.aspose.email/smtpfailedrecipientexception)
```
public class SmtpFailedRecipientsException extends SmtpFailedRecipientException
```

Summary description for SmtpFailedRecipientsException.
## Constructors

| Constructor | Description |
| --- | --- |
| [SmtpFailedRecipientsException()](#SmtpFailedRecipientsException--) | Initializes a new instance of the [SmtpFailedRecipientsException](../../com.aspose.email/smtpfailedrecipientsexception) class |
| [SmtpFailedRecipientsException(String message)](#SmtpFailedRecipientsException-java.lang.String-) | Initializes a new instance of the [SmtpFailedRecipientsException](../../com.aspose.email/smtpfailedrecipientsexception) class |
| [SmtpFailedRecipientsException(String message, Throwable innerException)](#SmtpFailedRecipientsException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the [SmtpFailedRecipientsException](../../com.aspose.email/smtpfailedrecipientsexception) class |
| [SmtpFailedRecipientsException(String message, SmtpFailedRecipientException[] innerExceptions)](#SmtpFailedRecipientsException-java.lang.String-com.aspose.email.SmtpFailedRecipientException---) | Initializes a new instance of the [SmtpFailedRecipientsException](../../com.aspose.email/smtpfailedrecipientsexception) class |
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
| [getInnerExceptions()](#getInnerExceptions--) | Array of inner exceptions |
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
### SmtpFailedRecipientsException() {#SmtpFailedRecipientsException--}
```
public SmtpFailedRecipientsException()
```


Initializes a new instance of the [SmtpFailedRecipientsException](../../com.aspose.email/smtpfailedrecipientsexception) class

### SmtpFailedRecipientsException(String message) {#SmtpFailedRecipientsException-java.lang.String-}
```
public SmtpFailedRecipientsException(String message)
```


Initializes a new instance of the [SmtpFailedRecipientsException](../../com.aspose.email/smtpfailedrecipientsexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |

### SmtpFailedRecipientsException(String message, Throwable innerException) {#SmtpFailedRecipientsException-java.lang.String-java.lang.Throwable-}
```
public SmtpFailedRecipientsException(String message, Throwable innerException)
```


Initializes a new instance of the [SmtpFailedRecipientsException](../../com.aspose.email/smtpfailedrecipientsexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |
| innerException | java.lang.Throwable | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### SmtpFailedRecipientsException(String message, SmtpFailedRecipientException[] innerExceptions) {#SmtpFailedRecipientsException-java.lang.String-com.aspose.email.SmtpFailedRecipientException---}
```
public SmtpFailedRecipientsException(String message, SmtpFailedRecipientException[] innerExceptions)
```


Initializes a new instance of the [SmtpFailedRecipientsException](../../com.aspose.email/smtpfailedrecipientsexception) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Error message |
| innerExceptions | [SmtpFailedRecipientException\[\]](../../com.aspose.email/smtpfailedrecipientexception) | The list of exceptions that is the cause of the current exception. |

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
### getInnerExceptions() {#getInnerExceptions--}
```
public final SmtpFailedRecipientException[] getInnerExceptions()
```


Array of inner exceptions

**Returns:**
com.aspose.email.SmtpFailedRecipientException[]
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

