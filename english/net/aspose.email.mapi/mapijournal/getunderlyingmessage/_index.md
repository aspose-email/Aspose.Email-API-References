---
title: MapiJournal.GetUnderlyingMessage
second_title: Aspose.Email for .NET API Reference
description: MapiJournal method. Retrieves the underlying MapiMessage object
type: docs
weight: 90
url: /net/aspose.email.mapi/mapijournal/getunderlyingmessage/
---
## MapiJournal.GetUnderlyingMessage method

Retrieves the underlying MapiMessage object.

```csharp
public MapiMessage GetUnderlyingMessage()
```

### Return Value

The [`MapiMessage`](../../mapimessage/) object.

## Examples

Retrieves the underlying MAPI message from a MapiJournal object and prints out its message class.

[C#]

```csharp
// Retrieve the underlying MAPI message from the MapiJournal object
MapiMessage msg = mapiJournal.GetUnderlyingMessage();
   
// Print out the message class of the MAPI message
// Will output "IPM.Activity"
Console.WriteLine(msg.MessageClass);
```

[Visual Basic]

```csharp
' Retrieve the underlying MAPI message from the MapiJournal object
Dim msg As MapiMessage = mapiJournal.GetUnderlyingMessage()

' Print out the message class of the MAPI message
' Will output "IPM.Activity"
Console.WriteLine(msg.MessageClass)
```

### See Also

* class [MapiMessage](../../mapimessage/)
* class [MapiJournal](../)
* namespace [Aspose.Email.Mapi](../../mapijournal/)
* assembly [Aspose.Email](../../../)


