---
title: ListFoldersOptions
second_title: Aspose.Email per riferimento all'API .NET
description: Le opzioni di selezione dellelenco delle cartelle Si prega di notare che queste opzioni sono supportate nel caso in cui il server supporti RFC 5258 IMAP LIST Command Extensions Vedere maggiori dettagli in https//tools.ietf.org/html/rfc5258
type: docs
weight: 16510
url: /it/net/aspose.email.clients.imap/listfoldersoptions/
---
## ListFoldersOptions enumeration

Le opzioni di selezione dell'elenco delle cartelle Si prega di notare che queste opzioni sono supportate nel caso in cui il server supporti RFC 5258 "IMAP LIST Command Extensions" Vedere maggiori dettagli in https://tools.ietf.org/html/rfc5258

```csharp
[Flags]
public enum ListFoldersOptions
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Non definito |
| Subscribed | `1` | SUBSCRIBED - fa in modo che il comando LIST elenchi i nomi sottoscritti, anziché le cassette postali esistenti. Questo sarà spesso un sottoinsieme delle cassette postali effettive. È anche possibile che questo elenco contenga i nomi di caselle di posta che non esistono. In ogni caso, l'elenco DEVE includere esattamente quei nomi di casella di posta che corrispondono al modello di elenco canonico e sono iscritti. Questa opzione ha lo scopo di integrare il comando LSUB. Di particolare rilievo sono gli attributi della casella di posta restituiti da questa opzione, rispetto a quanto restituito da LSUB. Con quest'ultimo, gli attributi restituiti potrebbero non riflettere lo stato effettivo dell'attributo sul nome della cassetta postale, e l'attributo \NoSelect ha un secondo significato speciale (indica che questa cassetta postale non è di per sé iscritta, ma ha cassette postali discendenti che sono). Con l'opzione di selezione ABBONATO qui descritta, gli attributi sono accurati e completi e non hanno significati speciali. "LSUB" e "LISTA (SUBSCRIBED)" non sono quindi la stessa cosa e alcuni server devono fare un lavoro extra significativo per rispondere a "LIST (SUBSCRIBED)". Per questo motivo, i client DEVONO continuare a utilizzare "LSUB" a meno che non desiderino specificamente le informazioni aggiuntive offerte da "LISTA (SUBSCRIBED)". Questa opzione definisce un nuovo attributo della casella di posta, "\Subscribed", che indica che il nome di una casella di posta è sottoscritto a. L'attributo "\Abbonato" DEVE essere supportato e DEVE essere calcolato accuratamente quando viene specificata l'opzione di selezione ABBONATO. Si noti che l'opzione di selezione ABBONATO implica l'opzione di ritorno ABBONATO (vedi sotto). |
| Remote | `2` | REMOTE - fa in modo che il comando LIST mostri le cassette postali remote oltre a quelle locali, come descritto in [MBRef]. Questa opzione ha lo scopo di sostituire il comando RLIST e, insieme all'opzione di selezione SUBSCRIBED, il comando RLSUB. Questa opzione definisce un nuovo attributo della casella di posta, "\Remote", che indica che una casella di posta è una casella di posta remota. Il L'attributo "\Remote" DEVE essere calcolato accuratamente quando viene specificata l'opzione REMOTA. L'opzione di selezione REMOTA non ha interazione con altre opzioni. Il suo effetto è di dire al server di applicare le altre opzioni, se presenti, alle cassette postali remote, in oltre a quelli locali. In particolare, non ha interazione con RECURSIVEMATCH (vedi sotto). Una richiesta per (REMOTE RECURSIVEMATCH) non è valida, perché lo è una richiesta per (RECURSIVEMATCH). Una richiesta per (REMOTE RECURSIVEMATCH SUBSCRIBED) richiede tutte le caselle di posta sottoscritte, sia locali che remote. |
| RecursiveMatch | `4` | RECURSIVEMATCH - questa opzione forza il server a restituire informazioni sulle cassette postali principali che non corrispondono ad altre opzioni di selezione, ma hanno alcune cassette postali secondarie che lo fanno. Le informazioni sui figli vengono restituite nell'elemento di dati estesi CHILDINFO. Nota 1: affinché una casella di posta principale venga restituita, deve comunque corrispondere al modello LIST canonico. Nota 2: Quando si restituisce l'elemento di dati estesi CHILDINFO, non importa se la casella di posta secondaria corrisponde o meno all'ELENCO canonico modello. L'opzione RECURSIVEMATCH NON DEVE verificarsi come unica opzione di selezione (o solo con REMOTE), poiché ha senso solo quando vengono utilizzate anche altre opzioni di selezione. Il server DEVE restituire una risposta con tag BAD in questo caso. Si noti che anche se viene specificata l'opzione RECURSIVEMATCH, il client DEVE essere ancora in grado di gestire un caso quando viene restituito un elemento di dati esteso CHILDINFO e non ci sono cassette postali secondarie che soddisfano i criteri di selezione del successivo comando LIST, in quanto può essere cancellato/rinominato dopo l'invio della risposta LIST, ma prima che il client avesse la possibilità di accedervi. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
