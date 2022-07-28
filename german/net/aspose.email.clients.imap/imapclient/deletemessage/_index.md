---
title: DeleteMessage
second_title: Aspose.Email für .NET-API-Referenz
description: Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht
type: docs
weight: 560
url: /de/net/aspose.email.clients.imap/imapclient/deletemessage/
---
## DeleteMessage(IConnection, int) {#deletemessage}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string) {#deletemessage_2}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessage(IConnection connection, string uniqueId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(int) {#deletemessage_6}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessage(int sequenceNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(string) {#deletemessage_8}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessage(string uniqueId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, int, long) {#deletemessage_1}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long) {#deletemessage_4}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(int, long) {#deletemessage_7}

Markiert eine Nachricht mit der angegebenen Sequenznummer als gelöscht

```csharp
public void DeleteMessage(int sequenceNumber, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequenznummer einer Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(string, long) {#deletemessage_10}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(string, bool) {#deletemessage_9}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, bool) {#deletemessage_3}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(string, long, bool) {#deletemessage_11}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long, bool) {#deletemessage_5}

Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID der Nachricht |
| modificationSequence | Int64 | Änderungssequenz. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definiert, ob die Nachricht jetzt festgeschrieben werden muss. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
