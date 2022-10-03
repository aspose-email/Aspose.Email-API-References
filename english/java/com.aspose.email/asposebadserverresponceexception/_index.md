---
title: AsposeBadServerResponceException
second_title: Aspose.Email for Java API Reference
description: Represents errors that occur during server operation execution.
type: docs
weight: 53
url: /java/com.aspose.email/asposebadserverresponceexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class AsposeBadServerResponceException extends AsposeException
```

Represents errors that occur during server operation execution.

 1 
## Constructors

| Constructor | Description |
| --- | --- |
| [AsposeBadServerResponceException(String message)](#AsposeBadServerResponceException-java.lang.String-) | Initializes a new instance of the [AsposeBadServerResponceException](../../com.aspose.email/asposebadserverresponceexception) class with a specified error message. |
| [AsposeBadServerResponceException()](#AsposeBadServerResponceException--) | Initializes a new instance of the [AsposeBadServerResponceException](../../com.aspose.email/asposebadserverresponceexception) class. |
| [AsposeBadServerResponceException(String message, RuntimeException innerException)](#AsposeBadServerResponceException-java.lang.String-java.lang.RuntimeException-) | Initializes a new instance of the [AsposeBadServerResponceException](../../com.aspose.email/asposebadserverresponceexception) class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| [AsposeBadServerResponceException(RuntimeException innerException)](#AsposeBadServerResponceException-java.lang.RuntimeException-) | Initializes a new instance of the [AsposeBadServerResponceException](../../com.aspose.email/asposebadserverresponceexception) class with a reference to the inner exception that is the cause of this exception. |
## Methods

| Method | Description |
| --- | --- |
| [getErrorCode()](#getErrorCode--) | Returns a code of error. |
### AsposeBadServerResponceException(String message) {#AsposeBadServerResponceException-java.lang.String-}
```
public AsposeBadServerResponceException(String message)
```


Initializes a new instance of the [AsposeBadServerResponceException](../../com.aspose.email/asposebadserverresponceexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A message that describes the error. |

### AsposeBadServerResponceException() {#AsposeBadServerResponceException--}
```
public AsposeBadServerResponceException()
```


Initializes a new instance of the [AsposeBadServerResponceException](../../com.aspose.email/asposebadserverresponceexception) class.

### AsposeBadServerResponceException(String message, RuntimeException innerException) {#AsposeBadServerResponceException-java.lang.String-java.lang.RuntimeException-}
```
public AsposeBadServerResponceException(String message, RuntimeException innerException)
```


Initializes a new instance of the [AsposeBadServerResponceException](../../com.aspose.email/asposebadserverresponceexception) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message that explains the reason for the exception. |
| innerException | java.lang.RuntimeException | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### AsposeBadServerResponceException(RuntimeException innerException) {#AsposeBadServerResponceException-java.lang.RuntimeException-}
```
public AsposeBadServerResponceException(RuntimeException innerException)
```


Initializes a new instance of the [AsposeBadServerResponceException](../../com.aspose.email/asposebadserverresponceexception) class with a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| innerException | java.lang.RuntimeException | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### getErrorCode() {#getErrorCode--}
```
public final int getErrorCode()
```


Returns a code of error.

**Returns:**
int
