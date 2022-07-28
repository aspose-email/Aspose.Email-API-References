---
title: CommitDeletes
second_title: Aspose.Email for .NET API Referansı
description: Silme işlemlerini gerçekleştir
type: docs
weight: 460
url: /tr/net/aspose.email.clients.imap/imapclient/commitdeletes/
---
## CommitDeletes() {#commitdeletes}

Silme işlemlerini gerçekleştir

```csharp
public void CommitDeletes()
```

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CommitDeletes(int) {#commitdeletes_6}

Silme işlemlerini gerçekleştir

```csharp
public void CommitDeletes(int sleep)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sleep | Int32 | Bekleme süresi, işlemi milisaniye cinsinden tamamlar |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CommitDeletes(IEnumerable&lt;string&gt;) {#commitdeletes_7}

Silme işlemlerini gerçekleştir Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IEnumerable<string> uidSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | İletiler için benzersiz tanımlayıcılar kümesi |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CommitDeletes(string) {#commitdeletes_8}

Silme işlemlerini gerçekleştir Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(string uniqueId)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | Bir mesajın kullanıcı kimliği |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CommitDeletes(string, string) {#commitdeletes_9}

Silme işlemlerini gerçekleştir Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(string startUid, string endUid)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, IEnumerable&lt;string&gt;) {#commitdeletes_3}

Silme işlemlerini gerçekleştir Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IConnection connection, IEnumerable<string> uidSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | İletiler için benzersiz tanımlayıcılar kümesi |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, string) {#commitdeletes_4}

Silme işlemlerini gerçekleştir

```csharp
public void CommitDeletes(IConnection connection, string uniqueId)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | Bir mesajın kullanıcı kimliği |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, string, string) {#commitdeletes_5}

Silme işlemlerini gerçekleştir Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IConnection connection, string startUid, string endUid)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CommitDeletes(IConnection) {#commitdeletes_1}

Silme işlemlerini gerçekleştir

```csharp
public void CommitDeletes(IConnection connection)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, int) {#commitdeletes_2}

Silme işlemlerini gerçekleştir

```csharp
public void CommitDeletes(IConnection connection, int sleep)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sleep | Int32 | Bekleme süresi, işlemi milisaniye cinsinden tamamlar |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
