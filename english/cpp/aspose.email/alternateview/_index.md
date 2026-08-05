---
title: "Aspose::Email::AlternateView class"
linktitle: "AlternateView"
articleTitle: "AlternateView"
second_title: "Aspose.Email for C++"
description: "Represents the format to view a message."
type: docs
weight: 10
url: /cpp/aspose.email/alternateview/
---

## AlternateView class

**Inherits:** Aspose::Email::AttachmentBase

Represents the format to view a message.

The following example shows how to create and add AlternateView to MailMessage .

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

```vb
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

## Constructors

| Name | Description |
| --- | --- |
| [AlternateView (8 overloads)](./alternateview/) | Initializes a new instance of the AlternateView class. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](./clone/) |  |
| [ConvertToMapiAttachment](./converttomapiattachment/) | Implements Aspose::Email::AttachmentBase . |
| [CreateAlternateViewFromString (5 overloads)](./createalternateviewfromstring/) | Creates a AlternateView of using the content specified in a string. |
| [Dispose](./dispose/) | Releases unmanaged and - optionally - managed resources. |
| [get_BaseUri](./get_baseuri/) | Gets the base URI. |
| [get_LinkedResources](./get_linkedresources/) | Gets the set of embedded resources referred to by this alternate view. |
| [set_BaseUri](./set_baseuri/) | Sets the base URI. |
| [baseObject](./baseobject/) | Reference to the base object |

