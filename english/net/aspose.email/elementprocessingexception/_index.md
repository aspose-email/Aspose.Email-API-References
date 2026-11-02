---
title: Class ElementProcessingException
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.ElementProcessingException class. The exception recorded when one element of a batch operation fails such as one message of a set being fetched the other elements are still processed
type: docs
weight: 16010
url: /net/aspose.email/elementprocessingexception/
---
## ElementProcessingException class

The exception recorded when one element of a batch operation fails, such as one message of a set being fetched; the other elements are still processed.

```csharp
public class ElementProcessingException : AsposeException
```

## Constructors

| Name | Description |
| --- | --- |
| [ElementProcessingException](elementprocessingexception/)(int, Exception) | Initializes a new instance of the `ElementProcessingException` class for the element at the specified index. |

## Properties

| Name | Description |
| --- | --- |
| [ElementIndex](../../aspose.email/elementprocessingexception/elementindex/) { get; } | Gets the zero-based index of the element that failed. |
| [ErrorDetails](../../aspose.email/asposeexception/errordetails/) { get; } | Gets additional information about the error, if the operation provides any. |
| override [Message](../../aspose.email/asposeexception/message/) { get; } | Gets the message that describes the error. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.email/asposeexception/tostring/)() | Returns the type, the message and the stack trace of the exception. |

### See Also

* class [AsposeException](../asposeexception/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


