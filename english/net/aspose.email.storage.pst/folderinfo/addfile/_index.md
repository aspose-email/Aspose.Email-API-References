---
title: FolderInfo.AddFile
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Adds a file into pst folder
type: docs
weight: 130
url: /net/aspose.email.storage.pst/folderinfo/addfile/
---
## FolderInfo.AddFile method

Adds a file into pst folder.

```csharp
public string AddFile(string fileName, string messageClass)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The name of file necessary to add. |
| messageClass | String | The message class. |

### Return Value

The string that represents the EntryId of the added message.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws, if a PST file version is ANSI. |
| ArgumentNullException | throws, if a name of file to add is null or empty. |
| InvalidOperationException | throws, if a PST is open for reading only. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


