---
title: MapiAttachmentCollection.AddFile
second_title: Aspose.Email for .NET API Reference
description: MapiAttachmentCollection method. Adds a new attachment reading its content from a file. The file name is used as the display name of the attachment
type: docs
weight: 30
url: /net/aspose.email.mapi/mapiattachmentcollection/addfile/
---
## AddFile(string) {#addfile}

Adds a new attachment reading its content from a file. The file name is used as the display name of the attachment.

```csharp
public MapiAttachment AddFile(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to attach. |

### Return Value

Newly created attachment[`MapiAttachment`](../../mapiattachment/)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown if the file path is null or empty. |

## Remarks

The file is opened for reading and stays open until the owning message is disposed, so the message must be disposed. The content is never copied into memory in full, which makes this the appropriate way to attach large files.

### See Also

* class [MapiAttachment](../../mapiattachment/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## AddFile(string, string) {#addfile_1}

Adds a new attachment reading its content from a file.

```csharp
public MapiAttachment AddFile(string filePath, string displayName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to attach. |
| displayName | String | The name of attachment to display in the message. |

### Return Value

Newly created attachment[`MapiAttachment`](../../mapiattachment/)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown if the file path is null or empty. |

## Remarks

The file is opened for reading and stays open until the owning message is disposed, so the message must be disposed.

### See Also

* class [MapiAttachment](../../mapiattachment/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)


