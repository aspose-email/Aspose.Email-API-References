---
title: Enum MapiRecipientType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiRecipientType enum. Represent the PR_RECIPIENT_TYPE property which contains the recipient type for a message recipient
type: docs
weight: 18880
url: /net/aspose.email.mapi/mapirecipienttype/
---
## MapiRecipientType enumeration

Represent the PR_RECIPIENT_TYPE property which contains the recipient type for a message recipient.

```csharp
public enum MapiRecipientType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| MAPI_BCC | `3` | The recipient is a blind carbon copy (BCC) recipient. Primary and carbon copy recipients are unaware of the existence of BCC recipients. |
| MAPI_CC | `2` | The recipient is a carbon copy (CC) recipient, a recipient that receives a message in addition to the primary recipients. |
| MAPI_P1 | `268435456` | The recipient did not successfully receive the message on the previous attempt. This is a resend of an earlier transmission. |
| MAPI_SUBMITTED | `-2147483648` | The recipient has already received the message and does not need to receive it again. This is a resend of an earlier transmission. This flag is set in conjunction with the MAPI_TO, MAPI_CC, and MAPI_BCC values. |
| MAPI_TO | `1` | The recipient is a primary (To) recipient. Clients are required to handle primary recipients; all other types are optional. |
| Unknown | `-1` | Unknow. |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


