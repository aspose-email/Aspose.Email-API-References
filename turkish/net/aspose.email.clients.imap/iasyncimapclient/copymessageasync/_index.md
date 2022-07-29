---
title: CopyMessageAsync
second_title: Aspose.Email for .NET API Referansı
description: İletiyi kopyalar
type: docs
weight: 80
url: /tr/net/aspose.email.clients.imap/iasyncimapclient/copymessageasync/
---
## CopyMessageAsync(int, string, IConnection, CancellationToken) {#copymessageasync}

İletiyi kopyalar

```csharp
public Task<string> CopyMessageAsync(int sequenceNumber, string folderName, 
    IConnection connection = null, CancellationToken token = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | Int32 | Bir sunucuya bağlantı |
| sequenceNumber | String | Mesajın sıra numarası |
| folderName | IConnection | İletinin kopyalanacağı klasör adı |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Sunucu, UIDPLUS uzantısını destekliyorsa, kopyalanan mesajın benzersiz kimliğini döndürür, aksi takdirde null döndürür. Lütfen daha fazla bilgi edinin https://tools.ietf.org/html/rfc4315

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessageAsync(string, string, IConnection, CancellationToken) {#copymessageasync_1}

Mesajı kopyalar.

```csharp
public Task<string> CopyMessageAsync(string uniqueId, string folderName, 
    IConnection connection = null, CancellationToken token = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | String | Bir sunucuya bağlantı. |
| uniqueId | String | Mesajın kullanıcı kimliği. |
| folderName | IConnection | İletinin kopyalanacağı klasör adı. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Sunucu UIDPLUS uzantısını destekliyorsa, kopyalanan mesajın benzersiz kimliğini döndürür, aksi takdirde null döndürür. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->