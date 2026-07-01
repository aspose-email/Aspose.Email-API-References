---
title: Class BuildResult
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Zimbra.TgzBackup.BuildResult class. Represents the outcome of a single Build run
type: docs
weight: 19390
url: /net/aspose.email.storage.zimbra.tgzbackup/buildresult/
---
## BuildResult class

Represents the outcome of a single [`Build`](../tgzbackupbuilder/build/) run.

```csharp
public sealed class BuildResult
```

## Constructors

| Name | Description |
| --- | --- |
| [BuildResult](buildresult/)() | Initialises a new instance of `BuildResult` with an empty error list. |

## Properties

| Name | Description |
| --- | --- |
| [Errors](../../aspose.email.storage.zimbra.tgzbackup/buildresult/errors/) { get; } | Gets the list of errors encountered during the build. Each entry contains the source file path and the exception message, separated by " - ". Files that appear here were skipped and are not present in the archive. |
| [MessagesWritten](../../aspose.email.storage.zimbra.tgzbackup/buildresult/messageswritten/) { get; set; } | Gets or sets the total number of EML messages successfully written to the archive. |

### See Also

* namespace [Aspose.Email.Storage.Zimbra.TgzBackup](../../aspose.email.storage.zimbra.tgzbackup/)
* assembly [Aspose.Email](../../)


