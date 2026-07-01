---
title: Enum GraphRetryDelayStrategy
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Graph.GraphRetryDelayStrategy enum. Specifies how retry delays are calculated for transient Microsoft Graph responses
type: docs
weight: 14650
url: /net/aspose.email.clients.graph/graphretrydelaystrategy/
---
## GraphRetryDelayStrategy enumeration

Specifies how retry delays are calculated for transient Microsoft Graph responses.

```csharp
public enum GraphRetryDelayStrategy
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| RetryAfterThenExponentialBackoffWithJitter | `0` | Uses Retry-After when it is supplied by Microsoft Graph, otherwise falls back to exponential backoff with jitter. |
| RetryAfterOnly | `1` | Uses only Retry-After. If the response does not contain Retry-After, the request is not retried. |
| ExponentialBackoffWithJitter | `2` | Always uses exponential backoff with jitter. |

### See Also

* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph/)
* assembly [Aspose.Email](../../)


