---
title: Class ReferenceAttachment
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.ReferenceAttachment class. An attachment that is a link to a file in a cloud storage such as OneDrive instead of the file itself
type: docs
weight: 18770
url: /net/aspose.email/referenceattachment/
---
## ReferenceAttachment class

An attachment that is a link to a file in a cloud storage, such as OneDrive, instead of the file itself.

```csharp
public class ReferenceAttachment : Attachment
```

## Constructors

| Name | Description |
| --- | --- |
| [ReferenceAttachment](referenceattachment/#constructor)() | Initializes a new instance of `ReferenceAttachment`. |
| [ReferenceAttachment](referenceattachment/#constructor_1)(string) | Initializes a new instance of the `ReferenceAttachment` class with the URL of the file. |
| [ReferenceAttachment](referenceattachment/#constructor_2)(Uri) | Initializes a new instance of the `ReferenceAttachment` class with the URL of the file. |

## Properties

| Name | Description |
| --- | --- |
| [ContentDisposition](../../aspose.email/attachment/contentdisposition/) { get; } | Gets the `Content-Disposition` header of the attachment, which tells whether it is shown inline or as a file, and holds its file name and dates. |
| [ContentId](../../aspose.email/attachmentbase/contentid/) { get; set; } | Gets or sets the content ID of the part, by which HTML refers to it with a `cid:` URL. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream/) { get; set; } | Gets or sets the stream that holds the content. |
| [ContentType](../../aspose.email/attachmentbase/contenttype/) { get; set; } | Gets or sets the content type of the part: its media type, name and character set. |
| virtual [Headers](../../aspose.email/attachmentbase/headers/) { get; } | Gets the MIME headers of the part. |
| [IsEmbeddedMessage](../../aspose.email/attachment/isembeddedmessage/) { get; } | Gets a value indicating whether the attachment is an attached e-mail message (`message/rfc822`). |
| [IsTnef](../../aspose.email/attachment/istnef/) { get; } | Gets a value indicating whether the attachment is a TNEF-encoded message (winmail.dat). |
| [IsUri](../../aspose.email/attachment/isuri/) { get; } | Gets a value indicating whether the attachment is a link to content elsewhere rather than the content itself. |
| [Name](../../aspose.email/attachment/name/) { get; set; } | Gets or sets the file name of the attachment. |
| [NameEncoding](../../aspose.email/attachment/nameencoding/) { get; set; } | Gets or sets the encoding used for the file name of the attachment in the headers. |
| [PermissionType](../../aspose.email/referenceattachment/permissiontype/) { get; set; } | Gets or sets who can view or edit the linked file. |
| [PreferredTextEncoding](../../aspose.email/attachment/preferredtextencoding/) { get; set; } | Gets or sets the encoding used for the text of the attachment when no other encoding is specified. |
| [ProviderType](../../aspose.email/referenceattachment/providertype/) { get; set; } | Gets or sets the cloud storage service that holds the file. |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding/) { get; set; } | Gets or sets how the content is encoded for transfer, such as Base64 or quoted-printable. |
| [UniqueId](../../aspose.email/attachmentbase/uniqueid/) { get; } | Gets an identifier of the part that stays the same while the application runs. |
| [Uri](../../aspose.email/referenceattachment/uri/) { get; set; } | Gets or sets the URL of the file. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.email/attachmentbase/dispose/)() | Releases the resources used by the part, including its content stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(Stream) | Saves the decoded content of the part to a stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(string) | Saves the decoded content of the part to a file. |

### See Also

* class [Attachment](../attachment/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


