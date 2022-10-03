---
title: SSPIException
second_title: Aspose.Email for Java API Reference
description: Represents errors that occur during SSPI execution.
type: docs
weight: 610
url: /java/com.aspose.email/sspiexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class SSPIException extends AsposeException
```

Represents errors that occur during SSPI execution.

 1 
## Constructors

| Constructor | Description |
| --- | --- |
| [SSPIException(String message)](#SSPIException-java.lang.String-) | Initializes a new instance of the [SSPIException](../../com.aspose.email/sspiexception) class with a specified error message. |
| [SSPIException(String format, Object[] parameters)](#SSPIException-java.lang.String-java.lang.Object...-) | Initializes a new instance of the [SSPIException](../../com.aspose.email/sspiexception) class with a specified error message. |
| [SSPIException()](#SSPIException--) | Initializes a new instance of the [SSPIException](../../com.aspose.email/sspiexception) class. |
| [SSPIException(String message, System.Exception innerException)](#SSPIException-java.lang.String-com.aspose.ms.System.Exception-) | Initializes a new instance of the [SSPIException](../../com.aspose.email/sspiexception) class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| [SSPIException(System.Exception innerException)](#SSPIException-com.aspose.ms.System.Exception-) | Initializes a new instance of the [SSPIException](../../com.aspose.email/sspiexception) class with a reference to the inner exception that is the cause of this exception. |
## Methods

| Method | Description |
| --- | --- |
| [getErrorCode()](#getErrorCode--) | Returns a code of error. |
### SSPIException(String message) {#SSPIException-java.lang.String-}
```
public SSPIException(String message)
```


Initializes a new instance of the [SSPIException](../../com.aspose.email/sspiexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A message that describes the error. |

### SSPIException(String format, Object[] parameters) {#SSPIException-java.lang.String-java.lang.Object...-}
```
public SSPIException(String format, Object[] parameters)
```


Initializes a new instance of the [SSPIException](../../com.aspose.email/sspiexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | Message format |
| parameters | java.lang.Object[] | Format parameters |

### SSPIException() {#SSPIException--}
```
public SSPIException()
```


Initializes a new instance of the [SSPIException](../../com.aspose.email/sspiexception) class.

### SSPIException(String message, System.Exception innerException) {#SSPIException-java.lang.String-com.aspose.ms.System.Exception-}
```
public SSPIException(String message, System.Exception innerException)
```


Initializes a new instance of the [SSPIException](../../com.aspose.email/sspiexception) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message that explains the reason for the exception. |
| innerException | com.aspose.ms.System.Exception | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### SSPIException(System.Exception innerException) {#SSPIException-com.aspose.ms.System.Exception-}
```
public SSPIException(System.Exception innerException)
```


Initializes a new instance of the [SSPIException](../../com.aspose.email/sspiexception) class with a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| innerException | com.aspose.ms.System.Exception | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### getErrorCode() {#getErrorCode--}
```
public final int getErrorCode()
```


Returns a code of error.

**Returns:**
int
