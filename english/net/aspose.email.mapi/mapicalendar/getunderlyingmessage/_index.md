---
title: MapiCalendar.GetUnderlyingMessage
second_title: Aspose.Email for .NET API Reference
description: MapiCalendar method. Retrieves the underlying MapiMessage object
type: docs
weight: 220
url: /net/aspose.email.mapi/mapicalendar/getunderlyingmessage/
---
## MapiCalendar.GetUnderlyingMessage method

Retrieves the underlying MapiMessage object.

```csharp
public MapiMessage GetUnderlyingMessage()
```

### Return Value

The [`MapiMessage`](../../mapimessage/) object.

## Examples

Retrieves the underlying MAPI message from a MapiCalendar object and prints out its message class.

[C#]

```csharp
// Retrieve the underlying MAPI message from the MapiCalendar object
MapiMessage msg = mapiCalendar.GetUnderlyingMessage();
   
// Print out the message class of the MAPI message
// Will output "IPM.Appointment"
Console.WriteLine(msg.MessageClass);
```

[Visual Basic]

```csharp
' Retrieve the underlying MAPI message from the MapiCalendar object
Dim msg As MapiMessage = mapiCalendar.GetUnderlyingMessage()

' Print out the message class of the MAPI message
' Will output "IPM.Appointment"
Console.WriteLine(msg.MessageClass)
```

### See Also

* class [MapiMessage](../../mapimessage/)
* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)


