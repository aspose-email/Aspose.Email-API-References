---
title: CopyMessagesAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Kopieren Sie die Nachrichteg
type: docs
weight: 510
url: /de/net/aspose.email.clients.imap/imapclient/copymessagesasync/
---
## CopyMessagesAsync(IConnection, int, int, string) {#copymessagesasync}

Kopieren Sie die Nachrichteg

```csharp
public Task CopyMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(int, int, string) {#copymessagesasync_10}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(int startSequence, int endSequence, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, string, string, string) {#copymessagesasync_8}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(string, string, string) {#copymessagesasync_19}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(string startUid, string endUid, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string) {#copymessagesasync_4}

Kopieren Sie die Nachrichteg

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;int&gt;, string) {#copymessagesasync_14}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IEnumerable<int> sequenceSet, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string) {#copymessagesasync_6}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;string&gt;, string) {#copymessagesasync_17}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IEnumerable<string> uidSet, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessagesasync_2}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessagesasync_12}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, int, int, string, CancellationToken) {#copymessagesasync_1}

Kopieren Sie die Nachrichteg

```csharp
public Task CopyMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(int, int, string, CancellationToken) {#copymessagesasync_11}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(int startSequence, int endSequence, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, string, string, string, CancellationToken) {#copymessagesasync_9}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(string, string, string, CancellationToken) {#copymessagesasync_20}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(string startUid, string endUid, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) {#copymessagesasync_5}

Kopieren Sie die Nachrichteg

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;int&gt;, string, CancellationToken) {#copymessagesasync_16}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) {#copymessagesasync_7}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;string&gt;, string, CancellationToken) {#copymessagesasync_18}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IEnumerable<string> uidSet, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#copymessagesasync_3}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#copymessagesasync_13}

Nachrichten kopieren

```csharp
public Task CopyMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
