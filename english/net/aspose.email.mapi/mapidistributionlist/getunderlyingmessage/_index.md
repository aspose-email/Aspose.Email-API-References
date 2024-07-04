---
title: MapiDistributionList.GetUnderlyingMessage
second_title: Aspose.Email for .NET API Reference
description: MapiDistributionList method. Retrieves the underlying MapiMessage object
type: docs
weight: 50
url: /net/aspose.email.mapi/mapidistributionlist/getunderlyingmessage/
---
## MapiDistributionList.GetUnderlyingMessage method

Retrieves the underlying MapiMessage object.

```csharp
public MapiMessage GetUnderlyingMessage()
```

### Return Value

The [`MapiMessage`](../../mapimessage/) object.

## Examples

Retrieves the underlying MAPI message from a MapiDistributionList object and prints out its message class.

[C#]

```csharp
// Retrieve the underlying MAPI message from the MapiDistributionList object
MapiMessage msg = mapiDistributionList.GetUnderlyingMessage();
   
// Print out the message class of the MAPI message
// Will output "IPM.DistList"
Console.WriteLine(msg.MessageClass);
```

[Visual Basic]

```csharp
' Retrieve the underlying MAPI message from the MapiDistributionList object
Dim msg As MapiMessage = mapiDistributionList.GetUnderlyingMessage()

' Print out the message class of the MAPI message
' Will output "IPM.DistList"
Console.WriteLine(msg.MessageClass)
```

### See Also

* class [MapiMessage](../../mapimessage/)
* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)


