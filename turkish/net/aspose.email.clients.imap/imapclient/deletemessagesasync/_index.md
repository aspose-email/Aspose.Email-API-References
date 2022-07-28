---
title: DeleteMessagesAsync
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler
type: docs
weight: 590
url: /tr/net/aspose.email.clients.imap/imapclient/deletemessagesasync/
---
## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessagesasync_19}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long) {#deletemessagesasync_45}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long) {#deletemessagesasync_51}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_49}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_17}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_52}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_20}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int) {#deletemessagesasync}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string) {#deletemessagesasync_24}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int) {#deletemessagesasync_32}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string) {#deletemessagesasync_56}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long) {#deletemessagesasync_1}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long) {#deletemessagesasync_27}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long) {#deletemessagesasync_33}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long) {#deletemessagesasync_59}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool) {#deletemessagesasync_57}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool) {#deletemessagesasync_25}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool) {#deletemessagesasync_60}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool) {#deletemessagesasync_28}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_4}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_36}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_7}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_39}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_37}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_5}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_40}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_8}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_15}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_23}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_47}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_55}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_14}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_22}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_46}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_54}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_50}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_18}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_53}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_21}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, CancellationToken) {#deletemessagesasync_3}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, CancellationToken) {#deletemessagesasync_31}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, CancellationToken) {#deletemessagesasync_35}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, CancellationToken) {#deletemessagesasync_63}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long, CancellationToken) {#deletemessagesasync_2}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, CancellationToken) {#deletemessagesasync_30}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long, CancellationToken) {#deletemessagesasync_34}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, CancellationToken) {#deletemessagesasync_62}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool, CancellationToken) {#deletemessagesasync_58}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool, CancellationToken) {#deletemessagesasync_26}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool, CancellationToken) {#deletemessagesasync_61}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool, CancellationToken) {#deletemessagesasync_29}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_11}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_43}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_10}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_42}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_38}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_6}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_41}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_9}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | Silinecek ImapMessageInfo kümesi |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#deletemessagesasync_12}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#deletemessagesasync_16}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;) {#deletemessagesasync_44}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;) {#deletemessagesasync_48}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessagesasync_13}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
