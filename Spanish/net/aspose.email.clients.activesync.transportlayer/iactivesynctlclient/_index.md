---
title: IActiveSyncTLClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Interfaz de cliente de ActiveSync
type: docs
weight: 1310
url: /es/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/
---
## IActiveSyncTLClient interface

Interfaz de cliente de ActiveSync

```csharp
public interface IActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AirSyncKeys](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/airsynckeys) { get; } | Contiene un valor que utiliza el servidor para marcar el estado de sincronización de cada colección sincronizada. Donde la clave del diccionario es el ID del servidor y el valor del diccionario es SyncKey. Para los comandos GetItemEstimate y Sync. |
| [FoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderssynckey) { get; } | Usado por el servidor para rastrear el estado actual del cliente. Solo para operaciones con carpetas |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/heartbeatinterval) { get; set; } | El elemento HeartbeatInterval es un elemento secundario del elemento Ping en las solicitudes y respuestas del comando Ping. En las solicitudes de comando Ping, especifica el tiempo, en segundos, que el servidor DEBE esperar antes de enviar una respuesta si no se agregan nuevos elementos al conjunto de carpetas especificado, como se especifica en la sección 3.1.5.6. El servidor también devuelve el elemento HeartbeatInterval con un código de estado de 5 y especifica el intervalo mínimo o máximo que se permite cuando el cliente ha solicitado un intervalo de latido que está fuera del rango aceptable. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FolderCreate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldercreate)(string, string, UserCreatedFolderTypes) | FolderCreate crea una nueva carpeta como carpeta secundaria de la carpeta principal especificada. |
| [FolderDelete](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderdelete)(string) | Elimina la colección con el identificador coincidente. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync)() | FolderSync sincroniza la jerarquía de la colección, pero no sincroniza los elementos de las colecciones. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync_1)(bool) | FolderSync sincroniza la jerarquía de la colección, pero no sincroniza los elementos de las colecciones. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate)(FolderInfo) | El comando FolderUpdate mueve una carpeta de una ubicación a otra en el servidor. El comando también se usa para cambiar el nombre de una carpeta. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate_1)(string, string, string) | El comando FolderUpdate mueve una carpeta de una ubicación a otra en el servidor. El comando también se usa para cambiar el nombre de una carpeta. |
| [GetAttachment](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getattachment)(string) | GetAttachment recupera un archivo adjunto de correo electrónico del servidor. GetAttachment no es compatible cuando la versión del protocolo es 14.0 o 14.1. Use el elemento Fetch del comando ItemOperations en su lugar. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_2)(IEnumerable&lt;ItemEstimateRequest&gt;) | El comando GetItemEstimate obtiene una estimación del número de elementos de una colección o carpeta en el servidor que deben sincronizarse. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate)(ItemEstimateRequest) | El comando GetItemEstimate obtiene una estimación del número de elementos de una colección o carpeta en el servidor que deben sincronizarse. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_1)(params ItemEstimateRequest[]) | El comando GetItemEstimate obtiene una estimación del número de elementos de una colección o carpeta en el servidor que deben sincronizarse. |
| [ItemOperations](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/itemoperations)(ItemOperationsRequest) | ItemOperations proporciona el manejo en línea por lotes de las operaciones Fetch, EmptyFolderContents y Move. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_3)(IEnumerable&lt;MeetingResponseRequest&gt;) | Acepta, acepta tentativamente o rechaza una solicitud de reunión en la carpeta Bandeja de entrada o la carpeta Calendario del usuario. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_2)(params MeetingResponseRequest[]) | Acepta, acepta tentativamente o rechaza una solicitud de reunión en la carpeta Bandeja de entrada o la carpeta Calendario del usuario. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse)(UserResponse, string, string) | Acepta, acepta tentativamente o rechaza una solicitud de reunión en la carpeta Bandeja de entrada o la carpeta Calendario del usuario. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_1)(UserResponse, string, string, string, string) | Acepta, acepta tentativamente o rechaza una solicitud de reunión en la carpeta Bandeja de entrada o la carpeta Calendario del usuario. |
| [MoveItem](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem)(string, string, string) | El comando MoveItems mueve un elemento o elementos de una carpeta del servidor a otra. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems_1)(IEnumerable&lt;MoveItemData&gt;) | El comando MoveItems mueve un elemento o elementos de una carpeta del servidor a otra. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems)(params MoveItemData[]) | El comando MoveItems mueve un elemento o elementos de una carpeta del servidor a otra. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_4)(IEnumerable&lt;PingParameter&gt;) | El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping)(params PingParameter[]) | El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_2)(int, IEnumerable&lt;PingParameter&gt;) | El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_1)(int, params PingParameter[]) | El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_5)(string, FolderClass) | El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_3)(int, string, FolderClass) | El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar. |
| [Provision](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/provision)(ProvisionRequest) | El comando Aprovisionar permite que los dispositivos cliente soliciten al servidor la configuración de la política de seguridad que establece el administrador, como el requisito mínimo de longitud de la contraseña del número de identificación personal (PIN). |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey)() | Restablecer SyncKeys para las operaciones GetItemEstimate y Sync para todas las colecciones. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey_1)(string) | Restablecer SyncKey para las operaciones GetItemEstimate y Sync para la colección definida. |
| [ResetFoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetfolderssynckey)() | Restablecer SyncKey para operaciones con carpetas |
| [ResolveRecipients](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resolverecipients)(ResolveRecipientsRequest) | ResolveRecipients se utiliza para resolver una lista de destinatarios proporcionados, recuperar su información de disponibilidad y, opcionalmente, recuperar sus certificados S/MIME para que los clientes puedan enviar mensajes de correo electrónico S/MIME cifrados. Recuperación de información de disponibilidad no se admite el uso del elemento Disponibilidad en el comando ResolveRecipients cuando la versión del protocolo es 12.1. |
| [Search](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/search)(SearchRequest) | La búsqueda se utiliza para buscar entradas en una libreta de direcciones, un buzón o una biblioteca de documentos (UNC o Windows SharePoint Services). |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail)(string) | Los clientes utilizan SendMail para enviar mensajes de correo electrónico con formato MIME al servidor. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_1)(string, bool) | Los clientes utilizan SendMail para enviar mensajes de correo electrónico con formato MIME al servidor. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_2)(string, bool, string) | Los clientes utilizan SendMail para enviar mensajes de correo electrónico con formato MIME al servidor. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_3)(string, bool, string, string) | Los clientes utilizan SendMail para enviar mensajes de correo electrónico con formato MIME al servidor. |
| [Settings](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/settings)(SettingsRequest) | La configuración admite operaciones de obtención y configuración en propiedades globales y configuraciones Fuera de la oficina (OOF) para el usuario. La configuración también envía información del dispositivo al servidor, implementa la recuperación de la contraseña del dispositivo/número de identificación personal (PIN) y recupera una lista de las direcciones de correo electrónico del usuario. |
| [SmartForward](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartforward)(SmartRequest) | Los clientes utilizan el comando SmartForward para reenviar mensajes sin recuperar el mensaje original completo del servidor. |
| [SmartReply](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartreply)(SmartRequest) | Los clientes utilizan el comando SmartReply para responder a los mensajes sin recuperar el mensaje original completo del servidor. |
| [Sync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sync)(SyncRequest) | El Sync sincroniza los cambios en una colección entre el cliente y el servidor. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert)(IEnumerable&lt;X509Certificate&gt;) | ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_4)(X509Certificate) | El cliente utiliza el comando ValidateCert para validar un certificado que se ha recibido a través de un correo S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_1)(IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_2)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_5)(X509Certificate, bool) | ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_6)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_3)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_7)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME. |

### Ver también

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
