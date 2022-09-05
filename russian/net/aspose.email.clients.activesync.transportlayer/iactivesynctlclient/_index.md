---
title: IActiveSyncTLClient
second_title: Справочник по Aspose.Email для .NET API
description: Клиентский интерфейс ActiveSync
type: docs
weight: 1310
url: /ru/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/
---
## IActiveSyncTLClient interface

Клиентский интерфейс ActiveSync

```csharp
public interface IActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AirSyncKeys](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/airsynckeys) { get; } | Содержит значения, используемые сервером для обозначения состояния синхронизации каждой синхронизированной коллекции. Где ключ словаря — это идентификатор сервера, а значение словаря — SyncKey. Для команд GetItemEstimate и Sync. |
| [FoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderssynckey) { get; } | Используется сервером для отслеживания текущего состояния клиента. Только для операций с папками |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/heartbeatinterval) { get; set; } | Элемент HeartbeatInterval является дочерним элементом элемента Ping в запросах и ответах команды Ping. В командных запросах Ping указывает период времени в секундах, в течение которого сервер ДОЛЖЕН ждать перед отправкой ответа, если в указанный набор папок не добавляются новые элементы, как указано в разделе 3.1.5.6. Элемент HeartbeatInterval также возвращается сервером с кодом состояния 5 и указывает либо минимальный, либо максимальный интервал , который разрешен, когда клиент запросил интервал пульса, выходящий за пределы допустимого диапазона. |

## Методы

| Имя | Описание |
| --- | --- |
| [FolderCreate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldercreate)(string, string, UserCreatedFolderTypes) | FolderCreate создает новую папку как дочернюю папку указанной родительской папки. |
| [FolderDelete](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderdelete)(string) | Удаляет коллекцию с совпадающим идентификатором. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync)() | FolderSync синхронизирует иерархию коллекций, но не синхронизирует элементы в самих коллекциях. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync_1)(bool) | FolderSync синхронизирует иерархию коллекций, но не синхронизирует элементы в самих коллекциях. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate)(FolderInfo) | Команда FolderUpdate перемещает папку из одного места в другое на сервере. Команда также используется для переименования папки. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate_1)(string, string, string) | Команда FolderUpdate перемещает папку из одного места в другое на сервере. Команда также используется для переименования папки. |
| [GetAttachment](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getattachment)(string) | GetAttachment извлекает вложение электронной почты с сервера. GetAttachment не поддерживается, если используется версия протокола 14.0 или 14.1. Вместо этого используйте элемент Fetch команды ItemOperations. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_2)(IEnumerable&lt;ItemEstimateRequest&gt;) | Команда GetItemEstimate получает оценку количества элементов в коллекции или папке на сервере, которые необходимо синхронизировать. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate)(ItemEstimateRequest) | Команда GetItemEstimate получает оценку количества элементов в коллекции или папке на сервере, которые необходимо синхронизировать. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_1)(params ItemEstimateRequest[]) | Команда GetItemEstimate получает оценку количества элементов в коллекции или папке на сервере, которые необходимо синхронизировать. |
| [ItemOperations](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/itemoperations)(ItemOperationsRequest) | ItemOperations обеспечивает пакетную онлайн-обработку операций Fetch, EmptyFolderContents и Move. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_3)(IEnumerable&lt;MeetingResponseRequest&gt;) | Принимает, предварительно принимает или отклоняет приглашение на собрание в папке "Входящие" или в папке "Календарь" пользователя. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_2)(params MeetingResponseRequest[]) | Принимает, предварительно принимает или отклоняет приглашение на собрание в папке "Входящие" или в папке "Календарь" пользователя. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse)(UserResponse, string, string) | Принимает, предварительно принимает или отклоняет приглашение на собрание в папке "Входящие" или в папке "Календарь" пользователя. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_1)(UserResponse, string, string, string, string) | Принимает, предварительно принимает или отклоняет приглашение на собрание в папке "Входящие" или в папке "Календарь" пользователя. |
| [MoveItem](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem)(string, string, string) | Команда MoveItems перемещает элемент или элементы из одной папки на сервере в другую. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems_1)(IEnumerable&lt;MoveItemData&gt;) | Команда MoveItems перемещает элемент или элементы из одной папки на сервере в другую. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems)(params MoveItemData[]) | Команда MoveItems перемещает элемент или элементы из одной папки на сервере в другую. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_4)(IEnumerable&lt;PingParameter&gt;) | Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping)(params PingParameter[]) | Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_2)(int, IEnumerable&lt;PingParameter&gt;) | Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_1)(int, params PingParameter[]) | Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_5)(string, FolderClass) | Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_3)(int, string, FolderClass) | Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента. |
| [Provision](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/provision)(ProvisionRequest) | Команда Provision позволяет клиентским устройствам запрашивать у сервера параметры политики безопасности, установленные администратором, такие как требования к минимальной длине пароля персонального идентификационного номера (PIN). |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey)() | Сбросить SyncKeys для операций GetItemEstimate и Sync для всех коллекций. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey_1)(string) | Сброс SyncKey для операций GetItemEstimate и Sync для определенной коллекции. |
| [ResetFoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetfolderssynckey)() | Сбросить SyncKey для операций с папками |
| [ResolveRecipients](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resolverecipients)(ResolveRecipientsRequest) | ResolveRecipients используется для разрешения списка предоставленных получателей, для получения их информации о занятости и, при необходимости, для получения их сертификатов S/MIME, чтобы клиенты могли отправлять зашифрованные сообщения электронной почты S/MIME. Получение информации о занятости использование элемента Availability в команде ResolveRecipients не поддерживается, если используется версия протокола 12.1. |
| [Search](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/search)(SearchRequest) | Поиск используется для поиска записей в адресной книге, почтовом ящике или библиотеке документов (UNC или Windows SharePoint Services). |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail)(string) | SendMail используется клиентами для отправки сообщений электронной почты в формате MIME на сервер. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_1)(string, bool) | SendMail используется клиентами для отправки сообщений электронной почты в формате MIME на сервер. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_2)(string, bool, string) | SendMail используется клиентами для отправки сообщений электронной почты в формате MIME на сервер. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_3)(string, bool, string, string) | SendMail используется клиентами для отправки сообщений электронной почты в формате MIME на сервер. |
| [Settings](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/settings)(SettingsRequest) | Параметры поддерживают операции получения и установки для глобальных свойств и параметров «Нет на месте» (OOF) для пользователя. Настройки также отправляют информацию об устройстве на сервер, реализуют восстановление пароля/личного идентификационного номера (PIN) устройства и извлекают список адресов электронной почты пользователя. |
| [SmartForward](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartforward)(SmartRequest) | Команда SmartForward используется клиентами для пересылки сообщений без получения полного исходного сообщения с сервера. |
| [SmartReply](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartreply)(SmartRequest) | Команда SmartReply используется клиентами для ответа на сообщения без получения полного исходного сообщения с сервера. |
| [Sync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sync)(SyncRequest) | Синхронизация синхронизирует изменения в коллекции между клиентом и сервером. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert)(IEnumerable&lt;X509Certificate&gt;) | ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_4)(X509Certificate) | Команда ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_1)(IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_2)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_5)(X509Certificate, bool) | ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_6)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_3)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_7)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert используется клиентом для проверки сертификата, полученного по почте S/MIME. |

### Смотрите также

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
