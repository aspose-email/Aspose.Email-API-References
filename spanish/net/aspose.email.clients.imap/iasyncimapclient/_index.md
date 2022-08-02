---
title: IAsyncImapClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Permite que las aplicaciones accedan y manipulen mensajes mediante el Protocolo de acceso a mensajes de Internet IMAP.
type: docs
weight: 16240
url: /es/net/aspose.email.clients.imap/iasyncimapclient/
---
## IAsyncImapClient interface

Permite que las aplicaciones accedan y manipulen mensajes mediante el Protocolo de acceso a mensajes de Internet (IMAP).

```csharp
public interface IAsyncImapClient
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/addmessageflagsasync)(ImapChangeMessageFlags) | Agrega las banderas al mensaje |
| [AppendMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessageasync)(MailMessage, string, IConnection, CancellationToken) | Sube el mensaje de correo a la carpeta especificada |
| [AppendMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, string, IConnection, CancellationToken) | Sube los mensajes de correo a la carpeta actual |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) | Realiza copias de seguridad del contenido de las carpetas especificadas |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync_1)(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) | Realiza copias de seguridad del contenido de las carpetas especificadas |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/changemessageflagsasync)(ImapChangeMessageFlags) | Cambia las banderas del mensaje |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Notifica al servidor qué extensiones son compatibles con el cliente. Tenga en cuenta que esta operación solo funciona en caso de que el servidor admita RFC5161 Ver más https://tools.ietf.org/html/rfc5161 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/iasyncimapclient/commitdeletesasync)(ImapUniqueIdParameterSet) | Confirmar las eliminaciones |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync)(int, string, IConnection, CancellationToken) | Copia el mensaje |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync_1)(string, string, IConnection, CancellationToken) | Copia el mensaje. |
| [CopyMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessagesasync)(ImapCopyMessages) | Copia los mensajes. |
| [CreateFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/createfolderasync)(string, IConnection, CancellationToken) | Crea una carpeta con el nombre especificado. |
| [DeleteFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/deletefolderasync)(string, IConnection, CancellationToken) | Elimina una carpeta especificada. Este método representa el comando ELIMINAR IMAP. |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/deletemessagesasync)(ImapDeleteMessages) | Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315 |
| [ExistFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/existfolderasync)(string, IConnection, CancellationToken) | Comprobar si esta carpeta existe |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync)(int, string, IConnection, CancellationToken) | Obtiene el archivo adjunto especificado. |
| [FetchMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchmessagesasync)(ImapFetchMessages) | Obtiene los mensajes de forma asíncrona |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/iasyncimapclient/getfolderinfoasync)(string, IConnection, CancellationToken) | Devuelve información sobre la carpeta especificada sin seleccionarla |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync)(BaseSearchConditions, IConnection, CancellationToken) | Obtener hilos de mensajes. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/iasyncimapclient/getnamespacesasync)(IConnection, CancellationToken) | Obtiene espacios de nombres que están disponibles en un servidor. |
| [GetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotaasync)(string, IConnection, CancellationToken) | Obtiene información de cuota |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotarootasync)(string, IConnection, CancellationToken) | Obtiene información de raíz de cuota para mailbox |
| [IntroduceClientAsync](../../aspose.email.clients.imap/iasyncimapclient/introduceclientasync)(ImapIdentificationInfo, IConnection, CancellationToken) | Introduce información del cliente a un servidor. |
| [ListFoldersAsync](../../aspose.email.clients.imap/iasyncimapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, IConnection, CancellationToken) | Obtiene la lista de subcarpetas en la carpeta especificada |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync)(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Obtiene información sobre un mensaje. |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync_1)(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Obtiene información sobre un mensaje. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync)(MailQuery, string, int, IConnection, CancellationToken) | Obtiene la lista de mensajes en la carpeta actual. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync_1)(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Obtiene la lista de mensajes en la carpeta especificada |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync_1)(int, int, PageSettings, CancellationToken) | Obtiene la lista de mensajes |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | Obtiene la lista de mensajes |
| [MoveFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/movefolderasync)(string, string, IConnection, CancellationToken) | Mueve la carpeta especificada y sus subcarpetas a una nueva ubicación. |
| [MoveMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/movemessagesasync)(ImapMoveMessages) | Mueve los mensajes. |
| [NoopAsync](../../aspose.email.clients.imap/iasyncimapclient/noopasync)(IConnection, CancellationToken) | Comando 'Sin operación' |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/removemessageflagsasync)(ImapChangeMessageFlags) | Elimina las banderas del mensaje |
| [RenameFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/renamefolderasync)(string, string, IConnection, CancellationToken) | Cambia el nombre de una carpeta especificada a un nuevo nombre |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/iasyncimapclient/requestcheckpointasync)(IConnection, CancellationToken) | Solicita un punto de control del buzón actualmente seleccionado. |
| [RestoreAsync](../../aspose.email.clients.imap/iasyncimapclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Comienza a restaurar carpetas imap desde el almacenamiento personal dado. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | Reanuda la supervisión de los cambios de mensajes para la carpeta especificada. A diferencia del método StartMonitoring, encontrará todos los cambios de buzón faltantes y llamará para devolver la llamada. |
| [SelectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/selectfolderasync)(string, bool?, IConnection, CancellationToken) | Selecciona la carpeta especificada |
| [SetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/setquotaasync)(string, string, int, IConnection, CancellationToken) | Establece información de cuota |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/sortmessagethreadsasync)(SortConditions, IConnection, CancellationToken) | Ordenar hilos de mensajes. |
| [StartMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Inicia la supervisión de los cambios de mensajes para la carpeta especificada. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/stopmonitoringasync)(string, CancellationToken) | Detiene la supervisión de los cambios de mensajes para la carpeta especificada. Detiene la supervisión de todas las carpetas si folderName es nulo. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/subscribefolderasync)(string, IConnection, CancellationToken) | Envió el comando SUBSCRIBE que agrega el nombre de buzón especificado al conjunto de buzones "activos" del servidor. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync)(int, long, IConnection, CancellationToken) | Marca un mensaje con el número de secuencia especificado como no eliminado |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync_1)(string, long, IConnection, CancellationToken) | Marca un mensaje con el número de secuencia especificado como no eliminado. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unselectfolderasync)(bool, IConnection, CancellationToken) | Anula la selección de la carpeta que está actualmente seleccionada. si la propiedad doNotExpunge es verdadera, se eliminan todos los mensajes marcados como eliminados; de lo contrario, se cancela la eliminación. Tenga en cuenta que esta operación solo funciona en caso de que el servidor admita RFC3691 Ver más https://tools. ietf.org/html/rfc3691 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync)(string, IConnection, CancellationToken) | Envió el comando UNSUBSCRIBE que elimina el nombre de buzón especificado del conjunto de buzones "activos" del servidor |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/iasyncimapclient/validatecredentialsasync)(IConnection, CancellationToken) | Ejecuta validación de credenciales |

### Ver también

* espacio de nombres [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
