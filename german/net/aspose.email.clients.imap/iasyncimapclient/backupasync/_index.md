---
title: BackupAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Sichert den Inhalt der angegebenen Ordner
type: docs
weight: 40
url: /de/net/aspose.email.clients.imap/iasyncimapclient/backupasync/
---
## BackupAsync(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) {#backupasync}

Sichert den Inhalt der angegebenen Ordner

```csharp
public Task BackupAsync(ImapFolderInfoCollection folders, Stream stream, BackupSettings options, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | ImapFolderInfoCollection | Verbindung zu einem Server |
| folders | Stream | Ein Ordner zum Sichern |
| stream | BackupSettings | Ein Stream, in den geschrieben werden kann |
| options | IConnection | Ein Backup-Optionen |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [BackupSettings](../../backupsettings)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* namensraum [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* Montage [Aspose.Email](../../../)

---

## BackupAsync(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) {#backupasync_1}

Sichert den Inhalt der angegebenen Ordner

```csharp
public Task BackupAsync(ImapFolderInfoCollection folders, string fileName, BackupSettings options, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | ImapFolderInfoCollection | Verbindung zu einem Server |
| folders | String | Ein Ordner zum Sichern |
| fileName | BackupSettings | Ein Pfad zur persönlichen Speicherdatei |
| options | IConnection | Ein Backup-Optionen |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [BackupSettings](../../backupsettings)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* namensraum [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->