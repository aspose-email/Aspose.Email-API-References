---
title: Appointment
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa un calendario para un correo electrónico.
type: docs
weight: 430
url: /es/net/aspose.email.calendar/appointment/
---
## Appointment class

Representa un calendario para un correo electrónico.

```csharp
public class Appointment
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Appointment](appointment#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | Inicializa una nueva instancia del[`Appointment`](../appointment) clase. |
| [Appointment](appointment#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | Inicializa una nueva instancia del[`Appointment`](../appointment) clase. |
| [Appointment](appointment#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | Inicializa una nueva instancia del[`Appointment`](../appointment) clase. |
| [Appointment](appointment#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | Inicializa una nueva instancia del[`Appointment`](../appointment) clase. |
| [Appointment](appointment#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | Inicializa una nueva instancia del[`Appointment`](../appointment) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments) { get; } | Obtiene la colección de adjuntos de la cita. |
| [Attendees](../../aspose.email.calendar/appointment/attendees) { get; set; } | Obtiene o establece los asistentes. |
| [Class](../../aspose.email.calendar/appointment/class) { get; set; } | Especifica la clasificación de acceso para la cita. |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate) { get; set; } | Obtiene o establece la fecha y la hora en que se creó la información del calendario. |
| [DateTimeStamp](../../aspose.email.calendar/appointment/datetimestamp) { get; set; } | Obtiene o establece la fecha/hora en que se creó la instancia del objeto iCalendar.. |
| [Description](../../aspose.email.calendar/appointment/description) { get; set; } | Obtiene o establece la descripción. |
| [EndDate](../../aspose.email.calendar/appointment/enddate) { get; set; } | Obtiene o establece la fecha de finalización. |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone) { get; set; } | Zona horaria final |
| [Flags](../../aspose.email.calendar/appointment/flags) { get; set; } | Obtiene o establece indicadores de citas. |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription) { get; set; } | Obtiene o establece la representación html de la descripción. |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate) { get; set; } | Obtiene o establece la fecha y la hora en que se revisó por última vez la información del calendario. |
| [Location](../../aspose.email.calendar/appointment/location) { get; set; } | Obtiene o establece la ubicación. |
| [MethodType](../../aspose.email.calendar/appointment/methodtype) { get; set; } | Obtiene o establece el tipo de método de objeto iCalendar asociado con el objeto de calendario. |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus) { get; set; } | Especifica el estado OCUPADO de una cita. |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance) { get; set; } | Especifica la importancia de una cita. |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus) { get; set; } | Especifica el estado PREVISTO de una cita. |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees) { get; } | Obtiene los asistentes opcionales. |
| [Organizer](../../aspose.email.calendar/appointment/organizer) { get; set; } | Obtiene o establece el organizador. |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence) { get; set; } | Obtiene o establece el patrón de recurrencia. |
| [Reminders](../../aspose.email.calendar/appointment/reminders) { get; } | Contiene una colección de AppointmentReminder[`AppointmentReminder`](../appointmentreminder) objetos. |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid) { get; } | Obtiene la secuencia id. |
| [StartDate](../../aspose.email.calendar/appointment/startdate) { get; set; } | Obtiene o establece la fecha de inicio. |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone) { get; set; } | Zona horaria de inicio |
| [Status](../../aspose.email.calendar/appointment/status) { get; set; } | Obtiene o establece el estado general o la confirmación del objeto. |
| [Summary](../../aspose.email.calendar/appointment/summary) { get; set; } | Obtiene o establece el resumen. |
| [Transparency](../../aspose.email.calendar/appointment/transparency) { get; set; } | Especifica si esta cita está destinada o no a ser visible en las búsquedas de disponibilidad. |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid) { get; set; } | Obtiene o establece un valor de cadena que contiene el GUID para el elemento del calendario. En MS Exchange, esta es la propiedad mapi PidLidGlobalObjectId. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load#load)(Stream) | Cargas[`Appointment`](../appointment) de la corriente |
| static [Load](../../aspose.email.calendar/appointment/load#load_3)(string) | Cargas[`Appointment`](../appointment) del archivo. Formatos de archivo admitidos: iCalendar |
| static [Load](../../aspose.email.calendar/appointment/load#load_1)(Stream, AppointmentLoadOptions) | Cargas[`Appointment`](../appointment) de la corriente |
| static [Load](../../aspose.email.calendar/appointment/load#load_2)(Stream, bool) | Cargas[`Appointment`](../appointment) de la corriente |
| static [Load](../../aspose.email.calendar/appointment/load#load_4)(string, AppointmentLoadOptions) | Cargas[`Appointment`](../appointment) del archivo. Formatos de archivo admitidos: iCalendar Una ruta de archivo.Representa las opciones de carga de citas[`AppointmentLoadOptions`](../appointmentloadoptions). una lectura[`Appointment`](../appointment). |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment)() | Cancela la cita. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment_1)(int) | Cancela la cita. |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml)() | Obtiene el calendario HTML. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext)() | Obtiene el texto del calendario. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext_1)(AppointmentFormattingOptions) | Obtiene el texto del calendario. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment)() | Solicita la cita. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment_1)(int) | Solicita la cita. |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone)() | Establecer zona horaria local |
| [Save](../../aspose.email.calendar/appointment/save#save)(Stream) | Guarda la cita en el archivo con formato iCalendar utilizando las opciones de guardado predeterminadas |
| [Save](../../aspose.email.calendar/appointment/save#save_3)(string) | Guarda la cita en el archivo con formato iCalendar utilizando las opciones de guardado predeterminadas |
| [Save](../../aspose.email.calendar/appointment/save#save_1)(Stream, AppointmentSaveFormat) | Guarda la cita en la secuencia con el formato especificado utilizando las opciones de guardado predeterminadas |
| [Save](../../aspose.email.calendar/appointment/save#save_2)(Stream, AppointmentSaveOptions) | Guarda la cita en la secuencia con las opciones de guardado especificadas |
| [Save](../../aspose.email.calendar/appointment/save#save_4)(string, AppointmentSaveFormat) | Guarda la cita en el archivo con el formato especificado utilizando las opciones de guardado predeterminadas |
| [Save](../../aspose.email.calendar/appointment/save#save_5)(string, AppointmentSaveOptions) | Guarda la cita en el archivo con las opciones de guardado especificadas |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone)(string) | Establecer zona horaria |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment)() | Actualiza la cita. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment_1)(int) | Actualiza la cita. |

### Ejemplos

Este ejemplo demuestra cómo agregar un calendario a un mensaje de correo electrónico.

[C#]

[Visual Basic]

```csharp
MailMessage msg = new MailMessage();

