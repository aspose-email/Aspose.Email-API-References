---
title: PersonalStorage.GetParentFolder
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Gets the folder that contains a message or folder
type: docs
weight: 300
url: /net/aspose.email.storage.pst/personalstorage/getparentfolder/
---
## GetParentFolder(string) {#getparentfolder_1}

Gets the folder that contains a message or folder.

```csharp
public FolderInfo GetParentFolder(string entryIdString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryIdString | String | The entry ID of the message or folder, as a string. |

### Return Value

The parent folder.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *entryIdString* is `null` or empty. |

### See Also

* class [FolderInfo](../../folderinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## GetParentFolder(byte[]) {#getparentfolder}

Gets the folder that contains a message or folder.

```csharp
public FolderInfo GetParentFolder(byte[] entryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | Byte[] | The entry ID of the message or folder. |

### Return Value

The parent folder.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *entryId* is `null`. |
| InvalidOperationException | *entryId* identifies the root folder, which has no parent. |

### See Also

* class [FolderInfo](../../folderinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


