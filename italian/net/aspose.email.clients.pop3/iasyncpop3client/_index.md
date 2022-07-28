---
title: IAsyncPop3Client
second_title: Aspose.Email per riferimento all'API .NET
description: Consente alle applicazioni di accedere e manipolare i messaggi utilizzando Post Office Protocol versione 3 POP3.
type: docs
weight: 16850
url: /it/net/aspose.email.clients.pop3/iasyncpop3client/
---
## IAsyncPop3Client interface

Consente alle applicazioni di accedere e manipolare i messaggi utilizzando Post Office Protocol versione 3 (POP3).

```csharp
public interface IAsyncPop3Client : IDisposable
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/iasyncpop3client/commitdeletesasync)(int, IConnection, CancellationToken) | Conferma le eliminazioni |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync#deletemessageasync)(int, IConnection, CancellationToken) | Elimina il messaggio |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync#deletemessageasync_1)(string, IConnection, CancellationToken) | Elimina il messaggio |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessagesasync)(IConnection, CancellationToken) | Elimina tutti i messaggi |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync#fetchmessageasync)(int, IConnection, CancellationToken) | Recupera il messaggio |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync#fetchmessageasync_1)(string, IConnection, CancellationToken) | Recupera il messaggio |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync#fetchmessagesasync)(IEnumerable&lt;int&gt;, IConnection, CancellationToken) | Recupera i messaggi in modo asincrono |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync#fetchmessagesasync_1)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Recupera i messaggi in modo asincrono |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxinfoasync)(bool, IConnection, CancellationToken) | Ottiene le informazioni sullo stato della casella di posta |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxsizeasync)(IConnection, CancellationToken) | Ottiene la dimensione della casella di posta |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagecountasync)(bool, IConnection, CancellationToken) | Ottiene il conteggio dei messaggi |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync#getmessageheadersasync)(int, IConnection, CancellationToken) | Ottiene le intestazioni dei messaggi |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync#getmessageheadersasync_1)(string, IConnection, CancellationToken) | Ottiene le intestazioni dei messaggi |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync#getmessageinfoasync)(int, Pop3ListFields, IConnection, CancellationToken) | Ottiene le informazioni per quel messaggio |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync#getmessageinfoasync_1)(string, Pop3ListFields, IConnection, CancellationToken) | Ottiene le informazioni per quel messaggio |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync#getmessagesizeasync)(int, IConnection, CancellationToken) | Ottiene la dimensione del messaggio |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync#getmessagesizeasync_1)(string, IConnection, CancellationToken) | Ottiene la dimensione del messaggio |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageuniqueidasync)(int, IConnection, CancellationToken) | Ottiene l'id univoco del messaggio |
| [ListMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/listmessagesasync)(Pop3ListFields, bool, MailQuery, IConnection, CancellationToken) | Elenca i messaggi. |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/iasyncpop3client/loadmessageinfolistasync)(Pop3LoadMessageInfoList) | Carica l'elenco di Pop3MessageInfo |
| [NoopAsync](../../aspose.email.clients.pop3/iasyncpop3client/noopasync)(IConnection, CancellationToken) | Comando 'Nessuna operazione' |
| [SaveMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/savemessageasync)(Pop3SaveMessage) | Recupera e salva il messaggio come stream |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/undeletemessagesasync)(IConnection, CancellationToken) | Annulla l'eliminazione dei messaggi. Se dei messaggi sono stati contrassegnati come eliminati dal server POP3, non vengono contrassegnati. |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/iasyncpop3client/validatecredentialsasync)(IConnection, CancellationToken) | Esegue la convalida delle credenziali |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
