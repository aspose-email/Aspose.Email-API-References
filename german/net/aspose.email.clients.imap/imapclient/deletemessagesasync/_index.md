---
title: DeleteMessagesAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht
type: docs
weight: 590
url: /de/net/aspose.email.clients.imap/imapclient/deletemessagesasync/
---
## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessagesasync_19}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long) {#deletemessagesasync_45}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long) {#deletemessagesasync_51}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_49}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_17}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_52}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_20}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
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

## DeleteMessagesAsync(IConnection, int, int) {#deletemessagesasync}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string) {#deletemessagesasync_24}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int) {#deletemessagesasync_32}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string) {#deletemessagesasync_56}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long) {#deletemessagesasync_1}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long) {#deletemessagesasync_27}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long) {#deletemessagesasync_33}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long) {#deletemessagesasync_59}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool) {#deletemessagesasync_57}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool) {#deletemessagesasync_25}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool) {#deletemessagesasync_60}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool) {#deletemessagesasync_28}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_4}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_36}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_7}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_39}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_37}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_5}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_40}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_8}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_15}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_23}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_47}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_55}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_14}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_22}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
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

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_46}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_54}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_50}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_18}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
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

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_53}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_21}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
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

---

## DeleteMessagesAsync(IConnection, int, int, CancellationToken) {#deletemessagesasync_3}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, CancellationToken) {#deletemessagesasync_31}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, CancellationToken) {#deletemessagesasync_35}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, CancellationToken) {#deletemessagesasync_63}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long, CancellationToken) {#deletemessagesasync_2}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
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

## DeleteMessagesAsync(IConnection, string, string, long, CancellationToken) {#deletemessagesasync_30}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
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

## DeleteMessagesAsync(int, int, long, CancellationToken) {#deletemessagesasync_34}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, CancellationToken) {#deletemessagesasync_62}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool, CancellationToken) {#deletemessagesasync_58}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool, CancellationToken) {#deletemessagesasync_26}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
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

## DeleteMessagesAsync(string, string, long, bool, CancellationToken) {#deletemessagesasync_61}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
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

## DeleteMessagesAsync(IConnection, string, string, long, bool, CancellationToken) {#deletemessagesasync_29}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
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

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_11}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
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

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_43}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_10}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
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

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_42}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_38}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_6}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
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

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_41}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_9}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#deletemessagesasync_12}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#deletemessagesasync_16}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;) {#deletemessagesasync_44}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;) {#deletemessagesasync_48}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessagesasync_13}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
