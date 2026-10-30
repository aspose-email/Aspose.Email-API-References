---
title: MapiMessage.SenderEmailAddress
second_title: Aspose.Email for .NET API Reference
description: MapiMessage property. Gets or sets the message senders email address
type: docs
weight: 250
url: /net/aspose.email.mapi/mapimessage/senderemailaddress/
---
## MapiMessage.SenderEmailAddress property

Gets or sets the message sender's e-mail address.

```csharp
public string SenderEmailAddress { get; set; }
```

### Property Value

The e-mail address of the sender.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | The address is not valid. |

## Remarks

Setting the address also updates the search key and the EntryID of the sender. Setting `null` or an empty string clears them.

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


