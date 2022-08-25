---
title: AppointmentMethodType
second_title: Aspose.Email for Android via Java API Reference
description:  Defines the iCalendar object method type associated with the calendar object.
type: docs
weight: 33
url: /java/com.aspose.email/appointmentmethodtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AppointmentMethodType extends System.Enum
```

Defines the iCalendar object method type associated with the calendar object.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Method is not defined. |
| [Publish](#Publish) | Post notification of an event. |
| [Request](#Request) | Make a request for an event. |
| [Reply](#Reply) | Reply to an event request. |
| [Add](#Add) | Add one or more instances to an existing event. |
| [Cancel](#Cancel) | Cancel one or more instances of an existing event. |
| [Refresh](#Refresh) | A request is sent to an "Organizer" by an "Attendee" asking for the latest version of an event to be resent to the requester. |
| [Counter](#Counter) | Counter a REQUEST with an alternative proposal, Sent by an "Attendee" to the "Organizer". |
| [DeclineCounter](#DeclineCounter) | Decline a counter proposal. |
### None {#None}
```
public static final int None
```


Method is not defined.

### Publish {#Publish}
```
public static final int Publish
```


Post notification of an event. Used primarily as a method of advertising the existence of an event.

### Request {#Request}
```
public static final int Request
```


Make a request for an event. This is an explicit invitation to one or more "Attendees".

### Reply {#Reply}
```
public static final int Reply
```


Reply to an event request.

### Add {#Add}
```
public static final int Add
```


Add one or more instances to an existing event.

### Cancel {#Cancel}
```
public static final int Cancel
```


Cancel one or more instances of an existing event.

### Refresh {#Refresh}
```
public static final int Refresh
```


A request is sent to an "Organizer" by an "Attendee" asking for the latest version of an event to be resent to the requester.

### Counter {#Counter}
```
public static final int Counter
```


Counter a REQUEST with an alternative proposal, Sent by an "Attendee" to the "Organizer".

### DeclineCounter {#DeclineCounter}
```
public static final int DeclineCounter
```


Decline a counter proposal. Sent to an "Attendee" by the "Organizer".

