---
title: ExistFolderAsync
second_title: Aspose.Email for .NET API Referansı
description: Bu klasörün var olup olmadığını kontrol edin
type: docs
weight: 130
url: /tr/net/aspose.email.clients.imap/iasyncimapclient/existfolderasync/
---
## IAsyncImapClient.ExistFolderAsync method

Bu klasörün var olup olmadığını kontrol edin

```csharp
public Task<bool> ExistFolderAsync(string folderName, IConnection connection = null, 
    CancellationToken token = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | String | Bir sunucuya bağlantı |
| folderName | IConnection | Klasörün adı |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Klasör varsa true, aksi takdirde false döndürür

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->