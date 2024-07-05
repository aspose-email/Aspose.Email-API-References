---
title: MapiTask.GetUnderlyingMessage
second_title: Aspose.Email for .NET API Reference
description: MapiTask method. Retrieves the underlying MapiMessage object
type: docs
weight: 230
url: /net/aspose.email.mapi/mapitask/getunderlyingmessage/
---
## MapiTask.GetUnderlyingMessage method

Retrieves the underlying MapiMessage object.

```csharp
public MapiMessage GetUnderlyingMessage()
```

### Return Value

The [`MapiMessage`](../../mapimessage/) object.

## Examples

Retrieves the underlying MAPI message from a MapiTask object and prints out its message class.

[C#]

```csharp
// Retrieve the underlying MAPI message from the MapiTask object
MapiMessage msg = mapiTask.GetUnderlyingMessage();
   
// Print out the message class of the MAPI message
// Will output "IPM.Task"
Console.WriteLine(msg.MessageClass);
```

[Visual Basic]

```csharp
' Retrieve the underlying MAPI message from the MapiTask object
Dim msg As MapiMessage = mapiTask.GetUnderlyingMessage()

' Print out the message class of the MAPI message
' Will output "IPM.Task"
Console.WriteLine(msg.MessageClass)
```

### See Also

* class [MapiMessage](../../mapimessage/)
* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)


