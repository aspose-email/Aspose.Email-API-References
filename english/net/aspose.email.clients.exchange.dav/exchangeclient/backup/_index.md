---
title: ExchangeClient.Backup
second_title: Aspose.Email for .NET API Reference
description: ExchangeClient method. Backups the content of the specified folders
type: docs
weight: 100
url: /net/aspose.email.clients.exchange.dav/exchangeclient/backup/
---
## Backup(ExchangeFolderInfoCollection, string, BackupOptions) {#backup_1}

Backups the content of the specified folders

```csharp
public void Backup(ExchangeFolderInfoCollection folders, string fileName, BackupOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folders | ExchangeFolderInfoCollection | A folders to backup |
| fileName | String | A path to the presonal storage file |
| options | BackupOptions | A backup options |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | A *fileName* is `null` or `empty` |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *folders* is `null` |

### See Also

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection/)
* enum [BackupOptions](../../../aspose.email.storage.pst/backupoptions/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## Backup(ExchangeFolderInfoCollection, Stream, BackupOptions) {#backup}

Backups the content of the specified folders

```csharp
public void Backup(ExchangeFolderInfoCollection folders, Stream stream, BackupOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folders | ExchangeFolderInfoCollection | A folders to backup |
| stream | Stream | A stream to write into |
| options | BackupOptions | A backup options |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | The given stream does not support writting |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *folders* or *stream* is `null` |

### See Also

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection/)
* enum [BackupOptions](../../../aspose.email.storage.pst/backupoptions/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)


