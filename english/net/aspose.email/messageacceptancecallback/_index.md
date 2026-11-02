---
title: Delegate MessageAcceptanceCallback
second_title: Aspose.Email for .NET API Reference
description: Represents a method that decides whether a message is included in a conversion
type: docs
weight: 17920
url: /net/aspose.email/messageacceptancecallback/
---
## MessageAcceptanceCallback delegate

Represents a method that decides whether a message is included in a conversion.

```csharp
public delegate bool MessageAcceptanceCallback(MapiMessage mapiMessage);
```

| Parameter | Type | Description |
| --- | --- | --- |
| mapiMessage | MapiMessage | [`MapiMessage`](../../aspose.email.mapi/mapimessage/) to check. |

### Return Value

`true` to convert the message; `false` to skip it.

### See Also

* class [MapiMessage](../../aspose.email.mapi/mapimessage/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


