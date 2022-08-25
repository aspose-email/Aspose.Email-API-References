---
title: AsposeNotSupportedException
second_title: Aspose.Email for Android via Java API Reference
description:  The exception that is thrown when an invoked method or parameter is not supported 
 or when there is an attempt to read seek or write to a stream that does not support the invoked functionality.
type: docs
weight: 48
url: /java/com.aspose.email/asposenotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class AsposeNotSupportedException extends AsposeException
```

The exception that is thrown when an invoked method or parameter is not supported, or when there is an attempt to read, seek, or write to a stream that does not support the invoked functionality.

\`\`\` 1 \`\`\`
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
| [getMessage()](#getMessage--) | Gets a message that describes the current exception. |
| [toString()](#toString--) | Returns a string that represents the current object. |
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
