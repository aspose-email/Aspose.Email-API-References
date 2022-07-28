---
title: ExchangeQueryBuilder
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta il builder dellespressione di ricerca in base ai filtri di ricerca utilizzati dal protocollo Exchange.
type: docs
weight: 3440
url: /it/net/aspose.email.clients.exchange/exchangequerybuilder/
---
## ExchangeQueryBuilder class

Rappresenta il builder dell'espressione di ricerca in base ai filtri di ricerca utilizzati dal protocollo Exchange.

```csharp
public sealed class ExchangeQueryBuilder : MailQueryBuilder
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExchangeQueryBuilder](exchangequerybuilder)() | Inizializza una nuova istanza di[`ExchangeQueryBuilder`](../exchangequerybuilder) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Appointment](../../aspose.email.clients.exchange/exchangequerybuilder/appointment) { get; } | Ottiene l'oggetto con le proprietà dell'appuntamento per creare la query |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo BCC della struttura della busta. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel corpo del messaggio. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo CC della struttura della busta. |
| [Contact](../../aspose.email.clients.exchange/exchangequerybuilder/contact) { get; } | Ottiene l'oggetto con le proprietà del contatto per creare la query |
| [ContentClass](../../aspose.email.clients.exchange/exchangequerybuilder/contentclass) { get; } | Ottiene elementi con una classe di contenuto specificata. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Ottiene la codifica predefinita (charset) per il generatore di query |
| [ExtendedProperties](../../aspose.email.clients.exchange/exchangequerybuilder/extendedproperties) { get; } | Ottiene un dizionario con coppie di descrittori di proprietà e un campo di confronto per la ricerca in base a proprietà estese. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo FROM della struttura della busta. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Ottiene il campo che permette di trovare i messaggi per data interna. |
| [ItemSize](../../aspose.email.clients.exchange/exchangequerybuilder/itemsize) { get; } | Ottiene il campo che consente di trovare elementi con una dimensione specificata. |
| [MessageId](../../aspose.email.clients.exchange/exchangequerybuilder/messageid) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo MessageId della struttura della busta. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Ottiene il campo che permette di trovare i messaggi per data di invio. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo SUBJECT della struttura della busta. |
| [TaskStatus](../../aspose.email.clients.exchange/exchangequerybuilder/taskstatus) { get; } | Ottiene il campo che consente di trovare attività che contengono lo stato specificato. Compatibilità server: Exchange 2010 e versioni successive |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nelle intestazioni (oggetto, da, a, cc) e nel corpo del messaggio. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo TO della struttura della busta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Ottiene la query. |
| [HasFlags](../../aspose.email.clients.exchange/exchangequerybuilder/hasflags)(ExchangeMessageFlag) | Cerca messaggi con i flag specificati. |
| [HasNoFlags](../../aspose.email.clients.exchange/exchangequerybuilder/hasnoflags)(ExchangeMessageFlag) | Cerca i messaggi con i flag non specificati. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Cerca i messaggi che corrispondono a una delle chiavi di ricerca. Fornisce la disgiunzione tra due espressioni (OR). |

### Guarda anche

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* spazio dei nomi [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
