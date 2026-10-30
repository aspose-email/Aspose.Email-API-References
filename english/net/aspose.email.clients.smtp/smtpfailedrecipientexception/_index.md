---
title: Class SmtpFailedRecipientException
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Smtp.SmtpFailedRecipientException class. Represents the exception which arises when the specified recipient is wrong
type: docs
weight: 15850
url: /net/aspose.email.clients.smtp/smtpfailedrecipientexception/
---
## SmtpFailedRecipientException class

Represents the exception which arises when the specified recipient is wrong

```csharp
public class SmtpFailedRecipientException : SmtpException
```

## Constructors

| Name | Description |
| --- | --- |
| [SmtpFailedRecipientException](smtpfailedrecipientexception/#constructor)() | Initializes a new instance of the `SmtpFailedRecipientException` class |
| [SmtpFailedRecipientException](smtpfailedrecipientexception/#constructor_3)(string) | Initializes a new instance of the `SmtpFailedRecipientException` class |
| [SmtpFailedRecipientException](smtpfailedrecipientexception/#constructor_1)(SmtpStatusCode, string) | Initializes a new instance of the `SmtpFailedRecipientException` class |
| [SmtpFailedRecipientException](smtpfailedrecipientexception/#constructor_4)(string, Exception) | Initializes a new instance of the `SmtpFailedRecipientException` class |
| [SmtpFailedRecipientException](smtpfailedrecipientexception/#constructor_2)(SmtpStatusCode, string, string) | Initializes a new instance of the `SmtpFailedRecipientException` class |
| [SmtpFailedRecipientException](smtpfailedrecipientexception/#constructor_5)(string, string, Exception) | Initializes a new instance of the `SmtpFailedRecipientException` class |

## Properties

| Name | Description |
| --- | --- |
| [ErrorDetails](../../aspose.email/asposeexception/errordetails/) { get; } | Gets additional information about the error, if the operation provides any. |
| [FailedRecipient](../../aspose.email.clients.smtp/smtpfailedrecipientexception/failedrecipient/) { get; } | Failed recipient |
| override [Message](../../aspose.email/asposeexception/message/) { get; } | Gets the message that describes the error. |
| [OperationDetails](../../aspose.email/smtpexception/operationdetails/) { get; } | Gets the result of the operation: the messages that were sent and the messages that failed, with their errors. |
| [StatusCode](../../aspose.email/smtpexception/statuscode/) { get; set; } | Gets or sets the SMTP status code returned by the server. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.email/asposeexception/tostring/)() | Returns the type, the message and the stack trace of the exception. |

### See Also

* class [SmtpException](../../aspose.email/smtpexception/)
* namespace [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp/)
* assembly [Aspose.Email](../../)


