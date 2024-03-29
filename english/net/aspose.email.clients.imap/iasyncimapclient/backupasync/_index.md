---
title: IAsyncImapClient.BackupAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Backups the content of the specified folders
type: docs
weight: 40
url: /net/aspose.email.clients.imap/iasyncimapclient/backupasync/
---
## BackupAsync(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) {#backupasync}

Backups the content of the specified folders

```csharp
public Task BackupAsync(ImapFolderInfoCollection folders, Stream stream, BackupSettings options, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | ImapFolderInfoCollection | Connection to a server |
| folders | Stream | A folders to backup |
| stream | BackupSettings | A stream to write into |
| options | IConnection | A backup options |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* class [BackupSettings](../../backupsettings/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)

---

## BackupAsync(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) {#backupasync_1}

Backups the content of the specified folders

```csharp
public Task BackupAsync(ImapFolderInfoCollection folders, string fileName, BackupSettings options, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | ImapFolderInfoCollection | Connection to a server |
| folders | String | A folders to backup |
| fileName | BackupSettings | A path to the presonal storage file |
| options | IConnection | A backup options |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* class [BackupSettings](../../backupsettings/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


