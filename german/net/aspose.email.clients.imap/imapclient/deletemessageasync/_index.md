---
title: DeleteMessageAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht
type: docs
weight: 570
url: /de/net/aspose.email.clients.imap/imapclient/deletemessageasync/
---
## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_4}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_12}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_16}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long) {#deletemessageasync_1}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long) {#deletemessageasync_7}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long) {#deletemessageasync_13}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long) {#deletemessageasync_19}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool) {#deletemessageasync_17}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool) {#deletemessageasync_5}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool) {#deletemessageasync_20}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool) {#deletemessageasync_8}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_3}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_11}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_15}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_23}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long, CancellationToken) {#deletemessageasync_2}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, CancellationToken) {#deletemessageasync_10}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long, CancellationToken) {#deletemessageasync_14}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, CancellationToken) {#deletemessageasync_22}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool, CancellationToken) {#deletemessageasync_18}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool, CancellationToken) {#deletemessageasync_6}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool, CancellationToken) {#deletemessageasync_21}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool, CancellationToken) {#deletemessageasync_9}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
