---
title: Class SmtpException
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.SmtpException class. Represents the exception that is thrown when the SmtpClient is not able to complete an operation
type: docs
weight: 20170
url: /net/aspose.email/smtpexception/
---
## SmtpException class

Represents the exception that is thrown when the SmtpClient is not able to complete an operation.

```csharp
public class SmtpException : AsposeException
```

## Constructors

| Name | Description |
| --- | --- |
| [SmtpException](smtpexception/#constructor)() | Initializes a new instance of the `SmtpException` class |
| [SmtpException](smtpexception/#constructor_1)(SmtpStatusCode) | Initializes a new instance of the `SmtpException` class |
| [SmtpException](smtpexception/#constructor_3)(string) | Initializes a new instance of the `SmtpException` class |
| [SmtpException](smtpexception/#constructor_2)(SmtpStatusCode, string) | Initializes a new instance of the `SmtpException` class |
| [SmtpException](smtpexception/#constructor_6)(string, Exception) | Initializes a new instance of the `SmtpException` class |
| [SmtpException](smtpexception/#constructor_5)(string, MailMessage) |  |
| [SmtpException](smtpexception/#constructor_4)(string, SendMessagesResult) | Initializes a new instance of the `SmtpException` class |
| [SmtpException](smtpexception/#constructor_7)(string, Exception, MailMessage) | Initializes a new instance of the `SmtpException` class |

## Properties

| Name | Description |
| --- | --- |
| [ErrorDetails](../../aspose.email/asposeexception/errordetails/) { get; } | Gets extra information aboout error |
| override [Message](../../aspose.email/asposeexception/message/) { get; } | Gets a message that describes the current exception. |
| [OperationDetails](../../aspose.email/smtpexception/operationdetails/) { get; } | Gets extra information aboout error |
| [StatusCode](../../aspose.email/smtpexception/statuscode/) { get; set; } | Smtp status code |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.email/asposeexception/tostring/)() | Returns a string that represents the current object. |

### See Also

* class [AsposeException](../asposeexception/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


