---
title: MapiTask
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa el objeto Tarea de Outlook.
type: docs
weight: 18670
url: /es/net/aspose.email.mapi/mapitask/
---
## MapiTask class

Representa el objeto Tarea de Outlook.

```csharp
public class MapiTask : MapiMessageItemBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MapiTask](mapitask#constructor)() | Inicializa una nueva instancia del[`MapiTask`](../mapitask) clase. |
| [MapiTask](mapitask#constructor_1)(string, string, DateTime, DateTime) | Inicializa una nueva instancia del[`MapiTask`](../mapitask) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AcceptanceState](../../aspose.email.mapi/mapitask/acceptancestate) { get; set; } | Obtiene o establece el estado de aceptación de la tarea. |
| [ActualEffort](../../aspose.email.mapi/mapitask/actualeffort) { get; set; } | Obtiene o establece la cantidad de minutos que el usuario realmente pasó trabajando en una tarea. |
| [Attachments](../../aspose.email.mapi/mapitask/attachments) { get; } | Obtiene la colección de adjuntos. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contiene la información de facturación asociada a un artículo. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Obtiene el texto del mensaje. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Obtiene el[`BodyRtf`](../mapimessageitembase/bodyrtf) del mensaje convertido a HTML, si está presente, de lo contrario, una cadena vacía. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Obtiene o establece el texto del mensaje con formato RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Obtiene el tipo del cuerpo. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contiene palabras clave o categorías para el objeto de mensaje. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtiene la página de códigos. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contiene los nombres de las empresas asociadas a un artículo. |
| [DateCompleted](../../aspose.email.mapi/mapitask/datecompleted) { get; set; } | Obtiene o establece la fecha en que el usuario completó el trabajo en la tarea. |
| [DueDate](../../aspose.email.mapi/mapitask/duedate) { get; set; } | Obtiene o establece la fecha en la que el usuario espera que se complete el trabajo en la tarea. |
| [EstimatedEffort](../../aspose.email.mapi/mapitask/estimatedeffort) { get; set; } | Obtiene o establece el número de minutos que el usuario espera trabajar en una tarea. |
| [Flags](../../aspose.email.mapi/mapitask/flags) { get; } | Obtiene las banderas de indicación del objeto Tarea. |
| [History](../../aspose.email.mapi/mapitask/history) { get; set; } | Obtiene o establece el tipo de cambio que se realizó por última vez en el objeto Tarea. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | El id del artículo, se usa con un servidor |
| [LastUpdate](../../aspose.email.mapi/mapitask/lastupdate) { get; set; } | Obtiene o establece la fecha y la hora del cambio más reciente realizado en el objeto Tarea. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Obtiene una cadena que distingue entre mayúsculas y minúsculas que identifica la clase de mensaje definida por el remitente, como IPM.Note. La clase de mensaje especifica el tipo, propósito o contenido del mensaje. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contiene la información de millaje asociada con un artículo. |
| [Mode](../../aspose.email.mapi/mapitask/mode) { get; set; } | Obtiene o establece el estado de asignación del objeto Tarea. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Obtiene las propiedades con nombre del mensaje. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Obtiene la asignación de propiedad nombrada. |
| [PercentComplete](../../aspose.email.mapi/mapitask/percentcomplete) { get; set; } | Obtiene o establece el progreso que el usuario ha realizado en una tarea. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtiene la colección de propiedades. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Obtiene el flujo de propiedad. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Obtiene los destinatarios del mensaje. |
| [Recurrence](../../aspose.email.mapi/mapitask/recurrence) { get; set; } | Obtiene o establece las propiedades de recurrencia. |
| [ReminderFileParameter](../../aspose.email.mapi/mapitask/reminderfileparameter) { get; set; } | Especifica la ruta completa del sonido que un cliente DEBE reproducir cuando el recordatorio vence. |
| [ReminderSet](../../aspose.email.mapi/mapitask/reminderset) { get; set; } | Obtiene o establece un valor que indica si se ha establecido un recordatorio en el objeto |
| [ReminderTime](../../aspose.email.mapi/mapitask/remindertime) { get; set; } | Obtiene o establece el tiempo de la señal inicial para un recordatorio |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Obtiene la Sensibilidad. |
| [StartDate](../../aspose.email.mapi/mapitask/startdate) { get; set; } | Obtiene o establece la fecha en la que el usuario espera que comience el trabajo en la tarea. |
| [State](../../aspose.email.mapi/mapitask/state) { get; set; } | Obtiene o establece la asignación actual estado del objeto Tarea. |
| [Status](../../aspose.email.mapi/mapitask/status) { get; set; } | Obtiene o establece el estado del progreso del usuario en la tarea. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Obtiene o establece el asunto del mensaje. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Obtiene un prefijo de asunto que normalmente indica alguna acción en un mensaje, como "FW: " para el reenvío. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Obtiene los subalmacenamientos. |
| [Users](../../aspose.email.mapi/mapitask/users) { get; set; } | Obtiene o establece información sobre los usuarios de la tarea. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo)(Stream) | Crea una instancia de MapiTask a partir del flujo especificado. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_2)(string) | Crea una instancia de MapiTask a partir del archivo .ics especificado. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_1)(Stream, bool) | Crea una instancia de MapiTask a partir del flujo especificado. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_3)(string, bool) | Crea una instancia de MapiTask a partir del archivo .ics especificado. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
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
| [Save](../../aspose.email.mapi/mapitask/save#save)(Stream, TaskSaveFormat) | Guarda esto[`MapiTask`](../mapitask) al flujo dado usando el formato especificado. |
| [Save](../../aspose.email.mapi/mapitask/save#save_1)(string, TaskSaveFormat) | Guarda esto[`MapiTask`](../mapitask) en el archivo usando el formato especificado. |
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
