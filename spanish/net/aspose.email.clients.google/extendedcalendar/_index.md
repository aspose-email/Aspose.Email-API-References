---
title: ExtendedCalendar
second_title: Referencia de la API de Aspose.Email para .NET
description: Un conjunto de metadatos extendidos como colores para un solo calendario.
type: docs
weight: 15700
url: /es/net/aspose.email.clients.google/extendedcalendar/
---
## ExtendedCalendar class

Un conjunto de metadatos extendidos, como colores, para un solo calendario.

```csharp
public class ExtendedCalendar : Calendar
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ExtendedCalendar](extendedcalendar#constructor)() | Inicializa una nueva instancia de la clase ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_1)(string) | Inicializa una nueva instancia de la clase ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_2)(string, string) | Inicializa una nueva instancia de la clase ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_3)(string, string, string, string) | Inicializa una nueva instancia de la clase ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_4)(string, string, string, string, string) | Inicializa una nueva instancia de la clase ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_5)(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Inicializa una nueva instancia de la clase ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_6)(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Inicializa una nueva instancia de la clase ExtendedCalendar. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [AccessRole](../../aspose.email.clients.google/extendedcalendar/accessrole) { get; } | El rol de acceso efectivo que tiene el usuario autenticado en el calendario. Solo lectura. Los valores posibles son: |
| virtual [BackgroundColor](../../aspose.email.clients.google/extendedcalendar/backgroundcolor) { get; set; } | El color principal del calendario en el formato '#0088aa'. Esta propiedad reemplaza la propiedad colorId basada en índice. |
| virtual [ColorId](../../aspose.email.clients.google/extendedcalendar/colorid) { get; set; } | El color del calendario. Este es un ID que hace referencia a una entrada en la sección "calendario" de la definición de colores (consulte el extremo "colores"). |
| virtual [ConferenceProperties](../../aspose.email.clients.google/calendar/conferenceproperties) { get; } | Obtiene las propiedades de conferencia para este calendario. |
| virtual [DefaultReminders](../../aspose.email.clients.google/extendedcalendar/defaultreminders) { get; set; } | Los recordatorios predeterminados que tiene el usuario autenticado para este calendario. |
| virtual [Description](../../aspose.email.clients.google/calendar/description) { get; set; } | Descripción del calendario. |
| virtual [ETag](../../aspose.email.clients.google/basedataobject/etag) { get; set; } | Una ETag o etiqueta de entidad es uno de varios mecanismos que proporciona HTTP para la validación de caché web y que permite a un cliente realizar solicitudes condicionales. Esto permite que los cachés sean más eficientes y ahorra ancho de banda, ya que un servidor web no necesita enviar una respuesta completa si el contenido no ha cambiado. Las etiquetas ETag también se pueden usar para el control de concurrencia optimista, como una forma de ayudar a evitar que las actualizaciones simultáneas de un recurso se sobrescriban entre sí. |
| virtual [ForegroundColor](../../aspose.email.clients.google/extendedcalendar/foregroundcolor) { get; set; } | El color de primer plano del calendario en el formato '#ffffff'. Esta propiedad reemplaza la propiedad colorId basada en índice. |
| virtual [Hidden](../../aspose.email.clients.google/extendedcalendar/hidden) { get; set; } | Si el calendario se ha ocultado de la lista. El valor predeterminado es Falso. |
| virtual [Id](../../aspose.email.clients.google/basedataobject/id) { get; set; } | Identificador del recurso. |
| virtual [Kind](../../aspose.email.clients.google/basedataobject/kind) { get; } | Tipo del recurso |
| virtual [Location](../../aspose.email.clients.google/calendar/location) { get; set; } | Ubicación geográfica del calendario como texto de formato libre. |
| virtual [NotificationSettings](../../aspose.email.clients.google/extendedcalendar/notificationsettings) { get; set; } | Las notificaciones que el usuario autenticado está recibiendo para este calendario. |
| virtual [Primary](../../aspose.email.clients.google/extendedcalendar/primary) { get; set; } | Si el calendario es el calendario principal del usuario autenticado. Solo lectura. El valor predeterminado es Falso. |
| virtual [Selected](../../aspose.email.clients.google/extendedcalendar/selected) { get; set; } | Si el contenido del calendario aparece en la interfaz de usuario del calendario. El valor predeterminado es Falso. |
| virtual [Summary](../../aspose.email.clients.google/calendar/summary) { get; set; } | Título del calendario. |
| virtual [SummaryOverride](../../aspose.email.clients.google/extendedcalendar/summaryoverride) { get; set; } | El resumen que el usuario autenticado ha establecido para este calendario. |
| virtual [TimeZone](../../aspose.email.clients.google/calendar/timezone) { get; set; } | La zona horaria del calendario. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.email.clients.google/extendedcalendar/tostring)() | Devuelve una cadena que representa la instancia del objeto. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [ExtendedCalendarKind](../../aspose.email.clients.google/extendedcalendar/extendedcalendarkind) | Tipo del recurso "calendar#calendarListEntry". |
| const [ListKind](../../aspose.email.clients.google/extendedcalendar/listkind) | Tipo de la lista de recursos "calendar#calendarList". |

### Ver también

* class [Calendar](../calendar)
* espacio de nombres [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
