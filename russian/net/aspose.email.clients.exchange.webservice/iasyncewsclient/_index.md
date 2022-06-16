---
title: IAsyncEwsClient
second_title: Справочник по Aspose.Email для .NET API
description: Представляет асинхронный интерфейс для клиента Exchange.
type: docs
weight: 3950
url: /ru/net/aspose.email.clients.exchange.webservice/iasyncewsclient/
---
## IAsyncEwsClient interface

Представляет асинхронный интерфейс для клиента Exchange.

```csharp
public interface IAsyncEwsClient : IExchangeClientBase
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iasyncewsclient/mailboxinfo) { get; } | Получает информацию о почтовом ящике. |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iasyncewsclient/useslashasfolderseparator) { get; set; } | Получает или задает значение, определяющее, используется ли косая черта '/' в качестве разделителя папок. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/appendmessagesasync)(EwsAppendMessage) | Загружает почтовые сообщения в указанную папку. |
| [ArchiveItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/archiveitemsasync)(EwsArchiveItems) | Операция ArchiveItem перемещает элемент в архивный почтовый ящик пользователя почтового ящика. |
| [BackupAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync#backupasync)(ExchangeFolderInfoCollection, Stream, BackupOptions, CancellationToken) | Резервирует содержимое указанных папок. |
| [BackupAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync#backupasync_1)(ExchangeFolderInfoCollection, string, BackupOptions, CancellationToken) | Резервирует содержимое указанных папок. |
| [CancelAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/cancelappointmentasync)(string, string, CancellationToken) | Отменяет выход из собрания в календаре организатора |
| [CopyConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/copyconversationitemsasync)(string, string, string, CancellationToken) | Копирует элементы беседы, находящиеся в указанной папке, в указанную целевую папку |
| [CopyItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/copyitemasync)(string, string, CancellationToken) | Копирует элемент в указанную папку |
| [CreateAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createappointmentasync)(Appointment, string, CancellationToken) | Создает встречу. |
| [CreateFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createfolderasync)(string, string, ExchangeFolderPermissionCollection, string, CancellationToken) | Создает новую папку |
| [CreateItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createitemasync)(MapiMessageItemBase, string, CancellationToken) | Создает данный элемент в указанной папке. |
| [CreateItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, string, CancellationToken) | Создает указанные элементы в указанной папке |
| [CreatePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync#createpublicfolderasync_1)(string, ExchangeFolderPermissionCollection, string, CancellationToken) | Создает указанную общую папку в корневой общей папке |
| [CreatePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync#createpublicfolderasync)(string, ExchangeFolderPermissionCollection, ExchangeFolderType, string, CancellationToken) | Создает указанную общую папку в корневой общей папке |
| [CreateTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createtaskasync)(ExchangeTask, string, CancellationToken) | Создает заданную задачу в указанной папке. |
| [DeleteConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteconversationitemsasync)(string, string, CancellationToken) | Удаляет элементы беседы, находящиеся в указанной папке |
| [DeleteFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deletefolderasync)(string, bool, CancellationToken) | Удаляет папку |
| [DeleteFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deletefoldersasync)(IEnumerable&lt;string&gt;, bool, CancellationToken) | Удаляет папки |
| [DeleteItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteitemasync)(string, DeletionOptions, CancellationToken) | Удаляет указанный элемент |
| [DeleteItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteitemsasync)(IEnumerable&lt;string&gt;, DeletionOptions, CancellationToken) | Удаляет указанные элементы |
| [EmptyFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/emptyfolderasync)(string, EmptyFolderOptions, CancellationToken) | Очищает указанную папку |
| [ExportItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/exportitemsasync)(IEnumerable&lt;string&gt;, CancellationToken) | Экспортирует указанные элементы из почтового ящика |
| [FetchAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchappointmentasync)(string, string, CancellationToken) | Получить указанную встречу с сервера. |
| [FetchAttachmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchattachmentasync)(string, CancellationToken) | Извлекает вложение |
| [FetchConversationMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchconversationmessagesasync)(string, CancellationToken) | Выбирает указанные сообщения беседы |
| [FetchItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Получает полный элемент с вложениями. |
| [FetchItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemsasync)(EwsFetchItems) | Выбирает указанные элементы. |
| [FetchMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchmessagesasync)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Выбирает указанные сообщения. |
| [FetchTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchtaskasync)(string, CancellationToken) | Выбирает указанную задачу. |
| [FindConversationsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/findconversationsasync)(string, CancellationToken) | Находит разговоры в указанной папке |
| [FindPeopleAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/findpeopleasync)(EwsFindPeople) | Найти контакты. |
| [FolderExistsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/folderexistsasync)(string, string, CancellationToken) | Проверяет, существует ли указанная папка. |
| [GetContactAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactasync)(string, ExchangeListContactsOptions, CancellationToken) | Получает контактную информацию по указанному идентификатору. |
| [GetContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Список контактов, находящихся в указанной папке на сервере |
| [GetFolderInfoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderinfoasync)(string, CancellationToken) | Получает информацию о папке |
| [GetFolderPermissionsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderpermissionsasync)(string, CancellationToken) | Получает права доступа к папке. |
| [GetMailboxesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxesasync)(CancellationToken) | Список почтовых ящиков, имеющих smtp-адреса. Примечание. Максимальное количество возвращаемых контактов – 100. Это ограничение используемой операции EWS. |
| [GetMailboxInfoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxinfoasync)(string, CancellationToken) | Получает информацию о почтовом ящике |
| [GetServerTimeZoneIdsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getservertimezoneidsasync)(IEnumerable&lt;string&gt;, CancellationToken) | GetServerTimeZoneIds возвращает информацию из идентификатора часового пояса, доступного на сервере Exchange. |
| [GetTimezoneIdAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/gettimezoneidasync)(CancellationToken) | Получает идентификатор часового пояса. |
| [ListAppointmentsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsasync)(string, MailQuery, bool, CancellationToken) | Получает список встреч для указанной папки календаря |
| [ListAppointmentsByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsbypageasync)(string, MailQuery, int, int, CancellationToken) | Извлекает страницу с встречами для указанной папки календаря |
| [ListContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listcontactsasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Список контактов, находящихся в указанной папке на сервере. |
| [ListItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listitemsasync)(string, string, MailQuery, bool, CancellationToken) | Получить список URI элементов в указанной папке |
| [ListMailboxesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmailboxesasync)(string, CancellationToken) | Список почтовых ящиков, имеющих smtp-адреса. Примечание. Максимальное количество возвращаемых контактов – 100. Это ограничение используемой операции EWS. |
| [ListMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync#listmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Список сообщений в указанной папке. |
| [ListMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync#listmessagesasync_1)(string, string, int, MailQuery, bool, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Список сообщений в указанной папке. |
| [ListMessagesByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync#listmessagesbypageasync)(string, PageInfo, CancellationToken) | Список сообщений в указанной папке. |
| [ListMessagesByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync#listmessagesbypageasync_1)(string, int, int, MailQuery, CancellationToken) | Список сообщений в указанной папке. |
| [ListPublicFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listpublicfoldersasync)(CancellationToken) | Получает коллекцию общих папок из корневой общей папки |
| [ListSubFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersasync)(string, string, CancellationToken) | Получает коллекцию дочерних папок от родительской |
| [ListSubFoldersByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersbypageasync)(string, PageInfo, CancellationToken) | Поиск указанной папки в заданной родительской папке с пейджингом Метод поддерживает пейджинг. |
| [ListTasksAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listtasksasync)(string, int, MailQuery, bool, CancellationToken) | Получает списки задач обмена. |
| [LoadContactPhotoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/loadcontactphotoasync)(ContactPhoto, CancellationToken) | Загружает бинарные данные фото контакта |
| [MailDisablePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/maildisablepublicfolderasync)(string, CancellationToken) | Отключить почту для общей папки |
| [MailEnablePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/mailenablepublicfolderasync)(string, CancellationToken) | Включить почту для общей папки |
| [MarkAllItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/markallitemsasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | Отмечает все элементы в указанных папках. |
| [MarkAsJunkAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/markasjunkasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | Метод MarkAsJunk перемещает почтовые сообщения в папку нежелательной почты и блокирует отправителя сообщения. |
| [MoveConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/moveconversationitemsasync)(string, string, string, CancellationToken) | Перемещает элементы беседы, находящиеся в указанной папке, в указанную целевую папку |
| [MoveItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/moveitemasync)(string, string, CancellationToken) | Перемещает элемент в указанную папку |
| [ResolveContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/resolvecontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Разрешает неоднозначные адреса электронной почты и отображаемые имена Примечание. Максимальное количество возвращаемых контактов — 100. Это ограничение используемой операции EWS. . |
| [ResolveMapiContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/resolvemapicontactsasync)(string, CancellationToken) | Разрешает неоднозначные адреса электронной почты и отображаемые имена Примечание. Максимальное количество возвращаемых контактов — 100. Это ограничение используемой операции EWS. . |
| [RestoreAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Восстанавливает указанные папки обмена из заданного личного хранилища. |
| [SendAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/sendasync)(MailMessage, FollowUpOptions, CancellationToken) | Отправляет сообщение. |
| [SetConversationReadStateAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/setconversationreadstateasync)(string, bool, string, CancellationToken) | Установить состояние чтения элементов беседы, находящихся в указанной папке, на указанное значение |
| [SetReadFlagAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/setreadflagasync)(string, bool, CancellationToken) | Отмечает указанное сообщение как прочитанное. |
| [SetTimezoneIdAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/settimezoneidasync)(string, CancellationToken) | Устанавливает идентификатор часового пояса. |
| [SyncFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/syncfolderasync)(SyncState, CancellationToken) | Получает изменения элементов в указанной папке. |
| [UpdateAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateappointmentasync)(Appointment, string, CancellationToken) | Обновляет встречу. |
| [UpdateContactAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updatecontactasync)(Contact, CancellationToken) | Обновляет элемент контакта в магазине Exchange. |
| [UpdateItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemasync)(EwsUpdateItem) | Обновляет элемент. |
| [UpdateItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, CancellationToken) | Обновляет указанные элементы в почтовый ящик. |
| [UpdateTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updatetaskasync)(ExchangeTask, CancellationToken) | Обновляет указанную задачу. |

### Смотрите также

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
