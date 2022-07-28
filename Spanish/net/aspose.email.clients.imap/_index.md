---
title: Aspose.Email.Clients.Imap
second_title: Referencia de la API de Aspose.Email para .NET
description: El Aspose.Correo electrónico.Clientes.Imap El espacio de nombres proporciona clases para acceder a y manipular mensajes mediante el Protocolo de acceso a mensajes de Internet IMAP.
type: docs
weight: 220
url: /es/net/aspose.email.clients.imap/
---
El **Aspose.Correo electrónico.Clientes.Imap** El espacio de nombres proporciona clases para acceder a y manipular mensajes mediante el Protocolo de acceso a mensajes de Internet (IMAP).

## Clases

| Clase | Descripción |
| --- | --- |
| [AppendMessagesResult](./appendmessagesresult) | Contiene el resultado de la operación con mensajes |
| [BackupSettings](./backupsettings) | La clase contiene opciones para la operación de copia de seguridad |
| [BaseSearchConditions](./basesearchconditions) | Proporciona la clase base para las condiciones de búsqueda. |
| [ESearchOptions](./esearchoptions) | Opciones de resultados de ESEARCH Este método solo funciona si el servidor admite la extensión ESEARCH. Lea más https://tools.ietf.org/html/rfc4315 |
| [FetchTimeoutException](./fetchtimeoutexception) | Representa la excepción que se lanza cuando un mensaje no se puede leer dentro del tiempo especificado. |
| [ImapAttachmentInfo](./imapattachmentinfo) | Representa una información adjunta. |
| [ImapAttachmentInfoCollection](./imapattachmentinfocollection) | Representa la colección de[`ImapAttachmentInfo`](../aspose.email.clients.imap/imapattachmentinfo) |
| [ImapClient](./imapclient) | Permite que las aplicaciones accedan y manipulen mensajes mediante el Protocolo de acceso a mensajes de Internet (IMAP). |
| [ImapFolderInfo](./imapfolderinfo) | Representa una carpeta IMAP. |
| [ImapFolderInfoCollection](./imapfolderinfocollection) | Proporciona un contenedor para una colección de objetos ImapFolderInfo. |
| [ImapIdentificationInfo](./imapidentificationinfo) | Representa un contenedor de clase con información de identificación para intercambiar entre el cliente de correo y el servidor. Lea más rfc2971 https://tools.ietf.org/html/rfc2971 |
| [ImapMailboxInfo](./imapmailboxinfo) | Contiene un conjunto de buzones de uso especial |
| [ImapMessageFlags](./imapmessageflags) | Representa las banderas asociadas con el mensaje. |
| [ImapMessageInfo](./imapmessageinfo) | Representa un objeto de mensaje Imap. |
| [ImapMessageInfoCollection](./imapmessageinfocollection) | Proporciona un contenedor para una colección de[`ImapMessageInfo`](../aspose.email.clients.imap/imapmessageinfo) objetos |
| [ImapMonitoringErrorEventArgs](./imapmonitoringerroreventargs) | La clase contiene datos de eventos de error de monitoreo. |
| [ImapMonitoringErrorEventHandler](./imapmonitoringerroreventhandler) | Representa el método que manejará un evento de error de monitoreo de imap |
| [ImapMonitoringEventArgs](./imapmonitoringeventargs) | La clase contiene datos de eventos de monitoreo. |
| [ImapMonitoringEventHandler](./imapmonitoringeventhandler) | Representa el método que manejará un evento de monitoreo de imap |
| [ImapNamespace](./imapnamespace) | Representa el espacio de nombres IMAP Más detalles: https://tools.ietf.org/html/rfc2342 |
| [ImapPageInfo](./imappageinfo) | Contiene información sobre la página recuperada cuando se utilizan métodos de paginación. |
| [ImapQueryBuilder](./imapquerybuilder) | Representa el generador de la expresión de búsqueda que usa el protocolo IMAP. |
| [ImapQuota](./imapquota) | Contiene información sobre la cuota del recurso de buzón. |
| [ImapQuotaRoot](./imapquotaroot) | Contiene información sobre la raíz de cuota para el recurso de buzón. |
| [MessageThreadResult](./messagethreadresult) | Contiene el resultado de los métodos SORT o THREAD Ver más: https://tools.ietf.org/html/rfc5256 |
| [ModificationSequenceField](./modificationsequencefield) | Define un conjunto de valores para el campo seleccionado para buscar. |
| [PageSettings](./pagesettings) | La configuración del método ImapClient.ListMessagesByPage |
| [PageSettingsAsync](./pagesettingsasync) | La configuración para el método asíncrono ImapClient.BeginListMessagesByPage. |
| [RangeSeqSet](./rangeseqset) | Contenedor con rango de valores a buscar. |
| [ReadLinesTimeoutException](./readlinestimeoutexception) | Representa la excepción que se lanza cuando una respuesta del servidor no se puede leer dentro del tiempo especificado. |
| [RestoreSettings](./restoresettings) | La configuración del método ImapClient.Restore |
| [RestoreSettingsAsync](./restoresettingsasync) | La configuración para el método asincrónico ImapClient.Restore. |
| [SequenceSetBaseValue](./sequencesetbasevalue) | Clase base para diferentes contenedores para valores a buscar. |
| [SequenceSetField](./sequencesetfield) | Define un conjunto de valores para el campo seleccionado para buscar. |
| [SimpleSeqSet](./simpleseqset) | Contenedor simple para el valor a buscar. |
| [SortConditions](./sortconditions) | Proporciona las condiciones de búsqueda para la extensión SORT. Compatible con la extensión SORT IMAP descrita en https://tools.ietf.org/html/rfc5256 |
| [ThreadSearchConditions](./threadsearchconditions) | Proporciona las condiciones de búsqueda para recuperar el hilo de correo electrónico. Compatible con la extensión IMAP THREAD descrita en https://tools.ietf.org/html/rfc5256 |
| [XGMThreadSearchConditions](./xgmthreadsearchconditions) | Proporciona las condiciones de búsqueda para recuperar el hilo de correo electrónico. Compatible con la extensión IMAP X-GM-EXT-1 descrita en https://developers.google.com/gmail/imap/imap-extensions#checking_for_the_presence_of_extensions. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IAsyncImapClient](./iasyncimapclient) | Permite que las aplicaciones accedan y manipulen mensajes mediante el Protocolo de acceso a mensajes de Internet (IMAP). |
| [IImapMonitoringState](./iimapmonitoringstate) | Mantiene el estado de supervisión de la carpeta. Esto se puede usar para reanudar el monitoreo de carpetas desde place donde se detuvo cuando ocurrió el error. Usar[`ResumeMonitoring`](../aspose.email.clients.imap/imapclient/resumemonitoring) método. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [ImapCommandResult](./imapcommandresult) | Enumera los resultados del comando imap. |
| [ImapKnownAuthenticationType](./imapknownauthenticationtype) |  |
| [ImapListFields](./imaplistfields) | Campos que se pueden recuperar del servidor |
| [ImapNamespaceType](./imapnamespacetype) | Representa el tipo de espacio de nombres IMAP Más detalles: https://tools.ietf.org/html/rfc2342 |
| [ImapSpecialFolderTypes](./imapspecialfoldertypes) | Representa la enumeración de buzones de correo de uso especial Más detalles ver en RFC6154 http://tools.ietf.org/html/rfc6154 |
| [ImapStatusCode](./imapstatuscode) | Representa las respuestas de estado. |
| [ListFoldersOptions](./listfoldersoptions) | Las opciones de selección de la lista de carpetas Tenga en cuenta que estas opciones son compatibles en caso de que el servidor admita RFC 5258 "Extensiones de comando de LISTA IMAP" Consulte más detalles en https://tools.ietf.org/html/rfc5258 |
| [ListFoldersReturnOptions](./listfoldersreturnoptions) | Opciones de devolución para la operación ListFolders Tenga en cuenta que estas opciones son compatibles en caso de que el servidor admita RFC 5258 "Extensiones de comando IMAP LIST" Consulte más detalles en https://tools.ietf.org/html/rfc5258 |
| [SortingKey](./sortingkey) | Criterios de clasificación para el comando "ORDENAR" Ver más: https://tools.ietf.org/html/rfc5256 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
