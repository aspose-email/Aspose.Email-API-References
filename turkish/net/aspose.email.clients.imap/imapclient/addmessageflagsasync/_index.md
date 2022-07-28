---
title: AddMessageFlagsAsync
second_title: Aspose.Email for .NET API Referansı
description: iletinin bayraklarını ekler
type: docs
weight: 350
url: /tr/net/aspose.email.clients.imap/imapclient/addmessageflagsasync/
---
## AddMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_35}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_27}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_7}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_54}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_34}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_26}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_6}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_47}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_43}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_19}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_15}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_46}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_42}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_18}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_14}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_39}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_11}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_38}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_10}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#addmessageflagsasync}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| flags | ImapMessageFlags | Eklenecek bayraklar |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#addmessageflagsasync_20}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | Bir mesajın benzersiz tanımlayıcısı |
| flags | ImapMessageFlags | Eklenecek bayraklar |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags) {#addmessageflagsasync_28}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| flags | ImapMessageFlags | Eklenecek bayraklar |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags) {#addmessageflagsasync_48}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | Bir mesajın benzersiz tanımlayıcısı |
| flags | ImapMessageFlags | Eklenecek bayraklar |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#addmessageflagsasync_1}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#addmessageflagsasync_21}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | Bir mesajın benzersiz tanımlayıcısı |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, long) {#addmessageflagsasync_29}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, long) {#addmessageflagsasync_49}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | Bir mesajın benzersiz tanımlayıcısı |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags) {#addmessageflagsasync_52}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags) {#addmessageflagsasync_32}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#addmessageflagsasync_24}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#addmessageflagsasync_4}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, long) {#addmessageflagsasync_53}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags, long) {#addmessageflagsasync_33}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#addmessageflagsasync_25}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#addmessageflagsasync_5}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#addmessageflagsasync_44}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#addmessageflagsasync_40}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#addmessageflagsasync_16}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#addmessageflagsasync_12}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#addmessageflagsasync_45}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#addmessageflagsasync_41}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#addmessageflagsasync_17}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#addmessageflagsasync_13}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| flags | ImapMessageFlags | Kaldırılacak bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#addmessageflagsasync_36}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#addmessageflagsasync_8}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#addmessageflagsasync_37}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#addmessageflagsasync_9}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_3}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_23}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | Bir mesajın benzersiz tanımlayıcısı |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_31}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_51}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | Bir mesajın benzersiz tanımlayıcısı |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_2}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_22}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | Bir mesajın benzersiz tanımlayıcısı |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_30}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_50}

İletiye bayrak ekler

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | Bir mesajın benzersiz tanımlayıcısı |
| flags | ImapMessageFlags | Eklenecek bayraklar |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_55}

iletinin bayraklarını ekler

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| flags | ImapMessageFlags | Bayraklar değiştirilecek |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
