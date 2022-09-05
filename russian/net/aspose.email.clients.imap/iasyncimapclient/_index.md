---
title: IAsyncImapClient
second_title: Справочник по Aspose.Email для .NET API
description: Позволяет приложениям получать доступ к сообщениям и управлять ими с помощью протокола доступа к сообщениям в Интернете IMAP.
type: docs
weight: 16240
url: /ru/net/aspose.email.clients.imap/iasyncimapclient/
---
## IAsyncImapClient interface

Позволяет приложениям получать доступ к сообщениям и управлять ими с помощью протокола доступа к сообщениям в Интернете (IMAP).

```csharp
public interface IAsyncImapClient
```

## Методы

| Имя | Описание |
| --- | --- |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/addmessageflagsasync)(ImapChangeMessageFlags) | Добавляет флаги к сообщению |
| [AppendMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessageasync)(MailMessage, string, IConnection, CancellationToken) | Загружает почтовое сообщение в указанную папку |
| [AppendMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, string, IConnection, CancellationToken) | Загружает почтовые сообщения в текущую папку |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) | Резервирует содержимое указанных папок |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync_1)(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) | Резервирует содержимое указанных папок |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/changemessageflagsasync)(ImapChangeMessageFlags) | Изменяет флаги сообщения |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Уведомляет сервер, какие расширения поддерживаются клиентом. Обратите внимание, эта операция работает только в том случае, если сервер поддерживает RFC5161 Подробнее https://tools.ietf.org/html/rfc5161 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/iasyncimapclient/commitdeletesasync)(ImapUniqueIdParameterSet) | Подтвердить удаление |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync)(int, string, IConnection, CancellationToken) | Копирует сообщение |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync_1)(string, string, IConnection, CancellationToken) | Копирует сообщение. |
| [CopyMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessagesasync)(ImapCopyMessages) | Скопируйте сообщения. |
| [CreateFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/createfolderasync)(string, IConnection, CancellationToken) | Создает папку с указанным именем. |
| [DeleteFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/deletefolderasync)(string, IConnection, CancellationToken) | Удаляет указанную папку. Этот метод представляет команду IMAP DELETE. |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/deletemessagesasync)(ImapDeleteMessages) | Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| [ExistFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/existfolderasync)(string, IConnection, CancellationToken) | Проверить, существует ли эта папка |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync)(int, string, IConnection, CancellationToken) | Извлекает указанное вложение. |
| [FetchMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchmessagesasync)(ImapFetchMessages) | Получает сообщения асинхронно |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/iasyncimapclient/getfolderinfoasync)(string, IConnection, CancellationToken) | Возвращает информацию об указанной папке без ее выбора |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync)(BaseSearchConditions, IConnection, CancellationToken) | Получить цепочки сообщений. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/iasyncimapclient/getnamespacesasync)(IConnection, CancellationToken) | Получает пространства имен, доступные на сервере. |
| [GetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotaasync)(string, IConnection, CancellationToken) | Получает информацию о квоте |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotarootasync)(string, IConnection, CancellationToken) | Получает информацию о корневой квоте для почтового ящика |
| [IntroduceClientAsync](../../aspose.email.clients.imap/iasyncimapclient/introduceclientasync)(ImapIdentificationInfo, IConnection, CancellationToken) | Представляет информацию о клиенте серверу. |
| [ListFoldersAsync](../../aspose.email.clients.imap/iasyncimapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, IConnection, CancellationToken) | Получает список подпапок в указанной папке |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync)(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Получает информацию о сообщении. |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync_1)(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Получает информацию о сообщении. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync)(MailQuery, string, int, IConnection, CancellationToken) | Получает список сообщений в текущей папке. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync_1)(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Получает список сообщений в указанной папке |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync_1)(int, int, PageSettings, CancellationToken) | Получает список сообщений |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | Получает список сообщений |
| [MoveFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/movefolderasync)(string, string, IConnection, CancellationToken) | Перемещает указанную папку и ее подпапки в новое место. |
| [MoveMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/movemessagesasync)(ImapMoveMessages) | Перемещает сообщения. |
| [NoopAsync](../../aspose.email.clients.imap/iasyncimapclient/noopasync)(IConnection, CancellationToken) | Команда "Нет операции" |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/removemessageflagsasync)(ImapChangeMessageFlags) | Удаляет флаги сообщения |
| [RenameFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/renamefolderasync)(string, string, IConnection, CancellationToken) | Переименовывает указанную папку в новое имя |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/iasyncimapclient/requestcheckpointasync)(IConnection, CancellationToken) | Запрашивает контрольную точку выбранного в данный момент почтового ящика. |
| [RestoreAsync](../../aspose.email.clients.imap/iasyncimapclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Начинает восстанавливать папки imap из заданного личного хранилища. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | Возобновляет мониторинг изменений сообщений для указанной папки. В отличие от метода StartMonitoring, он найдет все отсутствующие изменения почтового ящика и вызовет обратный вызов для них. |
| [SelectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/selectfolderasync)(string, bool?, IConnection, CancellationToken) | Выбирает указанную папку |
| [SetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/setquotaasync)(string, string, int, IConnection, CancellationToken) | Устанавливает информацию о квоте |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/sortmessagethreadsasync)(SortConditions, IConnection, CancellationToken) | Сортировать цепочки сообщений. |
| [StartMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Запускает мониторинг изменений сообщений для указанной папки. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/stopmonitoringasync)(string, CancellationToken) | Останавливает мониторинг изменений сообщений для указанной папки. Прекращает мониторинг всех папок, если имя папки равно null. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/subscribefolderasync)(string, IConnection, CancellationToken) | Отправлена команда SUBSCRIBE, которая добавляет указанное имя почтового ящика в набор «активных» почтовых ящиков сервера. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync)(int, long, IConnection, CancellationToken) | Помечает сообщение с указанным порядковым номером как не удаленное |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync_1)(string, long, IConnection, CancellationToken) | Помечает сообщение с указанным порядковым номером как не удаленное. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unselectfolderasync)(bool, IConnection, CancellationToken) | Отменяет выбор папки, которая выбрана в данный момент. если свойство doNotExpunge равно true, все сообщения помечаются как удаленные, удаляются, в противном случае удаление отменяется. ietf.org/html/rfc3691 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync)(string, IConnection, CancellationToken) | Отправлена команда UNSUBSCRIBE, которая удаляет указанное имя почтового ящика из набора «активных» почтовых ящиков сервера |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/iasyncimapclient/validatecredentialsasync)(IConnection, CancellationToken) | Выполняет проверку учетных данных |

### Смотрите также

* пространство имен [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
