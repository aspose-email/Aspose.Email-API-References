---
title: MapiJournal
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa el objeto Diario de Outlook.
type: docs
weight: 18420
url: /es/net/aspose.email.mapi/mapijournal/
---
## MapiJournal class

Representa el objeto Diario de Outlook.

```csharp
public sealed class MapiJournal : MapiMessageItemBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MapiJournal](mapijournal#constructor)() | Inicializa una nueva instancia del[`MapiJournal`](../mapijournal) clase. |
| [MapiJournal](mapijournal#constructor_1)(string, string, string, string) | Inicializa una nueva instancia del[`MapiJournal`](../mapijournal) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Obtiene los archivos adjuntos en el mensaje. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contiene la información de facturación asociada a un artículo. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Obtiene el texto del mensaje. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Obtiene el[`BodyRtf`](../mapimessageitembase/bodyrtf) del mensaje convertido a HTML, si está presente, de lo contrario, una cadena vacía. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Obtiene o establece el texto del mensaje con formato RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Obtiene el tipo del cuerpo. |
| [BriefDescription](../../aspose.email.mapi/mapijournal/briefdescription) { get; set; } | Obtiene o establece la breve descripción de la actividad que se está registrando. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contiene palabras clave o categorías para el objeto de mensaje. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtiene la página de códigos. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contiene los nombres de las empresas asociadas a un artículo. |
| [Description](../../aspose.email.mapi/mapijournal/description) { get; set; } | Obtiene o establece la descripción de la actividad que se está registrando. |
| [DocumentStatus](../../aspose.email.mapi/mapijournal/documentstatus) { get; set; } | Obtiene o establece el estado del documento. |
| [Duration](../../aspose.email.mapi/mapijournal/duration) { get; } | Obtiene la duración de la actividad. |
| [EndTime](../../aspose.email.mapi/mapijournal/endtime) { get; set; } | Obtiene o establece la hora a la que finalizó la actividad. |
| [Flags](../../aspose.email.mapi/mapijournal/flags) { get; set; } | Obtiene o establece indicadores que contienen metadatos sobre el objeto Journal. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | El id del artículo, se usa con un servidor |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Obtiene una cadena que distingue entre mayúsculas y minúsculas que identifica la clase de mensaje definida por el remitente, como IPM.Note. La clase de mensaje especifica el tipo, propósito o contenido del mensaje. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contiene la información de millaje asociada con un artículo. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Obtiene las propiedades con nombre del mensaje. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Obtiene la asignación de propiedad nombrada. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtiene la colección de propiedades. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Obtiene el flujo de propiedad. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Obtiene los destinatarios del mensaje. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Obtiene la Sensibilidad. |
| [StartTime](../../aspose.email.mapi/mapijournal/starttime) { get; set; } | Obtiene o establece la hora a la que comenzó la actividad. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Obtiene o establece el asunto del mensaje. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Obtiene un prefijo de asunto que normalmente indica alguna acción en un mensaje, como "FW: " para el reenvío. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Obtiene los subalmacenamientos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
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
| [Save](../../aspose.email.mapi/mapijournal/save#save)(Stream) | Guarda el flujo especificado. |
| [Save](../../aspose.email.mapi/mapijournal/save#save_1)(string) | Guarda el nombre de archivo especificado. |
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
