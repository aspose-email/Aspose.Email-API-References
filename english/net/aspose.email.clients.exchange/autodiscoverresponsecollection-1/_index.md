---
title: Class AutodiscoverResponseCollectionTResponse
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.AutodiscoverResponseCollection1TResponse class. Represents a collection of responses to a call to the Autodiscover service
type: docs
weight: 3090
url: /net/aspose.email.clients.exchange/autodiscoverresponsecollection-1/
---
## AutodiscoverResponseCollection&lt;TResponse&gt; class

Represents a collection of responses to a call to the Autodiscover service.

```csharp
public abstract class AutodiscoverResponseCollection<TResponse> : AutodiscoverResponse, 
    IEnumerable<TResponse>
    where TResponse : AutodiscoverResponse
```

| Parameter | Description |
| --- | --- |
| TResponse | The type of the responses in the collection. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.email.clients.exchange/autodiscoverresponsecollection-1/count/) { get; } | Gets the number of responses in the collection. |
| [ErrorCode](../../aspose.email.clients.exchange/autodiscoverresponse/errorcode/) { get; } | Gets the error code that was returned by the service. |
| [ErrorMessage](../../aspose.email.clients.exchange/autodiscoverresponse/errormessage/) { get; } | Gets the error message that was returned by the service. |
| [Item](../../aspose.email.clients.exchange/autodiscoverresponsecollection-1/item/) { get; } | Gets the response at the specified index. |

## Methods

| Name | Description |
| --- | --- |
| [GetEnumerator](../../aspose.email.clients.exchange/autodiscoverresponsecollection-1/getenumerator/)() | Gets an enumerator that iterates through the elements of the collection. |

### See Also

* class [AutodiscoverResponse](../autodiscoverresponse/)
* namespace [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange/)
* assembly [Aspose.Email](../../)


