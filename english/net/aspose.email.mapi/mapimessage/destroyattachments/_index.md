---
title: MapiMessage.DestroyAttachments
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Destroies the attachments in the specified Outlook Message files. DestroyAttachments will ignore the attachment parsing
type: docs
weight: 460
url: /net/aspose.email.mapi/mapimessage/destroyattachments/
---
## MapiMessage.DestroyAttachments method

Destroies the attachments in the specified Outlook Message files. DestroyAttachments will ignore the attachment parsing.

```csharp
public static void DestroyAttachments(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The name of the Outlook Message file. |

## Examples

The following exmaple demonstrates how to destroy attachments in Outlook Message files.

[C#]

```csharp
//Destroy attachments from Outlook Message files
MapiMessage.DestroyAttachment(@"c:\outlookmessage.msg");
```

[Visual Basic]

```csharp
'Destroy attachments from Outlook Message files
MapiMessage.DestroyAttachment("c:\outlookmessage.msg")
```

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


