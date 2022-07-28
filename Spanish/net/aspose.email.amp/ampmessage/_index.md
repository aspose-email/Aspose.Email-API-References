---
title: AmpMessage
second_title: Referencia de la API de Aspose.Email para .NET
description: Mensaje que permite a los remitentes incluir componentes AMP dentro de los correos electrónicos.
type: docs
weight: 140
url: /es/net/aspose.email.amp/ampmessage/
---
## AmpMessage class

Mensaje que permite a los remitentes incluir componentes AMP dentro de los correos electrónicos.

```csharp
public class AmpMessage : MailMessage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AmpMessage](ampmessage)() | Inicializa una nueva instancia del[`MailMessage`](../../aspose.email/mailmessage) clase |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews) { get; } | Obtiene la colección de vistas alternativas de message |
| virtual [AmpHtmlBody](../../aspose.email.amp/ampmessage/amphtmlbody) { get; set; } | Obtiene la representación AmpHtml del cuerpo del mensaje. |
| virtual [Attachments](../../aspose.email/mailmessage/attachments) { get; } | Obtiene la colección de archivos adjuntos de message |
| virtual [Bcc](../../aspose.email/mailmessage/bcc) { get; set; } | Obtiene o establece la colección de direcciones que contiene los destinatarios CCO del mensaje |
| virtual [Body](../../aspose.email/mailmessage/body) { get; set; } | Obtiene o establece la representación de texto sin formato del cuerpo del mensaje. Si la parte de texto/sin formato está presente en un mensaje, la propiedad devuelve sus datos de texto. De lo contrario, la propiedad devuelve el contenido de texto de la propiedad HtmlBody sin marcado html. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding) { get; set; } | Obtiene o establece la codificación de body |
| [BodyType](../../aspose.email/mailmessage/bodytype) { get; } | Obtiene el tipo del cuerpo. |
| virtual [CC](../../aspose.email/mailmessage/cc) { get; set; } | Obtiene o establece la colección de direcciones que contiene los destinatarios de CC |
| virtual [Date](../../aspose.email/mailmessage/date) { get; set; } | Obtiene o establece la fecha del mensaje |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions) { get; set; } | Obtiene o establece las notificaciones de entrega |
| [Epilogue](../../aspose.email/mailmessage/epilogue) { get; set; } | Obtiene o establece un texto de epílogo. Se ubica después del último límite. |
| virtual [From](../../aspose.email/mailmessage/from) { get; set; } | Obtiene o establece la dirección de origen |
| virtual [Headers](../../aspose.email/mailmessage/headers) { get; } | Obtiene la colección de encabezados de message |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody) { get; set; } | Obtiene o establece html body |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml) { get; set; } | Obtiene o establece un valor que indica si el cuerpo del mensaje está en Html |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft) { get; set; } | Obtiene o establece el valor que indica si se ha enviado o no un mensaje. |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted) { get; } | Obtiene un valor que indica si el mensaje está encriptado. |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly) { get; } | Obtiene un valor que indica si el mensaje es de solo lectura |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned) { get; } | Obtiene un valor que indica si el mensaje está firmado. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources) { get; } | Obtiene la colección de recursos vinculados de message |
| virtual [MessageId](../../aspose.email/mailmessage/messageid) { get; set; } | Obtiene o establece el mensaje id |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef) { get; } | Obtiene un valor que indica si el mensaje EML original está en formato TNEF. |
| [Preamble](../../aspose.email/mailmessage/preamble) { get; set; } | Obtiene o establece un texto de preámbulo. Se ubica antes del primer límite y generalmente incluye una nota explicativa para los lectores que no cumplen con MIME. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding) { get; set; } | Obtiene o establece la codificación preferida para todas las propiedades de texto |
| virtual [Priority](../../aspose.email/mailmessage/priority) { get; set; } | Obtiene o establece la prioridad del mensaje |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto) { get; set; } | Obtiene o establece la dirección de confirmación de lectura. |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist) { get; set; } | Obtiene o establece la lista de direcciones para responder al mensaje de correo |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath) { get; set; } | Obtiene o establece la dirección ReversePath |
| virtual [Sender](../../aspose.email/mailmessage/sender) { get; set; } | Obtiene o establece la dirección del remitente |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity) { get; set; } | Obtiene o establece la sensibilidad del mensaje |
| virtual [Subject](../../aspose.email/mailmessage/subject) { get; set; } | Obtiene o establece la línea de asunto |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding) { get; set; } | Obtiene o establece la codificación de subject |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset) { get; set; } | Obtiene o establece el desplazamiento de la hora universal coordinada (UTC) para las fechas del mensaje. Esta propiedad define la diferencia de zona horaria, entre la hora local y UTC. |
| virtual [To](../../aspose.email/mailmessage/to) { get; set; } | Obtiene o establece la colección de direcciones que contiene los destinatarios del mensaje |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer) { get; set; } | Obtiene o configura el X-Mailer el software que creó el mensaje de correo electrónico |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview)(AlternateView) | Agregar una vista alternativa al mensaje |
| [AddAmpComponent](../../aspose.email.amp/ampmessage/addampcomponent)(AmpComponent) | Agregar componente Amp a este mensaje. |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment)(Attachment) | Agregar un archivo adjunto al mensaje |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(CmsSigner) | Crea un mensaje firmado. Crea una copia de solo lectura del MailMessage especificado y le agrega una firma digital. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(X509Certificate2) | Crea un mensaje firmado. Crea una copia de solo lectura del MailMessage especificado y le agrega una firma digital. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(CmsSigner, bool) | Crea un mensaje firmado. Crea una copia de solo lectura del MailMessage especificado y le agrega una firma digital. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(X509Certificate2, bool) | Crea un mensaje firmado. Crea una copia de solo lectura del MailMessage especificado y le agrega una firma digital. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced)() | Comprueba si este mensaje se puede tratar como un mensaje de rebote. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature)() | Comprobando la firma existente MailMessage. |
| virtual [Clone](../../aspose.email/mailmessage/clone)() | Clona esta instancia |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt)(string, string) | Crea el recibo de lectura. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt)() | Descifra este mensaje |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt)(X509Certificate2) | Descifra este mensaje |
| [Dispose](../../aspose.email/mailmessage/dispose)() | Libera todos los recursos utilizados por MailMessage |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign)(RSACryptoServiceProvider, DKIMSignatureInfo) | Firma este mensaje usando la firma DKIM (DomainKeys Identified Mail). |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt)(X509Certificate2) | Cifra este mensaje |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt)(X509Certificate2[]) | Cifra este mensaje |
| override [Equals](../../aspose.email/mailmessage/equals)(object) | Determina si el Objeto especificado es igual al Objeto actual. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator)() | Devuelve un enumerador que itera a través de una colección. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode)() | Devuelve un código hash para object |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext)(bool) | Obtiene el cuerpo html del mensaje como texto sin formato. Este método analiza la propiedad HtmlBody y devuelve contenido de texto sin formato ignorando el marcado html. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext)(HyperlinkRenderingCallback) | Obtiene el mensaje htmlbody como texto sin formato. |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata)(SerializationInfo, StreamingContext) | Llena unSerializationInfo con los datos necesarios para serializar el objeto de destino. |
| virtual [Import](../../aspose.email/mailmessage/import)(Stream) | Importa mensaje de stream |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent)() | Compone el contenido TNEF. Tenga en cuenta que el archivo adjunto tnef se compone si un mensaje inicialmente contenía TNEF y se cargó sin el indicador FileCompatibilityMode.PreserveTnefAttachments, Es decir, este método no crea un mensaje tnef a partir del normal. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature)() | Eliminar firma |
| virtual [Save](../../aspose.email/mailmessage/save)(Stream) | Guardar mensaje como stream |
| virtual [Save](../../aspose.email/mailmessage/save)(string) | Guardar mensaje como archivo |
| override [Save](../../aspose.email.amp/ampmessage/save#save_1)(Stream, SaveOptions) | Guardar mensaje como stream |
| virtual [Save](../../aspose.email/mailmessage/save)(string, SaveOptions) | Guardar mensaje como un archivo con opciones adicionales. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody)(string, bool) | Establece el cuerpo html. |
| override [ToString](../../aspose.email/mailmessage/tostring)() | Devuelve una cadena que representa el objeto actual. |

### Ver también

* class [MailMessage](../../aspose.email/mailmessage)
* espacio de nombres [Aspose.Email.Amp](../../aspose.email.amp)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
