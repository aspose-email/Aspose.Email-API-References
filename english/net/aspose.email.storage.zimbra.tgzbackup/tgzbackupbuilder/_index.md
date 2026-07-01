---
title: Class TgzBackupBuilder
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Zimbra.TgzBackup.TgzBackupBuilder class. Scans a directory tree of EML files and writes them into a GZipcompressed TAR archive in the format required by Zimbras mailbox import tool zmmailbox importMailbox
type: docs
weight: 19400
url: /net/aspose.email.storage.zimbra.tgzbackup/tgzbackupbuilder/
---
## TgzBackupBuilder class

Scans a directory tree of EML files and writes them into a GZip-compressed TAR archive in the format required by Zimbra's mailbox import tool (`zmmailbox importMailbox`).

```csharp
public static class TgzBackupBuilder
```

## Methods

| Name | Description |
| --- | --- |
| static [Build](../../aspose.email.storage.zimbra.tgzbackup/tgzbackupbuilder/build/)(string, string, string) | Scans *inputDirectory* recursively for `*.eml` files and packages them into a Zimbra-importable TGZ archive at *outputArchive*. |

## Remarks

Each EML file is stored together with a companion `.meta` JSON file that carries the Zimbra-specific metadata (item id, folder path, flags, sender, digest, etc.). The relative sub-folder structure of the source directory is preserved inside the archive so that messages end up in the correct Zimbra folders after import.

### See Also

* namespace [Aspose.Email.Storage.Zimbra.TgzBackup](../../aspose.email.storage.zimbra.tgzbackup/)
* assembly [Aspose.Email](../../)


