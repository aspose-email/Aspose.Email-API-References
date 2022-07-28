---
title: IAsyncPop3Client
second_title: Aspose.Email för .NET API-referens
description: Tillåter applikationer att komma åt och manipulera meddelanden genom att använda Post Office Protocol Version 3 POP3.
type: docs
weight: 16850
url: /sv/net/aspose.email.clients.pop3/iasyncpop3client/
---
## IAsyncPop3Client interface

Tillåter applikationer att komma åt och manipulera meddelanden genom att använda Post Office Protocol Version 3 (POP3).

```csharp
public interface IAsyncPop3Client : IDisposable
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/iasyncpop3client/commitdeletesasync)(int, IConnection, CancellationToken) | Begå raderingarna |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync#deletemessageasync)(int, IConnection, CancellationToken) | Tar bort meddelandet |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync#deletemessageasync_1)(string, IConnection, CancellationToken) | Tar bort meddelandet |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessagesasync)(IConnection, CancellationToken) | Tar bort alla meddelanden |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync#fetchmessageasync)(int, IConnection, CancellationToken) | Hämtar meddelandet |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync#fetchmessageasync_1)(string, IConnection, CancellationToken) | Hämtar meddelandet |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync#fetchmessagesasync)(IEnumerable&lt;int&gt;, IConnection, CancellationToken) | Hämtar meddelandena asynkront |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync#fetchmessagesasync_1)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Hämtar meddelandena asynkront |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxinfoasync)(bool, IConnection, CancellationToken) | Hämtar postlådans status info |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxsizeasync)(IConnection, CancellationToken) | Får storleken på brevlådan |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagecountasync)(bool, IConnection, CancellationToken) | Hämtar meddelandet count |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync#getmessageheadersasync)(int, IConnection, CancellationToken) | Hämtar meddelandet headers |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync#getmessageheadersasync_1)(string, IConnection, CancellationToken) | Hämtar meddelandet headers |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync#getmessageinfoasync)(int, Pop3ListFields, IConnection, CancellationToken) | Hämtar informationen för det meddelandet |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync#getmessageinfoasync_1)(string, Pop3ListFields, IConnection, CancellationToken) | Hämtar informationen för det meddelandet |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync#getmessagesizeasync)(int, IConnection, CancellationToken) | Hämtar storleken på meddelandet |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync#getmessagesizeasync_1)(string, IConnection, CancellationToken) | Hämtar storleken på meddelandet |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageuniqueidasync)(int, IConnection, CancellationToken) | Hämtar meddelandet unikt id |
| [ListMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/listmessagesasync)(Pop3ListFields, bool, MailQuery, IConnection, CancellationToken) | Listar meddelandena. |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/iasyncpop3client/loadmessageinfolistasync)(Pop3LoadMessageInfoList) | Laddar lista med Pop3MessageInfo |
| [NoopAsync](../../aspose.email.clients.pop3/iasyncpop3client/noopasync)(IConnection, CancellationToken) | 'Ingen operation' kommando |
| [SaveMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/savemessageasync)(Pop3SaveMessage) | Hämtar och sparar meddelandet som en stream |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/undeletemessagesasync)(IConnection, CancellationToken) | Återställer meddelandena. Om några meddelanden har markerats som borttagna av POP3-servern, avmarkeras de. |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/iasyncpop3client/validatecredentialsasync)(IConnection, CancellationToken) | Utför behörighetsvalidering |

### Se även

* namnutrymme [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
