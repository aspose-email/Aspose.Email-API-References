---
title: IEWSClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa la interfaz para el cliente de Exchange.
type: docs
weight: 3960
url: /es/net/aspose.email.clients.exchange.webservice/iewsclient/
---
## IEWSClient interface

Representa la interfaz para el cliente de Exchange.

```csharp
public interface IEWSClient : IExchangeClientBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CalendarFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/calendarfoldereventfilter) { get; set; } | Especifica tipos de eventos para la carpeta Calendario |
| [ContactsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/contactsfoldereventfilter) { get; set; } | Especifica tipos de eventos para la carpeta de contactos |
| [CurrentCalendarFolderUri](../../aspose.email.clients.exchange.webservice/iewsclient/currentcalendarfolderuri) { get; set; } | Obtiene o establece la carpeta de calendario actual uri |
| [DeletedItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/deleteditemsfoldereventfilter) { get; set; } | Especifica tipos de eventos para la carpeta DeletedItems |
| [DraftsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/draftsfoldereventfilter) { get; set; } | Especifica tipos de eventos para la carpeta Borradores |
| [EnableDecompression](../../aspose.email.clients.exchange.webservice/iewsclient/enabledecompression) { get; set; } | Obtiene o establece un valor que indica si la descompresión está habilitada |
| [Headers](../../aspose.email.clients.exchange.webservice/iewsclient/headers) { get; } | Obtiene una matriz de pares de valores de nombre que se agregan a WebHeaderCollection en la solicitud de EWS. |
| [InboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/inboxfoldereventfilter) { get; set; } | Especifica tipos de eventos para la carpeta Bandeja de entrada |
| [JournalFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/journalfoldereventfilter) { get; set; } | Especifica los tipos de eventos para la carpeta Diario |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/mailboxinfo) { get; } | Obtiene la información del buzón. |
| [NotesFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/notesfoldereventfilter) { get; set; } | Especifica tipos de eventos para la carpeta de notas |
| [NotificationsCheckInterval](../../aspose.email.clients.exchange.webservice/iewsclient/notificationscheckinterval) { get; set; } | Define el intervalo para la verificación de notificaciones |
| [NotificationTimeout](../../aspose.email.clients.exchange.webservice/iewsclient/notificationtimeout) { get; set; } | Define el tiempo de espera para las notificaciones del servidor |
| [OutboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/outboxfoldereventfilter) { get; set; } | Especifica tipos de eventos para la carpeta Bandeja de salida |
| [ReconnectCount](../../aspose.email.clients.exchange.webservice/iewsclient/reconnectcount) { get; set; } | Obtiene o establece el número de intentos de reconexión cuando se interrumpe la conexión. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange.webservice/iewsclient/returnclientrequestid) { get; set; } | Obtiene o establece un indicador para indicar si el cliente requiere que el lado del servidor devuelva la solicitud id. |
| [RootFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/rootfoldereventfilter) { get; set; } | Especifica los tipos de eventos para la carpeta raíz |
| [SentItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/sentitemsfoldereventfilter) { get; set; } | Especifica tipos de eventos para la carpeta SentItems |
| [ServerVersion](../../aspose.email.clients.exchange.webservice/iewsclient/serverversion) { get; } | Obtiene la información sobre la versión actual de MS Exchange. |
| [TasksFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/tasksfoldereventfilter) { get; set; } | Especifica tipos de eventos para la carpeta Tareas |
| [TimezoneId](../../aspose.email.clients.exchange.webservice/iewsclient/timezoneid) { get; set; } | Obtiene o establece la zona horaria id |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iewsclient/useslashasfolderseparator) { get; set; } | Obtiene o establece el valor que determina si la barra inclinada '/' se usa como separador de carpetas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddHeader](../../aspose.email.clients.exchange.webservice/iewsclient/addheader)(string, string) | Agrega nombre y valor a WebHeaderCollection en la solicitud de EWS. |
| [AddToDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/addtodistributionlist)(ExchangeDistributionList, MailAddressCollection) | Agrega los miembros a la Lista de distribución. |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage)(MailMessage) | Sube el mensaje de correo a la carpeta Bandeja de entrada |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_1)(MapiMessage) | Sube el mensaje de correo a la carpeta especificada |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_2)(MapiMessage, bool) | Sube el mensaje de correo a la carpeta especificada |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_3)(string, MailMessage) | Sube el mensaje de correo a la carpeta especificada |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_5)(string, MapiMessage, bool) | Sube el mensaje de correo a la carpeta especificada |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_1)(IEnumerable&lt;MailMessage&gt;) | Sube el mensaje de correo a la carpeta especificada |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages)(params MailMessage[]) | Sube el mensaje de correo a la carpeta especificada |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_3)(string, IEnumerable&lt;MailMessage&gt;) | Sube los mensajes de correo a la carpeta especificada |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_4)(string, IEnumerable&lt;MapiMessage&gt;) | Sube los mensajes mapi a la carpeta especificada |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_2)(string, params MailMessage[]) | Sube el mensaje de correo a la carpeta especificada |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem)(string, Appointment) | La operación ArchiveItem mueve un elemento al buzón de archivo del usuario del buzón. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_1)(string, ExchangeTask) | La operación ArchiveItem mueve un elemento al buzón de archivo del usuario del buzón. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_2)(string, MapiMessageItemBase) | La operación ArchiveItem mueve un elemento al buzón de archivo del usuario del buzón. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_3)(string, string) | La operación ArchiveItem mueve un elemento al buzón de archivo del usuario del buzón. |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Realiza copias de seguridad del contenido de las carpetas especificadas |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Realiza copias de seguridad del contenido de las carpetas especificadas |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment)(Appointment) | Cancela cita. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_2)(MapiCalendar) | Cancela cita. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_4)(string) | Cancela una reunión existente en el calendario de un organizador |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_1)(Appointment, string) | Cancela cita. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_3)(MapiCalendar, string) | Cancela cita. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_5)(string, string) | Cancela una reunión existente en el calendario de un organizador |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability)(string, DateRange) | Verifica la disponibilidad del usuario dentro de la ventana de tiempo especificada. |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability_1)(StringCollection, DateRange) | Verifica la disponibilidad de los usuarios dentro de la ventana de tiempo especificada. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_1)(ExchangeDelegateUser, string) | Cierra el acceso al buzón especificado para el usuario especificado. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_2)(ExchangeDelegateUserCollection, string) | Cierra el acceso al buzón especificado para el usuario especificado. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess)(ExchangeFolderUserInfo, string) | Cierra el acceso al buzón especificado para el usuario especificado. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_3)(string, string) | Cierra el acceso al buzón especificado para el usuario especificado. |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems)(string, string) | Copia los elementos de conversación en la carpeta de destino especificada |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems_1)(string, string, string) | Copia los elementos de conversación, que se encuentran en la carpeta especificada, en la carpeta de destino especificada |
| [CopyItem](../../aspose.email.clients.exchange.webservice/iewsclient/copyitem)(string, string) | Copia el elemento a la carpeta especificada |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment)(Appointment) | Crea cita. |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_1)(Appointment, string) | Crea cita. |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_4)(MapiCalendar, string, bool) | Crea cita. |
| [CreateCalendarSharingInvitationMessage](../../aspose.email.clients.exchange.webservice/iewsclient/createcalendarsharinginvitationmessage)(string) | Crear mensaje de invitación para compartir calendario. |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_1)(Contact) | Crea un elemento de contacto en la tienda de Exchange. |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_3)(string, Contact) | Crea un elemento de contacto en la carpeta especificada. |
| [CreateDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/createdistributionlist)(ExchangeDistributionList, MailAddressCollection) | Crea la Lista de distribución privada. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder)(string) | Crea una nueva carpeta en la carpeta raíz. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_1)(string, ExchangeFolderType) | Crea una nueva carpeta en la carpeta raíz. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_2)(string, string) | Crea la nueva carpeta con el nombre especificado en la carpeta principal especificada. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_3)(string, string, ExchangeFolderPermissionCollection) | Crea la nueva carpeta |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_5)(string, string, ExchangeFolderType) | Crea la nueva carpeta |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_4)(string, string, ExchangeFolderPermissionCollection, string) | Crea la nueva carpeta |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule)(InboxRule) | Crea la regla de bandeja de entrada especificada |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule_1)(InboxRule, string) | Crea la regla de bandeja de entrada especificada |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem)(MapiMessageItemBase) | Crea el elemento dado en la carpeta de elementos predeterminada. |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem_1)(string, MapiMessageItemBase) | Crea el elemento dado en la carpeta especificada. |
| [CreateItems](../../aspose.email.clients.exchange.webservice/iewsclient/createitems)(ExchangeStreamedItem[], string) | Crea los elementos especificados en la carpeta especificada |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder)(string, ExchangeFolderPermissionCollection) | Crea la carpeta pública especificada en la carpeta pública raíz |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_1)(string, ExchangeFolderPermissionCollection, ExchangeFolderType) | Crea la carpeta pública especificada en la carpeta pública raíz |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_2)(string, string, ExchangeFolderPermissionCollection) | Crea la carpeta pública especificada en la carpeta pública raíz |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask)(ExchangeTask) | Crea la tarea dada en la carpeta de tareas predeterminada. |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask_2)(string, ExchangeTask) | Crea la tarea dada en la carpeta especificada. |
| [CreateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/createuserconfiguration)(UserConfiguration) | Crea la configuración de usuario especificada |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess)(ExchangeDelegateUser, string) | Delega el acceso al buzón especificado al usuario especificado. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_1)(ExchangeDelegateUserCollection, string) | Delega el acceso al buzón a los usuarios especificados. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_2)(string, ExchangeDelegateFolderPermissionLevel, string) | Delega el acceso al buzón principal al usuario especificado. |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems)(string) | Elimina todos los elementos de la conversación especificada |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems_1)(string, string) | Elimina los elementos de conversación, que se encuentran en la carpeta especificada |
| [DeleteDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletedistributionlist)(ExchangeDistributionList, bool) | Elimina la Lista de distribución. |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder)(string) | Elimina la carpeta |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder_1)(string, bool) | Elimina la carpeta |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders)(ExchangeFolderInfoCollection) | Elimina las carpetas especificadas |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_2)(StringCollection) | Elimina las carpetas especificadas |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_1)(ExchangeFolderInfoCollection, bool) | Elimina las carpetas especificadas |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_3)(StringCollection, bool) | Elimina la carpeta |
| [DeleteFromDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletefromdistributionlist)(ExchangeDistributionList, MailAddressCollection) | Elimina los miembros de la Lista de distribución. |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule)(string) | Elimina la regla de bandeja de entrada especificada |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule_1)(string, string) | Elimina la regla de bandeja de entrada especificada |
| [DeleteItem](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitem)(string, DeletionOptions) | Elimina el elemento especificado |
| [DeleteItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitems)(IEnumerable&lt;string&gt;, DeletionOptions) | Elimina elementos especificados |
| [DeleteUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/deleteuserconfiguration)(UserConfigurationName) | Elimina la configuración de usuario especificada |
| [DisconnectPhoneCall](../../aspose.email.clients.exchange.webservice/iewsclient/disconnectphonecall)(string) | Desconecta una llamada telefónica especificada por id. |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder)(string) | Vacía la carpeta especificada. Las subcarpetas no se eliminarán; los elementos eliminados se moverán a la carpeta DeletedItems |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder_1)(string, EmptyFolderOptions) | Vacía la carpeta especificada |
| [ExpandDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/expanddistributionlist)(MailAddress) | Expande los miembros de la lista de distribución pública. |
| [ExportItems](../../aspose.email.clients.exchange.webservice/iewsclient/exportitems)(params string[]) | Exporta los elementos especificados desde mailbox |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment)(string) | Obtener la cita especificada del servidor. |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment_1)(string, string) | Obtener la cita especificada del servidor. |
| [FetchAttachment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchattachment)(string) | Obtiene el archivo adjunto |
| [FetchConversationMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchconversationmessages)(string) | Obtiene los mensajes de conversación especificados |
| [FetchDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/fetchdistributionlist)(ExchangeDistributionList) | Obtiene los miembros de la lista de distribución privada. |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem)(string) | Recupera el elemento como[`MapiMessage`](../../aspose.email.mapi/mapimessage) . |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Recupera el elemento como[`MapiMessage`](../../aspose.email.mapi/mapimessage) . |
| [FetchItems](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitems)(EwsFetchItems) | Recupera los elementos. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar)(IEnumerable&lt;string&gt;) | Obtener matriz de[`MapiCalendar`](../../aspose.email.mapi/mapicalendar) objetos. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Obtener matriz de[`MapiCalendar`](../../aspose.email.mapi/mapicalendar) objetos. |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages)(IEnumerable&lt;string&gt;) | Obtiene los mensajes especificados |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Obtiene los mensajes especificados |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes)(IEnumerable&lt;string&gt;) | Obtener matriz de[`MapiNote`](../../aspose.email.mapi/mapinote) objetos. |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Obtener matriz de[`MapiNote`](../../aspose.email.mapi/mapinote) objetos. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks)(IEnumerable&lt;string&gt;) | Obtener matriz de[`MapiTask`](../../aspose.email.mapi/mapitask) objetos. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Obtener matriz de[`MapiTask`](../../aspose.email.mapi/mapitask) objetos. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage)(string) | Obtiene el mensaje. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Obtiene el mensaje del servidor |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages)(IEnumerable&lt;ExchangeMessageInfo&gt;) | Obtiene los mensajes especificados |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_1)(IEnumerable&lt;string&gt;) | Obtiene los mensajes especificados |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_3)(StringCollection) | Obtiene los mensajes especificados |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_2)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Obtiene los mensajes especificados |
| [FetchTask](../../aspose.email.clients.exchange.webservice/iewsclient/fetchtask)(string) | Obtiene la tarea especificada. |
| [FindConversations](../../aspose.email.clients.exchange.webservice/iewsclient/findconversations)(string) | Encuentra conversaciones en la carpeta especificada |
| [FindMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/findmessagetrackingreport)(FindMessageTrackingReportOptions) | Encuentra mensajes que cumplen los criterios especificados. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople_1)(string, int) | Encuentra contactos ubicados en la lista global de direcciones (GAL) en el servidor. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople)(string, MailQuery, int) | Buscar contactos ubicados en el buzón personal del usuario especificado en el servidor. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists)(string, string) | Comprueba si existe la carpeta especificada. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Comprueba si existe la carpeta especificada. |
| [Forward](../../aspose.email.clients.exchange.webservice/iewsclient/forward)(MailMessage, ExchangeMessageInfo) | Reenviar un mensaje. |
| [GetCallInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getcallinfo)(string) | Recupera información de llamadas telefónicas por llamada id |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact)(ObjectIdentifier) | Recupera información de contacto según el identificador especificado. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_2)(string) | Recupera información de contacto según el identificador especificado. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_1)(ObjectIdentifier, ExchangeListContactsOptions) | Recupera información de contacto según el identificador especificado. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_3)(string, ExchangeListContactsOptions) | Recupera información de contacto según el identificador especificado. |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts)(string) | Muestra los contactos ubicados en la carpeta especificada en server |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts_1)(string, ExchangeListContactsOptions) | Muestra los contactos ubicados en la carpeta especificada en server |
| [GetExchangeType](../../aspose.email.clients.exchange.webservice/iewsclient/getexchangetype)() | Obtiene la información sobre la versión actual de MS Exchange. |
| [GetFolderInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderinfo)(string) | Obtiene la información de la carpeta |
| [GetFolderPermissions](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderpermissions)(string) | Obtiene los permisos de la carpeta. |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules)() | Obtiene las reglas de la bandeja de entrada |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules_1)(string) | Obtiene las reglas de la bandeja de entrada |
| [GetMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxes)() | Enumera los buzones que tienen direcciones smtp. Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción de la operación EWS utilizada. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo)() | Obtiene la información del buzón. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo_1)(string) | Obtiene la información del buzón |
| [GetMailboxSize](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsize)() | Obtiene el tamaño del buzón. Por favor, tenga en cuenta que esta operación se realiza de forma recursiva para todas las subcarpetas y tarda algo de tiempo |
| [GetMailboxSizeEx](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsizeex)(string) | Obtiene el tamaño del buzón Tenga en cuenta que esta operación se realiza de forma recursiva para todas las subcarpetas y tarda algo de tiempo |
| [GetMailTips](../../aspose.email.clients.exchange.webservice/iewsclient/getmailtips)(GetMailTipsOptions) | Recibe sugerencias de correo |
| [GetMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/getmessagetrackingreport)(GetMessageTrackingReportOptions) | Obtiene el informe de seguimiento de mensajes |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids)() | GetServerTimeZoneIds devuelve información de la identificación de la zona horaria que está disponible en un servidor de Exchange. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_1)(IEnumerable&lt;string&gt;) | GetServerTimeZoneIds devuelve información de la identificación de la zona horaria que está disponible en un servidor de Exchange. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_2)(params string[]) | GetServerTimeZoneIds devuelve información de la identificación de la zona horaria que está disponible en un servidor de Exchange. |
| [GetUMConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getumconfiguration)() | Recupera la configuración de mensajería unificada |
| [GetUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getuserconfiguration)(UserConfigurationName) | Obtiene la configuración de usuario especificada |
| [GetVersionInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getversioninfo)() | Devuelve información de la versión del servidor de intercambio |
| [ImpersonateUser](../../aspose.email.clients.exchange.webservice/iewsclient/impersonateuser)(ItemChoice, string) | Se hace pasar por el usuario. |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments)() | Recupera la lista de citas para la carpeta de calendario predeterminada |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_3)(bool) | Recupera la lista de citas para la carpeta de calendario predeterminada |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_1)(MailQuery) | Recupera la lista de citas para la carpeta de calendario predeterminada |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_4)(string) | Recupera la lista de citas para la carpeta de calendario especificada |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_2)(MailQuery, bool) | Recupera la lista de citas para la carpeta de calendario predeterminada |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_7)(string, bool) | Recupera la lista de citas para la carpeta de calendario especificada |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_5)(string, MailQuery) | Recupera la lista de citas para la carpeta de calendario especificada |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_6)(string, MailQuery, bool) | Recupera la lista de citas para la carpeta de calendario especificada |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_2)(int) | Recupera la página con citas para la carpeta del calendario |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_3)(int, int) | Recupera la página con citas para la carpeta del calendario |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage)(MailQuery, int) | Recupera la página con citas para la carpeta del calendario |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_6)(string, int) | Recupera la página con citas para la carpeta de calendario especificada |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_1)(MailQuery, int, int) | Recupera la página con citas para la carpeta del calendario |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_7)(string, int, int) | Recupera la página con citas para la carpeta de calendario especificada |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_4)(string, MailQuery, int) | Recupera la página con citas para la carpeta de calendario especificada |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_5)(string, MailQuery, int, int) | Recupera la página con citas para la carpeta de calendario especificada |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts)(string) | Muestra los contactos ubicados en la carpeta especificada en server |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Muestra los contactos ubicados en la carpeta especificada en server |
| [ListDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/listdelegates)(string) | Enumera los usuarios a los que se les otorga acceso al buzón de correo especificado. |
| [ListDistributionLists](../../aspose.email.clients.exchange.webservice/iewsclient/listdistributionlists)() | Listar las Listas de Distribución privadas. |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems)(string) | Recuperar la lista de artículos en la carpeta especificada |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_1)(string, MailQuery) | Recuperar la lista de artículos en la carpeta especificada |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_3)(string, string) | Recuperar la lista de artículos en la carpeta especificada |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_2)(string, MailQuery, bool) | Recuperar la lista de artículos en la carpeta especificada |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_4)(string, string, MailQuery) | Recuperar la lista de artículos en la carpeta especificada |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_5)(string, string, MailQuery, bool) | Recuperar la lista de artículos en la carpeta especificada |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes)() | Lista de buzones. |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes_1)(string) | Preste atención, este método anulado funciona con Exchange Server 2013 y versiones posteriores. Lista de buzones. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages)() | Lista los mensajes en la carpeta de la bandeja de entrada. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_1)(IEnumerable&lt;string&gt;) | Lista los mensajes en la carpeta especificada. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_2)(string) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_7)(string, bool) | Lista los mensajes en la carpeta especificada |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_3)(string, ExchangeListMessagesOptions) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_8)(string, int) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_5)(string, MailQuery) | Lista los mensajes en la carpeta especificada. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_4)(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) | Lista los mensajes en la carpeta especificada |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_9)(string, int, ExchangeListMessagesOptions) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_10)(string, int, MailQuery) | Lista los mensajes en la carpeta especificada. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_6)(string, MailQuery, bool) | Lista los mensajes en la carpeta especificada. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_13)(string, string, bool) | Lista los mensajes en la carpeta especificada |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_12)(string, string, MailQuery) | Lista los mensajes en la carpeta especificada. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_11)(string, int, MailQuery, bool) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_4)(string, int) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage)(string, PageInfo) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_5)(string, int, int) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_2)(string, MailQuery, int) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_1)(string, PageInfo, ExchangeListMessagesOptions) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_6)(string, int, int, ExchangeListMessagesOptions) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_3)(string, MailQuery, int, int) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder)(ExchangeFolderInfo) | Obtener una colección de mensajes de la carpeta pública |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder_1)(string) | Obtener una colección de mensajes de la carpeta pública |
| [ListPublicFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listpublicfolders)() | Obtiene la colección de carpetas públicas de la carpeta pública raíz |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | Obtiene la colección de carpetas públicas secundarias de parent |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_1)(string) | Obtiene la colección de carpetas secundarias de parent |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_2)(string, string) | Obtiene la colección de carpetas secundarias de parent |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_1)(string, int) | Busca la carpeta especificada en la carpeta principal dada con paginación El método admite la paginación. Llama por primera vez en ciclo de paginación. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage)(string, PageInfo) | Busca la carpeta especificada en la carpeta principal dada con paging El método admite paginación. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_2)(string, int, int) | Busca la carpeta especificada en la carpeta principal dada con paging El método admite paginación. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks)() | Recupera listas de tareas de intercambio para la carpeta predeterminada. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_1)(string) | Recupera listas de tareas de intercambio. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_3)(string, int) | Recupera listas de tareas de intercambio. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_2)(string, MailQuery) | Recupera listas de tareas de intercambio. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_4)(string, int, MailQuery) | Recupera listas de tareas de intercambio. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_5)(string, int, MailQuery, bool) | Recupera listas de tareas de intercambio. |
| [LoadContactPhoto](../../aspose.email.clients.exchange.webservice/iewsclient/loadcontactphoto)(ContactPhoto) | Carga los datos binarios de la foto de contacto |
| [MailDisablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/maildisablepublicfolder)(string) | Mail-deshabilitar una carpeta pública |
| [MailEnablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/mailenablepublicfolder)(string) | Habilitar para correo una carpeta pública |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_2)(bool, params string[]) | Marca todos los elementos en las carpetas especificadas. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems)(bool, bool, IEnumerable&lt;string&gt;) | Marca todos los elementos en las carpetas especificadas. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_1)(bool, bool, params string[]) | Marca todos los elementos en las carpetas especificadas. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread)() | Marca todos los elementos en la carpeta de la bandeja de entrada como leídos sin recibos. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_1)(IEnumerable&lt;string&gt;) | Marca todos los elementos de las carpetas especificadas como leídos sin recibos. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_2)(params string[]) | Marca todos los elementos de las carpetas especificadas como leídos sin recibos. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread)() | Marca todos los elementos en la carpeta de la bandeja de entrada como no leídos. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_1)(IEnumerable&lt;string&gt;) | Marca todos los elementos de las carpetas especificadas como no leídos. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_2)(params string[]) | Marca todos los elementos de las carpetas especificadas como no leídos. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_2)(bool, IEnumerable&lt;string&gt;) | El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_3)(bool, params string[]) | El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk)(bool, bool, IEnumerable&lt;string&gt;) | El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_1)(bool, bool, params string[]) | El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_4)(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) | El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje. |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems)(string, string) | Mueve los elementos de conversación a la carpeta de destino especificada |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems_1)(string, string, string) | Mueve los elementos de conversación, que se encuentran en la carpeta especificada, a la carpeta de destino especificada |
| [MoveItem](../../aspose.email.clients.exchange.webservice/iewsclient/moveitem)(string, string) | Mueve el elemento a la carpeta especificada |
| [PlayOnPhone](../../aspose.email.clients.exchange.webservice/iewsclient/playonphone)(string, string) | La operación PlayOnPhone inicia una llamada saliente y reproduce un mensaje por teléfono. |
| [RemoveHeader](../../aspose.email.clients.exchange.webservice/iewsclient/removeheader)(string) | Eliminar WebHeader de WebHeaderCollection en la solicitud de EWS. |
| [Reply](../../aspose.email.clients.exchange.webservice/iewsclient/reply)(MailMessage, ExchangeMessageInfo) | Responder al mensaje del remitente. |
| [ReplyAll](../../aspose.email.clients.exchange.webservice/iewsclient/replyall)(MailMessage, ExchangeMessageInfo) | Responder al remitente y a todos los destinatarios de un mensaje. |
| [ResetImpersonation](../../aspose.email.clients.exchange.webservice/iewsclient/resetimpersonation)() | Hace resetear la suplantación. |
| [ResetSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/resetsubscription)() | Restablecer todas las suscripciones |
| [ResolveContact](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontact)(string) | Resuelve nombres de buzón ambiguos. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts)(string) | Resuelve nombres ambiguos para mostrar en los buzones. Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción del comando de intercambio usado. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts_1)(string, ExchangeListContactsOptions) | Resuelve direcciones de correo electrónico ambiguas y nombres para mostrar Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción de la operación EWS utilizada. |
| [Restore](../../aspose.email.clients.exchange.webservice/iewsclient/restore)(PersonalStorage, RestoreSettings) | Restaura las carpetas de intercambio especificadas del almacenamiento personal dado. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage)(string, Stream) | Guarda el mensaje. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage_1)(string, string) | Guarda el mensaje. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send)(MailMessage) | Envía el mensaje especificado. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_1)(MailMessage, FollowUpOptions) | Envía el mensaje. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_2)(string, string, string, string) | Envía el mensaje especificado |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate)(string, bool) | Establece el estado de lectura de los elementos de conversación en el valor especificado |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate_1)(string, string, bool) | Establece el estado de lectura de los elementos de conversación, que se encuentran en la carpeta especificada, en el valor especificado |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag)(string) | Establece el indicador de lectura. |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag_1)(string, bool) | Marca el mensaje especificado como leído. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_1)(string) | Recupera los cambios de los elementos y subcarpetas en una carpeta especificada. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder)(SyncState) | Recupera los cambios de los elementos en una carpeta especificada. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_3)(string, string) | Recupera los cambios de los elementos en una carpeta especificada. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_2)(string, SyncFolderType) | Recupera los cambios de los elementos y subcarpetas en una carpeta especificada. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_4)(string, string, IEnumerable&lt;string&gt;) | Recupera los cambios de los elementos en una carpeta especificada. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment)(Appointment) | Actualiza cita. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_2)(MapiCalendar) | Actualiza cita. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_1)(Appointment, string) | Actualiza cita. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_3)(MapiCalendar, string) | Actualiza cita. |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact_1)(Contact) | Actualiza un elemento de contacto en la tienda de Exchange. |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact)(MapiContact) | Actualiza un elemento de contacto en la tienda de Exchange. |
| [UpdateDelegate](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegate)(ExchangeDelegateUser, string) | Actualiza la configuración del usuario delegado a quien se le otorga acceso en el buzón especificado. |
| [UpdateDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegates)(ExchangeDelegateUserCollection, string) | Actualiza la configuración de los usuarios delegados a los que se otorga acceso al buzón de correo especificado. |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule)(InboxRule) | Actualiza la regla de bandeja de entrada especificada |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule_1)(InboxRule, string) | Actualiza la regla de bandeja de entrada especificada |
| [UpdateItems](../../aspose.email.clients.exchange.webservice/iewsclient/updateitems)(ExchangeStreamedItem[], string) | Actualiza los elementos especificados en un buzón |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote)(MapiNote) | Actualiza la nota especificada. |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_1)(string, MapiNote) | Actualiza la nota especificada. |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_2)(string, MapiNote, IEnumerable&lt;PropertyDescriptor&gt;) | Actualiza la nota especificada. |
| [UpdateSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/updatesubscription)() | Suscripciones de actualizaciones |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_3)(ExchangeTask) | Actualiza la tarea especificada. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask)(MapiTask) | Actualiza la tarea especificada. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_4)(ExchangeTask, UpdateTaskOptions) | Actualiza la tarea especificada. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_1)(string, MapiTask) | Actualiza la tarea especificada. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_2)(string, MapiTask, IEnumerable&lt;PropertyDescriptor&gt;) | Actualiza la tarea especificada. |
| [UpdateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/updateuserconfiguration)(UserConfiguration) | Actualiza la configuración de usuario especificada |

### Ver también

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
