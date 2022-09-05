---
title: AsposeException
second_title: Aspose.Email for Java API Reference
description:  Base exception type for Aspose.Email 
 Represents errors that occur during application execution.
type: docs
weight: 54
url: /java/com.aspose.email/asposeexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class AsposeException extends System.Exception
```

Base exception type for Aspose.Email Represents errors that occur during application execution.

\`\`\` 1 \`\`\`
## Constructors

| Constructor | Description |
| --- | --- |
| [AsposeException()](#AsposeException--) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class. |
| [AsposeException(String message)](#AsposeException-java.lang.String-) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with a specified error message. |
| [AsposeException(String format, Object[] parameters)](#AsposeException-java.lang.String-java.lang.Object...-) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with a specified error message. |
| [AsposeException(String format, String parameter)](#AsposeException-java.lang.String-java.lang.String-) |  |
| [AsposeException(String message, Throwable innerException)](#AsposeException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| [AsposeException(Throwable innerException)](#AsposeException-java.lang.Throwable-) | Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with a reference to the inner exception that is the cause of this exception. |
## Methods

| Method | Description |
| --- | --- |
| [getMessage()](#getMessage--) | Gets a message that describes the current exception. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [getErrorDetails()](#getErrorDetails--) | Gets extra information aboout error |
### AsposeException() {#AsposeException--}
```
public AsposeException()
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class.

### AsposeException(String message) {#AsposeException-java.lang.String-}
```
public AsposeException(String message)
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message that describes the error. |

### AsposeException(String format, Object[] parameters) {#AsposeException-java.lang.String-java.lang.Object...-}
```
public AsposeException(String format, Object[] parameters)
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | Message format |
| parameters | java.lang.Object[] | Format parameters |

### AsposeException(String format, String parameter) {#AsposeException-java.lang.String-java.lang.String-}
```
public AsposeException(String format, String parameter)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String |  |
| parameter | java.lang.String |  |

### AsposeException(String message, Throwable innerException) {#AsposeException-java.lang.String-java.lang.Throwable-}
```
public AsposeException(String message, Throwable innerException)
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message that explains the reason for the exception. |
| innerException | java.lang.Throwable | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### AsposeException(Throwable innerException) {#AsposeException-java.lang.Throwable-}
```
public AsposeException(Throwable innerException)
```


Initializes a new instance of the [AsposeException](../../com.aspose.email/asposeexception) class with a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| innerException | java.lang.Throwable | The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified. |

### getMessage() {#getMessage--}
```
public String getMessage()
```


Gets a message that describes the current exception.

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
### getErrorDetails() {#getErrorDetails--}
```
public final Object getErrorDetails()
```


Gets extra information aboout error

**Returns:**
java.lang.Object
