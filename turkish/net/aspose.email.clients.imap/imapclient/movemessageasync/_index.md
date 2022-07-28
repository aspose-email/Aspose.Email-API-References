---
title: MoveMessageAsync
second_title: Aspose.Email for .NET API Referansı
description: İletiyi taşır
type: docs
weight: 940
url: /tr/net/aspose.email.clients.imap/imapclient/movemessageasync/
---
## MoveMessageAsync(int, string, bool) {#movemessageasync_9}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool) {#movemessageasync_13}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | mesajın kullanıcı kimliği |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string) {#movemessageasync}

messaeg öğesini hareket ettirir

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string) {#movemessageasync_4}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | mesajın kullanıcı kimliği |
| folderName | String | İletinin taşınacağı klasör adı |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string) {#movemessageasync_8}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string) {#movemessageasync_12}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | mesajın kullanıcı kimliği |
| folderName | String | İletinin taşınacağı klasör adı |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool, CancellationToken) {#movemessageasync_2}

messaeg öğesini hareket ettirir

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool, CancellationToken) {#movemessageasync_6}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | mesajın kullanıcı kimliği |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, bool, CancellationToken) {#movemessageasync_10}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool, CancellationToken) {#movemessageasync_14}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | mesajın kullanıcı kimliği |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, CancellationToken) {#movemessageasync_3}

messaeg öğesini hareket ettirir

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, CancellationToken) {#movemessageasync_7}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | mesajın kullanıcı kimliği |
| folderName | String | İletinin taşınacağı klasör adı |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, CancellationToken) {#movemessageasync_11}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, CancellationToken) {#movemessageasync_15}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | mesajın kullanıcı kimliği |
| folderName | String | İletinin taşınacağı klasör adı |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool) {#movemessageasync_1}

messaeg öğesini hareket ettirir

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumber | Int32 | Mesajın sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool) {#movemessageasync_5}

İletiyi taşır

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | mesajın kullanıcı kimliği |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
