---
title: Class AsposeException
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.AsposeException class. The base class of the exceptions thrown by Aspose.Email
type: docs
weight: 280
url: /net/aspose.email/asposeexception/
---
## AsposeException class

The base class of the exceptions thrown by Aspose.Email.

```csharp
public class AsposeException : Exception
```

## Constructors

| Name | Description |
| --- | --- |
| [AsposeException](asposeexception/#constructor)() | Initializes a new instance of the `AsposeException` class. |
| [AsposeException](asposeexception/#constructor_1)(Exception) | Initializes a new instance of the `AsposeException` class with a reference to the exception that caused it. |
| [AsposeException](asposeexception/#constructor_2)(string) | Initializes a new instance of the `AsposeException` class with the specified error message. |
| [AsposeException](asposeexception/#constructor_3)(string, Exception) | Initializes a new instance of the `AsposeException` class with the specified error message and a reference to the exception that caused it. |
| [AsposeException](asposeexception/#constructor_4)(string, params object[]) | Initializes a new instance of the `AsposeException` class with an error message built from a composite format string. |
| [AsposeException](asposeexception/#constructor_5)(string, string) | Initializes a new instance of the `AsposeException` class with an error message built from a format string with one argument. |

## Properties

| Name | Description |
| --- | --- |
| [ErrorDetails](../../aspose.email/asposeexception/errordetails/) { get; } | Gets additional information about the error, if the operation provides any. |
| override [Message](../../aspose.email/asposeexception/message/) { get; } | Gets the message that describes the error. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.email/asposeexception/tostring/)() | Returns the type, the message and the stack trace of the exception. |

## Remarks

Catch this type to handle any error that the library reports with its own exception types, such as [`FormatNotSupportedException`](../formatnotsupportedexception/), [`SmtpException`](../smtpexception/) or [`ImapException`](../imapexception/).

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


