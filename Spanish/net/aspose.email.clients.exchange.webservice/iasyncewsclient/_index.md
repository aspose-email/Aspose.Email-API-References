---
title: IAsyncEwsClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa la interfaz asíncrona para el cliente de Exchange.
type: docs
weight: 3950
url: /es/net/aspose.email.clients.exchange.webservice/iasyncewsclient/
---
## IAsyncEwsClient interface

Representa la interfaz asíncrona para el cliente de Exchange.

```csharp
public interface IAsyncEwsClient : IExchangeClientBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iasyncewsclient/mailboxinfo) { get; } | Obtiene la información del buzón. |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iasyncewsclient/useslashasfolderseparator) { get; set; } | Obtiene o establece el valor que determina si la barra inclinada '/' se usa como separador de carpetas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/appendmessagesasync)(EwsAppendMessage) | Carga mensajes de correo a la carpeta especificada. |
| [ArchiveItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/archiveitemsasync)(EwsArchiveItems) | La operación ArchiveItem mueve un elemento al buzón de archivo del usuario del buzón. |
| [BackupAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync#backupasync)(ExchangeFolderInfoCollection, Stream, BackupOptions, CancellationToken) | Realiza una copia de seguridad del contenido de las carpetas especificadas. |
| [BackupAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync#backupasync_1)(ExchangeFolderInfoCollection, string, BackupOptions, CancellationToken) | Realiza una copia de seguridad del contenido de las carpetas especificadas. |
| [CancelAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/cancelappointmentasync)(string, string, CancellationToken) | Cancela una reunión existente en el calendario de un organizador |
| [CopyConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/copyconversationitemsasync)(string, string, string, CancellationToken) | Copia los elementos de conversación, que se encuentran en la carpeta especificada, en la carpeta de destino especificada |
| [CopyItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/copyitemasync)(string, string, CancellationToken) | Copia el elemento a la carpeta especificada |
| [CreateAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createappointmentasync)(Appointment, string, CancellationToken) | Crea cita. |
| [CreateFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createfolderasync)(string, string, ExchangeFolderPermissionCollection, string, CancellationToken) | Crea la nueva carpeta |
| [CreateItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createitemasync)(MapiMessageItemBase, string, CancellationToken) | Crea el elemento dado en la carpeta especificada. |
| [CreateItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, string, CancellationToken) | Crea los elementos especificados en la carpeta especificada |
| [CreatePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync#createpublicfolderasync_1)(string, ExchangeFolderPermissionCollection, string, CancellationToken) | Crea la carpeta pública especificada en la carpeta pública raíz |
| [CreatePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync#createpublicfolderasync)(string, ExchangeFolderPermissionCollection, ExchangeFolderType, string, CancellationToken) | Crea la carpeta pública especificada en la carpeta pública raíz |
| [CreateTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createtaskasync)(ExchangeTask, string, CancellationToken) | Crea la tarea dada en la carpeta especificada. |
| [DeleteConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteconversationitemsasync)(string, string, CancellationToken) | Elimina los elementos de conversación, que se encuentran en la carpeta especificada |
| [DeleteFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deletefolderasync)(string, bool, CancellationToken) | Elimina la carpeta |
| [DeleteFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deletefoldersasync)(IEnumerable&lt;string&gt;, bool, CancellationToken) | Elimina las carpetas |
| [DeleteItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteitemasync)(string, DeletionOptions, CancellationToken) | Elimina el elemento especificado |
| [DeleteItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteitemsasync)(IEnumerable&lt;string&gt;, DeletionOptions, CancellationToken) | Elimina elementos especificados |
| [EmptyFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/emptyfolderasync)(string, EmptyFolderOptions, CancellationToken) | Vacía la carpeta especificada |
| [ExportItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/exportitemsasync)(IEnumerable&lt;string&gt;, CancellationToken) | Exporta los elementos especificados desde mailbox |
| [FetchAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchappointmentasync)(string, string, CancellationToken) | Obtener la cita especificada del servidor. |
| [FetchAttachmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchattachmentasync)(string, CancellationToken) | Obtiene el archivo adjunto |
| [FetchConversationMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchconversationmessagesasync)(string, CancellationToken) | Obtiene los mensajes de conversación especificados |
| [FetchItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Recupera el elemento completo con archivos adjuntos. |
| [FetchItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemsasync)(EwsFetchItems) | Obtiene los elementos especificados. |
| [FetchMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchmessagesasync)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Obtiene los mensajes especificados. |
| [FetchTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchtaskasync)(string, CancellationToken) | Obtiene la tarea especificada. |
| [FindConversationsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/findconversationsasync)(string, CancellationToken) | Encuentra conversaciones en la carpeta especificada |
| [FindPeopleAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/findpeopleasync)(EwsFindPeople) | Buscar contactos. |
| [FolderExistsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/folderexistsasync)(string, string, CancellationToken) | Comprueba si existe la carpeta especificada. |
| [GetContactAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactasync)(string, ExchangeListContactsOptions, CancellationToken) | Recupera información de contacto según el identificador especificado. |
| [GetContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Muestra los contactos ubicados en la carpeta especificada en server |
| [GetFolderInfoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderinfoasync)(string, CancellationToken) | Obtiene la información de la carpeta |
| [GetFolderPermissionsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderpermissionsasync)(string, CancellationToken) | Obtiene los permisos de la carpeta. |
| [GetMailboxesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxesasync)(CancellationToken) | Enumera los buzones que tienen direcciones smtp. Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción de la operación EWS utilizada. |
| [GetMailboxInfoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxinfoasync)(string, CancellationToken) | Obtiene la información del buzón |
| [GetServerTimeZoneIdsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getservertimezoneidsasync)(IEnumerable&lt;string&gt;, CancellationToken) | GetServerTimeZoneIds devuelve información de la identificación de la zona horaria que está disponible en un servidor de Exchange. |
| [GetTimezoneIdAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/gettimezoneidasync)(CancellationToken) | Obtiene id. de zona horaria. |
| [ListAppointmentsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsasync)(string, MailQuery, bool, CancellationToken) | Recupera la lista de citas para la carpeta de calendario especificada |
| [ListAppointmentsByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsbypageasync)(string, MailQuery, int, int, CancellationToken) | Recupera la página con citas para la carpeta de calendario especificada |
| [ListContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listcontactsasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Muestra los contactos ubicados en la carpeta especificada en el servidor. |
| [ListItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listitemsasync)(string, string, MailQuery, bool, CancellationToken) | Recuperar la lista de elementos URI en la carpeta especificada |
| [ListMailboxesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmailboxesasync)(string, CancellationToken) | Enumera los buzones que tienen direcciones smtp. Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción de la operación EWS utilizada. |
| [ListMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync#listmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync#listmessagesasync_1)(string, string, int, MailQuery, bool, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync#listmessagesbypageasync)(string, PageInfo, CancellationToken) | Lista los mensajes en la carpeta especificada. |
| [ListMessagesByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync#listmessagesbypageasync_1)(string, int, int, MailQuery, CancellationToken) | Lista los mensajes en la carpeta especificada. |
| [ListPublicFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listpublicfoldersasync)(CancellationToken) | Obtiene la colección de carpetas públicas de la carpeta pública raíz |
| [ListSubFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersasync)(string, string, CancellationToken) | Obtiene la colección de carpetas secundarias de parent |
| [ListSubFoldersByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersbypageasync)(string, PageInfo, CancellationToken) | Busca la carpeta especificada en la carpeta principal dada con paging El método admite paginación. |
| [ListTasksAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listtasksasync)(string, int, MailQuery, bool, CancellationToken) | Recupera listas de tareas de intercambio. |
| [LoadContactPhotoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/loadcontactphotoasync)(ContactPhoto, CancellationToken) | Carga los datos binarios de la foto de contacto |
| [MailDisablePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/maildisablepublicfolderasync)(string, CancellationToken) | Mail-deshabilitar una carpeta pública |
| [MailEnablePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/mailenablepublicfolderasync)(string, CancellationToken) | Habilitar para correo una carpeta pública |
| [MarkAllItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/markallitemsasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | Marca todos los elementos en las carpetas especificadas. |
| [MarkAsJunkAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/markasjunkasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje. |
| [MoveConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/moveconversationitemsasync)(string, string, string, CancellationToken) | Mueve los elementos de conversación, que se encuentran en la carpeta especificada, a la carpeta de destino especificada |
| [MoveItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/moveitemasync)(string, string, CancellationToken) | Mueve el elemento a la carpeta especificada |
| [ResolveContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/resolvecontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Resuelve direcciones de correo electrónico ambiguas y nombres para mostrar Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción de la operación EWS utilizada. |
| [ResolveMapiContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/resolvemapicontactsasync)(string, CancellationToken) | Resuelve direcciones de correo electrónico ambiguas y nombres para mostrar Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción de la operación EWS utilizada. |
| [RestoreAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Restaura las carpetas de intercambio especificadas del almacenamiento personal dado. |
| [SendAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/sendasync)(MailMessage, FollowUpOptions, CancellationToken) | Envía el mensaje. |
| [SetConversationReadStateAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/setconversationreadstateasync)(string, bool, string, CancellationToken) | Establece el estado de lectura de los elementos de conversación, que se encuentran en la carpeta especificada, en el valor especificado |
| [SetReadFlagAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/setreadflagasync)(string, bool, CancellationToken) | Marca el mensaje especificado como leído. |
| [SetTimezoneIdAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/settimezoneidasync)(string, CancellationToken) | Establece la identificación de la zona horaria. |
| [SyncFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/syncfolderasync)(SyncState, CancellationToken) | Recupera los cambios de los elementos en una carpeta especificada. |
| [UpdateAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateappointmentasync)(Appointment, string, CancellationToken) | Actualiza cita. |
| [UpdateContactAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updatecontactasync)(Contact, CancellationToken) | Actualiza un elemento de contacto en la tienda de Exchange. |
| [UpdateItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemasync)(EwsUpdateItem) | Actualiza el elemento. |
| [UpdateItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, CancellationToken) | Actualiza los elementos especificados en un buzón. |
| [UpdateTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updatetaskasync)(ExchangeTask, CancellationToken) | Actualiza la tarea especificada. |

### Ver también

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
