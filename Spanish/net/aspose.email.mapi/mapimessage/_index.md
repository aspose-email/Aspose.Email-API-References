---
title: MapiMessage
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa un documento con formato de mensaje de Outlook que se puede analizar.
type: docs
weight: 18450
url: /es/net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

Representa un documento con formato de mensaje de Outlook que se puede analizar.

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MapiMessage](mapimessage#constructor)() | Inicializa una nueva instancia del[`MapiMessage`](../mapimessage) clase. |
| [MapiMessage](mapimessage#constructor_1)(OutlookMessageFormat) | Inicializa una nueva instancia del[`MapiMessage`](../mapimessage) clase. |
| [MapiMessage](mapimessage#constructor_2)(string, string, string, string) | Inicializa una nueva instancia del[`MapiMessage`](../mapimessage) clase. |
| [MapiMessage](mapimessage#constructor_3)(string, string, string, string, OutlookMessageFormat) | Inicializa una nueva instancia del[`MapiMessage`](../mapimessage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Obtiene los archivos adjuntos en el mensaje. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contiene la información de facturación asociada a un artículo. |
| [Body](../../aspose.email.mapi/mapimessage/body) { get; set; } | Obtiene el texto del mensaje. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Obtiene el[`BodyRtf`](../mapimessageitembase/bodyrtf) del mensaje convertido a HTML, si está presente, de lo contrario, una cadena vacía. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Obtiene o establece el texto del mensaje con formato RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Obtiene el tipo del cuerpo. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contiene palabras clave o categorías para el objeto de mensaje. |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime) { get; set; } | Obtiene o establece la fecha y la hora en que el remitente del mensaje envió un mensaje. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtiene la página de códigos. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contiene los nombres de las empresas asociadas a un artículo. |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic) { get; } | Obtiene el tema del primer mensaje en un hilo de conversación. |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime) { get; set; } | Obtiene o establece la fecha y hora en que se entregó un mensaje. |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc) { get; } | Obtiene una lista de los nombres para mostrar de los destinatarios de los mensajes en copia oculta (BCC), separados por punto y coma (;). |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc) { get; } | Obtiene una lista de los nombres para mostrar de los destinatarios del mensaje en copia carbón (CC), separados por punto y coma (;). |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname) { get; } | Obtiene el nombre para mostrar del mensaje. |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix) { get; } | Obtiene un prefijo del nombre para mostrar. |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto) { get; } | Obtiene una lista de los nombres para mostrar de los destinatarios del mensaje principal (Para), separados por punto y coma (;). |
| [Flags](../../aspose.email.mapi/mapimessage/flags) { get; } | Obtiene las banderas del mensaje. |
| [Headers](../../aspose.email.mapi/mapimessage/headers) { get; set; } | Obtiene los encabezados del mensaje de transporte |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid) { get; } | Obtiene la identificación del mensaje del mensaje. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | El id del artículo, se usa con un servidor |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Obtiene una cadena que distingue entre mayúsculas y minúsculas que identifica la clase de mensaje definida por el remitente, como IPM.Note. La clase de mensaje especifica el tipo, propósito o contenido del mensaje. |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat) { get; } | Obtiene el formato del mensaje de Outlook. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contiene la información de millaje asociada con un artículo. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Obtiene las propiedades con nombre del mensaje. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Obtiene la asignación de propiedad nombrada. |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject) { get; } | Obtiene el asunto normalizado del mensaje. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtiene la colección de propiedades. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Obtiene el flujo de propiedad. |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested) { get; set; } | Obtiene o establece un valor que indica si se solicita la confirmación de lectura. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Obtiene los destinatarios del mensaje. |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto) { get; set; } | Obtiene o establece la respuesta a nombres. |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype) { get; } | Obtiene el tipo de dirección de correo electrónico del remitente del mensaje. |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress) { get; set; } | Obtiene o establece la dirección de correo electrónico del remitente del mensaje. |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername) { get; set; } | Obtiene o establece el nombre para mostrar del remitente del mensaje. |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress) { get; set; } | Obtiene o establece la dirección de correo electrónico del remitente del mensaje. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Obtiene la Sensibilidad. |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype) { get; } | Obtiene el tipo de dirección del usuario de mensajería representado por el remitente. |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress) { get; set; } | Obtiene o establece la dirección de correo electrónico del usuario de mensajería representado por el remitente. |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname) { get; set; } | Obtiene o establece el nombre para mostrar del usuario de mensajería representado por el remitente. |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress) { get; } | Obtiene o establece la dirección de correo electrónico del usuario de mensajería representado por el remitente. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Obtiene o establece el asunto del mensaje. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Obtiene un prefijo de asunto que normalmente indica alguna acción en un mensaje, como "FW: " para el reenvío. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Obtiene los subalmacenamientos. |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders) { get; } | Obtiene la información del sobre del mensaje específico del transporte. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage)(MailMessage) | Crea una instancia de MapiMessage a partir de MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_2)(string) | Crea una instancia de MapiMessage a partir de MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_1)(MailMessage, MapiConversionOptions) | Crea una instancia de MapiMessage a partir de MailMessage. |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties)(MapiPropertyCollection) | Crea una instancia de MapiMessage a partir de una colección de propiedades de Mapi. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load)(Stream) | Carga el mensaje de stream. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_2)(string) | Carga el mensaje desde el archivo. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_1)(Stream, LoadOptions) | Carga el mensaje de la secuencia con opciones adicionales. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_3)(string, LoadOptions) | Carga mensaje desde archivo con opciones adicionales. |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef)(Stream) | Carga el mensaje de la estructura de datos del formato de encapsulación neutral para el transporte (TNEF) |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef_1)(string) | Carga el mensaje de la estructura de datos del formato de encapsulación neutral para el transporte (TNEF) |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty)(MapiProperty, string) | Agrega la propiedad personalizada. |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty_1)(MapiPropertyType, byte[], string) | Agrega la propiedad personalizada. |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced)() | Comprueba si este mensaje se puede tratar como un mensaje de rebote. |
| [Clone](../../aspose.email.mapi/mapimessage/clone)() | Crea un nuevo objeto que es una copia de la instancia actual. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties)() | Obtiene la colección de MapiProperties personalizadas. |
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
| [Save](../../aspose.email.mapi/mapimessage/save#save)(Stream) | Guarda en el flujo especificado como Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_2)(string) | Guarda en el archivo especificado como Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_1)(Stream, SaveOptions) | Guarda el mensaje como flujo con opciones adicionales. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_3)(string, SaveOptions) | Guarda el mensaje como un archivo con opciones adicionales. |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate)(Stream) | Guarda en la secuencia especificada como plantilla de archivo de Outlook (formato OFT). |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate_1)(string) | Guarda en el archivo especificado como plantilla de archivo de Outlook (formato OFT). |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef)(Stream) | Guardar mensaje en formato TNEF. |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef_1)(string) | Guardar mensaje en formato TNEF. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Establece el contenido del cuerpo. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Establece el contenido del cuerpo. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Obtiene o establece el texto del mensaje con formato RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Establece las banderas de mensajes. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Establece la propiedad. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Establece la propiedad MAPI. |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue)(long, string) | Establece el valor de la propiedad de cadena. |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage)(MailConversionOptions) | Crea una instancia de MailMessage a partir de este MapiMessage. |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem)() | Convertir MapiMessage en IMapiMessageItem object en dependencia con MessageClass. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Intente obtener los datos de la propiedad con la clave de etiqueta especificada. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Obtiene el valor de la propiedad especificada como tipo DateTime. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Obtiene el valor de la propiedad especificada como tipo Int32. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Obtiene el valor de la propiedad especificada como tipo Long. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Intente obtener los datos de una propiedad como una cadena con la etiqueta especificada. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Intente obtener los datos de una propiedad como una cadena con la etiqueta y la página de códigos especificadas. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Obtiene el valor de la propiedad especificada como tipo String. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Obtiene el valor de la propiedad especificada como tipo String. Un valor devuelto indica si la operación tuvo éxito. |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments)(string) | Destruye los archivos adjuntos en los archivos de mensajes de Outlook especificados. DestroyAttachments ignorará el análisis de archivos adjuntos. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat)(Stream) | Determina si la secuencia especificada tiene formato MSG. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat_1)(string) | Determina si el archivo especificado tiene formato MSG. |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments)(string) | Elimina todos los archivos adjuntos de los archivos de mensajes de Outlook especificados. |

### Observaciones

Las instancias de la clase MapiMessage se utilizan para representar archivos de documentos de mensajes de Microsoft Outlook que analiza la clase MapiMessageReader. Para acceder al remitente, destinatario y contenido de un mensaje de correo electrónico, use las propiedades asociadas de la clase MapiMessage.

### Ejemplos

El siguiente ejemplo muestra cómo leer archivos de mensajes de Outlook.

[C#]

[Visual Basic]

```csharp
//Abrir archivos de mensajes de Outlook
MapiMessage msg = MapiMessage.FromFile(@"c:\outlookmessage.msg");

/leer asunto
onsole.WriteLine("Subject:" + msg.Subject);

/nombre del remitente
onsole.WriteLine("From:" + msg.SenderName);

/Cuerpo del mensaje
onsole.WriteLine("Body:" + msg.Body);

/Archivos adjuntos
oreach(MapiAttachment att in msg.Attachments)

   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
    
```

```csharp
'Abrir archivos de mensajes de Outlook 
Dim msg As MapiMessage = MapiMessage.FromFile("c:\outlookmessage.msg") 

'leer tema 
Console.WriteLine("Subject:" + msg.Subject) 

'nombre del remitente 
Console.WriteLine("From:" + msg.SenderName) 

'Cuerpo del mensaje 
Console.WriteLine("Body:" + msg.Body) 

'Archivos adjuntos 
For Each att As MapiAttachment In msg.Attachments 
    Console.WriteLine("Attachment Name:" + att.FileName) 
    att.Save(att.FileName) 
Next
```

### Ver también

* class [MapiMessageItemBase](../mapimessageitembase)
* espacio de nombres [Aspose.Email.Mapi](../../aspose.email.mapi)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
