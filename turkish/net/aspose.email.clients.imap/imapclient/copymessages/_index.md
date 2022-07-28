---
title: CopyMessages
second_title: Aspose.Email for .NET API Referansı
description: messaeg dosyasını kopyalayın
type: docs
weight: 500
url: /tr/net/aspose.email.clients.imap/imapclient/copymessages/
---
## CopyMessages(IConnection, int, int, string) {#copymessages}

messaeg dosyasını kopyalayın

```csharp
public void CopyMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessages(int, int, string) {#copymessages_5}

Mesajları kopyala

```csharp
public void CopyMessages(int startSequence, int endSequence, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessages(IConnection, string, string, string) {#copymessages_4}

Mesajları kopyala

```csharp
public void CopyMessages(IConnection connection, string startUid, string endUid, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| folderName | String | İletinin taşınacağı klasör adı |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessages(string, string, string) {#copymessages_10}

Mesajları kopyala

```csharp
public void CopyMessages(string startUid, string endUid, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| folderName | String | İletinin taşınacağı klasör adı |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;int&gt;, string, bool) {#copymessages_8}

Mesajları kopyala

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessages(IConnection, IEnumerable&lt;int&gt;, string) {#copymessages_2}

messaeg dosyasını kopyalayın

```csharp
public void CopyMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| folderName | String | İletinin taşınacağı klasör adı |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;int&gt;, string) {#copymessages_7}

Mesajları kopyala

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| folderName | String | İletinin taşınacağı klasör adı |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessages(IConnection, IEnumerable&lt;string&gt;, string) {#copymessages_3}

Mesajları kopyala

```csharp
public void CopyMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| folderName | String | İletinin taşınacağı klasör adı |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;string&gt;, string) {#copymessages_9}

Mesajları kopyala

```csharp
public void CopyMessages(IEnumerable<string> uidSet, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| folderName | String | İletinin taşınacağı klasör adı |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_1}

Mesajları kopyala

```csharp
public void CopyMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| folderName | String | İletinin taşınacağı klasör adı |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_6}

Mesajları kopyala

```csharp
public void CopyMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| folderName | String | İletinin taşınacağı klasör adı |

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
