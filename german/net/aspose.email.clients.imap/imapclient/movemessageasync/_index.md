---
title: MoveMessageAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Verschiebt die Nachricht
type: docs
weight: 940
url: /de/net/aspose.email.clients.imap/imapclient/movemessageasync/
---
## MoveMessageAsync(int, string, bool) {#movemessageasync_9}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool) {#movemessageasync_13}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string) {#movemessageasync}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string) {#movemessageasync_4}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string) {#movemessageasync_8}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string) {#movemessageasync_12}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool, CancellationToken) {#movemessageasync_2}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool, CancellationToken) {#movemessageasync_6}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, bool, CancellationToken) {#movemessageasync_10}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool, CancellationToken) {#movemessageasync_14}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, CancellationToken) {#movemessageasync_3}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
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

## MoveMessageAsync(IConnection, string, string, CancellationToken) {#movemessageasync_7}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
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

## MoveMessageAsync(int, string, CancellationToken) {#movemessageasync_11}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, CancellationToken) {#movemessageasync_15}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool) {#movemessageasync_1}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool) {#movemessageasync_5}

Verschiebt die Nachricht

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
