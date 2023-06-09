---
title: Enum DeliveryNotificationOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.DeliveryNotificationOptions enum. Specifies delivery notifications
type: docs
weight: 17250
url: /net/aspose.email/deliverynotificationoptions/
---
## DeliveryNotificationOptions enumeration

Specifies delivery notifications.

```csharp
[Flags]
public enum DeliveryNotificationOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No notification information will be sent. The mail server will utilize its configured behavior to determine whether it should generate a delivery notification. |
| OnSuccess | `1` | Notify if the delivery is successful. |
| OnFailure | `2` | Notify if the delivery is unsuccessful. |
| Delay | `4` | Notify if the delivery is delayed. |
| Never | `8000000` | A notification should not be generated under any circumstances. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


