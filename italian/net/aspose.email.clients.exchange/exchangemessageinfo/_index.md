---
title: ExchangeMessageInfo
second_title: Aspose.Email per riferimento all'API .NET
description: ExchangeMessageInfo rappresenta le informazioni sui messaggi di posta elettronica recuperate dallarchivio di Exchange.
type: docs
weight: 3400
url: /it/net/aspose.email.clients.exchange/exchangemessageinfo/
---
## ExchangeMessageInfo class

ExchangeMessageInfo rappresenta le informazioni sui messaggi di posta elettronica recuperate dall'archivio di Exchange.

```csharp
public abstract class ExchangeMessageInfo : MessageInfoBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [Attachments](../../aspose.email.clients.exchange/exchangemessageinfo/attachments) { get; } | Ottiene gli allegati dei messaggi |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | Ottiene una copia nascosta del messaggio di posta elettronica. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | Ottiene CC del messaggio di posta elettronica. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | La data di origine specifica la data e l'ora in cui il creatore del messaggio ha indicato che il messaggio era completo e pronto per entrare nel sistema di recapito della posta. Ad esempio, questo potrebbe essere il momento in cui un utente preme il pulsante "invia" o "invia" in un programma applicativo. In ogni caso, non è specificamente inteso per trasmettere l'ora in cui il messaggio viene effettivamente trasportato, ma piuttosto il momento in cui l'essere umano o altro creatore del messaggio ha messo il messaggio nella sua forma finale, pronto per il trasporto. (ad esempio, un utente di un computer portatile che non è connesso a una rete potrebbe mettere in coda un messaggio per la consegna. La data di origine deve contenere la data e l'ora in cui l'utente ha messo in coda il messaggio, non l'ora in cui l'utente si è connesso alla rete per inviare il messaggio.) |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Ottiene l'elenco degli autori di questo messaggio. |
| virtual [HasAttachments](../../aspose.email.clients.exchange/exchangemessageinfo/hasattachments) { get; } | Ottiene un valore che indica se il messaggio contiene almeno un allegato. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | Ottiene le intestazioni del messaggio di posta elettronica. |
| virtual [InternalDate](../../aspose.email.clients.exchange/exchangemessageinfo/internaldate) { get; } | La data e l'ora interne del messaggio sul server. Questa non è la data e l'ora nell'intestazione [RFC-2822], ma piuttosto una data e un'ora che riflette quando è stato ricevuto il messaggio. - Nel caso di messaggi consegnati tramite [SMTP], questa DEVE essere la data e l'ora di consegna finale del messaggio come definito da [SMTP]. - Nel caso di messaggi consegnati dal comando IMAP4rev1 COPY, questa DOVREBBE essere la data e l'ora interna del messaggio di origine. - Nel caso di messaggi consegnati dal comando IMAP4rev1 APPEND, questa DOVREBBE essere la data e l'ora specificate nella descrizione del comando APPEND. - Tutti gli altri casi sono definiti dall'implementazione. |
| virtual [IsRead](../../aspose.email.clients.exchange/exchangemessageinfo/isread) { get; } | Ottiene un valore che indica se il messaggio è stato letto |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Il campo List-Unsubscribe descrive il comando (preferibilmente utilizzando la posta) per annullare direttamente l'iscrizione all'utente (rimuovendolo dall'elenco). Per maggiori dettagli vedere https://tools.ietf.org/html/rfc2369 |
| virtual [MessageClass](../../aspose.email.clients.exchange/exchangemessageinfo/messageclass) { get; } | Ottiene una stringa che rappresenta la classe per il messaggio. La proprietà corrisponde alla proprietà MAPI PidTagMessageClass. |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | Ottiene l'ID del messaggio. |
| virtual [MessageInfoType](../../aspose.email.clients.exchange/exchangemessageinfo/messageinfotype) { get; } | Ottiene il tipo del messaggio |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Ottiene una proprietà mapi. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Ottiene l'elenco di indirizzi che dovrebbero ricevere risposte a questo messaggio. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Ottiene il mittente di questo messaggio. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | Ottiene la dimensione del messaggio di posta elettronica. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | Ottiene l'oggetto del messaggio di posta elettronica. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | Ottiene le ricevute del messaggio di posta elettronica. |
| virtual [UniqueUri](../../aspose.email.clients.exchange/exchangemessageinfo/uniqueuri) { get; } | Ottiene l'URI univoco del messaggio. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Esegue attività associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| override [ToString](../../aspose.email.clients/messageinfobase/tostring)() | Una stringa che rappresenta l'oggetto corrente. |

### Guarda anche

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* spazio dei nomi [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
