---
title: IAsyncPop3Client
second_title: Référence de l'API Aspose.Email pour .NET
description: Permet aux applications daccéder aux messages et de les manipuler à laide de Post Office Protocol Version 3 POP3.
type: docs
weight: 16850
url: /fr/net/aspose.email.clients.pop3/iasyncpop3client/
---
## IAsyncPop3Client interface

Permet aux applications d'accéder aux messages et de les manipuler à l'aide de Post Office Protocol Version 3 (POP3).

```csharp
public interface IAsyncPop3Client : IDisposable
```

## Méthodes

| Nom | La description |
| --- | --- |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/iasyncpop3client/commitdeletesasync)(int, IConnection, CancellationToken) | Valider les suppressions |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync#deletemessageasync)(int, IConnection, CancellationToken) | Supprime le message |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync#deletemessageasync_1)(string, IConnection, CancellationToken) | Supprime le message |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessagesasync)(IConnection, CancellationToken) | Supprime tous les messages |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync#fetchmessageasync)(int, IConnection, CancellationToken) | Récupère le message |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync#fetchmessageasync_1)(string, IConnection, CancellationToken) | Récupère le message |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync#fetchmessagesasync)(IEnumerable&lt;int&gt;, IConnection, CancellationToken) | Récupère les messages de manière asynchrone |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync#fetchmessagesasync_1)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Récupère les messages de manière asynchrone |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxinfoasync)(bool, IConnection, CancellationToken) | Obtient les informations sur l'état de la boîte aux lettres |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxsizeasync)(IConnection, CancellationToken) | Obtient la taille de la boîte aux lettres |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagecountasync)(bool, IConnection, CancellationToken) | Obtient le nombre de messages |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync#getmessageheadersasync)(int, IConnection, CancellationToken) | Obtient les en-têtes de message |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync#getmessageheadersasync_1)(string, IConnection, CancellationToken) | Obtient les en-têtes de message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync#getmessageinfoasync)(int, Pop3ListFields, IConnection, CancellationToken) | Obtient les informations pour ce message |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync#getmessageinfoasync_1)(string, Pop3ListFields, IConnection, CancellationToken) | Obtient les informations pour ce message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync#getmessagesizeasync)(int, IConnection, CancellationToken) | Obtient la taille du message |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync#getmessagesizeasync_1)(string, IConnection, CancellationToken) | Obtient la taille du message |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageuniqueidasync)(int, IConnection, CancellationToken) | Obtient l'identifiant unique du message |
| [ListMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/listmessagesasync)(Pop3ListFields, bool, MailQuery, IConnection, CancellationToken) | Liste les messages. |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/iasyncpop3client/loadmessageinfolistasync)(Pop3LoadMessageInfoList) | Charge la liste de Pop3MessageInfo |
| [NoopAsync](../../aspose.email.clients.pop3/iasyncpop3client/noopasync)(IConnection, CancellationToken) | Commande 'Aucune opération' |
| [SaveMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/savemessageasync)(Pop3SaveMessage) | Récupère et enregistre le message sous forme de flux |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/undeletemessagesasync)(IConnection, CancellationToken) | Rétablit les messages. Si des messages ont été marqués comme supprimés par le serveur POP3, ils ne sont pas marqués. |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/iasyncpop3client/validatecredentialsasync)(IConnection, CancellationToken) | Exécute la validation des identifiants |

### Voir également

* espace de noms [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
