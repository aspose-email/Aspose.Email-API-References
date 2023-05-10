---
title: Class AlternateView
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.AlternateView class. Represents the format to view a message
type: docs
weight: 30
url: /net/aspose.email/alternateview/
---
## AlternateView class

Represents the format to view a message.

```csharp
public class AlternateView : AttachmentBase
```

## Constructors

| Name | Description |
| --- | --- |
| [AlternateView](alternateview/#constructor)(Stream) | Initializes a new instance of the `AlternateView` class. |
| [AlternateView](alternateview/#constructor_3)(string) | Initializes a new instance of the `AlternateView` class. |
| [AlternateView](alternateview/#constructor_1)(Stream, ContentType) | Initializes a new instance of the `AlternateView` class. |
| [AlternateView](alternateview/#constructor_2)(Stream, string) | Initializes a new instance of the `AlternateView` class. |
| [AlternateView](alternateview/#constructor_4)(string, ContentType) | Initializes a new instance of the `AlternateView` class. |
| [AlternateView](alternateview/#constructor_5)(string, string) | Initializes a new instance of the `AlternateView` class. |

## Properties

| Name | Description |
| --- | --- |
| [BaseUri](../../aspose.email/alternateview/baseuri/) { get; set; } | Gets or sets the base URI. |
| [ContentId](../../aspose.email/attachmentbase/contentid/) { get; set; } | Gets or sets the content id. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream/) { get; set; } | Gets or sets the content stream. |
| [ContentType](../../aspose.email/attachmentbase/contenttype/) { get; set; } | Gets or sets the type of the content. |
| virtual [Headers](../../aspose.email/attachmentbase/headers/) { get; } | Gets headers collection of attachment. |
| [LinkedResources](../../aspose.email/alternateview/linkedresources/) { get; } | Gets the set of embedded resources referred to by this alternate view. |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding/) { get; set; } | Gets or sets the transfer encoding. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateAlternateViewFromString](../../aspose.email/alternateview/createalternateviewfromstring/#createalternateviewfromstring)(string) | Creates a AlternateView of using the content specified in a string. |
| static [CreateAlternateViewFromString](../../aspose.email/alternateview/createalternateviewfromstring/#createalternateviewfromstring_1)(string, ContentType) | Creates a AlternateView of using the content specified in a string. |
| static [CreateAlternateViewFromString](../../aspose.email/alternateview/createalternateviewfromstring/#createalternateviewfromstring_2)(string, ContentType, TransferEncoding) | Creates a AlternateView of using the content specified in a string. |
| static [CreateAlternateViewFromString](../../aspose.email/alternateview/createalternateviewfromstring/#createalternateviewfromstring_3)(string, Encoding, string) | Creates a AlternateView of using the content specified in a string. |
| [Dispose](../../aspose.email/attachmentbase/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(Stream) | Saves the specified stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(string) | Saves the specified file name. |

## Examples

The following example shows how to create and add AlternateView to MailMessage

```csharp
[C#]
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
	var htmlView = AlternateView.CreateAlternateViewFromString("Here is an embedded image.<img src=cid:barcode>", null, "text/html");

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

```csharp
[VB.NET]

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


