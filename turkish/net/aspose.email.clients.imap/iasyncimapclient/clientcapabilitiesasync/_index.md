---
title: ClientCapabilitiesAsync
second_title: Aspose.Email for .NET API Referansı
description: İstemci tarafından hangi uzantıların desteklendiğini sunucuya bildirir. Lütfen bu işlemin yalnızca sunucunun RFC5161i desteklemesi durumunda çalıştığını unutmayın Daha fazlasını görün https//tools.ietf.org/html/rfc5161
type: docs
weight: 60
url: /tr/net/aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync/
---
## IAsyncImapClient.ClientCapabilitiesAsync method

İstemci tarafından hangi uzantıların desteklendiğini sunucuya bildirir. Lütfen bu işlemin yalnızca sunucunun RFC5161'i desteklemesi durumunda çalıştığını unutmayın Daha fazlasını görün https://tools.ietf.org/html/rfc5161

```csharp
public Task<IEnumerable<string>> ClientCapabilitiesAsync(IEnumerable<string> capabilityNames, 
    IConnection connection = null, CancellationToken token = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IEnumerable`1 | Bir sunucuya bağlantı |
| token | IConnection | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |
| capabilityNames | CancellationToken | İstemci tarafından desteklenen yetenekler dizisi |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->