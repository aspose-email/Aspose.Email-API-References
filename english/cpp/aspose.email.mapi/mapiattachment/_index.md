---
title: "Aspose::Email::Mapi::MapiAttachment class"
linktitle: "MapiAttachment"
articleTitle: "MapiAttachment"
second_title: "Aspose.Email for C++"
description: "Represents a message attachment."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapiattachment/
---

## MapiAttachment class

**Inherits:** Aspose::Email::Mapi::MapiPropertyContainer

Represents a message attachment.

This class encapsulates an attachment, providing methods to access and manipulate its properties.

This code example loads a message from a file and iterates over each attachment. If an attachment is inline, it prints its display name. If not, it checks if the attachment is an embedded message. If so, it saves the attachment to a memory stream. If not, it saves to a specified path.

```csharp
// Load the MAPI message from the specified file
var msg = MapiMessage.Load("source.msg");
 
// Iterate over each attachment in the MAPI message
foreach (var mapiAttachment in msg.Attachments)
{
 // Check if the attachment is inline
 if (mapiAttachment.IsInline)
    {
 // If inline, print its display name
        Console.WriteLine($"Inline: {mapiAttachment.DisplayName}");
    }
 else
    {
 // If not inline
 // Check if the attachment contains an embedded message
 if (mapiAttachment.ObjectData != null && mapiAttachment.ObjectData.IsOutlookMessage)
        {
 // If it's an embedded message
 // Save the attachment to a memory stream
 using (MemoryStream ms = new MemoryStream())
            {
                mapiAttachment.Save(ms);
                ms.Position = 0;
 // Load the embedded message from the memory stream
                var embeddedMessage = MapiMessage.Load(ms);
            }
        }
 else
        {
 // If it's not an embedded message
 // Save the attachment to the specified path
            mapiAttachment.Save(Path.Combine(path, mapiAttachment.LongFileName));
        }
    }
}
```

```vb
' Load the MAPI message from the specified file
Dim msg = MapiMessage.Load("source.msg")
 
' Iterate over each attachment in the MAPI message
For Each mapiAttachment In msg.Attachments
 ' Check if the attachment is inline
    If mapiAttachment.IsInline Then
        ' If inline, print its display name
        Console.WriteLine($"Inline: {mapiAttachment.DisplayName}")
    Else
 ' If not inline
        ' Check if the attachment contains an embedded message
        If mapiAttachment.ObjectData IsNot Nothing AndAlso mapiAttachment.ObjectData.IsOutlookMessage Then
 ' If it's an embedded message
 ' Save the attachment to a memory stream
            Using ms As New MemoryStream()
                mapiAttachment.Save(ms)
                ms.Position = 0
                ' Load the embedded message from the memory stream
                Dim embeddedMessage = MapiMessage.Load(ms)
 End Using
        Else
 ' If it's not an embedded message
 ' Save the attachment to the specified path
            mapiAttachment.Save(Path.Combine(path, mapiAttachment.LongFileName))
        End If
    End If
Next
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiAttachment (8 overloads)](./mapiattachment/) | Initializes a new instance of the MapiAttachment class. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](./clone/) |  |
| [CreateMapiNode](./createmapinode/) | Creates the mapi node. |
| [get_BinaryData](./get_binarydata/) | Gets binary attachment data. |
| [get_Content](./get_content/) | Gets the content. |
| [get_ContentId](./get_contentid/) |  |
| [get_DisplayName](./get_displayname/) | Gets the display name of the ole object in an attachment. |
| [get_Extension](./get_extension/) | Gets a filename extension that indicates the document type of an attachment. |
| [get_FileName](./get_filename/) | Gets an attachment's base filename and extension, excluding path. |
| [get_Hidden](./get_hidden/) |  |
| [get_IsInline](./get_isinline/) | Gets a value indicating whether the attachment is inline or regular. If inline returns true, otherwise false. |
| [get_IsReference](./get_isreference/) | Gets a value indicating whether the attachment is stored as a reference rather than being embedded in the email. |
| [get_ItemId](./get_itemid/) | The item id, uses with a server |
| [get_LongFileName](./get_longfilename/) | Gets an attachment's long filename and extension, excluding path. |
| [get_MimeTag](./get_mimetag/) | Gets formatting information about a Multipurpose Internet Mail Extensions (MIME) attachment. |
| [get_NamedProperties](./get_namedproperties/) | Gets the named properties of message. |
| [get_ObjectData](./get_objectdata/) | Gets an attachment object typically accessed through the OLE IStorage interface. |
| [get_PropertyStream](./get_propertystream/) | Gets the property stream. |
| [get_SubStorages](./get_substorages/) | Gets the sub storages. |
| [GetProperty](./getproperty/) | Gets MAPI property by property descriptor. |
| [GetSize](./getsize/) | Gets the size of the attachment. Contains the sum, in bytes, of the sizes of all properties on an attachment. The sum contained in PR_ATTACH_SIZE property includes the size of the PR_ATTACH_DATA_BIN or PR_ATTACH_DATA_OBJ property. |
| [LoadFromTnef (2 overloads)](./loadfromtnef/) | Load MapiAttachment from stream with tnef content. |
| [RemoveProperty](./removeproperty/) | Provides correctly removing property from all collections. |
| [Save (2 overloads)](./save/) | Save attachment content. |
| [SaveInternal](./saveinternal/) | Save attachment content. |
| [SaveToTnef (2 overloads)](./savetotnef/) | Save attachment to tnef content. |
| [SaveToTnefInternal](./savetotnefinternal/) |  |
| [set_BinaryData](./set_binarydata/) | Sets binary attachment data. |
| [set_DisplayName](./set_displayname/) | Gets the display name of the ole object in an attachment. |
| [set_ItemId](./set_itemid/) | The item id, uses with a server |
| [SetNamedPropertyMapping](./setnamedpropertymapping/) | Sets the named property mapping. |
| [SetOwner](./setowner/) | Sets the owner. |
| [SetProperty (2 overloads)](./setproperty/) | Sets the property. |
| [ToMapiMessage](./tomapimessage/) |  |
| [ToMemoryStream](./tomemorystream/) |  |
| [TryGetNamedProperty](./trygetnamedproperty/) | If MapiNamedPropertyMappingStorage is available, initializes and returns MapiNamedProperty , otherwise null. |
| [Aspose::Email::Clients::Graph::GraphClientV1](./asposeemailclientsgraphgraphclientv1/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::CreateAttachmentCommand](./asposeemailclientsgraphv1commandscreateattachmentcommand/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::CreateTaskAttachmentCommand](./asposeemailclientsgraphv1commandscreatetaskattachmentcommand/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::GetAttachmentCommand](./asposeemailclientsgraphv1commandsgetattachmentcommand/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::GetTaskAttachmentCommand](./asposeemailclientsgraphv1commandsgettaskattachmentcommand/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::ListAttachmentsCommand](./asposeemailclientsgraphv1commandslistattachmentscommand/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::ListTaskAttachmentsCommand](./asposeemailclientsgraphv1commandslisttaskattachmentscommand/) |  |
| [namedPropertyMappingStorage](./namedpropertymappingstorage/) | The named property mapping storage. |

