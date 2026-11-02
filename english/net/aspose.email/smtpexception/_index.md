---
title: Class SmtpException
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.SmtpException class. The exception that is thrown when an SMTP client cannot complete an operation
type: docs
weight: 18850
url: /net/aspose.email/smtpexception/
---
## SmtpException class

The exception that is thrown when an SMTP client cannot complete an operation.

```csharp
public class SmtpException : AsposeException
```

## Constructors

| Name | Description |
| --- | --- |
| [SmtpException](smtpexception/#constructor)() | Initializes a new instance of the `SmtpException` class. |
| [SmtpException](smtpexception/#constructor_1)(SmtpStatusCode) | Initializes a new instance of the `SmtpException` class with the status code returned by the server. |
| [SmtpException](smtpexception/#constructor_3)(string) | Initializes a new instance of the `SmtpException` class with the specified error message. |
| [SmtpException](smtpexception/#constructor_2)(SmtpStatusCode, string) | Initializes a new instance of the `SmtpException` class with the status code returned by the server and an error message. |
| [SmtpException](smtpexception/#constructor_6)(string, Exception) | Initializes a new instance of the `SmtpException` class with the specified error message and a reference to the exception that caused it. |
| [SmtpException](smtpexception/#constructor_5)(string, MailMessage) | Initializes a new instance of the `SmtpException` class for a message that could not be sent. |
| [SmtpException](smtpexception/#constructor_4)(string, SendMessagesResult) | Initializes a new instance of the `SmtpException` class with an error message and the result of sending several messages. |
| [SmtpException](smtpexception/#constructor_7)(string, Exception, MailMessage) | Initializes a new instance of the `SmtpException` class for a message that could not be sent. |

## Properties

| Name | Description |
| --- | --- |
| [ErrorDetails](../../aspose.email/asposeexception/errordetails/) { get; } | Gets additional information about the error, if the operation provides any. |
| override [Message](../../aspose.email/asposeexception/message/) { get; } | Gets the message that describes the error. |
| [OperationDetails](../../aspose.email/smtpexception/operationdetails/) { get; } | Gets the result of the operation: the messages that were sent and the messages that failed, with their errors. |
| [StatusCode](../../aspose.email/smtpexception/statuscode/) { get; set; } | Gets or sets the SMTP status code returned by the server. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.email/asposeexception/tostring/)() | Returns the type, the message and the stack trace of the exception. |

## Remarks

When several messages are sent at once, [`OperationDetails`](./operationdetails/) tells which messages were sent and which failed.

### See Also

* class [AsposeException](../asposeexception/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


