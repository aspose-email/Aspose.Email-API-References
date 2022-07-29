---
title: ListMessagesByPageAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Ottiene lelenco dei messaggi
type: docs
weight: 250
url: /it/net/aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync/
---
## ListMessagesByPageAsync(int, int, PageSettings, CancellationToken) {#listmessagesbypageasync_1}

Ottiene l'elenco dei messaggi

```csharp
public Task<ImapPageInfo> ListMessagesByPageAsync(int itemsPerPage, int pageOffset, 
    PageSettings settings, CancellationToken token = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| itemsPerPage | Int32 | Una serie di elementi nella pagina |
| pageOffset | Int32 | Un offset della pagina successiva visualizzata |
| settings | PageSettings | Le impostazioni. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapPageInfo](../../imappageinfo)
* class [PageSettings](../../pagesettings)
* interface [IAsyncImapClient](../../iasyncimapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesByPageAsync(MailQuery, PageInfo, PageSettings, CancellationToken) {#listmessagesbypageasync}

Ottiene l'elenco dei messaggi

```csharp
public Task<ImapPageInfo> ListMessagesByPageAsync(MailQuery query, PageInfo pageInfo, 
    PageSettings settings, CancellationToken token = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| pageInfo | PageInfo | La prossima pagina da recuperare. |
| settings | PageSettings | Le impostazioni. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapPageInfo](../../imappageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* class [PageSettings](../../pagesettings)
* interface [IAsyncImapClient](../../iasyncimapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->