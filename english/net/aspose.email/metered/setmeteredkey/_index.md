---
title: Metered.SetMeteredKey
second_title: Aspose.Email for .NET API Reference
description: Metered method. Activates the metered license with the public and private keys
type: docs
weight: 40
url: /net/aspose.email/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Activates the metered license with the public and private keys.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | String | The public key. |
| privateKey | String | The private key. |

## Remarks

Call it once at application start. If the consumption data cannot be uploaded for more than 24 hours, the license falls back to evaluation mode; check [`IsMeteredLicensed`](../ismeteredlicensed/) periodically and call this method again if needed.

### See Also

* class [Metered](../)
* namespace [Aspose.Email](../../metered/)
* assembly [Aspose.Email](../../../)


