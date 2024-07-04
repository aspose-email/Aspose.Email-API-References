---
title: MapiContact.GetUnderlyingMessage
second_title: Aspose.Email for .NET API Reference
description: MapiContact method. Retrieves the underlying MapiMessage object
type: docs
weight: 130
url: /net/aspose.email.mapi/mapicontact/getunderlyingmessage/
---
## MapiContact.GetUnderlyingMessage method

Retrieves the underlying MapiMessage object.

```csharp
public MapiMessage GetUnderlyingMessage()
```

### Return Value

The [`MapiMessage`](../../mapimessage/) object.

## Examples

Retrieves the underlying MAPI message from a MapiContact object and prints out its message class.

[C#]

```csharp
// Retrieve the underlying MAPI message from the MapiContact object
MapiMessage msg = mapiContact.GetUnderlyingMessage();
   
// Print out the message class of the MAPI message
// Will output "IPM.Contact"
Console.WriteLine(msg.MessageClass);
```

[Visual Basic]

```csharp
' Retrieve the underlying MAPI message from the MapiContact object
Dim msg As MapiMessage = mapiContact.GetUnderlyingMessage()

' Print out the message class of the MAPI message
' Will output "IPM.Contact"
Console.WriteLine(msg.MessageClass)
```

### See Also

* class [MapiMessage](../../mapimessage/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)


