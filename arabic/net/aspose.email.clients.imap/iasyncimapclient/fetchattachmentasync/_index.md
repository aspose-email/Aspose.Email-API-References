---
title: FetchAttachmentAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يجلب المرفق المحدد .
type: docs
weight: 140
url: /ar/net/aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync/
---
## IAsyncImapClient.FetchAttachmentAsync method

يجلب المرفق المحدد .

```csharp
public Task<Attachment> FetchAttachmentAsync(int sequenceNumber, string attachmentName, 
    IConnection connection = null, CancellationToken token = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | Int32 | الاتصال بالخادم. |
| sequenceNumber | String | الرقم التسلسلي للرسالة. |
| attachmentName | IConnection | اسم المرفق. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

[`Attachment`](../../../aspose.email/attachment) الذي يمثل المرفق.

### أنظر أيضا

* class [Attachment](../../../aspose.email/attachment)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->