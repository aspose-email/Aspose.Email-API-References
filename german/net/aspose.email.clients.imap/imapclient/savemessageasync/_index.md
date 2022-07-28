---
title: SaveMessageAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in einen bereitgestellten Stream
type: docs
weight: 1100
url: /de/net/aspose.email.clients.imap/imapclient/savemessageasync/
---
## SaveMessageAsync(IConnection, int, Stream) {#savemessageasync}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in einen bereitgestellten Stream

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| resultStream | Stream | Stream, der die Nachricht empfängt |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream) {#savemessageasync_4}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in einen bereitgestellten Stream

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die eindeutige ID der Nachricht |
| resultStream | Stream | Stream, der die Nachricht empfängt |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string) {#savemessageasync_6}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in eine lokale Datei

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die eindeutige ID der Nachricht |
| fileName | String | Der Pfad der lokalen Datei. Dies kann kein Verzeichnis sein |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string) {#savemessageasync_2}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in eine lokale Datei

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| fileName | String | Der Pfad der lokalen Datei. Dies kann kein Verzeichnis sein |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream) {#savemessageasync_8}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in einen bereitgestellten Stream

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| resultStream | Stream | Stream, der die Nachricht empfängt |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream) {#savemessageasync_12}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in einen bereitgestellten Stream

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die eindeutige ID der Nachricht |
| resultStream | Stream | Stream, der die Nachricht empfängt |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string) {#savemessageasync_14}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in eine lokale Datei

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die eindeutige ID der Nachricht |
| fileName | String | Der Pfad der lokalen Datei. Dies kann kein Verzeichnis sein |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string) {#savemessageasync_10}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in eine lokale Datei

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| fileName | String | Der Pfad der lokalen Datei. Dies kann kein Verzeichnis sein |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream, CancellationToken) {#savemessageasync_1}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in einen bereitgestellten Stream

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| resultStream | Stream | Stream, der die Nachricht empfängt |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream, CancellationToken) {#savemessageasync_5}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in einen bereitgestellten Stream

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die eindeutige ID der Nachricht |
| resultStream | Stream | Stream, der die Nachricht empfängt |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string, CancellationToken) {#savemessageasync_7}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in eine lokale Datei

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die eindeutige ID der Nachricht |
| fileName | String | Der Pfad der lokalen Datei. Dies kann kein Verzeichnis sein |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string, CancellationToken) {#savemessageasync_3}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in eine lokale Datei

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| fileName | String | Der Pfad der lokalen Datei. Dies kann kein Verzeichnis sein |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream, CancellationToken) {#savemessageasync_9}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in einen bereitgestellten Stream

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| resultStream | Stream | Stream, der die Nachricht empfängt |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream, CancellationToken) {#savemessageasync_13}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in einen bereitgestellten Stream

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die eindeutige ID der Nachricht |
| resultStream | Stream | Stream, der die Nachricht empfängt |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string, CancellationToken) {#savemessageasync_15}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in eine lokale Datei

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die eindeutige ID der Nachricht |
| fileName | String | Der Pfad der lokalen Datei. Dies kann kein Verzeichnis sein |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string, CancellationToken) {#savemessageasync_11}

Lädt die Nachricht mit der angegebenen Sequenznummer herunter und schreibt ihre Daten in eine lokale Datei

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| fileName | String | Der Pfad der lokalen Datei. Dies kann kein Verzeichnis sein |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
