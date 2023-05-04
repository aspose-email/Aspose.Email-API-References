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

## Add(string, byte[]) {#add_3}

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

## Add(string, string, string, string) {#add_4}

Adds the reference attachment.

```csharp
public void Add(string name, string sharedLink, string url, string providerName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of attachment. |
| sharedLink | String | A fully qualified shared link to the attachment provided by web service manipulating the attachment. |
| url | String | A file location. |
| providerName | String | A name of reference attachment provider. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if attachment name is null or empty. |
| ArgumentNullException | throws if attachment shared link is null or empty. |

## Remarks

A reference attachment is a type of attachment that includes a link or a reference to a file or item, rather than including the file or item itself in the email message. When the recipients of the email click on the reference attachment, they will be able to access the linked file if they have the appropriate permissions to do so. By using a reference attachment, you can send a smaller email message and ensure that everyone has access to the most up-to-date version of the file or item.

## Examples

This example demonstrates how to add a reference attachment to a message.

[C#]

```csharp
// Let's say you want to send an email message that includes a link to a Document.pdf file stored on a Google Drive.
// Instead of attaching the document directly to the email message,
// you can create a reference attachment that links to the file on the Google Drive.

// Create a message
var msg = new MapiMessage("from@domain.com", "to@domain.com", "Outlook message file",
    "This message is created by Aspose.Email", OutlookMessageFormat.Unicode);

// Add reference attachment
msg.Attachments.Add("Document.pdf",
    "https://drive.google.com/file/d/1HJ-M3F2qq1oRrTZ2GZhUdErJNy2CT3DF/",
    "https://drive.google.com/drive/my-drive",
    "GoogleDrive");
//Also, you can set additional attachment properties
msg.Attachments[0].SetProperty(KnownPropertyList.AttachmentPermissionType, AttachmentPermissionType.AnyoneCanEdit);
msg.Attachments[0].SetProperty(KnownPropertyList.AttachmentOriginalPermissionType, 0);
msg.Attachments[0].SetProperty(KnownPropertyList.AttachmentIsFolder, false);
msg.Attachments[0].SetProperty(KnownPropertyList.AttachmentProviderEndpointUrl, "");
msg.Attachments[0].SetProperty(KnownPropertyList.AttachmentPreviewUrl, "");
msg.Attachments[0].SetProperty(KnownPropertyList.AttachmentThumbnailUrl, "");
// Finally save the message
msg.Save(@"my.msg");
```

[Visual Basic]

```csharp
' Let's say you want to send an email message that includes a link to a Document.pdf file stored on a Google Drive.
' Instead of attaching the document directly to the email message,
' you can create a reference attachment that links to the file on the Google Drive.

' Create a message
Dim msg As New MapiMessage("from@domain.com", "to@domain.com", "Outlook message file", "This message is created by Aspose.Email", OutlookMessageFormat.Unicode)

' Add reference attachment
msg.Attachments.Add("Document.pdf", "https://drive.google.com/file/d/1HJ-M3F2qq1oRrTZ2GZhUdErJNy2CT3DF/", "https://drive.google.com/drive/my-drive", "GoogleDrive")

' Also, you can set additional attachment properties
msg.Attachments(0).SetProperty(KnownPropertyList.AttachmentPermissionType, AttachmentPermissionType.AnyoneCanEdit)
msg.Attachments(0).SetProperty(KnownPropertyList.AttachmentOriginalPermissionType, AttachmentPermissionType.None)
msg.Attachments(0).SetProperty(KnownPropertyList.AttachmentIsFolder, False)
msg.Attachments(0).SetProperty(KnownPropertyList.AttachmentProviderEndpointUrl, "")
msg.Attachments(0).SetProperty(KnownPropertyList.AttachmentPreviewUrl, "")
msg.Attachments(0).SetProperty(KnownPropertyList.AttachmentThumbnailUrl, "")

' Finally save the message
msg.Save("my.msg")
```

### See Also

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


