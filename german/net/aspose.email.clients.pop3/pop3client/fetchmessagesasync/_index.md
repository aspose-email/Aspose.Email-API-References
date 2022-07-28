---
title: FetchMessagesAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Ruft die Nachrichten asynchron ab
type: docs
weight: 140
url: /de/net/aspose.email.clients.pop3/pop3client/fetchmessagesasync/
---
## FetchMessagesAsync(IEnumerable&lt;int&gt;) {#fetchmessagesasync_4}

Ruft die Nachrichten asynchron ab

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<int> sequenceNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumbers | IEnumerable`1 | Die Sequenznummern der Nachrichten |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;) {#fetchmessagesasync_6}

Ruft die Nachrichten asynchron ab

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<string> uids)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uids | IEnumerable`1 | Die Sequenznummern der Nachrichten |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#fetchmessagesasync}

Ruft die Nachrichten asynchron ab

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<int> sequenceNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumbers | IEnumerable`1 | Die Sequenznummern der Nachrichten |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#fetchmessagesasync_2}

Ruft die Nachrichten asynchron ab

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, IEnumerable<string> uids)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uids | IEnumerable`1 | Die Sequenznummern der Nachrichten |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#fetchmessagesasync_5}

Ruft die Nachrichten asynchron ab

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<int> sequenceNumbers, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumbers | IEnumerable`1 | Die Sequenznummern der Nachrichten |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#fetchmessagesasync_7}

Ruft die Nachrichten asynchron ab

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<string> uids, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uids | IEnumerable`1 | Die Sequenznummern der Nachrichten |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#fetchmessagesasync_1}

Ruft die Nachrichten asynchron ab

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<int> sequenceNumbers, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumbers | IEnumerable`1 | Die Sequenznummern der Nachrichten |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#fetchmessagesasync_3}

Ruft die Nachrichten asynchron ab

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<string> uids, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uids | IEnumerable`1 | Die Sequenznummern der Nachrichten |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
