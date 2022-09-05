---
title: ExchangeClient
second_title: Справочник по Aspose.Email для .NET API
description: Класс ExchangeClient позволяет приложениям управлять ящиком электронной почты в Microsoft Exchange Server с помощью протокола WebDav Exchange Store.
type: docs
weight: 3150
url: /ru/net/aspose.email.clients.exchange.dav/exchangeclient/
---
## ExchangeClient class

Класс ExchangeClient позволяет приложениям управлять ящиком электронной почты в Microsoft Exchange Server с помощью протокола WebDav Exchange Store.

```csharp
public sealed class ExchangeClient : ExchangeClientBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ExchangeClient](exchangeclient#constructor)(string, ICredentials) | Инициализировать новый экземпляр класса[`ExchageClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_1)(string, string, string) | Инициализировать новый экземпляр класса[`ExchageClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_2)(string, string, string, string) | Инициализировать новый экземпляр класса[`ExchageClient`](../exchangeclient) |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate) { get; set; } | Получает или задает сертификат клиента. |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer) { get; set; } | Получает или задает контейнер cookie. |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Получает или устанавливает учетные данные |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding) { get; set; } | Получает или задает кодировку. |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive) { get; set; } | Указывает, следует ли сохранять активность. |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Получает или задает имя файла журнала |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo) { get; } | Получает информацию о почтовом ящике. |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Получает или задает почтовый ящик uri |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate) { get; set; } | Указывает, следует ли выполнять предварительную аутентификацию. |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Получает или задает прокси. |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked) { get; set; } | Получает или задает значение, указывающее, следует ли [отправить фрагментами]. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Получает или задает количество миллисекунд ожидания до истечения времени ожидания операции. Значение по умолчанию — 100 000 миллисекунд (100 секунд). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Получает или задает значение, указывающее, следует ли использовать дату в имени файла журнала. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage)(string, MailMessage) | Загружает почтовое сообщение в указанную папку |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage_1)(string, MailMessage, bool) | Загружает почтовое сообщение в указанную папку |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Резервирует содержимое указанных папок |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Резервирует содержимое указанных папок |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact)(Contact) | Создает элемент контакта в магазине Exchange. |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder)(string, string) | Создает новую папку с указанным именем в указанной родительской папке. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_1)(Contact) | Удаляет контакт. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact)(MapiContact) | Удаляет контакт. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_2)(string) | Удаляет контакт. |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder)(string) | Удаляет папку |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage)(string) | Удаляет почтовое сообщение. |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage_1)(string, bool) | Удаляет почтовое сообщение. |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Выполняет определяемые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment)(string) | Извлекает вложение |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage)(string) | Получает сообщение mapi с указанным uri. |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage)(string) | Извлекает почтовое сообщение с указанным uri. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists)(string, string) | Проверяет, существует ли указанная папка. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Проверяет, существует ли указанная папка. |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts)(string) | Список контактов, расположенных в указанной папке на server |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo)(string) | Получает информацию о папке. |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes)() | Список почтовых ящиков в глобальном списке адресов. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo)() | Получить информацию о почтовом ящике |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo_1)(string) | Получает информацию о почтовом ящике |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize)() | Получить размер почтового ящика |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize_1)(string) | Получить размер почтового ящика |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo)() | Возвращает информацию о версии сервера обмена |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts)(string) | Список контактов, расположенных в указанной папке на server |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes)() | Список почтовых ящиков в глобальном списке адресов. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages)(string) | Список сообщений. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_3)(string, bool) | Список сообщений в указанной папке |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_1)(string, ExchangeListMessagesOptions) | Список почтовых сообщений в указанной папке. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_4)(string, int) | Список сообщений. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_6)(string, string) | Список сообщений. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_5)(string, int, ExchangeListMessagesOptions) | Список сообщений в указанной папке |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_2)(string, MailQuery, bool) | Список сообщений. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_7)(string, string, bool) | Список сообщений. |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid)(string, string) | Список сообщений по идентификатору. |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders)() | Получает коллекцию общих папок из корневой общей папки |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | Получает коллекцию дочерних общих папок от parent |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders_1)(string) | Получает коллекцию дочерних папок от parent |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems_1)(string, params string[]) | Перемещает предметы. |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems)(string, bool, params string[]) | Перемещает предметы. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage)(ExchangeMessageInfo, string) | Перемещает сообщение. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_3)(string, string) | Перемещает сообщение. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_1)(ExchangeMessageInfo, string, bool) | Перемещает сообщение. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_2)(string, bool, string) | Перемещает сообщение. |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts)(string) | Разрешает неоднозначные отображаемые имена почтовых ящиков. Примечание: максимальное количество возвращаемых контактов равно 100. Это ограничение используемой команды обмена. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_1)(PersonalStorage, RestoreOptions) | Восстанавливает папки обмена из указанного личного хранилища. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_3)(Stream, RestoreOptions) | Восстанавливает папки обмена из указанного личного хранилища. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_5)(string, RestoreOptions) | Восстанавливает папки обмена из указанного файла личного хранилища. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | Восстанавливает указанные папки обмена из заданного личного хранилища. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_2)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | Восстанавливает указанные папки обмена из заданного личного хранилища. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_4)(string, ExchangeFolderInfoCollection, RestoreOptions) | Восстанавливает указанные папки обмена из указанного файла личного хранилища. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage)(string, Stream) | Сохраняет сообщение. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage_1)(string, string) | Сохраняет почтовое сообщение, указанное в uri, в локальной файловой системе. Файл почтового сообщения имеет формат, совместимый с RFC 822 (EML).  если вы хотите проанализировать файлы почтовых сообщений, используйте[`MailMessage`](../../aspose.email/mailmessage). |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send)(MailMessage) | Отправляет почтовое сообщение. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag)(string) | Помечает указанное сообщение как прочитанное. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag_1)(string, bool) | Помечает указанное сообщение как прочитанное. |

### Смотрите также

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
