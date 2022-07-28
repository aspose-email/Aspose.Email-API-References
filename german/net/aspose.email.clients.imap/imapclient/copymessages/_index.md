---
title: CopyMessages
second_title: Aspose.Email für .NET-API-Referenz
description: Kopieren Sie die Nachrichteg
type: docs
weight: 500
url: /de/net/aspose.email.clients.imap/imapclient/copymessages/
---
## CopyMessages(IConnection, int, int, string) {#copymessages}

Kopieren Sie die Nachrichteg

```csharp
public void CopyMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessages(int, int, string) {#copymessages_5}

Nachrichten kopieren

```csharp
public void CopyMessages(int startSequence, int endSequence, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessages(IConnection, string, string, string) {#copymessages_4}

Nachrichten kopieren

```csharp
public void CopyMessages(IConnection connection, string startUid, string endUid, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessages(string, string, string) {#copymessages_10}

Nachrichten kopieren

```csharp
public void CopyMessages(string startUid, string endUid, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;int&gt;, string, bool) {#copymessages_8}

Nachrichten kopieren

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessages(IConnection, IEnumerable&lt;int&gt;, string) {#copymessages_2}

Kopieren Sie die Nachrichteg

```csharp
public void CopyMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;int&gt;, string) {#copymessages_7}

Nachrichten kopieren

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessages(IConnection, IEnumerable&lt;string&gt;, string) {#copymessages_3}

Nachrichten kopieren

```csharp
public void CopyMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;string&gt;, string) {#copymessages_9}

Nachrichten kopieren

```csharp
public void CopyMessages(IEnumerable<string> uidSet, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_1}

Nachrichten kopieren

```csharp
public void CopyMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_6}

Nachrichten kopieren

```csharp
public void CopyMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
