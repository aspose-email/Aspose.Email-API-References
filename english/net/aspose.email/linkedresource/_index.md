---
title: Class LinkedResource
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.LinkedResource class. Represents an embedded resource in a message
type: docs
weight: 17800
url: /net/aspose.email/linkedresource/
---
## LinkedResource class

Represents an embedded resource in a message.

```csharp
public class LinkedResource : AttachmentBase
```

## Constructors

| Name | Description |
| --- | --- |
| [LinkedResource](linkedresource/#constructor)(Stream) | Initializes a new instance of the `LinkedResource` class. |
| [LinkedResource](linkedresource/#constructor_3)(string) | Initializes a new instance of the `LinkedResource` class. |
| [LinkedResource](linkedresource/#constructor_1)(Stream, ContentType) | Initializes a new instance of the `LinkedResource` class. |
| [LinkedResource](linkedresource/#constructor_2)(Stream, string) | Initializes a new instance of the `LinkedResource` class. |
| [LinkedResource](linkedresource/#constructor_4)(string, ContentType) | Initializes a new instance of the `LinkedResource` class. |
| [LinkedResource](linkedresource/#constructor_5)(string, string) | Initializes a new instance of the `LinkedResource` class. |

## Properties

| Name | Description |
| --- | --- |
| [ContentDisposition](../../aspose.email/linkedresource/contentdisposition/) { get; } | Gets Content-Disposition header |
| [ContentId](../../aspose.email/attachmentbase/contentid/) { get; set; } | Gets or sets the content id. |
| [ContentLink](../../aspose.email/linkedresource/contentlink/) { get; set; } | Gets or sets a URI that the resource must match. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream/) { get; set; } | Gets or sets the content stream. |
| [ContentType](../../aspose.email/attachmentbase/contenttype/) { get; set; } | Gets or sets the type of the content. |
| virtual [Headers](../../aspose.email/attachmentbase/headers/) { get; } | Gets headers collection of attachment. |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding/) { get; set; } | Gets or sets the transfer encoding. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateLinkedResourceFromString](../../aspose.email/linkedresource/createlinkedresourcefromstring/#createlinkedresourcefromstring)(string) | Creates the linked resource from string. |
| static [CreateLinkedResourceFromString](../../aspose.email/linkedresource/createlinkedresourcefromstring/#createlinkedresourcefromstring_1)(string, ContentType) | Creates the linked resource from string. |
| static [CreateLinkedResourceFromString](../../aspose.email/linkedresource/createlinkedresourcefromstring/#createlinkedresourcefromstring_2)(string, Encoding, string) | Creates the linked resource from string. |
| [Dispose](../../aspose.email/attachmentbase/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(Stream) | Saves the specified stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(string) | Saves the specified file name. |

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


