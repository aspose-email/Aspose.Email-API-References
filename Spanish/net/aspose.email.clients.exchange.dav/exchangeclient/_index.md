---
title: ExchangeClient
second_title: Referencia de la API de Aspose.Email para .NET
description: La clase ExchangeClient permite que las aplicaciones administren el buzón de correo electrónico en Microsoft Exchange Server mediante el protocolo de almacenamiento WebDav Exchange.
type: docs
weight: 3150
url: /es/net/aspose.email.clients.exchange.dav/exchangeclient/
---
## ExchangeClient class

La clase ExchangeClient permite que las aplicaciones administren el buzón de correo electrónico en Microsoft Exchange Server mediante el protocolo de almacenamiento WebDav Exchange.

```csharp
public sealed class ExchangeClient : ExchangeClientBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ExchangeClient](exchangeclient#constructor)(string, ICredentials) | Inicializar una nueva instancia de la clase[`ExchangeClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_1)(string, string, string) | Inicializar una nueva instancia de la clase[`ExchangeClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_2)(string, string, string, string) | Inicializar una nueva instancia de la clase[`ExchangeClient`](../exchangeclient) |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate) { get; set; } | Obtiene o establece el certificado del cliente. |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer) { get; set; } | Obtiene o establece el contenedor de cookies. |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Obtiene o establece las credenciales |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding) { get; set; } | Obtiene o establece la codificación. |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive) { get; set; } | Indica si mantener vivo. |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Obtiene o establece el nombre del archivo de registro |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo) { get; } | Obtiene la información del buzón. |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Obtiene o establece el buzón uri |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate) { get; set; } | Indica si se debe realizar una autenticación previa. |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Obtiene o establece el proxy. |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked) { get; set; } | Obtiene o establece un valor que indica si [enviar fragmentos]. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Obtiene o establece el número de milisegundos de espera antes de que se agote el tiempo de espera de la operación. El valor predeterminado es 100 000 milisegundos (100 segundos). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Obtiene o establece el valor que indica si se debe usar la fecha en el nombre del archivo de registro. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage)(string, MailMessage) | Sube el mensaje de correo a la carpeta especificada |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage_1)(string, MailMessage, bool) | Sube el mensaje de correo a la carpeta especificada |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Realiza copias de seguridad del contenido de las carpetas especificadas |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Realiza copias de seguridad del contenido de las carpetas especificadas |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact)(Contact) | Crea un elemento de contacto en la tienda de Exchange. |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder)(string, string) | Crea la nueva carpeta con el nombre especificado en la carpeta principal especificada. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_1)(Contact) | Elimina el contacto. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact)(MapiContact) | Elimina el contacto. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_2)(string) | Elimina el contacto. |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder)(string) | Elimina la carpeta |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage)(string) | Elimina el mensaje de correo. |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage_1)(string, bool) | Elimina el mensaje de correo. |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment)(string) | Obtiene el archivo adjunto |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage)(string) | Obtiene el mensaje mapi con el uri especificado. |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage)(string) | Obtiene el mensaje de correo con el uri especificado. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists)(string, string) | Comprueba si existe la carpeta especificada. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Comprueba si existe la carpeta especificada. |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts)(string) | Muestra los contactos ubicados en la carpeta especificada en server |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo)(string) | Obtiene la información de la carpeta. |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes)() | Enumera los buzones en la lista global de direcciones. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo)() | Obtener la información del buzón |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo_1)(string) | Obtiene la información del buzón |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize)() | Obtener el tamaño del maibox |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize_1)(string) | Obtener el tamaño del maibox |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo)() | Devuelve información de la versión del servidor de intercambio |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts)(string) | Muestra los contactos ubicados en la carpeta especificada en server |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes)() | Enumera los buzones en la lista global de direcciones. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages)(string) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_3)(string, bool) | Lista los mensajes en la carpeta especificada |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_1)(string, ExchangeListMessagesOptions) | Muestra el mensaje de correo en la carpeta especificada. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_4)(string, int) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_6)(string, string) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_5)(string, int, ExchangeListMessagesOptions) | Lista los mensajes en la carpeta especificada |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_2)(string, MailQuery, bool) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_7)(string, string, bool) | Lista los mensajes. |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid)(string, string) | Lista los mensajes por id. |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders)() | Obtiene la colección de carpetas públicas de la carpeta pública raíz |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | Obtiene la colección de carpetas públicas secundarias de parent |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders_1)(string) | Obtiene la colección de carpetas secundarias de parent |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems_1)(string, params string[]) | Mueve elementos. |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems)(string, bool, params string[]) | Mueve elementos. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage)(ExchangeMessageInfo, string) | Mueve el mensaje. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_3)(string, string) | Mueve el mensaje. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_1)(ExchangeMessageInfo, string, bool) | Mueve el mensaje. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_2)(string, bool, string) | Mueve el mensaje. |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts)(string) | Resuelve nombres ambiguos para mostrar en los buzones. Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción del comando de intercambio usado. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_1)(PersonalStorage, RestoreOptions) | Restaura carpetas de intercambio del almacenamiento personal dado. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_3)(Stream, RestoreOptions) | Restaura carpetas de intercambio del almacenamiento personal dado. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_5)(string, RestoreOptions) | Restaura carpetas de intercambio desde el archivo de almacenamiento personal especificado. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | Restaura las carpetas de intercambio especificadas del almacenamiento personal dado. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_2)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | Restaura las carpetas de intercambio especificadas del almacenamiento personal dado. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_4)(string, ExchangeFolderInfoCollection, RestoreOptions) | Restaura las carpetas de intercambio especificadas del archivo de almacenamiento personal especificado. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage)(string, Stream) | Guarda el mensaje. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage_1)(string, string) | Guarda el mensaje de correo especificado por el uri en el sistema de archivos local. El archivo de mensajes de correo tiene un formato compatible con RFC 822 (EML).  si desea analizar los archivos de mensajes de correo, utilice[`MailMessage`](../../aspose.email/mailmessage). |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send)(MailMessage) | Envía el mensaje de correo. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag)(string) | Marca el mensaje especificado como leído. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag_1)(string, bool) | Marca el mensaje especificado como leído. |

### Ver también

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
