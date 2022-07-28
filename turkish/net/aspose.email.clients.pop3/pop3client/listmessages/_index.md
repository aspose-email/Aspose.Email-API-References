---
title: ListMessages
second_title: Aspose.Email for .NET API Referansı
description: Mesajları listeler. Arama mesajı için bir bilgi alır
type: docs
weight: 290
url: /tr/net/aspose.email.clients.pop3/pop3client/listmessages/
---
## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_13}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<string> uniqueIdLst)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueIdLst | IEnumerable`1 | için benzersiz kimlik listesi[`Pop3MessageInfo`](../../pop3messageinfo) bir sunucudan almak için. |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;int&gt;) {#listmessages_12}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<int> sequenceNumberLst)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumberLst | IEnumerable`1 | için sıra numarası listesi[`Pop3MessageInfo`](../../pop3messageinfo) bir sunucudan almak için. |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;string&gt;) {#listmessages_7}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<string> uniqueIdLst)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueIdLst | IEnumerable`1 | için benzersiz kimlik listesi[`Pop3MessageInfo`](../../pop3messageinfo) bir sunucudan almak için. |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;int&gt;) {#listmessages_6}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<int> sequenceNumberLst)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumberLst | IEnumerable`1 | için sıra numarası listesi[`Pop3MessageInfo`](../../pop3messageinfo) bir sunucudan almak için. |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_5}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, bool closeTransaction)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_4}

Mesajları listeler.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) nesne. |

### Geri dönüş değeri

Pop3MessageInfo nesneleri koleksiyonu.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields) {#listmessages_2}

Mesajları listeler.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| fields | Pop3ListFields | Almak istediğimiz alanlar |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields, bool, MailQuery) {#listmessages_3}

Mesajları listeler.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| fields | Pop3ListFields | Almak istediğimiz alanlar |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) nesne. |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Pop3MessageInfoCollection ListMessages()
```

### Geri dönüş değeri

Pop3MessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_11}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Pop3MessageInfoCollection ListMessages(bool closeTransaction)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_10}

Mesajları listeler.

```csharp
public Pop3MessageInfoCollection ListMessages(MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) nesne. |

### Geri dönüş değeri

Pop3MessageInfo nesneleri koleksiyonu.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields) {#listmessages_8}

Mesajları listeler.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fields | Pop3ListFields | Almak istediğimiz alanlar |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields, bool, MailQuery) {#listmessages_9}

Mesajları listeler.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields, bool closeTransaction, 
    MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fields | Pop3ListFields | Almak istediğimiz alanlar |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) nesne. |

### Geri dönüş değeri

Pop3MessageInfoCollection

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
