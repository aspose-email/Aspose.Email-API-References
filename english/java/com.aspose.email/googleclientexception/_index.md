---
title: GoogleClientException
second_title: Aspose.Email for Java API Reference
description: Represents errors that occur during ActiveSync protocol execution.
type: docs
weight: 278
url: /java/com.aspose.email/googleclientexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class GoogleClientException extends AsposeException
```

Represents errors that occur during ActiveSync protocol execution.

 1 
## Constructors

| Constructor | Description |
| --- | --- |
| [GoogleClientException(String message)](#GoogleClientException-java.lang.String-) | Initializes a new instance of the [GoogleClientException](../../com.aspose.email/googleclientexception) class with a specified error message. |
| [GoogleClientException()](#GoogleClientException--) | Initializes a new instance of the [GoogleClientException](../../com.aspose.email/googleclientexception) class. |
| [GoogleClientException(String message, Throwable innerException)](#GoogleClientException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the [GoogleClientException](../../com.aspose.email/googleclientexception) class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| [GoogleClientException(Throwable innerException)](#GoogleClientException-java.lang.Throwable-) | Initializes a new instance of the [GoogleClientException](../../com.aspose.email/googleclientexception) class with a reference to the inner exception that is the cause of this exception. |
## Methods

| Method | Description |
| --- | --- |
| [getErrorCode()](#getErrorCode--) | Returns a code of error. |
### GoogleClientException(String message) {#GoogleClientException-java.lang.String-}
```
public GoogleClientException(String message)
```


Initializes a new instance of the [GoogleClientException](../../com.aspose.email/googleclientexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A message that describes the error. |

### GoogleClientException() {#GoogleClientException--}
```
public GoogleClientException()
```


Initializes a new instance of the [GoogleClientException](../../com.aspose.email/googleclientexception) class.

### GoogleClientException(String message, Throwable innerException) {#GoogleClientException-java.lang.String-java.lang.Throwable-}
```
public GoogleClientException(String message, Throwable innerException)
```


Initializes a new instance of the [GoogleClientException](../../com.aspose.email/googleclientexception) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message that explains the reason for the exception. |
| innerException | java.lang.Throwable | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### GoogleClientException(Throwable innerException) {#GoogleClientException-java.lang.Throwable-}
```
public GoogleClientException(Throwable innerException)
```


Initializes a new instance of the [GoogleClientException](../../com.aspose.email/googleclientexception) class with a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| innerException | java.lang.Throwable | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### getErrorCode() {#getErrorCode--}
```
public final int getErrorCode()
```


Returns a code of error.

**Returns:**
int
