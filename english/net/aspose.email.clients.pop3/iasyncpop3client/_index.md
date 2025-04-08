---
title: Interface IAsyncPop3Client
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Pop3.IAsyncPop3Client interface. Allows applications to access and manipulate messages by using the Post Office Protocol Version 3 POP3
type: docs
weight: 17010
url: /net/aspose.email.clients.pop3/iasyncpop3client/
---
## IAsyncPop3Client interface

Allows applications to access and manipulate messages by using the Post Office Protocol Version 3 (POP3).

```csharp
public interface IAsyncPop3Client : IDisposable
```

## Methods

| Name | Description |
| --- | --- |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/iasyncpop3client/commitdeletesasync/)(int, IConnection, CancellationToken) | Commit the deletions |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync/#deletemessageasync)(int, IConnection, CancellationToken) | Deletes the message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync/#deletemessageasync_1)(string, IConnection, CancellationToken) | Deletes the message |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessagesasync/)(IConnection, CancellationToken) | Deletes all messages |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync/#fetchmessageasync)(int, IConnection, CancellationToken) | Fetches the message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync/#fetchmessageasync_1)(string, IConnection, CancellationToken) | Fetches the message |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync/#fetchmessagesasync)(IEnumerable&lt;int&gt;, IConnection, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync/#fetchmessagesasync_1)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Fetches the messages asynchronously |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxinfoasync/)(bool, IConnection, CancellationToken) | Gets the mailbox status info |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxsizeasync/)(IConnection, CancellationToken) | Gets the size of the mailbox |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagecountasync/)(bool, IConnection, CancellationToken) | Gets the message count |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync/#getmessageheadersasync)(int, IConnection, CancellationToken) | Gets the message headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync/#getmessageheadersasync_1)(string, IConnection, CancellationToken) | Gets the message headers |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync/#getmessageinfoasync)(int, Pop3ListFields, IConnection, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync/#getmessageinfoasync_1)(string, Pop3ListFields, IConnection, CancellationToken) | Gets the information for that message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync/#getmessagesizeasync)(int, IConnection, CancellationToken) | Gets the size of the message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync/#getmessagesizeasync_1)(string, IConnection, CancellationToken) | Gets the size of the message |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageuniqueidasync/)(int, IConnection, CancellationToken) | Gets the message unique id |
| [ListMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/listmessagesasync/)(Pop3ListFields, bool, MailQuery, IConnection, CancellationToken) | Lists the messages. |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/iasyncpop3client/loadmessageinfolistasync/)(Pop3LoadMessageInfoList) | Loads list of Pop3MessageInfo |
| [NoopAsync](../../aspose.email.clients.pop3/iasyncpop3client/noopasync/)(IConnection, CancellationToken) | 'No operation' command |
| [SaveMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/savemessageasync/)(Pop3SaveMessage) | Fetches and save the message as a stream |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/undeletemessagesasync/)(IConnection, CancellationToken) | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/iasyncpop3client/validatecredentialsasync/)(IConnection, CancellationToken) | Executes credentials validation |

### See Also

* namespace [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3/)
* assembly [Aspose.Email](../../)


