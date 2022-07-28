---
title: ListMessages
second_title: Aspose.Email für .NET-API-Referenz
description: Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab
type: docs
weight: 870
url: /de/net/aspose.email.clients.imap/imapclient/listmessages/
---
## ListMessages(string, ImapListFields, int) {#listmessages_21}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, ImapListFields fieldsList, 
    int maxNumberOfMessages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderName | String | Ordner zum Abrufen von Nachrichten. |
| fieldsList | ImapListFields | Felder, die vom Server abgerufen werden können. |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten. |

### Rückgabewert

ImapMessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, ImapListFields, int) {#listmessages_8}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    ImapListFields fieldsList, int maxNumberOfMessages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| folderName | String | Ordner zum Abrufen von Nachrichten. |
| fieldsList | ImapListFields | Felder, die vom Server abgerufen werden können. |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten. |

### Rückgabewert

ImapMessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;string&gt;) {#listmessages_26}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderName | String | Ordner zum Abrufen von Nachrichten. |
| uniqueIdLst | IEnumerable`1 | UniqueId-Liste für[`ImapMessageInfo`](../../imapmessageinfo) von einem Server abzurufen. |

### Rückgabewert

ImapMessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;int&gt;) {#listmessages_25}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderName | String | Ordner zum Abrufen von Nachrichten. |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber Liste für[`ImapMessageInfo`](../../imapmessageinfo) von einem Server abzurufen. |

### Rückgabewert

ImapMessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;string&gt;) {#listmessages_13}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| folderName | String | Ordner zum Abrufen von Nachrichten. |
| uniqueIdLst | IEnumerable`1 | UniqueId-Liste für[`ImapMessageInfo`](../../imapmessageinfo) von einem Server abzurufen. |

### Rückgabewert

ImapMessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;int&gt;) {#listmessages_12}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| folderName | String | Ordner zum Abrufen von Nachrichten. |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber Liste für[`ImapMessageInfo`](../../imapmessageinfo) von einem Server abzurufen. |

### Rückgabewert

ImapMessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessages_11}

Ruft die Liste der Nachrichten im angegebenen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| folderName | String | Ordner zum Abrufen von Nachrichten. |
| modificationSequence | Int64 | Änderungssequenz |
| retrieveRecursively | Boolean | Gibt an, ob Nachrichten rekursiv abgerufen werden müssen. |
| messageExtraFields | IEnumerable`1 | Liste der zusätzlichen Parameter für eine Nachricht, die angefordert werden. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Ruft die Liste der Nachrichten im aktuellen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, string) {#listmessages_7}

Ruft die Liste der Nachrichten im angegebenen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| folderName | String | Ordner zum Abrufen von Nachrichten. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_4}

Ruft die Liste der Nachrichten im aktuellen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, bool retrieveRecursively)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| retrieveRecursively | Boolean | Gibt an, ob Nachrichten rekursiv abgerufen werden müssen. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, long) {#listmessages_6}

Ruft die Liste der Nachrichten im aktuellen Ordner ab, deren Änderungssequenz größer als der angegebene Wert ist. Weitere Informationen finden Sie unter https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| modificationSequence | Int64 | Änderungssequenz |

### Rückgabewert

Sammlung von[`ImapMessageInfo`](../../imapmessageinfo) die Nachrichteninformationen darstellen.

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, bool) {#listmessages_10}

Ruft die Liste der Nachrichten im angegebenen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| folderName | String | Ordner zum Abrufen von Nachrichten. |
| retrieveRecursively | Boolean | Gibt an, ob Nachrichten rekursiv abgerufen werden müssen. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Ruft die Liste der Nachrichten im aktuellen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages()
```

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_19}

Ruft die Liste der Nachrichten im aktuellen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages(IEnumerable<string> messageExtraFields)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Liste der zusätzlichen Parameter für eine Nachricht, die angefordert werden. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_16}

Ruft die Liste der Nachrichten im aktuellen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages(bool retrieveRecursively)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| retrieveRecursively | Boolean | Gibt an, ob Nachrichten rekursiv abgerufen werden müssen. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string) {#listmessages_20}

Ruft die Liste der Nachrichten im angegebenen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages(string folderName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderName | String | Ordner zum Abrufen von Nachrichten. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_23}

Ruft die Liste der Nachrichten im angegebenen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderName | String | Ordner zum Abrufen von Nachrichten. |
| retrieveRecursively | Boolean | Gibt an, ob Nachrichten rekursiv abgerufen werden müssen. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, bool, IEnumerable&lt;string&gt;) {#listmessages_24}

Ruft die Liste der Nachrichten im angegebenen Ordner ab

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively, 
    IEnumerable<string> messageExtraFields)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderName | String | Ordner zum Abrufen von Nachrichten. |
| retrieveRecursively | Boolean | Gibt an, ob Nachrichten rekursiv abgerufen werden müssen. |
| messageExtraFields | IEnumerable`1 | Liste der zusätzlichen Parameter für eine Nachricht, die angefordert werden. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(long) {#listmessages_18}

Ruft die Liste der Nachrichten im aktuellen Ordner ab, deren Änderungssequenz größer als der angegebene Wert ist. Weitere Informationen finden Sie unter https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| modificationSequence | Int64 | Änderungssequenz |

### Rückgabewert

Sammlung von[`ImapMessageInfo`](../../imapmessageinfo) die Nachrichteninformationen darstellen.

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, MailQuery, int) {#listmessages_9}

Ruft die Liste der Nachrichten im aktuellen Ordner ab.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| folderName | String | Nachrichtenspeicherort |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die eine Suchanfrage darstellt. |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten.

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_2}

Ruft die Liste der Nachrichten im aktuellen Ordner ab.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die eine Suchanfrage darstellt. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten.

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery, int) {#listmessages_3}

Ruft die Liste der Nachrichten im aktuellen Ordner ab.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die eine Suchanfrage darstellt. |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten.

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_14}

Ruft die Liste der Nachrichten im aktuellen Ordner ab.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die eine Suchanfrage darstellt. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten.

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, int) {#listmessages_22}

Ruft die Liste der Nachrichten im aktuellen Ordner ab.

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderName | String | Nachrichtenspeicherort |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die eine Suchanfrage darstellt. |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten.

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(MailQuery, int) {#listmessages_15}

Ruft die Liste der Nachrichten im aktuellen Ordner ab.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die eine Suchanfrage darstellt. |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten.

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, int) {#listmessages_5}

Ruft die Liste der Nachrichten im aktuellen Ordner ab.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten. |

### Rückgabewert

Sammlung von[`ImapMessageInfo`](../../imapmessageinfo) die Nachrichteninformationen darstellen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* ist negativ. |

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(int) {#listmessages_17}

Ruft die Liste der Nachrichten im aktuellen Ordner ab.

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten. |

### Rückgabewert

Sammlung von[`ImapMessageInfo`](../../imapmessageinfo) die Nachrichteninformationen darstellen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* ist negativ. |

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
