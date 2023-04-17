---
title: MapiMessage.SenderSmtpAddress
second_title: Aspose.Email for .NET API Reference
description: MapiMessage property. Gets or sets the message senders email address
type: docs
weight: 280
url: /net/aspose.email.mapi/mapimessage/sendersmtpaddress/
---
## MapiMessage.SenderSmtpAddress property

Gets or sets the message sender's e-mail address.

```csharp
public string SenderSmtpAddress { get; set; }
```

### Property Value

The string that represents sender email address.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | throws if sender address is not in a recognized format. |

## Remarks

When setting a value, the values of PR_SENDER_SEARCH_KEY and PR_SENDER_ENTRYID properties are updated as well. When setting a null value or empty string, the values of properties are set null.

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


