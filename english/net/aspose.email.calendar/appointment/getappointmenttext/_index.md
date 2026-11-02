---
title: Appointment.GetAppointmentText
second_title: Aspose.Email for .NET API Reference
description: Appointment method. Returns the details of the appointment formatted with the specified templates
type: docs
weight: 350
url: /net/aspose.email.calendar/appointment/getappointmenttext/
---
## GetAppointmentText(AppointmentFormattingOptions) {#getappointmenttext_1}

Returns the details of the appointment, formatted with the specified templates.

```csharp
public string GetAppointmentText(AppointmentFormattingOptions formattingOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattingOptions | AppointmentFormattingOptions | The templates to format the details with. Use `AppointmentFormattingOptions.CreateAsHtml` to get HTML. |

### Return Value

The title, organizer, start and end time, time zone, location and description of the appointment.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *formattingOptions* is `null`. |

### See Also

* class [AppointmentFormattingOptions](../../appointmentformattingoptions/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## GetAppointmentText() {#getappointmenttext}

Returns the details of the appointment as plain text.

```csharp
public string GetAppointmentText()
```

### Return Value

The title, organizer, start and end time, time zone, location and description of the appointment, formatted with the default plain-text templates.

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)


