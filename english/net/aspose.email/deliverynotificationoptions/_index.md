---
title: Enum DeliveryNotificationOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.DeliveryNotificationOptions enum. Defines when the SMTP server sends a delivery status notification to the sender. The values can be combined
type: docs
weight: 16000
url: /net/aspose.email/deliverynotificationoptions/
---
## DeliveryNotificationOptions enumeration

Defines when the SMTP server sends a delivery status notification to the sender. The values can be combined.

```csharp
[Flags]
public enum DeliveryNotificationOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No preference; the server decides whether to send a notification. |
| OnSuccess | `1` | Notify when the message is delivered. |
| OnFailure | `2` | Notify when delivery fails. |
| Delay | `4` | Notify when delivery is delayed. |
| Never | `8000000` | Never send a notification. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


