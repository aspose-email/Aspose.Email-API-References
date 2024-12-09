---
title: MapiAttachmentCollection.Add
second_title: Aspose.Email for .NET API Reference
description: MapiAttachmentCollection method. Adds the new attachment as embedded message
type: docs
weight: 20
url: /net/aspose.email.mapi/mapiattachmentcollection/add/
---
## Add(string, MapiMessage) {#add_2}

Adds the new attachment as embedded message.

```csharp
public void Add(string name, MapiMessage msg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of attachment. |
| msg | MapiMessage | The [`MapiMessage`](../../mapimessage/) that represents the attached message. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if message is null. |

### See Also

* class [MapiMessage](../../mapimessage/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(string, byte[]) {#add_4}

Adds the new attachment.

```csharp
public void Add(string name, byte[] data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of attachment. |
| data | Byte[] | The attachment data. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if attachment name is null or empty. |
| ArgumentNullException | throws if attachment data is null. |

### See Also

* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(string, ReferenceAttachmentOptions) {#add_3}

Adds a reference attachment to the collection using the specified name and configuration options.

```csharp
public void Add(string name, ReferenceAttachmentOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the attachment to display in the message. |
| options | ReferenceAttachmentOptions | An instance of [`ReferenceAttachmentOptions`](../../referenceattachmentoptions/) containing the configuration details for the reference attachment, such as the shared link, URL, and provider name. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown if *options* is `null`. |

## Remarks

This method adds a reference attachment to the message and applies additional properties based on the provided [`ReferenceAttachmentOptions`](../../referenceattachmentoptions/) object. The additional properties include permission type, original permission type, folder indicator, provider endpoint URL, preview URL, and thumbnail URL.

## Examples

The following example demonstrates how to use this method in C#:

[C#]

```csharp
var options = new ReferenceAttachmentOptions(
    "https://drive.google.com/file/d/1HJ-M3F2qq1oRrTZ2GZhUdErJNy2CT3DF/",
    "https://drive.google.com/drive/my-drive",
    "GoogleDrive"
)
{
    PermissionType = AttachmentPermissionType.AnyoneCanEdit,
    OriginalPermissionType = 0,
    IsFolder = false
};

msg.Attachments.Add("Document.pdf", options);
```

The following example demonstrates how to use this method in Visual Basic:

[Visual Basic]

```csharp
Dim options As New ReferenceAttachmentOptions(
    "https://drive.google.com/file/d/1HJ-M3F2qq1oRrTZ2GZhUdErJNy2CT3DF/",
    "https://drive.google.com/drive/my-drive",
    "GoogleDrive"
)
options.PermissionType = AttachmentPermissionType.AnyoneCanEdit
options.OriginalPermissionType = 0
options.IsFolder = False

msg.Attachments.Add("Document.pdf", options)
```

### See Also

* class [ReferenceAttachmentOptions](../../referenceattachmentoptions/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(MapiAttachment) {#add}

Adds an object to the end of the Collection.

```csharp
public void Add(MapiAttachment item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | MapiAttachment | The object to be added to the end of the Collection. The value can be null for reference types. |

### See Also

* class [MapiAttachment](../../mapiattachment/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)


