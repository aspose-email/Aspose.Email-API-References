---
title: MapiMessage.RemoveAttachments
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Removes all of the attachments from the specified Outlook Message files
type: docs
weight: 470
url: /net/aspose.email.mapi/mapimessage/removeattachments/
---
## MapiMessage.RemoveAttachments method

Removes all of the attachments from the specified Outlook Message files.

```csharp
public static MapiAttachmentCollection RemoveAttachments(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The name of the Outlook Message file. |

### Return Value

The attachments collection.

## Examples

The following exmaple demonstrates how to destroy attachments in Outlook Message files.

[C#]

```csharp
//Remove attachments from Outlook Message files
MapiAttachmentCollection attachments = MapiMessage.RemoveAttachments(@"c:\outlookmessage.msg");

//Attachments
foreach(MapiAttachment att in attachments)
{
   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
}
```

[Visual Basic]

```csharp
'Remove attachments from Outlook Message files
MapiAttachmentCollection attachments = MapiMessage.RemoveAttachments("c:\outlookmessage.msg");

'Attachments 
For Each att As MapiAttachment In msg.Attachments 
     Console.WriteLine("Attachment Name:" + att.FileName) 
     att.Save(att.FileName) 
Next
```

### See Also

* class [MapiAttachmentCollection](../../mapiattachmentcollection/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


