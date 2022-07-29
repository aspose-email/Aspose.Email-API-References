---
title: GetMessageThreadsAsync
second_title: Aspose.Email for .NET API Referansı
description: İleti dizilerini alın.
type: docs
weight: 170
url: /tr/net/aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync/
---
## IAsyncImapClient.GetMessageThreadsAsync method

İleti dizilerini alın.

```csharp
public Task<IEnumerable<MessageThreadResult>> GetMessageThreadsAsync(
    BaseSearchConditions conditions, IConnection connection = null, 
    CancellationToken token = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | BaseSearchConditions | Bir sunucuya bağlantı |
| conditions | IConnection | İplik koşulları. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Mesaj dizileri

### Ayrıca bakınız

* class [MessageThreadResult](../../messagethreadresult)
* class [BaseSearchConditions](../../basesearchconditions)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->