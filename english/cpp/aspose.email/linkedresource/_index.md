---
title: "Aspose::Email::LinkedResource class"
linktitle: "LinkedResource"
articleTitle: "LinkedResource"
second_title: "Aspose.Email for C++"
description: "Represents an embedded resource in a message."
type: docs
weight: 10
url: /cpp/aspose.email/linkedresource/
---

## LinkedResource class

**Inherits:** Aspose::Email::AttachmentBase

Represents an embedded resource in a message.

The following example shows how to embed objects using LinkedResource into an Email .

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
| [LinkedResource (8 overloads)](./linkedresource/) | Initializes a new instance of the LinkedResource class. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](./clone/) |  |
| [ConvertToMapiAttachment](./converttomapiattachment/) | Implements Aspose::Email::AttachmentBase . |
| [CreateLinkedResourceFromString (3 overloads)](./createlinkedresourcefromstring/) | Creates the linked resource from string. |
| [get_ContentDisposition](./get_contentdisposition/) | Gets Content-Disposition header |
| [get_ContentLink](./get_contentlink/) | Gets a URI that the resource must match. |
| [get_Name](./get_name/) |  |
| [set_ContentLink](./set_contentlink/) | Sets a URI that the resource must match. |

