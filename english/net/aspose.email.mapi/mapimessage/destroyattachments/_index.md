---
title: MapiMessage.DestroyAttachments
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Removes all attachments from an MSG file and overwrites the file. The attachments are not read which is faster than RemoveAttachments
type: docs
weight: 460
url: /net/aspose.email.mapi/mapimessage/destroyattachments/
---
## MapiMessage.DestroyAttachments method

Removes all attachments from an MSG file and overwrites the file. The attachments are not read, which is faster than [`RemoveAttachments`](../removeattachments/).

```csharp
public static void DestroyAttachments(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path of the MSG file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *path* is `null`. |
| ArgumentException | *path* is empty. |

## Examples

This example removes the attachments of an MSG file without reading them.

[C#]

```csharp
MapiMessage.DestroyAttachments(@"c:\messages\message.msg");
```

[Visual Basic]

```csharp
MapiMessage.DestroyAttachments("c:\messages\message.msg")
```

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


