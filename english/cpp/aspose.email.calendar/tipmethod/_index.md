---
title: "TIPMethod Enum"
linktitle: "TIPMethod"
articleTitle: "TIPMethod"
second_title: "Aspose.Email for C++"
description: "Defines the iTIP (iCalendar Transport-Independent Interoperability Protocol) methods associated with an object."
type: docs
weight: 10
url: /cpp/aspose.email.calendar/tipmethod/
---

## TIPMethod enumeration (9 values)

Defines the iTIP (iCalendar Transport-Independent Interoperability Protocol) methods associated with an object.

| Value | Description |
| --- | --- |
| None | Method is not defined. |
| Publish | Post notification of an object. Used primarily as a method of advertising the existence of an object. |
| Request | Assign an object. This is an explicit assignment to one or more Calendar Users. The REQUEST method is also used to update or change an existing object. Clients that cannot handle REQUEST MAY degrade the method to treat it as a PUBLISH. |
| Reply | Reply to an object request. |
| Add | Add one or more instances to an existing object. |
| Cancel | Cancel one or more instances of an existing object. |
| Refresh | A request sent to an object Organizer asking for the latest version of an object. |
| Counter | Counter a REQUEST with an alternative proposal. |
| DeclineCounter | Decline a counter proposal by an Attendee. |

