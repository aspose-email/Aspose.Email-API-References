---
title: ListMessages
second_title: Aspose.Email for .NET API Referansı
description: Mesajları listeler. Arama mesajı için bir bilgi alır
type: docs
weight: 870
url: /tr/net/aspose.email.clients.imap/imapclient/listmessages/
---
## ListMessages(string, ImapListFields, int) {#listmessages_21}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, ImapListFields fieldsList, 
    int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |
| fieldsList | ImapListFields | Sunucudan alınabilecek alanlar. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |

### Geri dönüş değeri

ImapMessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, ImapListFields, int) {#listmessages_8}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    ImapListFields fieldsList, int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |
| fieldsList | ImapListFields | Sunucudan alınabilecek alanlar. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |

### Geri dönüş değeri

ImapMessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;string&gt;) {#listmessages_26}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |
| uniqueIdLst | IEnumerable`1 | için benzersiz kimlik listesi[`ImapMessageInfo`](../../imapmessageinfo) bir sunucudan almak için. |

### Geri dönüş değeri

ImapMessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;int&gt;) {#listmessages_25}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |
| sequenceNumberLst | IEnumerable`1 | için sıra numarası listesi[`ImapMessageInfo`](../../imapmessageinfo) bir sunucudan almak için. |

### Geri dönüş değeri

ImapMessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;string&gt;) {#listmessages_13}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |
| uniqueIdLst | IEnumerable`1 | için benzersiz kimlik listesi[`ImapMessageInfo`](../../imapmessageinfo) bir sunucudan almak için. |

### Geri dönüş değeri

ImapMessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;int&gt;) {#listmessages_12}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |
| sequenceNumberLst | IEnumerable`1 | için sıra numarası listesi[`ImapMessageInfo`](../../imapmessageinfo) bir sunucudan almak için. |

### Geri dönüş değeri

ImapMessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessages_11}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
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

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, string) {#listmessages_7}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_4}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, bool retrieveRecursively)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, long) {#listmessages_6}

Geçerli klasördeki, belirtilen değerden daha büyük bir değişiklik dizisine sahip mesajların listesini alır. Lütfen daha fazla bilgi edinin https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| modificationSequence | Int64 | Değişiklik sırası |

### Geri dönüş değeri

Koleksiyonu[`ImapMessageInfo`](../../imapmessageinfo) mesaj bilgilerini temsil eder.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, bool) {#listmessages_10}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| folderName | String | Mesajları almak için klasör. |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages()
```

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_19}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages(IEnumerable<string> messageExtraFields)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Talep edilecek bir mesaj için ekstra parametrelerin listesi. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_16}

Geçerli klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages(bool retrieveRecursively)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string) {#listmessages_20}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages(string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_23}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, bool, IEnumerable&lt;string&gt;) {#listmessages_24}

Belirtilen klasöründeki iletilerin listesini alır

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively, 
    IEnumerable<string> messageExtraFields)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folderName | String | Mesajları almak için klasör. |
| retrieveRecursively | Boolean | İletilerin yinelemeli olarak alınması gerekip gerekmediğini gösterir. |
| messageExtraFields | IEnumerable`1 | Talep edilecek bir mesaj için ekstra parametrelerin listesi. |

### Geri dönüş değeri

ImapMessageInfo nesnelerinin toplanması

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(long) {#listmessages_18}

Geçerli klasördeki, belirtilen değerden daha büyük bir değişiklik dizisine sahip mesajların listesini alır. Lütfen daha fazla bilgi edinin https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| modificationSequence | Int64 | Değişiklik sırası |

### Geri dönüş değeri

Koleksiyonu[`ImapMessageInfo`](../../imapmessageinfo) mesaj bilgilerini temsil eder.

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, MailQuery, int) {#listmessages_9}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
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

## ListMessages(IConnection, MailQuery) {#listmessages_2}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
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

## ListMessages(IConnection, MailQuery, int) {#listmessages_3}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
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

## ListMessages(MailQuery) {#listmessages_14}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
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

## ListMessages(string, MailQuery, int) {#listmessages_22}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
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

## ListMessages(MailQuery, int) {#listmessages_15}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
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

## ListMessages(IConnection, int) {#listmessages_5}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |

### Geri dönüş değeri

Koleksiyonu[`ImapMessageInfo`](../../imapmessageinfo) mesaj bilgilerini temsil eder.

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

## ListMessages(int) {#listmessages_17}

Geçerli klasördeki iletilerin listesini alır.

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |

### Geri dönüş değeri

Koleksiyonu[`ImapMessageInfo`](../../imapmessageinfo) mesaj bilgilerini temsil eder.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* negatif. |

### Ayrıca bakınız

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
