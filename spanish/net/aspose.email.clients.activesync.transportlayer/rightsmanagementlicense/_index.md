---
title: RightsManagementLicense
second_title: Referencia de la API de Aspose.Email para .NET
description: Contiene la configuración de la plantilla de política de derechos para la plantilla aplicada al mensaje de correo electrónico que se está sincronizando.
type: docs
weight: 1900
url: /es/net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/
---
## RightsManagementLicense class

Contiene la configuración de la plantilla de política de derechos para la plantilla aplicada al mensaje de correo electrónico que se está sincronizando.

```csharp
public class RightsManagementLicense
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RightsManagementLicense](rightsmanagementlicense)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ContentExpiryDate](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentexpirydate) { get; set; } | Especifica la fecha de vencimiento de la licencia. El elemento ContentExpiryDate se establece en "9999-12-30T23:59:59.999Z" si la licencia de administración de derechos no tiene una fecha de vencimiento establecida. |
| [ContentOwner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentowner) { get; set; } | Especifica si el usuario puede modificar el contenido del correo electrónico original cuando el usuario reenvía, responde o responde todo el mensaje de correo electrónico. El valor es VERDADERO si el usuario puede modificar el correo electrónico; de lo contrario, FALSO. Un valor de FALSO requiere que el cliente DEBE excluir el mensaje de correo electrónico original con derechos administrados de la solicitud de SmartForward o SmartReply. En consecuencia, las respuestas en línea no están permitidas si el elemento EditAllowed se establece en FALSO. Cuando EditAllowed se establece en FALSE y ReplaceMime no está presente en una solicitud de SmartForward o SmartReply, el servidor agregará el mensaje de correo electrónico original con derechos administrados como un archivo adjunto al nuevo mensaje. Por el contrario, si ReplaceMime está presente, el servidor no adjuntará el mensaje de correo electrónico original con derechos administrados como archivo adjunto. |
| [EditAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/editallowed) { get; set; } | Especifica si el usuario puede modificar el contenido del correo electrónico original cuando el usuario reenvía, responde o responde todo el mensaje de correo electrónico. El valor es VERDADERO si el usuario puede modificar el correo electrónico; de lo contrario, FALSO. Un valor de FALSO requiere que el cliente DEBE excluir el mensaje de correo electrónico original con derechos administrados de la solicitud de SmartForward o SmartReply. En consecuencia, las respuestas en línea no están permitidas si el elemento EditAllowed se establece en FALSO. Cuando EditAllowed se establece en FALSE y ReplaceMime no está presente en una solicitud de SmartForward o SmartReply, el servidor agregará el mensaje de correo electrónico original con derechos administrados como un archivo adjunto al nuevo mensaje. Por el contrario, si composemail:ReplaceMime está presente, el servidor no adjuntará el mensaje de correo electrónico original con derechos administrados como archivo adjunto. |
| [ExportAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/exportallowed) { get; set; } | Especifica si el usuario puede eliminar la protección IRM del mensaje de correo electrónico. El valor es TRUE si el usuario puede eliminar la protección IRM cuando reenvía, responde o responde todo el mensaje de correo electrónico; de lo contrario, FALSO. Si un mensaje de correo electrónico con derechos administrados se reenvía o responde mediante el comando SmartForward o SmartReply, se evalúan las siguientes condiciones: : la plantilla de política de derechos original tiene el elemento ExportAllowed establecido en TRUE : el ID de plantilla en el nuevo el mensaje se establece en la plantilla "Sin restricción" (valor de TemplateID "00000000-0000-0000-0000-000000000000") Si ambas condiciones son verdaderas, la protección IRM se elimina del mensaje saliente. El mensaje original conserva su protección IRM. |
| [ExtractAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/extractallowed) { get; set; } | Especifica si el usuario puede copiar el contenido del mensaje de correo electrónico. El valor es VERDADERO si el contenido del mensaje de correo electrónico se puede cortar, copiar o se puede tomar una captura de pantalla del contenido; en caso contrario, FALSO. |
| [ForwardAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/forwardallowed) { get; set; } | Especifica si el usuario puede reenviar el mensaje de correo electrónico. El valor es VERDADERO si el usuario puede reenviar el mensaje de correo electrónico; en caso contrario, FALSO. |
| [ModifyRecipientsAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/modifyrecipientsallowed) { get; set; } | Especifica si el usuario puede modificar la lista de destinatarios cuando reenvía o responde el mensaje de correo electrónico. El valor es VERDADERO si el usuario puede modificar la lista de destinatarios (1); en caso contrario, FALSO. |
| [Owner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/owner) { get; set; } | Especifica si el usuario es el propietario del mensaje de correo electrónico. El valor es VERDADERO si el usuario es el propietario del mensaje de correo electrónico; en caso contrario, FALSO. Un valor de TRUE indica que el usuario autenticado tiene derechos de propiedad sobre este mensaje. Este elemento se utiliza únicamente con fines de presentación de información. Los elementos Permitidos (EditAllowed, ReplyAllowed, etc.) se utilizan para evaluar si una determinada acción está permitida o restringida. |
| [PrintAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/printallowed) { get; set; } | Especifica si el usuario puede imprimir el correo electrónico. Este elemento no indica el soporte del cliente para imprimir un mensaje de correo electrónico; solo especifica si el mensaje de correo electrónico se puede imprimir si el cliente admite la impresión. El valor es VERDADERO si el usuario puede imprimir el correo electrónico; en caso contrario, FALSO. |
| [ProgrammaticAccessAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/programmaticaccessallowed) { get; set; } | Especifica si las aplicaciones de terceros pueden acceder mediante programación al contenido del mensaje de correo electrónico. El valor es TRUE si las aplicaciones de terceros pueden acceder al contenido del mensaje de correo electrónico mediante programación; en caso contrario, FALSO. Un valor de TRUE indica si otras aplicaciones pueden acceder al contenido protegido. El contenido protegido consta del cuerpo del mensaje y los archivos adjuntos. |
| [ReplyAllAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallallowed) { get; set; } | Especifica si el usuario puede responder a todos los destinatarios (1) del mensaje de correo electrónico original. El valor es VERDADERO si el usuario puede responder a todos los destinatarios del mensaje de correo electrónico; en caso contrario, FALSO. |
| [ReplyAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallowed) { get; set; } | Especifica si el usuario puede responder al mensaje de correo electrónico. El valor es VERDADERO si el usuario puede responder al mensaje de correo electrónico; en caso contrario, FALSO. |
| [TemplateDescription](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatedescription) { get; set; } | Contiene una descripción de la plantilla de política de derechos representada por el elemento principal RightsManagementLicense. Este elemento se utiliza únicamente con fines de presentación informativa. La longitud máxima del elemento TemplateDescription es de 10240 caracteres. |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templateid) { get; set; } | Contiene una cadena que identifica la plantilla de política de derechos representada por el elemento principal RightsManagementLicense. |
| [TemplateName](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatename) { get; set; } | Especifica el nombre de la plantilla de política de derechos representada por el elemento principal RightsManagementLicense. Este elemento se utiliza únicamente con fines informativos. La longitud máxima del elemento TemplateName es de 256 caracteres. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
