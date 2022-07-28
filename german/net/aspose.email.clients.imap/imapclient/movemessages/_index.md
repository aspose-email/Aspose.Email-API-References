---
title: MoveMessages
second_title: Aspose.Email für .NET-API-Referenz
description: Verschiebt die Nachricht
type: docs
weight: 950
url: /de/net/aspose.email.clients.imap/imapclient/movemessages/
---
## MoveMessages(IConnection, string, string, string) {#movemessages_8}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName)
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

## MoveMessages(string, string, string) {#movemessages_18}

Verschiebt die Nachricht

```csharp
public void MoveMessages(string startUid, string endUid, string folderName)
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

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessages_7}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string, bool) {#movemessages_17}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Der UID-Satz für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string) {#movemessages_6}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
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

## MoveMessages(IEnumerable&lt;string&gt;, string) {#movemessages_16}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName)
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

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_3}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_13}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Der Satz von ImapMessageInfo |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Siehe auch

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_2}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_12}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
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

---

## MoveMessages(IConnection, int, int, string, bool) {#movemessages_1}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessages(int, int, string, bool) {#movemessages_11}

Verschiebt die Nachricht

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startSequence | Int32 | Die Startsequenznummer einer Nachrichtenliste |
| endSequence | Int32 | Die Endsequenznummer einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string) {#movemessages}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
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

## MoveMessages(int, int, string) {#movemessages_10}

Verschiebt die Nachricht

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName)
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

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessages_5}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceSet | IEnumerable`1 | Der Satz von Sequenznummern für Nachrichten |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string, bool) {#movemessages_15}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
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

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string) {#movemessages_4}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
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

## MoveMessages(IEnumerable&lt;int&gt;, string) {#movemessages_14}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName)
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

## MoveMessages(IConnection, string, string, string, bool) {#movemessages_9}

Verschiebt die Nachricht

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## MoveMessages(string, string, string, bool) {#movemessages_19}

Verschiebt die Nachricht

```csharp
public void MoveMessages(string startUid, string endUid, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startUid | String | Die Start-UID einer Nachrichtenliste |
| endUid | String | Die End-UID einer Nachrichtenliste |
| folderName | String | Ordnername, in den eine Nachricht verschoben werden soll |
| commitDeletions | Boolean | Gibt an, ob Löschungen festgeschrieben werden sollen. |

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
