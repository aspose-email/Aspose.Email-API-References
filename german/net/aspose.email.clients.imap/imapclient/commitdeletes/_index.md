---
title: CommitDeletes
second_title: Aspose.Email für .NET-API-Referenz
description: Übernehmen Sie die Löschungen
type: docs
weight: 460
url: /de/net/aspose.email.clients.imap/imapclient/commitdeletes/
---
## CommitDeletes() {#commitdeletes}

Übernehmen Sie die Löschungen

```csharp
public void CommitDeletes()
```

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CommitDeletes(int) {#commitdeletes_6}

Übernehmen Sie die Löschungen

```csharp
public void CommitDeletes(int sleep)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sleep | Int32 | Wartezeit zum Abschluss des Vorgangs in Millisekunden |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CommitDeletes(IEnumerable&lt;string&gt;) {#commitdeletes_7}

Übertragen Sie die Löschungen Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IEnumerable<string> uidSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Satz eindeutiger Kennungen für Nachrichten |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CommitDeletes(string) {#commitdeletes_8}

Übertragen Sie die Löschungen Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(string uniqueId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die UID einer Nachricht |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CommitDeletes(string, string) {#commitdeletes_9}

Übertragen Sie die Löschungen Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(string startUid, string endUid)
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

## CommitDeletes(IConnection, IEnumerable&lt;string&gt;) {#commitdeletes_3}

Übertragen Sie die Löschungen Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IConnection connection, IEnumerable<string> uidSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Satz eindeutiger Kennungen für Nachrichten |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, string) {#commitdeletes_4}

Übernehmen Sie die Löschungen

```csharp
public void CommitDeletes(IConnection connection, string uniqueId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die UID einer Nachricht |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, string, string) {#commitdeletes_5}

Übertragen Sie die Löschungen Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IConnection connection, string startUid, string endUid)
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

## CommitDeletes(IConnection) {#commitdeletes_1}

Übernehmen Sie die Löschungen

```csharp
public void CommitDeletes(IConnection connection)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, int) {#commitdeletes_2}

Übernehmen Sie die Löschungen

```csharp
public void CommitDeletes(IConnection connection, int sleep)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sleep | Int32 | Wartezeit zum Abschluss des Vorgangs in Millisekunden |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
