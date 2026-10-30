---
title: Enum MapiItemType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiItemType enum. Defines the type of an Outlook item which determines the class ToMapiMessageItem converts it to
type: docs
weight: 17250
url: /net/aspose.email.mapi/mapiitemtype/
---
## MapiItemType enumeration

Defines the type of an Outlook item, which determines the class [`ToMapiMessageItem`](../mapimessage/tomapimessageitem/) converts it to.

```csharp
public enum MapiItemType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | An unsupported type; the message cannot be converted. |
| Message | `1` | An e-mail message; it needs no conversion. |
| Contact | `2` | A contact item. Can be converted to [`MapiContact`](../mapicontact/). |
| Calendar | `3` | A calendar item. Can be converted to [`MapiCalendar`](../mapicalendar/). |
| DistList | `4` | A distribution list. Can be converted to [`MapiDistributionList`](../mapidistributionlist/). |
| Journal | `5` | A journal entry. Can be converted to [`MapiJournal`](../mapijournal/). |
| Note | `6` | A sticky note. Can be converted to [`MapiNote`](../mapinote/). |
| Task | `7` | A task. Can be converted to [`MapiTask`](../mapitask/). |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


