---
title: Enum MapiRecipientType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiRecipientType enum. Defines the types of message recipients the PR_RECIPIENT_TYPE property
type: docs
weight: 17500
url: /net/aspose.email.mapi/mapirecipienttype/
---
## MapiRecipientType enumeration

Defines the types of message recipients (the `PR_RECIPIENT_TYPE` property).

```csharp
public enum MapiRecipientType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| MAPI_BCC | `3` | A blind carbon copy (BCC) recipient. The other recipients do not see BCC recipients. |
| MAPI_CC | `2` | A carbon copy (CC) recipient. |
| MAPI_P1 | `268435456` | The recipient did not receive the message on a previous attempt; the message is resent. |
| MAPI_SUBMITTED | `-2147483648` | The recipient has already received the message and does not need it again; the message is resent. Combined with `MAPI_TO`, `MAPI_CC` or `MAPI_BCC`. |
| MAPI_TO | `1` | A primary (To) recipient. |
| Unknown | `-1` | The type is unknown. |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


