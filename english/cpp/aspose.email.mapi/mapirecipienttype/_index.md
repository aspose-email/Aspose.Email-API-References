---
title: "MapiRecipientType Enum"
linktitle: "MapiRecipientType"
articleTitle: "MapiRecipientType"
second_title: "Aspose.Email for C++"
description: "Represent the PR_RECIPIENT_TYPE property which contains the recipient type for a message recipient."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapirecipienttype/
---

## MapiRecipientType enumeration (6 values)

Represent the PR_RECIPIENT_TYPE property which contains the recipient type for a message recipient.

| Value | Description |
| --- | --- |
| MAPI_BCC | The recipient is a blind carbon copy (BCC) recipient. Primary and carbon copy recipients are unaware of the existence of BCC recipients. |
| MAPI_CC | The recipient is a carbon copy (CC) recipient, a recipient that receives a message in addition to the primary recipients. |
| MAPI_P1 | The recipient did not successfully receive the message on the previous attempt. This is a resend of an earlier transmission. |
| MAPI_SUBMITTED | The recipient has already received the message and does not need to receive it again. This is a resend of an earlier transmission. This flag is set in conjunction with the MAPI_TO, MAPI_CC, and MAPI_BCC values. |
| MAPI_TO | The recipient is a primary (To) recipient. Clients are required to handle primary recipients; all other types are optional. |
| Unknown | Unknow. |

