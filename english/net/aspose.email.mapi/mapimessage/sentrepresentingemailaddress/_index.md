---
title: MapiMessage.SentRepresentingEmailAddress
second_title: Aspose.Email for .NET API Reference
description: MapiMessage property. Gets or sets the email address of the user on whose behalf the message was sent
type: docs
weight: 290
url: /net/aspose.email.mapi/mapimessage/sentrepresentingemailaddress/
---
## MapiMessage.SentRepresentingEmailAddress property

Gets or sets the e-mail address of the user on whose behalf the message was sent.

```csharp
public string SentRepresentingEmailAddress { get; set; }
```

### Property Value

The e-mail address.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | The address is not valid. |

## Remarks

Setting the address also updates the search key and the EntryID of that user. Setting `null` or an empty string clears them.

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


