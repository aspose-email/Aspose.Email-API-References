---
title: MapiCalendar
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa el objeto calendario mapi
type: docs
weight: 17910
url: /es/net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

Representa el objeto calendario mapi

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MapiCalendar](mapicalendar#constructor)() | Inicializa una nueva instancia del[`MapiCalendar`](../mapicalendar) clase |
| [MapiCalendar](mapicalendar#constructor_1)(string, string, string, DateTime, DateTime) | Inicializa una nueva instancia del[`MapiCalendar`](../mapicalendar) clase. |
| [MapiCalendar](mapicalendar#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | Inicializa una nueva instancia del[`MapiCalendar`](../mapicalendar) clase. |
| [MapiCalendar](mapicalendar#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | Inicializa una nueva instancia del[`MapiCalendar`](../mapicalendar) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal) { get; set; } | Obtiene o establece un valor que indica si un objeto Respuesta a la reunión es una contrapropuesta. |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments) { get; } | Obtiene la colección de adjuntos. |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees) { get; set; } | Obtiene o establece los asistentes |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contiene la información de facturación asociada a un artículo. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Obtiene el texto del mensaje. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Obtiene el[`BodyRtf`](../mapimessageitembase/bodyrtf) del mensaje convertido a HTML, si está presente, de lo contrario, una cadena vacía. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Obtiene o establece el texto del mensaje con formato RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Obtiene el tipo del cuerpo. |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus) { get; set; } | Obtiene o establece el estado ocupado |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contiene palabras clave o categorías para el objeto de mensaje. |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent) { get; set; } | Obtiene o establece las acciones que el usuario ha realizado en este objeto Reunión. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtiene la página de códigos. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contiene los nombres de las empresas asociadas a un artículo. |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate) { get; set; } | Obtiene o establece la fecha y hora de finalización del evento. Si no se establece la fecha, el valor predeterminado paraDateTime se devuelve. |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone) { get; set; } | Obtiene o establece información de zona horaria que indica la zona horaria de la propiedad EndDate |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday) { get; set; } | Obtiene o establece un valor que indica si el evento es un evento de todo el día |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | El id del artículo, se usa con un servidor |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords) { get; set; } | Obtiene o establece las categorías del objeto de calendario |
| [Location](../../aspose.email.mapi/mapicalendar/location) { get; set; } | Obtiene o establece la ubicación del evento |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Obtiene una cadena que distingue entre mayúsculas y minúsculas que identifica la clase de mensaje definida por el remitente, como IPM.Note. La clase de mensaje especifica el tipo, propósito o contenido del mensaje. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contiene la información de millaje asociada con un artículo. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Obtiene las propiedades con nombre del mensaje. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Obtiene la asignación de propiedad nombrada. |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer) { get; set; } | Obtiene o establece el organizador. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtiene la colección de propiedades. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Obtiene el flujo de propiedad. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Obtiene los destinatarios del mensaje. |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence) { get; set; } | Obtiene o establece las propiedades de recurrencia |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta) { get; set; } | Obtiene o establece el intervalo, en minutos, entre la hora en que el recordatorio se vence por primera vez y la hora de inicio del objeto Calendar |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter) { get; set; } | Especifica la ruta completa del sonido que un cliente DEBE reproducir cuando el recordatorio vence. |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset) { get; set; } | Obtiene o establece un valor que indica si se ha establecido un recordatorio en el objeto |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Obtiene la Sensibilidad. |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence) { get; set; } | Obtiene o establece el número de secuencia |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate) { get; set; } | Obtiene o establece la fecha y hora de inicio del evento. Si no se establece la fecha, el valor predeterminado paraDateTime se devuelve. |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone) { get; set; } | Obtiene o establece información de zona horaria que indica la zona horaria de la propiedad StartDate |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Obtiene o establece el asunto del mensaje. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Obtiene un prefijo de asunto que normalmente indica alguna acción en un mensaje, como "FW: " para el reenvío. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Obtiene los subalmacenamientos. |
| [Uid](../../aspose.email.mapi/mapicalendar/uid) { get; set; } | Obtiene el identificador único |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose)() | Libera todos los recursos. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Obtiene la propiedad MAPI por descriptor de propiedad. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Obtiene el valor de la propiedad especificada por la etiqueta como tipo booleano. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Obtiene el valor de cadena de la propiedad especificada por la etiqueta. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Obtiene el valor de la propiedad especificada por la etiqueta como tipo DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Obtiene el valor int32 de la propiedad especificada por tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Obtiene el valor de la propiedad especificada por la etiqueta como tipo Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Obtiene el valor de la propiedad especificada por etiqueta como Tipo corto. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Obtiene el valor de cadena de la propiedad especificada por la etiqueta. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Obtiene el valor de cadena de la propiedad especificada por la etiqueta. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determina si las propiedades de la cadena están codificadas en Unicode o no. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Proporciona la eliminación correcta de propiedades de todas las colecciones. |
| [Save](../../aspose.email.mapi/mapicalendar/save#save)(Stream) | Guarda el objeto de calendario en el archivo con formato iCalendar utilizando las opciones de guardado predeterminadas |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_3)(string) | Guarda el objeto de calendario en el archivo con formato iCalendar utilizando las opciones de guardado predeterminadas |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_1)(Stream, AppointmentSaveFormat) | Guarda el objeto de calendario en la secuencia con el formato especificado utilizando las opciones de guardado predeterminadas |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_2)(Stream, MapiCalendarSaveOptions) | Guarda el calendario en la secuencia con las opciones de guardado especificadas |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_4)(string, AppointmentSaveFormat) | Guarda el objeto de calendario en el archivo con el formato especificado utilizando las opciones de guardado predeterminadas |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_5)(string, MapiCalendarSaveOptions) | Guarda el objeto de calendario en el archivo con el formato especificado utilizando las opciones de guardado predeterminadas |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Establece el contenido del cuerpo. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Establece el contenido del cuerpo. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Obtiene o establece el texto del mensaje con formato RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Establece las banderas de mensajes. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Establece la propiedad. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Establece la propiedad MAPI. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Intente obtener los datos de la propiedad con la clave de etiqueta especificada. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Obtiene el valor de la propiedad especificada como tipo DateTime. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Obtiene el valor de la propiedad especificada como tipo Int32. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Obtiene el valor de la propiedad especificada como tipo Long. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Intente obtener los datos de una propiedad como una cadena con la etiqueta especificada. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Intente obtener los datos de una propiedad como una cadena con la etiqueta y la página de códigos especificadas. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Obtiene el valor de la propiedad especificada como tipo String. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Obtiene el valor de la propiedad especificada como tipo String. Un valor devuelto indica si la operación tuvo éxito. |

### Ver también

* class [MapiMessageItemBase](../mapimessageitembase)
* espacio de nombres [Aspose.Email.Mapi](../../aspose.email.mapi)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
