---
title: Class MapiAttachment
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiAttachment class. Represents an attachment of an Outlook item
type: docs
weight: 16670
url: /net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

Represents an attachment of an Outlook item.

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## Properties

| Name | Description |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata/) { get; set; } | Gets or sets the content of a file attachment. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page of the ANSI strings of the object. |
| [Content](../../aspose.email.mapi/mapiattachment/content/) { get; } | Gets the content of the attachment. |
| [ContentLength](../../aspose.email.mapi/mapiattachment/contentlength/) { get; } | Gets the length of the attachment content in bytes. |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname/) { get; set; } | Gets or sets the name of the attachment shown to the user. |
| [Extension](../../aspose.email.mapi/mapiattachment/extension/) { get; } | Gets the file name extension of the attachment, such as `.docx`. |
| [FileName](../../aspose.email.mapi/mapiattachment/filename/) { get; } | Gets the short (8.3) file name of the attachment, without a path. Use [`LongFileName`](./longfilename/) for the full name. |
| virtual [IsInline](../../aspose.email.mapi/mapiattachment/isinline/) { get; } | Gets a value indicating whether the attachment is shown inside the message body (an inline image, for example) rather than as a regular attachment. |
| [IsReference](../../aspose.email.mapi/mapiattachment/isreference/) { get; } | Gets a value indicating whether the attachment is stored as a reference rather than being embedded in the email. |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid/) { get; } | Gets the identifier of the attachment on the mail server, for attachments obtained from a server; `null` otherwise. |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename/) { get; } | Gets the full file name of the attachment, without a path. |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag/) { get; } | Gets the MIME content type of the attachment, such as `image/png`. |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties/) { get; } | Gets the named properties of the attachment. |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata/) { get; } | Gets the embedded object of the attachment, such as an attached Outlook message or an OLE document. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets all properties of the object. |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream/) { get; } | Gets the property stream of the attachment. |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages/) { get; } | Gets the sub-storages of the attachment. |

## Methods

| Name | Description |
| --- | --- |
| static [LoadFromTnef](../../aspose.email.mapi/mapiattachment/loadfromtnef/#loadfromtnef)(Stream) | Loads an attachment from a stream in TNEF format. |
| static [LoadFromTnef](../../aspose.email.mapi/mapiattachment/loadfromtnef/#loadfromtnef_1)(string) | Loads an attachment from a file in TNEF format. |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty/)(PropertyDescriptor) | Gets a MAPI property of the attachment by its descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of a property as a Boolean. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the value of a property as bytes. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of a property as a date and time. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the value of a property as a 32-bit integer. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of a property as a 64-bit integer. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of a property as a 16-bit integer. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the value of a property as a string. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines whether the string properties of the object are stored in Unicode. |
| [OpenRead](../../aspose.email.mapi/mapiattachment/openread/)() | Opens the attachment content for reading. |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty/)(long) | Removes a property from the attachment, including its named-property mapping. |
| [Save](../../aspose.email.mapi/mapiattachment/save/#save)(Stream) | Saves the content of the attachment to a stream. An embedded message is saved in MSG format. |
| [Save](../../aspose.email.mapi/mapiattachment/save/#save_1)(string) | Saves the content of the attachment to a file. An embedded message is saved in MSG format. |
| [SaveAsync](../../aspose.email.mapi/mapiattachment/saveasync/#saveasync)(Stream, CancellationToken) | Save attachment content asynchronously. |
| [SaveAsync](../../aspose.email.mapi/mapiattachment/saveasync/#saveasync_1)(string, CancellationToken) | Save attachment content asynchronously. |
| [SaveToTnef](../../aspose.email.mapi/mapiattachment/savetotnef/#savetotnef)(Stream) | Saves the attachment to a stream in TNEF format. |
| [SaveToTnef](../../aspose.email.mapi/mapiattachment/savetotnef/#savetotnef_1)(string) | Saves the attachment to a file in TNEF format. |
| [SaveToTnefAsync](../../aspose.email.mapi/mapiattachment/savetotnefasync/#savetotnefasync)(Stream, CancellationToken) | Save attachment to tnef content asynchronously. |
| [SaveToTnefAsync](../../aspose.email.mapi/mapiattachment/savetotnefasync/#savetotnefasync_1)(string, CancellationToken) | Save attachment to tnef content asynchronously. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty/#setproperty)(MapiProperty) | Adds the property to the attachment, or replaces the property with the same tag. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty/#setproperty_1)(PropertyDescriptor, object) | Sets the value of a MAPI property of the attachment. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Gets the value of a property as bytes. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of a property as a date and time, if the property exists. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Gets the value of a property as a string. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of a property as a string, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |

## Remarks

An attachment is either a file, whose content is in [`BinaryData`](./binarydata/), or an embedded object, such as an attached Outlook message, which is in [`ObjectData`](./objectdata/). Like the message itself, the attachment is a set of MAPI properties: use the inherited property methods for data that has no dedicated member.

Add attachments through the [`MapiAttachmentCollection`](../mapiattachmentcollection/) returned by [`Attachments`](../mapimessageitembase/attachments/).

## Examples

This example saves the attachments of a message: an embedded message is loaded as a [`MapiMessage`](../mapimessage/), any other attachment is saved to a file.

[C#]

```csharp
var msg = MapiMessage.Load("source.msg");

foreach (MapiAttachment attachment in msg.Attachments)
{
    if (attachment.IsInline)
    {
        // an image or object shown in the message body
        Console.WriteLine($"Inline: {attachment.DisplayName}");
    }
    else if (attachment.ObjectData != null && attachment.ObjectData.IsOutlookMessage)
    {
        // an attached Outlook message
        MapiMessage embedded = attachment.ObjectData.ToMapiMessage();
        Console.WriteLine($"Embedded message: {embedded.Subject}");
    }
    else
    {
        attachment.Save(Path.Combine("output", attachment.LongFileName));
    }
}
```

[Visual Basic]

```csharp
Dim msg = MapiMessage.Load("source.msg")

For Each attachment As MapiAttachment In msg.Attachments
    If attachment.IsInline Then
        ' an image or object shown in the message body
        Console.WriteLine($"Inline: {attachment.DisplayName}")
    ElseIf attachment.ObjectData IsNot Nothing AndAlso attachment.ObjectData.IsOutlookMessage Then
        ' an attached Outlook message
        Dim embedded As MapiMessage = attachment.ObjectData.ToMapiMessage()
        Console.WriteLine($"Embedded message: {embedded.Subject}")
    Else
        attachment.Save(Path.Combine("output", attachment.LongFileName))
    End If
Next
```

### See Also

* class [MapiPropertyContainer](../mapipropertycontainer/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


