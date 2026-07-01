---
title: Class GraphThrottlingException
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Graph.GraphThrottlingException class. Represents a Microsoft Graph throttling or transient service response
type: docs
weight: 14670
url: /net/aspose.email.clients.graph/graphthrottlingexception/
---
## GraphThrottlingException class

Represents a Microsoft Graph throttling or transient service response.

```csharp
public class GraphThrottlingException : Exception
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphThrottlingException](graphthrottlingexception/)(HttpStatusCode, string, TimeSpan?, int, WebHeaderCollection, string) | Initializes a new instance of the `GraphThrottlingException` class. |

## Properties

| Name | Description |
| --- | --- |
| [ClientRequestId](../../aspose.email.clients.graph/graphthrottlingexception/clientrequestid/) { get; } | Gets the client request identifier, when present. |
| [Headers](../../aspose.email.clients.graph/graphthrottlingexception/headers/) { get; } | Gets response headers captured from the throttling response. |
| [RequestId](../../aspose.email.clients.graph/graphthrottlingexception/requestid/) { get; } | Gets the Microsoft Graph request identifier, when present. |
| [RetryAfter](../../aspose.email.clients.graph/graphthrottlingexception/retryafter/) { get; } | Gets the Retry-After value returned by Microsoft Graph, when present. |
| [RetryAfterHeader](../../aspose.email.clients.graph/graphthrottlingexception/retryafterheader/) { get; } | Gets the raw Retry-After header value returned by Microsoft Graph, when present. |
| [RetryAttempts](../../aspose.email.clients.graph/graphthrottlingexception/retryattempts/) { get; } | Gets the number of retry attempts that were performed before the exception was raised. |
| [StatusCode](../../aspose.email.clients.graph/graphthrottlingexception/statuscode/) { get; } | Gets the HTTP status code returned by Microsoft Graph. |
| [StatusDescription](../../aspose.email.clients.graph/graphthrottlingexception/statusdescription/) { get; } | Gets the HTTP status description returned by Microsoft Graph. |

### See Also

* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph/)
* assembly [Aspose.Email](../../)


