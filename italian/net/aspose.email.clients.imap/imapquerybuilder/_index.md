---
title: ImapQueryBuilder
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta il builder dellespressione di ricerca utilizzata dal protocollo IMAP.
type: docs
weight: 16460
url: /it/net/aspose.email.clients.imap/imapquerybuilder/
---
## ImapQueryBuilder class

Rappresenta il builder dell'espressione di ricerca utilizzata dal protocollo IMAP.

```csharp
public sealed class ImapQueryBuilder : MailQueryBuilder
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImapQueryBuilder](imapquerybuilder#constructor)() | Inizializza una nuova istanza di[`ImapQueryBuilder`](../imapquerybuilder) classe. |
| [ImapQueryBuilder](imapquerybuilder#constructor_1)(Encoding) | Inizializza una nuova istanza di[`ImapQueryBuilder`](../imapquerybuilder) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo BCC della struttura della busta. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel corpo del messaggio. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo CC della struttura della busta. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Ottiene la codifica predefinita (charset) per il generatore di query |
| [ESearchParameters](../../aspose.email.clients.imap/imapquerybuilder/esearchparameters) { get; set; } | Ottiene o imposta i parametri ESEARCH Questo metodo funziona solo se il server supporta l'estensione ESEARCH. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo FROM della struttura della busta. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Ottiene il campo che permette di trovare i messaggi per data interna. |
| [MessageSize](../../aspose.email.clients.imap/imapquerybuilder/messagesize) { get; } | Ottiene i messaggi con una dimensione specificata. |
| [ModSeq](../../aspose.email.clients.imap/imapquerybuilder/modseq) { get; } | Sequenza di modifica |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Ottiene il campo che permette di trovare i messaggi per data di invio. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo SUBJECT della struttura della busta. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nelle intestazioni (oggetto, da, a, cc) e nel corpo del messaggio. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Ottiene il campo che permette di trovare i messaggi che contengono la stringa specificata nel campo TO della struttura della busta. |
| [UniqueId](../../aspose.email.clients.imap/imapquerybuilder/uniqueid) { get; } | Identificatore univoco |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CustomSearch](../../aspose.email.clients.imap/imapquerybuilder/customsearch)(string) | Cerca i messaggi in base alla sintassi di ricerca del server estesa. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Ottiene la query. |
| [HasFlags](../../aspose.email.clients.imap/imapquerybuilder/hasflags)(ImapMessageFlags) | Cerca messaggi con i flag specificati. |
| [HasHeader](../../aspose.email.clients.imap/imapquerybuilder/hasheader)(string, string) | Cerca i messaggi che hanno un'intestazione con il nome-campo specificato e che contiene la stringa specificata nel testo dell'intestazione (che viene dopo i due punti). Se la stringa da cercare è di lunghezza zero, corrisponde a tutti i messaggi che hanno una riga di intestazione con il nome del campo specificato indipendentemente da il contenuto. |
| [HasNoFlags](../../aspose.email.clients.imap/imapquerybuilder/hasnoflags)(ImapMessageFlags) | Cerca i messaggi con i flag non specificati. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Cerca i messaggi che corrispondono a una delle chiavi di ricerca. Fornisce la disgiunzione tra due espressioni (OR). |

### Guarda anche

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->