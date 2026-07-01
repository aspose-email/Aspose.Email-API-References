---
title: TgzBackupBuilder.Build
second_title: Aspose.Email for .NET API Reference
description: TgzBackupBuilder method. Scans inputDirectory recursively for .eml files and packages them into a Zimbraimportable TGZ archive at outputArchive
type: docs
weight: 10
url: /net/aspose.email.storage.zimbra.tgzbackup/tgzbackupbuilder/build/
---
## TgzBackupBuilder.Build method

Scans *inputDirectory* recursively for `*.eml` files and packages them into a Zimbra-importable TGZ archive at *outputArchive*.

```csharp
public static BuildResult Build(string inputDirectory, string outputArchive, string rootFolderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputDirectory | String | Absolute or relative path to the folder that contains the source EML files. Sub-folders are included and their relative paths are preserved inside the archive. |
| outputArchive | String | Path of the `.tgz` file to create. The file is overwritten if it already exists. The parent directory must exist before calling this method. |
| rootFolderName | String | Name of the top-level folder inside the archive (e.g. `"Imported"`). This becomes the Zimbra mailbox root that all messages are imported under. |

### Return Value

A [`BuildResult`](../../buildresult/) with the count of successfully written messages and a list of any per-file errors.

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Thrown if the output file cannot be created or the input directory cannot be read. |

## Remarks

For every EML file the method writes two entries into the TAR stream in this order:

1. A `.meta` JSON file with Zimbra metadata (date, subject, sender, digest, etc.).
2. The normalised EML file itself.

Files that cannot be parsed are skipped; the error is recorded in [`Errors`](../../buildresult/errors/).

### See Also

* class [BuildResult](../../buildresult/)
* class [TgzBackupBuilder](../)
* namespace [Aspose.Email.Storage.Zimbra.TgzBackup](../../tgzbackupbuilder/)
* assembly [Aspose.Email](../../../)


