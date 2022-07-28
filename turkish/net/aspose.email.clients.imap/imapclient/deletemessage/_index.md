---
title: DeleteMessage
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler
type: docs
weight: 560
url: /tr/net/aspose.email.clients.imap/imapclient/deletemessage/
---
## DeleteMessage(IConnection, int) {#deletemessage}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumber | Int32 | Bir mesajın sıra numarası |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string) {#deletemessage_2}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public void DeleteMessage(IConnection connection, string uniqueId)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | mesajın kullanıcı kimliği |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(int) {#deletemessage_6}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public void DeleteMessage(int sequenceNumber)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumber | Int32 | Bir mesajın sıra numarası |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(string) {#deletemessage_8}

Belirtilen sıra numarasına sahip bir iletiyi delete olarak işaretler

```csharp
public void DeleteMessage(string uniqueId)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | mesajın kullanıcı kimliği |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, int, long) {#deletemessage_1}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceNumber | Int32 | Bir mesajın sıra numarası |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long) {#deletemessage_4}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | mesajın kullanıcı kimliği |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(int, long) {#deletemessage_7}

Belirtilen sıra numarasına sahip bir mesajı silindi olarak işaretler

```csharp
public void DeleteMessage(int sequenceNumber, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceNumber | Int32 | Bir mesajın sıra numarası |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(string, long) {#deletemessage_10}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi delete olarak işaretler

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | mesajın kullanıcı kimliği |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(string, bool) {#deletemessage_9}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | mesajın kullanıcı kimliği |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, bool) {#deletemessage_3}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | mesajın kullanıcı kimliği |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(string, long, bool) {#deletemessage_11}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence, bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uniqueId | String | mesajın kullanıcı kimliği |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long, bool) {#deletemessage_5}

Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uniqueId | String | mesajın kullanıcı kimliği |
| modificationSequence | Int64 | Değişiklik sırası. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Mesajın şimdi işlenmesi gerekip gerekmediğini tanımlar. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
