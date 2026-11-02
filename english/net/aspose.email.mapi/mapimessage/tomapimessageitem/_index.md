---
title: MapiMessage.ToMapiMessageItem
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Converts the message to the item class that matches its message class such as MapiContact for IPM.Contact
type: docs
weight: 450
url: /net/aspose.email.mapi/mapimessage/tomapimessageitem/
---
## MapiMessage.ToMapiMessageItem method

Converts the message to the item class that matches its message class, such as [`MapiContact`](../../mapicontact/) for `IPM.Contact`.

```csharp
public IMapiMessageItem ToMapiMessageItem()
```

### Return Value

The item: a [`MapiContact`](../../mapicontact/), [`MapiCalendar`](../../mapicalendar/), [`MapiTask`](../../mapitask/), [`MapiNote`](../../mapinote/), [`MapiJournal`](../../mapijournal/) or [`MapiDistributionList`](../../mapidistributionlist/); a copy of the message for `IPM.Note`.

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | The message class is not one of the supported classes. |

## Remarks

The supported message classes are `IPM.Note`, `IPM.Contact`, `IPM.DistList`, `IPM.Appointment`, `IPM.Schedule.Meeting`, `IPM.Task`, `IPM.StickyNote` and `IPM.Activity`. Check [`SupportedType`](../../mapimessageitembase/supportedtype/) before the call to avoid the exception.

### See Also

* interface [IMapiMessageItem](../../imapimessageitem/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


