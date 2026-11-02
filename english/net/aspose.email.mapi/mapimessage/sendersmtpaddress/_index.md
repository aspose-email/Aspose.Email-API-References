---
title: MapiMessage.SenderSmtpAddress
second_title: Aspose.Email for .NET API Reference
description: MapiMessage property. Gets or sets the SMTP address of the sender
type: docs
weight: 270
url: /net/aspose.email.mapi/mapimessage/sendersmtpaddress/
---
## MapiMessage.SenderSmtpAddress property

Gets or sets the SMTP address of the sender.

```csharp
public string SenderSmtpAddress { get; set; }
```

### Property Value

The SMTP address of the sender.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | The address is not valid. |

## Remarks

Use this property when the sender address is of another type, such as an Exchange (`EX`) address. Setting the address also updates the search key and the EntryID of the sender; setting `null` or an empty string clears them.

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


