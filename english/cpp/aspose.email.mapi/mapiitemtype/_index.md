---
title: "MapiItemType Enum"
linktitle: "MapiItemType"
articleTitle: "MapiItemType"
second_title: "Aspose.Email for C++"
description: "Represents a MAPI item type that can be explicitly converted into an object of the corresponding class derived from the IMapiMessageItem interface."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapiitemtype/
---

## MapiItemType enumeration (8 values)

Represents a MAPI item type that can be explicitly converted into an object of the corresponding class derived from the IMapiMessageItem interface.

| Value | Description |
| --- | --- |
| None | Non-supported type. MapiMessage cannot be converted to an appropriate item type. |
| Message | An email message. This type does not need to be converted. |
| Contact | A contact item. Can be converted to MapiContact . if (mapiMessage.SupportedType == MapiItemType.Contact ) { var contact = ( MapiContact )mapiMessage.ToMapiMessageItem(); } |
| Calendar | A calendar item. Can be converted to MapiCalendar . if (mapiMessage.SupportedType == MapiItemType.Calendar ) { var calendar = ( MapiCalendar )mapiMessage.ToMapiMessageItem(); } |
| DistList | A distribution list. Can be converted to MapiDistributionList . if (mapiMessage.SupportedType == MapiItemType.DistList) { var distList = ( MapiDistributionList )mapiMessage.ToMapiMessageItem(); } |
| Journal | A Journal entry. Can be converted to MapiJournal . if (mapiMessage.SupportedType == MapiItemType.Journal) { var journal = ( MapiJournal )mapiMessage.ToMapiMessageItem(); } |
| Note | A StickyNote. Can be converted to MapiNote . if (mapiMessage.SupportedType == MapiItemType.Note ) { var note = ( MapiNote )mapiMessage.ToMapiMessageItem(); } |
| Task | A Task item. Can be converted to MapiTask . if (mapiMessage.SupportedType == MapiItemType.Task ) { var task = ( MapiTask )mapiMessage.ToMapiMessageItem(); } |

