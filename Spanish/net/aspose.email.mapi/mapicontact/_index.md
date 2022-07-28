---
title: MapiContact
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa la información de contacto de Outlook
type: docs
weight: 18190
url: /es/net/aspose.email.mapi/mapicontact/
---
## MapiContact class

Representa la información de contacto de Outlook

```csharp
public sealed class MapiContact : MapiMessageItemBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MapiContact](mapicontact#constructor)() | Inicializa una nueva instancia del[`MapiContact`](../mapicontact) clase |
| [MapiContact](mapicontact#constructor_1)(string, string) | Inicializa una nueva instancia del[`MapiContact`](../mapicontact) clase. |
| [MapiContact](mapicontact#constructor_2)(string, string, string) | Inicializa una nueva instancia del[`MapiContact`](../mapicontact) clase. |
| [MapiContact](mapicontact#constructor_3)(string, string, string, string) | Inicializa una nueva instancia del[`MapiContact`](../mapicontact) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapicontact/attachments) { get; } | Obtiene los archivos adjuntos en el contacto. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contiene la información de facturación asociada a un artículo. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Obtiene el texto del mensaje. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Obtiene el[`BodyRtf`](../mapimessageitembase/bodyrtf) del mensaje convertido a HTML, si está presente, de lo contrario, una cadena vacía. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Obtiene o establece el texto del mensaje con formato RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Obtiene el tipo del cuerpo. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contiene palabras clave o categorías para el objeto de mensaje. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtiene la página de códigos. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contiene los nombres de las empresas asociadas a un artículo. |
| [ElectronicAddresses](../../aspose.email.mapi/mapicontact/electronicaddresses) { get; set; } | Especifique propiedades para hasta tres direcciones de correo electrónico diferentes y tres direcciones de fax diferentes |
| [Events](../../aspose.email.mapi/mapicontact/events) { get; set; } | Especificar eventos asociados a un contacto |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | El id del artículo, se usa con un servidor |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Obtiene una cadena que distingue entre mayúsculas y minúsculas que identifica la clase de mensaje definida por el remitente, como IPM.Note. La clase de mensaje especifica el tipo, propósito o contenido del mensaje. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contiene la información de millaje asociada con un artículo. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Obtiene las propiedades con nombre del mensaje. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Obtiene la asignación de propiedad nombrada. |
| [NameInfo](../../aspose.email.mapi/mapicontact/nameinfo) { get; set; } | Las propiedades se utilizan para especificar el nombre de la persona representada por el contacto |
| [OtherFields](../../aspose.email.mapi/mapicontact/otherfields) { get; set; } | Especificar otros campos de contacto. |
| [PersonalInfo](../../aspose.email.mapi/mapicontact/personalinfo) { get; set; } | Especificar otra información de contacto adicional |
| [Photo](../../aspose.email.mapi/mapicontact/photo) { get; set; } | Contiene foto de contacto[`MapiContactPhoto`](../mapicontactphoto) . |
| [PhysicalAddresses](../../aspose.email.mapi/mapicontact/physicaladdresses) { get; set; } | Especifique tres direcciones físicas: Dirección particular, Dirección del trabajo y Otra dirección. Una de las direcciones se puede marcar como Dirección postal |
| [ProfessionalInfo](../../aspose.email.mapi/mapicontact/professionalinfo) { get; set; } | Las propiedades se utilizan para almacenar detalles profesionales para la persona representada por el contacto |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtiene la colección de propiedades. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Obtiene el flujo de propiedad. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Obtiene los destinatarios del mensaje. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Obtiene la Sensibilidad. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Obtiene o establece el asunto del mensaje. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Obtiene un prefijo de asunto que normalmente indica alguna acción en un mensaje, como "FW: " para el reenvío. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Obtiene los subalmacenamientos. |
| [Telephones](../../aspose.email.mapi/mapicontact/telephones) { get; set; } | Especifique los números de teléfono para el contacto |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard)(Stream) | Lecturas[`MapiContact`](../mapicontact) del flujo especificado que contiene vCard. Las versiones de vCard admitidas son 2.1 y 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_2)(string) | Lecturas[`MapiContact`](../mapicontact) del archivo vCard especificado Las versiones compatibles de vCard son 2.1 y 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_1)(Stream, Encoding) | Lecturas[`MapiContact`](../mapicontact) del flujo especificado que contiene vCard. Las versiones de vCard admitidas son 2.1 y 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_3)(string, Encoding) | Lecturas[`MapiContact`](../mapicontact) del archivo vCard especificado Las versiones compatibles de vCard son 2.1 y 3.0 |
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
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicontact/getunderlyingmessage)() | Obtenga el MapiMessage que representa el contacto. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determina si las propiedades de la cadena están codificadas en Unicode o no. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Proporciona la eliminación correcta de propiedades de todas las colecciones. |
| [Save](../../aspose.email.mapi/mapicontact/save#save)(Stream) | Guarda esto[`MapiContact`](../mapicontact) en el flujo dado con formato vCard. La versión vCard admitida es 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_3)(string) | Guarda esto[`MapiContact`](../mapicontact) al archivo vCard con opciones predeterminadas. La versión compatible de vCard es 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_1)(Stream, ContactSaveFormat) | Guarda esto[`MapiContact`](../mapicontact) a la transmisión dada con un formato usando las opciones predeterminadas. El formato de guardado admitido es vCard |
| [Save](../../aspose.email.mapi/mapicontact/save#save_2)(Stream, ContactSaveOptions) | Guarda esto[`MapiContact`](../mapicontact) a la transmisión dada usando las opciones de guardado especificadas. Las opciones de guardado admitidas son[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| [Save](../../aspose.email.mapi/mapicontact/save#save_4)(string, ContactSaveFormat) | Guarda esto[`MapiContact`](../mapicontact)al archivo especificado con un formato utilizando las opciones predeterminadas. El formato de guardado compatible es vCard. |
| [Save](../../aspose.email.mapi/mapicontact/save#save_5)(string, ContactSaveOptions) | Guarda esto[`MapiContact`](../mapicontact) en un archivo utilizando las opciones de guardado especificadas. Las opciones de guardado admitidas son[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| override [SetBodyContent](../../aspose.email.mapi/mapicontact/setbodycontent#setbodycontent)(string, BodyContentType) | Establece el contenido del cuerpo. |
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
