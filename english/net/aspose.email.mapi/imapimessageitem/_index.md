---
title: Interface IMapiMessageItem
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.IMapiMessageItem interface. Defines the base interface for all Outlook message item types including messages appointments tasks contacts and notes. This interface provides common properties for accessing message class item type body content and subject across different Outlook item types
type: docs
weight: 16610
url: /net/aspose.email.mapi/imapimessageitem/
---
## IMapiMessageItem interface

Defines the base interface for all Outlook message item types including messages, appointments, tasks, contacts, and notes. This interface provides common properties for accessing message class, item type, body content, and subject across different Outlook item types.

```csharp
public interface IMapiMessageItem
```

## Properties

| Name | Description |
| --- | --- |
| [Body](../../aspose.email.mapi/imapimessageitem/body/) { get; set; } | Gets message body |
| [MessageClass](../../aspose.email.mapi/imapimessageitem/messageclass/) { get; } | Gets message class |
| [Subject](../../aspose.email.mapi/imapimessageitem/subject/) { get; set; } | Gets message subject |
| [SupportedType](../../aspose.email.mapi/imapimessageitem/supportedtype/) { get; } | Gets the supported item type. |

## Remarks

Implementing types include [`MapiMessage`](../mapimessage/), [`MapiCalendar`](../mapicalendar/), [`MapiTask`](../mapitask/), [`MapiContact`](../mapicontact/), and other message item types in the Aspose.Email library. The interface provides a consistent way to access common properties regardless of the specific Outlook item type.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


