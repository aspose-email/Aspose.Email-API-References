---
title: Enum CanonicalizationType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.DKIM.CanonicalizationType enum. Normalization applied to the headers and body before they are hashed for a DKIM signature
type: docs
weight: 17360
url: /net/aspose.email.dkim/canonicalizationtype/
---
## CanonicalizationType enumeration

Normalization applied to the headers and body before they are hashed for a DKIM signature.

```csharp
public enum CanonicalizationType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Simple | `0` | Almost nothing may change in transit, so any reformatting of the headers or body breaks the signature. |
| Relaxed | `1` | Minor reformatting is tolerated, so extra spaces or refolded headers do not break the signature. |

### See Also

* namespace [Aspose.Email.DKIM](../../aspose.email.dkim/)
* assembly [Aspose.Email](../../)


