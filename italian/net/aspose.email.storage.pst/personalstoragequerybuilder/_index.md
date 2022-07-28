---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta il builder dellespressione di ricerca utilizzata da pst.
type: docs
weight: 20310
url: /it/net/aspose.email.storage.pst/personalstoragequerybuilder/
---
## PersonalStorageQueryBuilder class

Rappresenta il builder dell'espressione di ricerca utilizzata da pst.

```csharp
public sealed class PersonalStorageQueryBuilder : MailQueryBuilder
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PersonalStorageQueryBuilder](personalstoragequerybuilder)() | Inizializza una nuova istanza di[`PersonalStorageQueryBuilder`](../personalstoragequerybuilder) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo BCC della struttura della busta. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel corpo del messaggio. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo CC della struttura della busta. |
| [ContainerClass](../../aspose.email.storage.pst/personalstoragequerybuilder/containerclass) { get; } | Ottiene le cartelle con una classe di messaggi specificata. |
| [ContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/contentscount) { get; } | Cerca nelle cartelle con un numero di contenuti specificato. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Ottiene la codifica predefinita (charset) per il generatore di query |
| [FolderName](../../aspose.email.storage.pst/personalstoragequerybuilder/foldername) { get; } | Cerca nelle cartelle con un nome visualizzato specificato. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo FROM della struttura della busta. |
| [Importance](../../aspose.email.storage.pst/personalstoragequerybuilder/importance) { get; } | Cerca messaggi con un'importanza specificata. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Ottiene il campo che permette di trovare i messaggi per data interna. |
| [MessageClass](../../aspose.email.storage.pst/personalstoragequerybuilder/messageclass) { get; } | Ottiene i messaggi con una classe di messaggi specificata. |
| [MessageId](../../aspose.email.storage.pst/personalstoragequerybuilder/messageid) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo MessageId della struttura della busta. |
| [MessageSize](../../aspose.email.storage.pst/personalstoragequerybuilder/messagesize) { get; } | Cerca messaggi con una dimensione specificata. |
| [OnlyFoldersCreatedByUser](../../aspose.email.storage.pst/personalstoragequerybuilder/onlyfolderscreatedbyuser) { get; } | Ottiene le cartelle create dall'utente, ovvero esclude tutte le cartelle IPM standard. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Ottiene il campo che permette di trovare i messaggi per data di invio. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo SUBJECT della struttura della busta. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nelle intestazioni (oggetto, da, a, cc) e nel corpo del messaggio. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo TO della struttura della busta. |
| [UnreadContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/unreadcontentscount) { get; } | Cerca nelle cartelle con un numero di contenuti non letti specificato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [FindConversationThread](../../aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread)(MessageInfo) | Trova il thread della conversazione. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Ottiene la query. |
| [HasFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasflags)(MapiMessageFlags) | Cerca messaggi con i flag specificati. |
| [HasNoFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnoflags)(MapiMessageFlags) | Cerca i messaggi con i flag non specificati. |
| [HasNoSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnosubfolders)() | Cerca nelle cartelle che non contengono sottocartelle. |
| [HasSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hassubfolders)() | Cerca nelle cartelle che contengono sottocartelle. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Cerca i messaggi che corrispondono a una delle chiavi di ricerca. Fornisce la disgiunzione tra due espressioni (OR). |

### Guarda anche

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* spazio dei nomi [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
