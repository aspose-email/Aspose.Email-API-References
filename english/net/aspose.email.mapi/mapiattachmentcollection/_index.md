---
title: Class MapiAttachmentCollection
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiAttachmentCollection class. The attachments of an Outlook item
type: docs
weight: 16680
url: /net/aspose.email.mapi/mapiattachmentcollection/
---
## MapiAttachmentCollection class

The attachments of an Outlook item.

```csharp
public class MapiAttachmentCollection : List<MapiAttachment>
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiAttachmentCollection](mapiattachmentcollection/#constructor)() | Initializes a new instance of the `MapiAttachmentCollection` class. |
| [MapiAttachmentCollection](mapiattachmentcollection/#constructor_1)(MapiMessageItemBase) | Initializes a new instance of the `MapiAttachmentCollection` class that belongs to the specified item. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.email.mapi/mapiattachmentcollection/add/#add_5)(MapiAttachment) | Adds an existing attachment to the end of the collection. |
| [Add](../../aspose.email.mapi/mapiattachmentcollection/add/#add_2)(string, byte[]) | Adds a file attachment with the content in memory. |
| [Add](../../aspose.email.mapi/mapiattachmentcollection/add/#add)(string, MapiMessage) | Attaches a message as an embedded message. |
| [Add](../../aspose.email.mapi/mapiattachmentcollection/add/#add_1)(string, ReferenceAttachmentOptions) | Adds a reference attachment to the collection using the specified name and configuration options. |
| [Add](../../aspose.email.mapi/mapiattachmentcollection/add/#add_3)(string, Stream) | Adds a new attachment whose content is read from a stream. |
| [Add](../../aspose.email.mapi/mapiattachmentcollection/add/#add_4)(string, Stream, bool) | Adds a new attachment whose content is read from a stream. |
| [AddFile](../../aspose.email.mapi/mapiattachmentcollection/addfile/#addfile)(string) | Adds a new attachment reading its content from a file. The file name is used as the display name of the attachment. |
| [AddFile](../../aspose.email.mapi/mapiattachmentcollection/addfile/#addfile_1)(string, string) | Adds a new attachment reading its content from a file. |
| [Insert](../../aspose.email.mapi/mapiattachmentcollection/insert/#insert)(int, MapiAttachment) | Inserts an attachment at the specified position. |
| [Insert](../../aspose.email.mapi/mapiattachmentcollection/insert/#insert_2)(int, string, MapiMessage) | Inserts a message as an embedded attachment at the specified position. |
| [Remove](../../aspose.email.mapi/mapiattachmentcollection/remove/#remove)(MapiAttachment) | Removes the first occurrence of the attachment from the collection. |
| [RemoveAt](../../aspose.email.mapi/mapiattachmentcollection/removeat/#removeat)(int) | Removes the attachment at the specified position. |
| [Replace](../../aspose.email.mapi/mapiattachmentcollection/replace/)(int, string, MapiMessage) | Replaces the attachment at the specified position with an embedded message. |

## Remarks

Returned by [`Attachments`](../mapimessageitembase/attachments/). Besides the list operations, it adds files from memory, from a stream or from disk, embedded messages and reference (cloud) attachments.

## Examples

This example attaches a file from disk, a file from memory and another message.

[C#]

```csharp
using (var msg = new MapiMessage("from@domain.com", "to@domain.com", "Report", "See the attachments."))
{
    // the file is read when the message is saved
    msg.Attachments.AddFile("report.pdf");

    msg.Attachments.Add("notes.txt", Encoding.UTF8.GetBytes("Notes for the report"));

    var original = MapiMessage.Load("original.msg");
    msg.Attachments.Add("Original message", original);

    msg.Save("report.msg");
}
```

[Visual Basic]

```csharp
Using msg = New MapiMessage("from@domain.com", "to@domain.com", "Report", "See the attachments.")
    ' the file is read when the message is saved
    msg.Attachments.AddFile("report.pdf")

    msg.Attachments.Add("notes.txt", Encoding.UTF8.GetBytes("Notes for the report"))

    Dim original = MapiMessage.Load("original.msg")
    msg.Attachments.Add("Original message", original)

    msg.Save("report.msg")
End Using
```

### See Also

* class [MapiAttachment](../mapiattachment/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


