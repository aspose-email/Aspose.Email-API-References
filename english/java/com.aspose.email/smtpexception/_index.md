---
title: SmtpException
second_title: Aspose.Email for Java API Reference
description:  Represents the exception that is thrown when the SmtpClient is not able to complete an operation.
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
| [getStatusCode()](#getStatusCode--) | Smtp status code |
| [setStatusCode(int value)](#setStatusCode-int-) | Smtp status code |
| [getOperationDetails()](#getOperationDetails--) | Gets extra information aboout error |
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

### getStatusCode() {#getStatusCode--}
```
public final int getStatusCode()
```


Smtp status code

**Returns:**
int
### setStatusCode(int value) {#setStatusCode-int-}
```
public final void setStatusCode(int value)
```


Smtp status code

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOperationDetails() {#getOperationDetails--}
```
public final SendMessagesResult getOperationDetails()
```


Gets extra information aboout error

**Returns:**
[SendMessagesResult](../../com.aspose.email/sendmessagesresult)
