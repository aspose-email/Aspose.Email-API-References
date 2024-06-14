---
title: MapiRecipientType
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 1150
url: /python-net/aspose.email.mapi/mapirecipienttype/
---

## MapiRecipientType enumeration

Represent the PR_RECIPIENT_TYPE property which contains the recipient type for a message recipient.

## Members
| Member name | Description |
| :- | :- |
|BCC|The recipient is a blind carbon copy (BCC) recipient. Primary and carbon copy recipients are unaware of the existence of BCC recipients.|
|CC|The recipient is a carbon copy (CC) recipient, a recipient that receives a message in addition to the primary recipients.|
|P1|The recipient did not successfully receive the message on the previous attempt. This is a resend of an earlier transmission.|
|SUBMITTED|The recipient has already received the message and does not need to receive it again. This is a resend of an earlier transmission. This flag is set in conjunction with the MAPI_TO, MAPI_CC, and MAPI_BCC values.|
|TO|The recipient is a primary (To) recipient. Clients are required to handle primary recipients; all other types are optional.|
|UNKNOWN|Unknow.|

### See Also

* namespace [aspose.email.mapi](/email/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/email/python-net/)

