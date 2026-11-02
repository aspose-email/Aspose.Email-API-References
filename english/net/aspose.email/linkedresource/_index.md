---
title: Class LinkedResource
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.LinkedResource class. Represents an embedded resource such as an image or file that can be referenced by an AlternateView in an email message. Linked resources are typically used to embed images fonts or other assets directly into HTML email content using ContentID references
type: docs
weight: 16390
url: /net/aspose.email/linkedresource/
---
## LinkedResource class

Represents an embedded resource (such as an image or file) that can be referenced by an [`AlternateView`](../alternateview/) in an email message. Linked resources are typically used to embed images, fonts, or other assets directly into HTML email content using Content-ID references.

```csharp
public class LinkedResource : AttachmentBase
```

## Constructors

| Name | Description |
| --- | --- |
| [LinkedResource](linkedresource/#constructor)(Stream) | Initializes a new instance of the `LinkedResource` class with the content of a stream. |
| [LinkedResource](linkedresource/#constructor_3)(string) | Initializes a new instance of the `LinkedResource` class with the content of a file. |
| [LinkedResource](linkedresource/#constructor_1)(Stream, ContentType) | Initializes a new instance of the `LinkedResource` class with the content of a stream. |
| [LinkedResource](linkedresource/#constructor_2)(Stream, string) | Initializes a new instance of the `LinkedResource` class with the content of a stream. |
| [LinkedResource](linkedresource/#constructor_4)(string, ContentType) | Initializes a new instance of the `LinkedResource` class with the content of a file. |
| [LinkedResource](linkedresource/#constructor_5)(string, string) | Initializes a new instance of the `LinkedResource` class with the content of a file. |

## Properties

| Name | Description |
| --- | --- |
| [ContentDisposition](../../aspose.email/linkedresource/contentdisposition/) { get; } | Gets the `Content-Disposition` header of the resource. |
| [ContentId](../../aspose.email/attachmentbase/contentid/) { get; set; } | Gets or sets the content ID of the part, by which HTML refers to it with a `cid:` URL. |
| [ContentLink](../../aspose.email/linkedresource/contentlink/) { get; set; } | Gets or sets the URI by which the HTML refers to the resource, as an alternative to its content ID. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream/) { get; set; } | Gets or sets the stream that holds the content. |
| [ContentType](../../aspose.email/attachmentbase/contenttype/) { get; set; } | Gets or sets the content type of the part: its media type, name and character set. |
| virtual [Headers](../../aspose.email/attachmentbase/headers/) { get; } | Gets the MIME headers of the part. |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding/) { get; set; } | Gets or sets how the content is encoded for transfer, such as Base64 or quoted-printable. |
| [UniqueId](../../aspose.email/attachmentbase/uniqueid/) { get; } | Gets an identifier of the part that stays the same while the application runs. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateLinkedResourceFromString](../../aspose.email/linkedresource/createlinkedresourcefromstring/#createlinkedresourcefromstring)(string) | Creates a linked resource from a string. |
| static [CreateLinkedResourceFromString](../../aspose.email/linkedresource/createlinkedresourcefromstring/#createlinkedresourcefromstring_1)(string, ContentType) | Creates a linked resource from a string. |
| static [CreateLinkedResourceFromString](../../aspose.email/linkedresource/createlinkedresourcefromstring/#createlinkedresourcefromstring_2)(string, Encoding, string) | Creates a linked resource from a string. |
| [Dispose](../../aspose.email/attachmentbase/dispose/)() | Releases the resources used by the part, including its content stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(Stream) | Saves the decoded content of the part to a stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(string) | Saves the decoded content of the part to a file. |

## Remarks

Linked resources are added to [`LinkedResources`](../mailmessage/linkedresources/) and referenced in HTML content using the 'cid:' prefix (e.g., &lt;img src='cid:resourceId'&gt;). They differ from regular [`Attachment`](../attachment/) objects in that they are embedded within the message body rather than appearing as downloadable attachments.

## Examples

The following example shows how to embed objects using LinkedResource into an Email.

[C#]

```csharp
var eml = new MailMessage
{
	From = "AndrewIrwin@from.com",
	To = "SusanMarc@to.com",
	Subject = "This is an email"
};

// Create the plain text part It is viewable by those clients that don't support HTML
var plainView =
	AlternateView.CreateAlternateViewFromString("This is my plain text content", null, "text/plain");

// Create the HTML part.To embed images, we need to use the prefix 'cid' in the img src value.
// The cid value will map to the Content-Id of a Linked resource. Thus <img src='cid:barcode'>
// will map to a LinkedResource with a ContentId of 'barcode'.
var htmlView =
	AlternateView.CreateAlternateViewFromString("Here is an embedded image.<img src=cid:barcode>", null,
		"text/html");

// Create the LinkedResource (embedded image) and Add the LinkedResource to the appropriate view
var barcode = new LinkedResource("1.jpg", MediaTypeNames.Image.Jpeg)
{
	ContentId = "barcode"
};

eml.LinkedResources.Add(barcode);
eml.AlternateViews.Add(plainView);
eml.AlternateViews.Add(htmlView);

eml.Save("EmbeddedImage_out.msg", SaveOptions.DefaultMsgUnicode);
```

[Visual Basic]

```csharp
Dim eml = New MailMessage With {
.From = "AndrewIrwin@from.com",
.[To] = "SusanMarc@to.com",
.Subject = "This is an email"
}

' Create the plain text part It is viewable by those clients that don't support HTML
Dim plainView = AlternateView.CreateAlternateViewFromString("This is my plain text content", Nothing, "text/plain")

' Create the HTML part.To embed images, we need to use the prefix 'cid' in the img src value.
' The cid value will map to the Content-Id of a Linked resource. Thus <img src='cid:barcode'>
' will map to a LinkedResource with a ContentId of 'barcode'.
Dim htmlView = AlternateView.CreateAlternateViewFromString("Here is an embedded image.<img src=cid:barcode>", Nothing, "text/html")

' Create the LinkedResource (embedded image) and Add the LinkedResource to the appropriate view
Dim barcode = New LinkedResource("1.jpg", MediaTypeNames.Image.Jpeg) With {
  .ContentId = "barcode"
		}

eml.LinkedResources.Add(barcode)
eml.AlternateViews.Add(plainView)
eml.AlternateViews.Add(htmlView)

eml.Save("EmbeddedImage_out.msg", SaveOptions.DefaultMsgUnicode)
```

### See Also

* class [AttachmentBase](../attachmentbase/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


