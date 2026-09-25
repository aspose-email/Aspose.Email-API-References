---
title: MapiAttachmentCollection.Add
second_title: Aspose.Email for .NET API Reference
description: MapiAttachmentCollection method. Adds the new attachment as embedded message
type: docs
weight: 20
url: /net/aspose.email.mapi/mapiattachmentcollection/add/
---
## Add(string, MapiMessage) {#add}

Adds the new attachment as embedded message.

```csharp
public MapiAttachment Add(string name, MapiMessage msg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of attachment. |
| msg | MapiMessage | The [`MapiMessage`](../../mapimessage/) that represents the attached message. |

### Return Value

Newly created attachment[`MapiAttachment`](../../mapiattachment/)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if message is null. |

### See Also

* class [MapiAttachment](../../mapiattachment/)
* class [MapiMessage](../../mapimessage/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(string, byte[]) {#add_2}

Adds the new attachment.

```csharp
public MapiAttachment Add(string name, byte[] data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of attachment. |
| data | Byte[] | The attachment data. |

### Return Value

Newly created attachment[`MapiAttachment`](../../mapiattachment/)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if attachment name is null or empty. |
| ArgumentNullException | throws if attachment data is null. |

### See Also

* class [MapiAttachment](../../mapiattachment/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(string, Stream) {#add_3}

Adds a new attachment whose content is read from a stream.

```csharp
public MapiAttachment Add(string name, Stream content)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of attachment. |
| content | Stream | The attachment content. The stream must be seekable and readable. Content is taken from the stream's current position to its end, and the range is fixed at the moment of this call. The stream must stay open until the message is saved or the attachment content is accessed, and the caller keeps ownership of it. |

### Return Value

Newly created attachment[`MapiAttachment`](../../mapiattachment/)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown if the name is null or empty, or the content is null. |
| ArgumentException | Thrown if the content stream is not seekable or not readable. |

## Remarks

The content is not copied into memory: it is read from the stream on demand when the message is saved or when the attachment content is accessed. Modifying the contents of the stream between this call and reading the attachment gives undefined results.

Unlike [`Attachment`](../../../aspose.email/attachment/), which reads MIME content once into its own storage and therefore tolerates forward-only streams, this method requires a seekable stream: the content is read again on every save and its length must be known in advance.

### See Also

* class [MapiAttachment](../../mapiattachment/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(string, Stream, bool) {#add_4}

Adds a new attachment whose content is read from a stream.

```csharp
public MapiAttachment Add(string name, Stream content, bool leaveStreamOpen)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of attachment. |
| content | Stream | The attachment content. The stream must be seekable and readable. Content is taken from the stream's current position to its end, and the range is fixed at the moment of this call. The stream must stay open until the message is saved or the attachment content is accessed. |
| leaveStreamOpen | Boolean | When `false`, the stream is disposed together with the owning message, so the message must be disposed. When `true`, the caller keeps ownership of the stream. |

### Return Value

Newly created attachment[`MapiAttachment`](../../mapiattachment/)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown if the name is null or empty, or the content is null. |
| ArgumentException | Thrown if the content stream is not seekable or not readable. |

### See Also

* class [MapiAttachment](../../mapiattachment/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(string, ReferenceAttachmentOptions) {#add_1}

Adds a reference attachment to the collection using the specified name and configuration options.

```csharp
public MapiAttachment Add(string name, ReferenceAttachmentOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the attachment to display in the message. |
| options | ReferenceAttachmentOptions | An instance of [`ReferenceAttachmentOptions`](../../referenceattachmentoptions/) containing the configuration details for the reference attachment, such as the shared link, URL, and provider name. |

### Return Value

Newly created attachment[`MapiAttachment`](../../mapiattachment/)

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

* class [MapiAttachment](../../mapiattachment/)
* class [ReferenceAttachmentOptions](../../referenceattachmentoptions/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(MapiAttachment) {#add_5}

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


