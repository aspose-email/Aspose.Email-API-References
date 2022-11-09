---
title: TIPMethod
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 450
url: /python-net/aspose.email.calendar/tipmethod/
---

## TIPMethod enumeration

Defines the iTIP (iCalendar Transport-Independent Interoperability Protocol) methods associated with an object.

## Members
| Member name | Description |
| :- | :- |
|NONE|Method is not defined.|
|PUBLISH|Post notification of an object.  <br/>            Used primarily as a method of advertising the existence of an object.|
|REQUEST|Assign an object.<br/>            This is an explicit assignment to one or more Calendar Users.<br/>            The REQUEST method is also used to update or change an existing object.<br/>            Clients that cannot handle REQUEST MAY degrade the method to treat it as a PUBLISH.|
|REPLY|Reply to an object request.|
|ADD|Add one or more instances to an existing object.|
|CANCEL|Cancel one or more instances of an existing object.|
|REFRESH|A request sent to an object Organizer asking for the latest version of an object.|
|COUNTER|Counter a REQUEST with an alternative proposal.|
|DECLINE_COUNTER|Decline a counter proposal by an Attendee.|

### See Also

* namespace [aspose.email.calendar](/python-net/aspose.email.calendar/)
* assembly [Aspose.Email](/python-net/)

