---
title: ListMessagesByPageAsync
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen klasördeki iletileri listeleyin.
type: docs
weight: 460
url: /tr/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync/
---
## ListMessagesByPageAsync(string, int, int, MailQuery, CancellationToken) {#listmessagesbypageasync_1}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public Task<ExchangeMessagePageInfo> ListMessagesByPageAsync(string folder, int itemsPerPage, 
    int offset = 0, MailQuery query = null, CancellationToken cancellationToken = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| itemsPerPage | Int32 | Sayfadaki bir dizi öğe |
| offset | Int32 | Görünümdeki sonraki sayfanın bir ofseti |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) Bu, arama kriterlerini temsil eder. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesByPageAsync(string, PageInfo, CancellationToken) {#listmessagesbypageasync}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public Task<ExchangeMessagePageInfo> ListMessagesByPageAsync(string folder, PageInfo pageInfo, 
    CancellationToken cancellationToken = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| pageInfo | PageInfo | Bir sayfa bilgisi |
| cancellationToken | CancellationToken | İptal belirteci. |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->