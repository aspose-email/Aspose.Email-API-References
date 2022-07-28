---
title: UpdateItemsAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يقوم بتحديث العناصر المحددة في صندوق البريد.
type: docs
weight: 690
url: /ar/net/aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemsasync/
---
## IAsyncEwsClient.UpdateItemsAsync method

يقوم بتحديث العناصر المحددة في صندوق البريد.

```csharp
public Task<IEnumerable<ExchangeUploadItemResult>> UpdateItemsAsync(
    IEnumerable<ExchangeStreamedItem> items, CancellationToken cancellationToken = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| items | IEnumerable`1 | العناصر المراد تحديثها. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مجموعة من[`ExchangeUploadItemResult`](../../exchangeuploaditemresult)

### استثناءات

| استثناء | حالة |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *items* هو`لا شيء` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *items* هو`فارغة` |

### أنظر أيضا

* class [ExchangeUploadItemResult](../../exchangeuploaditemresult)
* class [ExchangeStreamedItem](../../exchangestreameditem)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->