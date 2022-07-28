---
title: ImapMessageInfo
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta un oggetto messaggio Imap.
type: docs
weight: 16370
url: /it/net/aspose.email.clients.imap/imapmessageinfo/
---
## ImapMessageInfo class

Rappresenta un oggetto messaggio Imap.

```csharp
public sealed class ImapMessageInfo : MessageInfoBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Answered](../../aspose.email.clients.imap/imapmessageinfo/answered) { get; } | Ottiene un valore che indica se la proprietà Flags contiene il flag Risposte. |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | Ottiene una copia nascosta del messaggio di posta elettronica. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | Ottiene CC del messaggio di posta elettronica. |
| [ConversationId](../../aspose.email.clients.imap/imapmessageinfo/conversationid) { get; } | Ottiene un valore che indica l'ID conversazione. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | La data di origine specifica la data e l'ora in cui il creatore del messaggio ha indicato che il messaggio era completo e pronto per entrare nel sistema di recapito della posta. Ad esempio, questo potrebbe essere il momento in cui un utente preme il pulsante "invia" o "invia" in un programma applicativo. In ogni caso, non è specificamente inteso per trasmettere l'ora in cui il messaggio viene effettivamente trasportato, ma piuttosto il momento in cui l'essere umano o altro creatore del messaggio ha messo il messaggio nella sua forma finale, pronto per il trasporto. (ad esempio, un utente di un computer portatile che non è connesso a una rete potrebbe mettere in coda un messaggio per la consegna. La data di origine deve contenere la data e l'ora in cui l'utente ha messo in coda il messaggio, non l'ora in cui l'utente si è connesso alla rete per inviare il messaggio.) |
| [Deleted](../../aspose.email.clients.imap/imapmessageinfo/deleted) { get; } | Ottiene un valore che indica se la proprietà Flags contiene il flag Eliminato. |
| [Draft](../../aspose.email.clients.imap/imapmessageinfo/draft) { get; } | Ottiene un valore che indica se la proprietà Flags contiene il flag Draft. |
| [ExtraParameters](../../aspose.email.clients.imap/imapmessageinfo/extraparameters) { get; } | Ottiene parametri aggiuntivi di un messaggio. |
| [Flagged](../../aspose.email.clients.imap/imapmessageinfo/flagged) { get; } | Ottiene un valore che indica se la proprietà Flags contiene il flag Contrassegnato. |
| [Flags](../../aspose.email.clients.imap/imapmessageinfo/flags) { get; } | Ottiene i flag dei messaggi. |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Ottiene l'elenco degli autori di questo messaggio. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | Ottiene le intestazioni del messaggio di posta elettronica. |
| [InternalDate](../../aspose.email.clients.imap/imapmessageinfo/internaldate) { get; } | La data e l'ora interne del messaggio sul server. Questa non è la data e l'ora nell'intestazione [RFC-2822], ma piuttosto una data e un'ora che riflette quando è stato ricevuto il messaggio. - Nel caso di messaggi consegnati tramite [SMTP], questa DEVE essere la data e l'ora di consegna finale del messaggio come definito da [SMTP]. - Nel caso di messaggi consegnati dal comando IMAP4rev1 COPY, questa DOVREBBE essere la data e l'ora interna del messaggio di origine. - Nel caso di messaggi consegnati dal comando IMAP4rev1 APPEND, questa DOVREBBE essere la data e l'ora specificate nella descrizione del comando APPEND. - Tutti gli altri casi sono definiti dall'implementazione. |
| [IsRead](../../aspose.email.clients.imap/imapmessageinfo/isread) { get; } | Ottiene un valore che indica se la proprietà Flags contiene il flag di lettura. |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Il campo List-Unsubscribe descrive il comando (preferibilmente utilizzando la posta) per annullare direttamente l'iscrizione all'utente (rimuovendolo dall'elenco). Per maggiori dettagli vedere https://tools.ietf.org/html/rfc2369 |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | Ottiene l'ID del messaggio. |
| [ModificationSequence](../../aspose.email.clients.imap/imapmessageinfo/modificationsequence) { get; } | Ottiene la sequenza di modifica di questo messaggio. Vedi di più: https://tools.ietf.org/html/rfc7162 |
| [ParentFolder](../../aspose.email.clients.imap/imapmessageinfo/parentfolder) { get; } | Ottiene la cartella principale per il messaggio |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Ottiene una proprietà mapi. |
| [Recent](../../aspose.email.clients.imap/imapmessageinfo/recent) { get; } | Ottiene un valore che indica se la proprietà Flags contiene il flag Recenti. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Ottiene l'elenco di indirizzi che dovrebbero ricevere risposte a questo messaggio. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Ottiene il mittente di questo messaggio. |
| [SequenceNumber](../../aspose.email.clients.imap/imapmessageinfo/sequencenumber) { get; } | Ottiene il numero di sequenza del messaggio. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | Ottiene la dimensione del messaggio di posta elettronica. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | Ottiene l'oggetto del messaggio di posta elettronica. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | Ottiene le ricevute del messaggio di posta elettronica. |
| [UniqueId](../../aspose.email.clients.imap/imapmessageinfo/uniqueid) { get; } | Ottiene l'ID univoco del messaggio. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ContainsKeyword](../../aspose.email.clients.imap/imapmessageinfo/containskeyword)(string) | Ottiene un valore che indica se la proprietà Flags contiene il flag Parola chiave. |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Esegue attività associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| override [ToString](../../aspose.email.clients.imap/imapmessageinfo/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Guarda anche

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
