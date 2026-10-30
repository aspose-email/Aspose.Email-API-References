---
title: Class AlternateView
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.AlternateView class. One representation of the body of a message such as plain text or HTML. A message can carry several and the mail client shows the best one it supports
type: docs
weight: 10
url: /net/aspose.email/alternateview/
---
## AlternateView class

One representation of the body of a message, such as plain text or HTML. A message can carry several, and the mail client shows the best one it supports.

```csharp
public class AlternateView : AttachmentBase
```

## Constructors

| Name | Description |
| --- | --- |
| [AlternateView](alternateview/#constructor)(Stream) | Initializes a new instance of the `AlternateView` class with the content of a stream. |
| [AlternateView](alternateview/#constructor_3)(string) | Initializes a new instance of the `AlternateView` class with the content of a file. |
| [AlternateView](alternateview/#constructor_1)(Stream, ContentType) | Initializes a new instance of the `AlternateView` class with the content of a stream. |
| [AlternateView](alternateview/#constructor_2)(Stream, string) | Initializes a new instance of the `AlternateView` class with the content of a stream. |
| [AlternateView](alternateview/#constructor_4)(string, ContentType) | Initializes a new instance of the `AlternateView` class with the content of a file. |
| [AlternateView](alternateview/#constructor_5)(string, string) | Initializes a new instance of the `AlternateView` class with the content of a file. |

## Properties

| Name | Description |
| --- | --- |
| [BaseUri](../../aspose.email/alternateview/baseuri/) { get; set; } | Gets or sets the base URI used to resolve relative URLs in the content of the view. |
| [ContentId](../../aspose.email/attachmentbase/contentid/) { get; set; } | Gets or sets the content ID of the part, by which HTML refers to it with a `cid:` URL. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream/) { get; set; } | Gets or sets the stream that holds the content. |
| [ContentType](../../aspose.email/attachmentbase/contenttype/) { get; set; } | Gets or sets the content type of the part: its media type, name and character set. |
| virtual [Headers](../../aspose.email/attachmentbase/headers/) { get; } | Gets the MIME headers of the part. |
| [LinkedResources](../../aspose.email/alternateview/linkedresources/) { get; } | Gets the resources embedded in this view, such as the images an HTML view refers to by `cid:` URLs. |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding/) { get; set; } | Gets or sets how the content is encoded for transfer, such as Base64 or quoted-printable. |
| [UniqueId](../../aspose.email/attachmentbase/uniqueid/) { get; } | Gets an identifier of the part that stays the same while the application runs. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateAlternateViewFromString](../../aspose.email/alternateview/createalternateviewfromstring/#createalternateviewfromstring)(string) | Creates a plain-text view from a string. |
| static [CreateAlternateViewFromString](../../aspose.email/alternateview/createalternateviewfromstring/#createalternateviewfromstring_1)(string, ContentType) | Creates a view from a string with the specified content type. |
| static [CreateAlternateViewFromString](../../aspose.email/alternateview/createalternateviewfromstring/#createalternateviewfromstring_2)(string, ContentType, TransferEncoding) | Creates a view from a string with the specified content type and transfer encoding. |
| static [CreateAlternateViewFromString](../../aspose.email/alternateview/createalternateviewfromstring/#createalternateviewfromstring_3)(string, Encoding, string) | Creates a view from a string with the specified encoding and media type. |
| [Dispose](../../aspose.email/attachmentbase/dispose/)() | Releases the resources used by the part, including its content stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(Stream) | Saves the decoded content of the part to a stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(string) | Saves the decoded content of the part to a file. |

## Remarks

Use [`CreateAlternateViewFromString`](./createalternateviewfromstring/) to create alternate views from string content. Add alternate views to [`AlternateViews`](../mailmessage/alternateviews/) to include them in the message.

## Examples

The following example shows how to create and add AlternateView to MailMessage.

[C#]

```csharp
var eml = new MailMessage
{
	From = "AndrewIrwin@from.com",
	To = "SusanMarc@to.com",
	Subject = "This is an email"
};

// Create the plain text part It is viewable by those clients that don't support HTML
var plainView = AlternateView.CreateAlternateViewFromString("This is my plain text content", null, "text/plain");

// Create the HTML part.To embed images, we need to use the prefix 'cid' in the img src value.
// The cid value will map to the Content-Id of a Linked resource. Thus <img src='cid:barcode'>
// will map to a LinkedResource with a ContentId of 'barcode'.
var htmlView = AlternateView.CreateAlternateViewFromString("Here is an embedded image. <img src=cid:barcode>", null, "text/html");

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


