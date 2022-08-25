---
title: SmtpFailedRecipientException
second_title: Aspose.Email for Java API Reference
description:  Represents the exception which arises when the specified recipient is wrong
type: docs
weight: 636
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
| [getFailedRecipient()](#getFailedRecipient--) | Failed recipient |
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

### getFailedRecipient() {#getFailedRecipient--}
```
public final String getFailedRecipient()
```


Failed recipient

**Returns:**
java.lang.String
