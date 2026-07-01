---
title: Class GraphRetryPolicy
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Graph.GraphRetryPolicy class. Configures automatic retry handling for transient Microsoft Graph responses
type: docs
weight: 14660
url: /net/aspose.email.clients.graph/graphretrypolicy/
---
## GraphRetryPolicy class

Configures automatic retry handling for transient Microsoft Graph responses.

```csharp
public class GraphRetryPolicy
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphRetryPolicy](graphretrypolicy/)() | Initializes a new instance of the `GraphRetryPolicy` class. |

## Properties

| Name | Description |
| --- | --- |
| static [Default](../../aspose.email.clients.graph/graphretrypolicy/default/) { get; } | Gets the default Microsoft Graph retry policy. |
| [BaseDelay](../../aspose.email.clients.graph/graphretrypolicy/basedelay/) { get; set; } | Gets or sets the base delay used for exponential backoff when Retry-After is not available. |
| [DelayStrategy](../../aspose.email.clients.graph/graphretrypolicy/delaystrategy/) { get; set; } | Gets or sets the delay strategy. |
| [Enabled](../../aspose.email.clients.graph/graphretrypolicy/enabled/) { get; set; } | Gets or sets a value indicating whether automatic retries are enabled. |
| [MaxDelay](../../aspose.email.clients.graph/graphretrypolicy/maxdelay/) { get; set; } | Gets or sets the maximum delay used for exponential backoff when Retry-After is not available. |
| [MaxRetryAttempts](../../aspose.email.clients.graph/graphretrypolicy/maxretryattempts/) { get; set; } | Gets or sets the maximum number of retry attempts after the initial request. |

### See Also

* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph/)
* assembly [Aspose.Email](../../)


