---
title: ListMessagesAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Ruft die Liste der Nachrichten im angegebenen Ordner ab
type: docs
weight: 240
url: /de/net/aspose.email.clients.imap/iasyncimapclient/listmessagesasync/
---
## ListMessagesAsync(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) {#listmessagesasync_1}

Ruft die Liste der Nachrichten im angegebenen Ordner ab

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName = null, 
    long modificationSequence = 0, bool retrieveRecursively = false, 
    IEnumerable<string> messageExtraFields = null, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | String | Verbindung zu einem Server |
| folderName | Int64 | Ordner zum Abrufen von Nachrichten. |
| modificationSequence | Boolean | Änderungssequenz |
| retrieveRecursively | IEnumerable`1 | Gibt an, ob Nachrichten rekursiv abgerufen werden müssen. |
| messageExtraFields | IConnection | Liste der zusätzlichen Parameter für eine Nachricht, die angefordert werden. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* namensraum [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, string, int, IConnection, CancellationToken) {#listmessagesasync}

Ruft die Liste der Nachrichten im aktuellen Ordner ab.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, string folderName = null, 
    int maxNumberOfMessages = 0, IConnection connection = null, CancellationToken token = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | MailQuery | Verbindung zu einem Server |
| folderName | String | Nachrichtenspeicherort |
| query | Int32 | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die eine Suchanfrage darstellt. |
| maxNumberOfMessages | IConnection | Maximale Anzahl von Nachrichten. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Sammlung von ImapMessageInfo-Objekten.

### Siehe auch

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* namensraum [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->