---
title: MapiNote.GetUnderlyingMessage
second_title: Aspose.Email for .NET API Reference
description: MapiNote method. Retrieves the underlying MapiMessage object
type: docs
weight: 80
url: /net/aspose.email.mapi/mapinote/getunderlyingmessage/
---
## MapiNote.GetUnderlyingMessage method

Retrieves the underlying MapiMessage object.

```csharp
public MapiMessage GetUnderlyingMessage()
```

### Return Value

The [`MapiMessage`](../../mapimessage/) object.

## Examples

Retrieves the underlying MAPI message from a MapiNote object and prints out its message class.

[C#]

```csharp
// Retrieve the underlying MAPI message from the MapiNote object
MapiMessage msg = mapiNote.GetUnderlyingMessage();
   
// Print out the message class of the MAPI message
// Will output "IPM.StickyNote"
Console.WriteLine(msg.MessageClass);
```

[Visual Basic]

```csharp
' Retrieve the underlying MAPI message from the MapiNote object
Dim msg As MapiMessage = mapiNote.GetUnderlyingMessage()

' Print out the message class of the MAPI message
' Will output "IPM.StickyNote"
Console.WriteLine(msg.MessageClass)
```

### See Also

* class [MapiMessage](../../mapimessage/)
* class [MapiNote](../)
* namespace [Aspose.Email.Mapi](../../mapinote/)
* assembly [Aspose.Email](../../../)


