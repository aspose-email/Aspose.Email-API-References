---
title: ListMessagesAsync
second_title: Aspose.Email for .NET API Referansı
description: Mesajları listeler. Arama mesajı için bir bilgi alır
type: docs
weight: 300
url: /tr/net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_8}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_6}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
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

## ListMessagesAsync(IConnection, Pop3ListFields) {#listmessagesasync_2}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| fields | Pop3ListFields | Almak istediğimiz alanlar |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

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

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery) {#listmessagesasync_3}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| fields | Pop3ListFields | Almak istediğimiz alanlar |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) nesne. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_17}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_15}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
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

## ListMessagesAsync(Pop3ListFields) {#listmessagesasync_11}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fields | Pop3ListFields | Almak istediğimiz alanlar |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery) {#listmessagesasync_12}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fields | Pop3ListFields | Almak istediğimiz alanlar |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) nesne. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_10}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_9}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_7}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) nesne. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

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

## ListMessagesAsync(IConnection, Pop3ListFields, CancellationToken) {#listmessagesasync_5}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| fields | Pop3ListFields | Almak istediğimiz alanlar |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

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

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_4}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| fields | Pop3ListFields | Almak istediğimiz alanlar |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) nesne. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_19}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_18}

Mesajları listeler. Arama mesajı için bir bilgi alır

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_16}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) nesne. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Pop3MessageInfo nesnelerinin toplanması.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, CancellationToken) {#listmessagesasync_14}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fields | Pop3ListFields | Almak istediğimiz alanlar |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Notlar

Silindi olarak işaretlenen mesajların listelenmediğini unutmayın.

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_13}

Mesajları listeler.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fields | Pop3ListFields | Almak istediğimiz alanlar |
| closeTransaction | Boolean | Liste alınmadan önce cari işlemin kapatılması gerekip gerekmediğini gösterir. |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) nesne. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../pop3client)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
