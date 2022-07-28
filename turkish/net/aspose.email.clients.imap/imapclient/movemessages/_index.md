---
title: MoveMessages
second_title: Aspose.Email for .NET API Referansı
description: İletiyi taşır
type: docs
weight: 950
url: /tr/net/aspose.email.clients.imap/imapclient/movemessages/
---
## MoveMessages(IConnection, string, string, string) {#movemessages_8}

İletiyi taşır

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName)
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

## MoveMessages(string, string, string) {#movemessages_18}

İletiyi taşır

```csharp
public void MoveMessages(string startUid, string endUid, string folderName)
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

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessages_7}

İletiyi taşır

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName, 
    bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string, bool) {#movemessages_17}

İletiyi taşır

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Mesajlar için UID seti |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string) {#movemessages_6}

İletiyi taşır

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
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

## MoveMessages(IEnumerable&lt;string&gt;, string) {#movemessages_16}

İletiyi taşır

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName)
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

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_3}

İletiyi taşır

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_13}

İletiyi taşır

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo kümesi |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Ayrıca bakınız

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_2}

İletiyi taşır

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_12}

İletiyi taşır

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
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

---

## MoveMessages(IConnection, int, int, string, bool) {#movemessages_1}

messaeg öğesini hareket ettirir

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessages(int, int, string, bool) {#movemessages_11}

İletiyi taşır

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startSequence | Int32 | Bir mesaj listesinin başlangıç sıra numarası |
| endSequence | Int32 | Bir mesaj listesinin bitiş sıra numarası |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string) {#movemessages}

messaeg öğesini hareket ettirir

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
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

## MoveMessages(int, int, string) {#movemessages_10}

İletiyi taşır

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName)
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

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessages_5}

messaeg öğesini hareket ettirir

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sequenceSet | IEnumerable`1 | Mesajlar için sıra numaraları seti |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string, bool) {#movemessages_15}

İletiyi taşır

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
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

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string) {#movemessages_4}

messaeg öğesini hareket ettirir

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
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

## MoveMessages(IEnumerable&lt;int&gt;, string) {#movemessages_14}

İletiyi taşır

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName)
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

## MoveMessages(IConnection, string, string, string, bool) {#movemessages_9}

İletiyi taşır

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

---

## MoveMessages(string, string, string, bool) {#movemessages_19}

İletiyi taşır

```csharp
public void MoveMessages(string startUid, string endUid, string folderName, bool commitDeletions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| startUid | String | Bir mesaj listesinin başlangıç UID'si |
| endUid | String | Bir mesaj listesinin bitiş UID'si |
| folderName | String | İletinin taşınacağı klasör adı |
| commitDeletions | Boolean | Silme işlemlerinin gerçekleştirilip gerçekleştirilmeyeceğini belirtir. |

### Ayrıca bakınız

* class [ImapClient](../../imapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../imapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
