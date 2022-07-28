---
title: ListMessagesAsync
second_title: Aspose.Email for .NET API Referansı
description: Geçerli klasördeki iletilerin listesini alır.
type: docs
weight: 880
url: /tr/net/aspose.email.clients.imap/imapclient/listmessagesasync/
---
## ListMessagesAsync(int, CancellationToken) {#listmessagesasync_28}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* negatif. |

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_17}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |
| modificationSequence | Int64 | Değişiklik sırası |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |
| messageExtraFields | IEnumerable`1 | Talep edilecek bir mesaj için ekstra parametrelerin listesi. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string) {#listmessagesasync_12}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_6}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long) {#listmessagesasync_10}

Geçerli klasördeki, belirtilen değerden daha büyük bir değişiklik dizisine sahip mesajların listesini alır. Lütfen daha fazla bilgi edinin https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| modificationSequence | Int64 | Değişiklik sırası |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool) {#listmessagesasync_15}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync()
```

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;) {#listmessagesasync_31}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Talep edilecek bir mesaj için ekstra parametrelerin listesi. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_25}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(string) {#listmessagesasync_33}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool) {#listmessagesasync_36}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_37}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |
| messageExtraFields | IEnumerable`1 | Talep edilecek bir mesaj için ekstra parametrelerin listesi. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(long) {#listmessagesasync_29}

Geçerli klasördeki, belirtilen değerden daha büyük bir değişiklik dizisine sahip mesajların listesini alır. Lütfen daha fazla bilgi edinin https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| modificationSequence | Int64 | Değişiklik sırası |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int) {#listmessagesasync_13}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesaj konumu |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_2}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int) {#listmessagesasync_3}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_21}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int) {#listmessagesasync_34}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesaj konumu |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int) {#listmessagesasync_22}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int) {#listmessagesasync_8}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* negatif. |

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(int) {#listmessagesasync_27}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* negatif. |

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_18}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |
| modificationSequence | Int64 | Değişiklik sırası |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |
| messageExtraFields | IEnumerable`1 | Talep edilecek bir mesaj için ekstra parametrelerin listesi. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_20}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, CancellationToken) {#listmessagesasync_19}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_7}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long, CancellationToken) {#listmessagesasync_11}

Geçerli klasördeki, belirtilen değerden daha büyük bir değişiklik dizisine sahip mesajların listesini alır. Lütfen daha fazla bilgi edinin https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| modificationSequence | Int64 | Değişiklik sırası |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool, CancellationToken) {#listmessagesasync_16}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_41}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_32}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Talep edilecek bir mesaj için ekstra parametrelerin listesi. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_26}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(string, CancellationToken) {#listmessagesasync_40}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, CancellationToken) {#listmessagesasync_39}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_38}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |
| messageExtraFields | IEnumerable`1 | Talep edilecek bir mesaj için ekstra parametrelerin listesi. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(long, CancellationToken) {#listmessagesasync_30}

Geçerli klasördeki, belirtilen değerden daha büyük bir değişiklik dizisine sahip mesajların listesini alır. Lütfen daha fazla bilgi edinin https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| modificationSequence | Int64 | Değişiklik sırası |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int, CancellationToken) {#listmessagesasync_14}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesaj konumu |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_5}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int, CancellationToken) {#listmessagesasync_4}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_24}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int, CancellationToken) {#listmessagesasync_35}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesaj konumu |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int, CancellationToken) {#listmessagesasync_23}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) arama sorgusunu temsil eder. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int, CancellationToken) {#listmessagesasync_9}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* negatif. |

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
