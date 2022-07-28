---
title: MailQuery
second_title: Aspose.Email per riferimento all'API .NET
description: Inizializza una nuova istanza diMailQueryaspose.email.tools.search/mailquery classe.
type: docs
weight: 10
url: /it/net/aspose.email.tools.search/mailquery/mailquery/
---
## MailQuery(string) {#constructor}

Inizializza una nuova istanza di[`MailQuery`](../../mailquery) classe.

```csharp
public MailQuery(string queryString)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| queryString | String | La stringa di query. |

### Osservazioni

La stringa di query dovrebbe avere la seguente vista.

L'esempio di un'espressione semplice:

'&lt;Nome campo&gt;' &lt;Operatore di confronto&gt; '&lt;Valore campo&gt;',

dove &lt;Nome campo&gt; - il nome di un campo messaggio attraverso il quale viene effettuato il filtraggio, &lt;Operatore di confronto&gt; - gli operatori di confronto, come suggerisce il nome, consentono di confrontare il campo messaggio e il valore specificato, &lt;Valore campo&gt; - valore con essere confrontato con un campo messaggio.

Il numero di espressioni semplici può farne una composta, es.: (&lt;Espressione semplice 1&gt; &amp; &lt;Espressione semplice 2&gt;) &#x7C; &lt;Espressione semplice 3&gt;,

dove "&amp;" - operatore AND logico, "&#x7C;" - operatore OR logico

Attualmente sono ammessi i seguenti valori come nome campo (&lt;Nome campo&gt;):

"A" - rappresenta un campo TO del messaggio, "Testo" - rappresenta una stringa nell'intestazione o nel corpo del messaggio, "Ccn" - rappresenta un campo BCC del messaggio, "Body" - rappresenta una stringa nel corpo del messaggio, "Cc" - rappresenta un campo CC del messaggio, "Da" - rappresenta un campo Da del messaggio, "Oggetto" - rappresenta una stringa nell'oggetto del messaggio, "InternalDate" - rappresenta un interno data del messaggio, "SentDate" - rappresenta una data di invio del messaggio

Inoltre, per il protocollo IMAP sono consentiti i seguenti nomi di campo:

"Risposta" - rappresenta un flag /Risposta del messaggio "Visto" - rappresenta un flag /Visto del messaggio "Segnalato" - rappresenta un flag /Segnalato del messaggio "Bozza" - rappresenta un flag /Bozza del messaggio "Cancellato" - rappresenta un flag Deleted/ di message "Recent" - rappresenta un flag Deleted/ di message "MessageSize" - rappresenta una dimensione (in byte) di message

Inoltre, per Exchange sono consentiti i seguenti nomi di campo:

"IsRead" - Indica se il messaggio è stato letto "HasAttachment" - Indica se il messaggio ha allegati o meno "IsSubmitted" - Indica se il messaggio è stato inviato alla Posta in uscita "ContentClass" - rappresenta una classe di contenuto di item

Inoltre, per i file pst/ost sono consentiti i seguenti nomi di campo:

"MessageClass" - Rappresenta una classe di messaggi "ContainerClass" - Rappresenta una classe di contenitori di cartelle "Importance" - Rappresenta un messaggio. - rappresenta il numero totale di elementi nella cartella "UnreadContentsCount" - rappresenta il numero di elementi non letti nella cartella. "Sottocartelle" - Indica se la cartella contiene o meno sottocartelle "Leggi" - il messaggio è contrassegnato come letto " HasAttachment" - il messaggio ha almeno un allegato "Non inviato" - il messaggio è ancora in fase di composizione "Non modificato" - il messaggio non è stato modificato dal primo salvataggio (se non inviato) o consegnato (se inviato) "FromMe " - l'utente che ha ricevuto il messaggio è stato anche l'utente che ha inviato il messaggio "Resend" - il messaggio include una richiesta per un'operazione di nuovo invio con un rapporto di mancato recapito_x000 d_ "NotifyRead" - l'utente che ha inviato il messaggio ha richiesto la notifica quando un destinatario lo legge per la prima volta "NotifyUnread" - l'utente che ha inviato il messaggio ha richiesto la notifica quando un destinatario lo elimina prima della lettura o l'oggetto del messaggio scade "EverRead" - il il messaggio è stato letto almeno una volta

Il valore del campo (&lt;Valore campo&gt;) può assumere i seguenti valori: Per i campi di testo - qualsiasi stringa, Per i campi di tipo data - la stringa di formato "g-MMM-aaa", es. "10-Feb-2009", Per i flag (campi di tipo booleano) - "Vero" o "Falso"

### Esempi

```csharp
MailQuery mailQuery = new MailQuery("(('From' Contains 'test@test.com' | 'Seen' = 'True') & 'SentDate' >= '12-May-2010')");
```

### Guarda anche

* class [MailQuery](../../mailquery)
* spazio dei nomi [Aspose.Email.Tools.Search](../../mailquery)
* assemblea [Aspose.Email](../../../)

---

## MailQuery(string, string) {#constructor_1}

Inizializza una nuova istanza di[`MailQuery`](../../mailquery) classe.

```csharp
public MailQuery(string queryString, string orderByString)
```

### Osservazioni

La stringa di query di ordinamento dovrebbe avere la seguente vista.

L'esempio di un'espressione semplice:

'&lt;Nome campo&gt;' Ordina per ['ASC'&#x7C;'DESC'],

dove &lt;Nome campo&gt; - il nome di un campo messaggio attraverso il quale viene effettuato l'ordinamento, ['ASC'&#x7C;'DESC'] - operatori di ordinamento, consentono di ordinare in ordine crescente o decrescente,

Il numero di espressioni semplici può farne una composta, es.: (&lt;Espressione semplice 1&gt; &amp; &lt;Espressione semplice 2&gt;),

### Esempi

```csharp
MailQuery mailQuery = new MailQuery("", "(('From' OrderBy 'ASC') & ('SentDate' OrderBy 'DESC'))");
```

### Guarda anche

* class [MailQuery](../../mailquery)
* spazio dei nomi [Aspose.Email.Tools.Search](../../mailquery)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
