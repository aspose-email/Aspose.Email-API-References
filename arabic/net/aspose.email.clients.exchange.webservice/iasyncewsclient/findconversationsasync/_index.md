---
title: FindConversationsAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: البحث عن المحادثات في المجلد المحدد
type: docs
weight: 290
url: /ar/net/aspose.email.clients.exchange.webservice/iasyncewsclient/findconversationsasync/
---
## IAsyncEwsClient.FindConversationsAsync method

البحث عن المحادثات في المجلد المحدد

```csharp
public Task<ExchangeConversation[]> FindConversationsAsync(string folderId, 
    CancellationToken cancellationToken = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderId | String | معرف المجلد الذي البحث فيه |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

وجدت مجموعة من[`ExchangeConversation`](../../exchangeconversation)

### استثناءات

| استثناء | حالة |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *folderId* هو`لا شيء`أو`فارغة` |

### أنظر أيضا

* class [ExchangeConversation](../../exchangeconversation)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->