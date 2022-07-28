---
title: DeleteMessages
second_title: Aspose.Email für .NET-API-Referenz
description: Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht
type: docs
weight: 580
url: /de/net/aspose.email.clients.imap/imapclient/deletemessages/
---
## DeleteMessages(IConnection, IEnumerable&lt;int&gt;) {#deletemessages_6}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;) {#deletemessages_8}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;) {#deletemessages_22}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;) {#deletemessages_24}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IEnumerable<string> uidSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessages_7}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessages_10}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;, long) {#deletemessages_23}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long) {#deletemessages_26}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, bool) {#deletemessages_25}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessages_9}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long, bool) {#deletemessages_27}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessages_11}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int) {#deletemessages}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string) {#deletemessages_12}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(int, int) {#deletemessages_16}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(int startSequence, int endSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(string, string) {#deletemessages_28}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(string startUid, string endUid)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int, long) {#deletemessages_1}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long) {#deletemessages_14}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(int, int, long) {#deletemessages_17}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(int startSequence, int endSequence, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long) {#deletemessages_30}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(string, string, bool) {#deletemessages_29}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, bool) {#deletemessages_13}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long, bool) {#deletemessages_31}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long, bool) {#deletemessages_15}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_2}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_18}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_4}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_20}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_19}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_3}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_21}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_5}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo zum Löschen |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
