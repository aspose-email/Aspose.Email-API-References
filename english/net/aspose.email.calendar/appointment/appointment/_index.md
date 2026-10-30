---
title: Appointment.Appointment
second_title: Aspose.Email for .NET API Reference
description: Appointment constructor. Initializes a new instance of the Appointment class with the location time organizer and attendees of the event
type: docs
weight: 10
url: /net/aspose.email.calendar/appointment/appointment/
---
## Appointment(string, DateTime, DateTime, MailAddress, MailAddressCollection) {#constructor}

Initializes a new instance of the [`Appointment`](../) class with the location, time, organizer and attendees of the event.

```csharp
public Appointment(string location, DateTime startDate, DateTime endDate, MailAddress organizer, 
    MailAddressCollection attendees)
```

| Parameter | Type | Description |
| --- | --- | --- |
| location | String | The location of the event. |
| startDate | DateTime | The start date and time of the event. |
| endDate | DateTime | The end date and time of the event. |
| organizer | MailAddress | The organizer of the event. |
| attendees | MailAddressCollection | The attendees of the event. |

### See Also

* class [MailAddress](../../../aspose.email/mailaddress/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Appointment(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) {#constructor_1}

Initializes a new instance of the [`Appointment`](../) class with the location, summary, description, time, organizer and attendees of the event.

```csharp
public Appointment(string location, string summary, string description, DateTime startDate, 
    DateTime endDate, MailAddress organizer, MailAddressCollection attendees)
```

| Parameter | Type | Description |
| --- | --- | --- |
| location | String | The location of the event. |
| summary | String | The summary (subject) of the event. |
| description | String | The plain-text description of the event. |
| startDate | DateTime | The start date and time of the event. |
| endDate | DateTime | The end date and time of the event. |
| organizer | MailAddress | The organizer of the event. |
| attendees | MailAddressCollection | The attendees of the event. |

### See Also

* class [MailAddress](../../../aspose.email/mailaddress/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Appointment(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) {#constructor_3}

Initializes a new instance of the [`Appointment`](../) class with an explicit unique identifier.

```csharp
public Appointment(string location, string summary, string description, DateTime startDate, 
    DateTime endDate, MailAddress organizer, MailAddressCollection attendees, string uid)
```

| Parameter | Type | Description |
| --- | --- | --- |
| location | String | The location of the event. |
| summary | String | The summary (subject) of the event. |
| description | String | The plain-text description of the event. |
| startDate | DateTime | The start date and time of the event. |
| endDate | DateTime | The end date and time of the event. |
| organizer | MailAddress | The organizer of the event. |
| attendees | MailAddressCollection | The attendees of the event. |
| uid | String | The unique identifier of the event (the iCalendar UID property). |

### See Also

* class [MailAddress](../../../aspose.email/mailaddress/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Appointment(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) {#constructor_2}

Initializes a new instance of the [`Appointment`](../) class for a recurring event.

```csharp
public Appointment(string location, string summary, string description, DateTime startDate, 
    DateTime endDate, MailAddress organizer, MailAddressCollection attendees, 
    RecurrencePattern recurrencePattern)
```

| Parameter | Type | Description |
| --- | --- | --- |
| location | String | The location of the event. |
| summary | String | The summary (subject) of the event. |
| description | String | The plain-text description of the event. |
| startDate | DateTime | The start date and time of the event. |
| endDate | DateTime | The end date and time of the event. |
| organizer | MailAddress | The organizer of the event. |
| attendees | MailAddressCollection | The attendees of the event. |
| recurrencePattern | RecurrencePattern | The recurrence pattern of the event, or `null` for a single occurrence. |

### See Also

* class [MailAddress](../../../aspose.email/mailaddress/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [RecurrencePattern](../../../aspose.email.calendar.recurrences/recurrencepattern/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Appointment(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) {#constructor_4}

Initializes a new instance of the [`Appointment`](../) class for a recurring event with an explicit unique identifier.

```csharp
public Appointment(string location, string summary, string description, DateTime startDate, 
    DateTime endDate, MailAddress organizer, MailAddressCollection attendees, string uid, 
    RecurrencePattern recurrencePattern)
```

| Parameter | Type | Description |
| --- | --- | --- |
| location | String | The location of the event. |
| summary | String | The summary (subject) of the event. |
| description | String | The plain-text description of the event. |
| startDate | DateTime | The start date and time of the event. |
| endDate | DateTime | The end date and time of the event. |
| organizer | MailAddress | The organizer of the event. |
| attendees | MailAddressCollection | The attendees of the event. |
| uid | String | The unique identifier of the event (the iCalendar UID property). |
| recurrencePattern | RecurrencePattern | The recurrence pattern of the event, or `null` for a single occurrence. |

### See Also

* class [MailAddress](../../../aspose.email/mailaddress/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [RecurrencePattern](../../../aspose.email.calendar.recurrences/recurrencepattern/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)


