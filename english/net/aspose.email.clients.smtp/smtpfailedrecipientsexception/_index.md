---
title: Class SmtpFailedRecipientsException
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Smtp.SmtpFailedRecipientsException class. Summary description for SmtpFailedRecipientsException
type: docs
weight: 15860
url: /net/aspose.email.clients.smtp/smtpfailedrecipientsexception/
---
## SmtpFailedRecipientsException class

Summary description for SmtpFailedRecipientsException.

```csharp
public class SmtpFailedRecipientsException : SmtpFailedRecipientException
```

## Constructors

| Name | Description |
| --- | --- |
| [SmtpFailedRecipientsException](smtpfailedrecipientsexception/#constructor)() | Initializes a new instance of the `SmtpFailedRecipientsException` class |
| [SmtpFailedRecipientsException](smtpfailedrecipientsexception/#constructor_1)(string) | Initializes a new instance of the `SmtpFailedRecipientsException` class |
| [SmtpFailedRecipientsException](smtpfailedrecipientsexception/#constructor_3)(string, Exception) | Initializes a new instance of the `SmtpFailedRecipientsException` class |
| [SmtpFailedRecipientsException](smtpfailedrecipientsexception/#constructor_2)(string, SmtpFailedRecipientException[]) | Initializes a new instance of the `SmtpFailedRecipientsException` class |

## Properties

| Name | Description |
| --- | --- |
| [ErrorDetails](../../aspose.email/asposeexception/errordetails/) { get; } | Gets additional information about the error, if the operation provides any. |
| [FailedRecipient](../../aspose.email.clients.smtp/smtpfailedrecipientexception/failedrecipient/) { get; } | Failed recipient |
| [InnerExceptions](../../aspose.email.clients.smtp/smtpfailedrecipientsexception/innerexceptions/) { get; } | Array of inner exceptions |
| override [Message](../../aspose.email/asposeexception/message/) { get; } | Gets the message that describes the error. |
| [OperationDetails](../../aspose.email/smtpexception/operationdetails/) { get; } | Gets the result of the operation: the messages that were sent and the messages that failed, with their errors. |
| [StatusCode](../../aspose.email/smtpexception/statuscode/) { get; set; } | Gets or sets the SMTP status code returned by the server. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.email/asposeexception/tostring/)() | Returns the type, the message and the stack trace of the exception. |

### See Also

* class [SmtpFailedRecipientException](../smtpfailedrecipientexception/)
* namespace [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp/)
* assembly [Aspose.Email](../../)


