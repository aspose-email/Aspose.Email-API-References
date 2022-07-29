---
title: IAsyncPop3Client
second_title: Справочник по Aspose.Email для .NET API
description: Позволяет приложениям получать доступ к сообщениям и управлять ими с помощью почтового протокола версии 3 POP3.
type: docs
weight: 16850
url: /ru/net/aspose.email.clients.pop3/iasyncpop3client/
---
## IAsyncPop3Client interface

Позволяет приложениям получать доступ к сообщениям и управлять ими с помощью почтового протокола версии 3 (POP3).

```csharp
public interface IAsyncPop3Client : IDisposable
```

## Методы

| Имя | Описание |
| --- | --- |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/iasyncpop3client/commitdeletesasync)(int, IConnection, CancellationToken) | Подтвердить удаление |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync#deletemessageasync)(int, IConnection, CancellationToken) | Удаляет сообщение |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync#deletemessageasync_1)(string, IConnection, CancellationToken) | Удаляет сообщение |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessagesasync)(IConnection, CancellationToken) | Удаляет все сообщения |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync#fetchmessageasync)(int, IConnection, CancellationToken) | Получает сообщение |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync#fetchmessageasync_1)(string, IConnection, CancellationToken) | Получает сообщение |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync#fetchmessagesasync)(IEnumerable&lt;int&gt;, IConnection, CancellationToken) | Получает сообщения асинхронно |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync#fetchmessagesasync_1)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Получает сообщения асинхронно |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxinfoasync)(bool, IConnection, CancellationToken) | Получает информацию о состоянии почтового ящика |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxsizeasync)(IConnection, CancellationToken) | Получает размер почтового ящика |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagecountasync)(bool, IConnection, CancellationToken) | Получает количество сообщений count |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync#getmessageheadersasync)(int, IConnection, CancellationToken) | Получает заголовки сообщения |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync#getmessageheadersasync_1)(string, IConnection, CancellationToken) | Получает заголовки сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync#getmessageinfoasync)(int, Pop3ListFields, IConnection, CancellationToken) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync#getmessageinfoasync_1)(string, Pop3ListFields, IConnection, CancellationToken) | Получает информацию для этого сообщения |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync#getmessagesizeasync)(int, IConnection, CancellationToken) | Получает размер сообщения |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync#getmessagesizeasync_1)(string, IConnection, CancellationToken) | Получает размер сообщения |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageuniqueidasync)(int, IConnection, CancellationToken) | Получает уникальный идентификатор сообщения |
| [ListMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/listmessagesasync)(Pop3ListFields, bool, MailQuery, IConnection, CancellationToken) | Список сообщений. |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/iasyncpop3client/loadmessageinfolistasync)(Pop3LoadMessageInfoList) | Загружает список Pop3MessageInfo |
| [NoopAsync](../../aspose.email.clients.pop3/iasyncpop3client/noopasync)(IConnection, CancellationToken) | Команда "Нет операции" |
| [SaveMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/savemessageasync)(Pop3SaveMessage) | Извлекает и сохраняет сообщение как поток |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/undeletemessagesasync)(IConnection, CancellationToken) | Восстанавливает сообщения. Если какие-либо сообщения были помечены сервером POP3 как удаленные, они не помечаются. |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/iasyncpop3client/validatecredentialsasync)(IConnection, CancellationToken) | Выполняет проверку учетных данных |

### Смотрите также

* пространство имен [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