// asistentes al evento
MailAddressCollection attendees = new MailAddressCollection();
attendees.Add(new MailAddress("person1@domain.com"));
attendees.Add(new MailAddress("person2@domain.com"));
attendees.Add(new MailAddress("person3@domain.com"));

//crear cita
Appointment app = new Appointment("Room 112",new DateTime(2006,7,17,13,0,0),new DateTime(2006,7,17,14,0,0),new MailAddress("somebody@domain.com"), attendees );
cal.Summary = "Release Meetting";
cal.Description = "Discuss for the next release";

//añadir calendario al mensaje
msg.AddAlternateView(app.RequestApointment());

//enviar el mensaje de correo electrónico
SmtpClient smtp= new SmtpClient("smtp.server.com", 25, "user", "password");
smtp.Send(msg);
```

```csharp
Dim msg As MailMessage =  New MailMessage() 

'asistentes al evento
Dim attendees As MailAddressCollection =  New MailAddressCollection() 
attendees.Add(New MailAddress("person1@domain.com"))
attendees.Add(New MailAddress("person2@domain.com"))
attendees.Add(New MailAddress("person3@domain.com"))

'crear calendario
Dim cal As Appointment =  New Appointment("Room 112",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com"),attendees) 
cal.Summary = "Release Meetting"
cal.Description = "Discuss for the next release"

'añadir calendario al mensaje
msg.AddAlternateView(app.RequestApointment())
```

### Ver también

* espacio de nombres [Aspose.Email.Calendar](../../aspose.email.calendar)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
