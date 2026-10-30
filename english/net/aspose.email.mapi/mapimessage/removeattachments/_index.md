---
title: MapiMessage.RemoveAttachments
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Removes all attachments from an MSG file overwrites the file and returns the removed attachments
type: docs
weight: 490
url: /net/aspose.email.mapi/mapimessage/removeattachments/
---
## MapiMessage.RemoveAttachments method

Removes all attachments from an MSG file, overwrites the file, and returns the removed attachments.

```csharp
public static MapiAttachmentCollection RemoveAttachments(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path of the MSG file. |

### Return Value

The removed attachments.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *path* is `null`. |
| ArgumentException | *path* is empty. |

## Examples

This example removes the attachments from an MSG file and saves them to disk.

[C#]

```csharp
MapiAttachmentCollection attachments = MapiMessage.RemoveAttachments(@"c:\messages\message.msg");

foreach (MapiAttachment attachment in attachments)
{
    Console.WriteLine("Attachment: " + attachment.LongFileName);
    attachment.Save(Path.Combine(@"c:\attachments", attachment.LongFileName));
}
```

[Visual Basic]

```csharp
Dim attachments As MapiAttachmentCollection = MapiMessage.RemoveAttachments("c:\messages\message.msg")

For Each attachment As MapiAttachment In attachments
    Console.WriteLine("Attachment: " + attachment.LongFileName)
    attachment.Save(Path.Combine("c:\attachments", attachment.LongFileName))
Next
```

### See Also

* class [MapiAttachmentCollection](../../mapiattachmentcollection/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


