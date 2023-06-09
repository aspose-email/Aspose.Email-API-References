---
title: MapiMessage.ToMapiMessageItem
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Convert MapiMessage to IMapiMessageItem object in dependence with MessageClass
type: docs
weight: 440
url: /net/aspose.email.mapi/mapimessage/tomapimessageitem/
---
## MapiMessage.ToMapiMessageItem method

Convert MapiMessage to IMapiMessageItem object in dependence with MessageClass.

```csharp
public IMapiMessageItem ToMapiMessageItem()
```

### Return Value

The IMapiMessageItem interface.

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | Thrown when MessageClass doesn't belong to IPM.Note, IPM.StickyNote, IPM.Contact, IPM.Activity, IPM.Appointment, IPM.Schedule.meeting, IPM.Task. |

## Remarks

Note, that the following message classes are supported by now: IPM.Note, IPM.StickyNote, IPM.Contact, IPM.Activity, IPM.Appointment, IPM.Schedule.meeting, IPM.Task. If MapiMessage has another class, different from these ones, then NotSupportedException is thrown. If MessageClass is IPM.Note, then MapiMessage copy is returned.

### See Also

* interface [IMapiMessageItem](../../imapimessageitem/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


