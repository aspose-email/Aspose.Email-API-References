---
title: Interface IMapiMessageItem
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.IMapiMessageItem interface. The common interface of Outlook items messages appointments tasks contacts notes journal entries and distribution lists
type: docs
weight: 16610
url: /net/aspose.email.mapi/imapimessageitem/
---
## IMapiMessageItem interface

The common interface of Outlook items: messages, appointments, tasks, contacts, notes, journal entries and distribution lists.

```csharp
public interface IMapiMessageItem
```

## Properties

| Name | Description |
| --- | --- |
| [Body](../../aspose.email.mapi/imapimessageitem/body/) { get; set; } | Gets or sets the plain-text body of the item. |
| [MessageClass](../../aspose.email.mapi/imapimessageitem/messageclass/) { get; } | Gets the message class of the item, such as `IPM.Note` or `IPM.Contact`. |
| [Subject](../../aspose.email.mapi/imapimessageitem/subject/) { get; set; } | Gets or sets the subject of the item. |
| [SupportedType](../../aspose.email.mapi/imapimessageitem/supportedtype/) { get; } | Gets the type of the item, as determined by its message class. |

## Remarks

Implemented by [`MapiMessage`](../mapimessage/) and by the item classes derived from [`MapiMessageItemBase`](../mapimessageitembase/). [`ToMapiMessageItem`](../mapimessage/tomapimessageitem/) returns the item class that matches the message class, so check [`SupportedType`](./supportedtype/) or the run-time type of the result.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


