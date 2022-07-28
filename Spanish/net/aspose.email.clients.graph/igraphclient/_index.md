---
title: IGraphClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa la interfaz para el cliente Exchange REST.
type: docs
weight: 15950
url: /es/net/aspose.email.clients.graph/igraphclient/
---
## IGraphClient interface

Representa la interfaz para el cliente Exchange REST.

```csharp
public interface IGraphClient : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.graph/igraphclient/multipleservicestokenprovider) { get; set; } | Obtiene o establece un objeto que permite recuperar el token de acceso OAuth. |
| [Proxy](../../aspose.email.clients.graph/igraphclient/proxy) { get; set; } | Obtiene o establece datos para el acceso de proxy al servidor de Exchange. |
| [Resource](../../aspose.email.clients.graph/igraphclient/resource) { get; set; } | Obtiene o establece el tipo de recurso. |
| [ResourceId](../../aspose.email.clients.graph/igraphclient/resourceid) { get; set; } | Obtiene o establece la identificación del recurso. Por ejemplo, para los usuarios, puede ser el nombre principal del usuario (UPN) o la identificación del usuario |
| [TenantId](../../aspose.email.clients.graph/igraphclient/tenantid) { get; set; } | Obtiene o establece el identificador de arrendatario |
| [Timeout](../../aspose.email.clients.graph/igraphclient/timeout) { get; set; } | Obtiene o establece el número de milisegundos de espera antes de que se agote el tiempo de espera de la operación. El valor predeterminado es 100 000 milisegundos (100 segundos). |
| [TokenProvider](../../aspose.email.clients.graph/igraphclient/tokenprovider) { get; set; } | Obtiene o establece un objeto que permite recuperar el token de acceso OAuth. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CopyFolder](../../aspose.email.clients.graph/igraphclient/copyfolder)(string, string) | Copia una carpeta de correo y su contenido a otra carpeta de correo. |
| [CopyMessage](../../aspose.email.clients.graph/igraphclient/copymessage)(string, string) | Copiar un mensaje a otra carpeta de correo. |
| [CopyNotebook](../../aspose.email.clients.graph/igraphclient/copynotebook)(string, string, string) | Copia un bloc de notas en la carpeta Blocs de notas de la biblioteca Documentos de destino. La carpeta se crea si no existe. Para las operaciones de copia, sigue un patrón de llamada asíncrono: primero llame a la acción Copiar y luego sondee el punto final de la operación para obtener el resultado. Permisos Se requiere uno de los siguientes permisos para llamar esta API. Delegado (cuenta profesional o educativa) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegado (cuenta personal de Microsoft) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateAttachment](../../aspose.email.clients.graph/igraphclient/createattachment)(string, MapiAttachment) | Crea un nuevo archivo adjunto para el elemento especificado |
| [CreateCategory](../../aspose.email.clients.graph/igraphclient/createcategory)(string, CategoryPreset) | Crea un[`OutlookCategory`](../outlookcategory) objeto en la lista maestra de categorías del usuario. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder)(string) | Crear nueva carpeta. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder_1)(string, string) | Crear nueva carpeta. |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage)(string, MapiMessage) | Crea un mensaje en la carpeta especificada |
| [CreateNotebook](../../aspose.email.clients.graph/igraphclient/createnotebook)(Notebook) | Crear un nuevo bloc de notas de OneNote. Permisos Se requiere uno de los siguientes permisos para llamar a esta API. Delegado (cuenta profesional o educativa) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegado (cuenta personal de Microsoft) Notes. Crear, Notas.ReadWrite Notas de aplicación.ReadWrite.All |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride)(ClassificationOverride) | Crear una anulación para un remitente identificado por una dirección SMTP. Los mensajes futuros de esa dirección SMTP se clasificarán consistentemente como se especifica en la anulación. Nota: : si ya existe una anulación con la misma dirección SMTP, los campos classifyAs y name de esa anulación se actualizarán con los valores proporcionados. - La cantidad máxima de anulaciones admitidas para un buzón de correo es 1000, según las direcciones SMTP del remitente único. Permisos: Delegado (cuenta profesional o educativa) Mail.ReadWrite Delegado (cuenta personal de Microsoft) Mail.ReadWrite Application Mail.ReadWrite |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride_1)(MailAddress, ClassificationType) | Crear una anulación para un remitente identificado por una dirección SMTP. Los mensajes futuros de esa dirección SMTP se clasificarán consistentemente como se especifica en la anulación. Nota: : si ya existe una anulación con la misma dirección SMTP, los campos classifyAs y name de esa anulación se actualizarán con los valores proporcionados. - La cantidad máxima de anulaciones admitidas para un buzón de correo es 1000, según las direcciones SMTP del remitente único. Permisos: Delegado (cuenta profesional o educativa) Mail.ReadWrite Delegado (cuenta personal de Microsoft) Mail.ReadWrite Application Mail.ReadWrite |
| [CreateRule](../../aspose.email.clients.graph/igraphclient/createrule)(InboxRule) | Cree una regla de mensajes especificando un conjunto de condiciones y acciones. Outlook lleva a cabo esas acciones si un mensaje entrante en la bandeja de entrada del usuario cumple las condiciones especificadas. Permisos: Se requiere uno de los siguientes permisos para llamar a esta API. Obtenga más información, incluido cómo elegir permisos, consulte Permisos. Delegado (cuenta profesional o educativa) MailboxSettings.ReadWrite Delegado (cuenta personal de Microsoft) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [Delete](../../aspose.email.clients.graph/igraphclient/delete)(string) | Eliminar objeto. |
| [DeleteAttachment](../../aspose.email.clients.graph/igraphclient/deleteattachment)(string) | Elimina adjunto |
| [FetchAttachment](../../aspose.email.clients.graph/igraphclient/fetchattachment)(string) | Obtiene datos adjuntos para el id especificado |
| [FetchCategory](../../aspose.email.clients.graph/igraphclient/fetchcategory)(string) | Obtener las propiedades y relaciones del objeto OutlookCategory especificado. |
| [FetchMessage](../../aspose.email.clients.graph/igraphclient/fetchmessage)(string) | Obtiene el mensaje en el id especificado |
| [FetchNotebook](../../aspose.email.clients.graph/igraphclient/fetchnotebook)(string) | Recuperar las propiedades y relaciones de un objeto de bloc de notas. Permisos Se requiere uno de los siguientes permisos para llamar a esta API. Delegado (cuenta profesional o educativa) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All , Notes.ReadWrite.All Delegado (cuenta personal de Microsoft) Notes.Create, Notes.Read, Notes.ReadWrite Aplicación Notes.Read.All, Notes.ReadWrite.All |
| [FetchRule](../../aspose.email.clients.graph/igraphclient/fetchrule)(string) | Obtener las propiedades y relaciones de un objeto de regla de mensaje. Permisos Se requiere uno de los siguientes permisos para llamar a esta API. Para obtener más información, incluido cómo elegir permisos, consulte Permisos. Delegado (cuenta profesional o educativa) MailboxSettings.Read Delegado (cuenta personal de Microsoft) MailboxSettings.Read Application MailboxSettings.Read |
| [GetFolder](../../aspose.email.clients.graph/igraphclient/getfolder)(string) | Obtiene carpeta por id. |
| [GetOneNoteOperationStatus](../../aspose.email.clients.graph/igraphclient/getonenoteoperationstatus)(string) | Obtener el estado de una operación de OneNote de ejecución prolongada. Esto se aplica a las operaciones que devuelven el encabezado Operation-Location en la respuesta, como CopyNotebook, CopyToNotebook, CopyToSectionGroup y CopyToSection. Puede sondear el extremo Operation-Location hasta que la propiedad de estado devuelve completado o fallido. Si el estado es completado, la propiedad resourceLocation contiene el URI del extremo del recurso. Si el estado falla, las propiedades error y @api.diagnostics brindan información sobre el error. |
| [ListAttachments](../../aspose.email.clients.graph/igraphclient/listattachments)(string) | Listar adjuntos del mensaje principal. |
| [ListCategories](../../aspose.email.clients.graph/igraphclient/listcategories)() | Obtener todas las categorías que se han definido para el usuario. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders)() | Enumera las carpetas de la carpeta principal para las carpetas que se muestran en los clientes de correo normales, como la bandeja de entrada. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders_1)(string) | Enumera las carpetas de la carpeta principal para las carpetas que se muestran en los clientes de correo normales, como la bandeja de entrada. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages_1)(string) | Lista MessageInfo de la carpeta principal. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages)(string, PageInfo, MailQuery) | Lista MessageInfo de la carpeta principal. |
| [ListNotebooks](../../aspose.email.clients.graph/igraphclient/listnotebooks)() | Recuperar una lista de objetos del cuaderno. Permisos Se requiere uno de los siguientes permisos para llamar a esta API. Delegado (cuenta profesional o educativa) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes. ReadWrite.All Delegado (cuenta personal de Microsoft) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [ListOverrides](../../aspose.email.clients.graph/igraphclient/listoverrides)() | Obtenga las anulaciones que un usuario ha configurado para clasificar siempre los mensajes de ciertos remitentes de formas específicas. Cada anulación corresponde a una dirección SMTP de un remitente. Inicialmente, un usuario no tiene ninguna anulación. Permisos: Uno de los Se requieren los siguientes permisos para llamar a esta API. Para obtener más información, incluido cómo elegir permisos, consulte Permisos. Delegado (cuenta profesional o educativa) Mail.Read Delegado (cuenta personal de Microsoft) Mail.Read Application Mail.Read |
| [ListRules](../../aspose.email.clients.graph/igraphclient/listrules)() | Obtener todos los objetos messageRule definidos para la Bandeja de entrada del usuario. Permisos Se requiere uno de los siguientes permisos para llamar a esta API. Para obtener más información, incluido cómo elegir permisos, consulte Permisos. Delegado (cuenta profesional o educativa) MailboxSettings.Read Delegado (cuenta personal de Microsoft) MailboxSettings.Read Application MailboxSettings.Read |
| [MoveFolder](../../aspose.email.clients.graph/igraphclient/movefolder)(string, string) | Mover una carpeta de correo y su contenido a otra carpeta de correo. |
| [MoveMessage](../../aspose.email.clients.graph/igraphclient/movemessage)(string, string) | Mover un mensaje a otra carpeta de correo. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send)(MapiMessage) | Envía mensaje de correo electrónico |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_2)(string) | Enviar un mensaje en la carpeta de borradores. El borrador del mensaje puede ser un borrador de mensaje nuevo, un borrador de respuesta, un borrador de respuesta a todos o un borrador de reenvío. El mensaje se guarda en la carpeta Elementos enviados. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_1)(MapiMessage, bool) | Envía mensaje de correo electrónico |
| [SetRead](../../aspose.email.clients.graph/igraphclient/setread)(string) | Marcar mensaje como leído |
| [UpdateCategory](../../aspose.email.clients.graph/igraphclient/updatecategory)(OutlookCategory) | Actualiza la constante de color preestablecida para la categoría especificada |
| [UpdateFolder](../../aspose.email.clients.graph/igraphclient/updatefolder)(FolderInfo) | Carpeta de actualizaciones. |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage)(MapiMessage) | Mensaje de actualizaciones |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage_1)(MapiMessage, UpdateSettings) | Mensaje de actualizaciones |
| [UpdateOverride](../../aspose.email.clients.graph/igraphclient/updateoverride)(ClassificationOverride) | Cambie el campo classifyAs de una invalidación como se especifica. No puede usar este método para cambiar ningún otro campo en una instancia de ClassificationOverride. Si existe una invalidación para un remitente y el remitente cambia su nombre para mostrar, puede usar CreateOrUpdateOverride para forzar una actualización del campo de nombre en la anulación existente. Si existe una anulación para un remitente y el remitente cambia su dirección SMTP, eliminar la anulación existente y crear una nueva con la nueva dirección SMTP es la única forma de "actualizar" la anulación para este remitente. Permisos: Se requiere uno de los siguientes permisos para llamar a esta API. Para obtener más información, incluido cómo elegir permisos, consulte Permisos. Delegado (cuenta profesional o educativa) Mail.ReadWrite Delegado (cuenta personal de Microsoft) Mail.ReadWrite Application Mail.ReadWrite |
| [UpdateRule](../../aspose.email.clients.graph/igraphclient/updaterule)(InboxRule) | Cambie las propiedades de escritura en un objeto messageRule y guarde los cambios. Permisos Se requiere uno de los siguientes permisos para llamar a esta API. Para obtener más información, incluido cómo elegir permisos, consulte Permisos. Configuración de buzón de correo delegado (cuenta profesional o educativa). ReadWrite Delegado (cuenta personal de Microsoft) MailboxSettings.ReadWrite Aplicación MailboxSettings.ReadWrite |

### Ver también

* espacio de nombres [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
