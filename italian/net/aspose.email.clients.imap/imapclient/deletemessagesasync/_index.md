---
title: DeleteMessagesAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Contrassegna un messaggio con lidentificatore univoco specificato come eliminato
type: docs
weight: 590
url: /it/net/aspose.email.clients.imap/imapclient/deletemessagesasync/
---
## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessagesasync_19}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long) {#deletemessagesasync_45}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long) {#deletemessagesasync_51}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_49}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_17}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_52}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_20}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int) {#deletemessagesasync}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string) {#deletemessagesasync_24}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int) {#deletemessagesasync_32}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string) {#deletemessagesasync_56}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long) {#deletemessagesasync_1}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long) {#deletemessagesasync_27}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long) {#deletemessagesasync_33}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long) {#deletemessagesasync_59}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool) {#deletemessagesasync_57}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool) {#deletemessagesasync_25}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool) {#deletemessagesasync_60}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool) {#deletemessagesasync_28}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_4}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_36}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_7}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_39}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_37}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_5}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_40}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_8}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_15}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_23}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_47}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_55}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_14}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_22}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_46}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_54}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_50}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_18}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_53}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_21}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, CancellationToken) {#deletemessagesasync_3}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, CancellationToken) {#deletemessagesasync_31}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, CancellationToken) {#deletemessagesasync_35}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, CancellationToken) {#deletemessagesasync_63}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long, CancellationToken) {#deletemessagesasync_2}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, CancellationToken) {#deletemessagesasync_30}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long, CancellationToken) {#deletemessagesasync_34}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, CancellationToken) {#deletemessagesasync_62}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool, CancellationToken) {#deletemessagesasync_58}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool, CancellationToken) {#deletemessagesasync_26}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool, CancellationToken) {#deletemessagesasync_61}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool, CancellationToken) {#deletemessagesasync_29}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_11}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_43}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_10}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_42}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_38}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_6}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_41}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_9}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#deletemessagesasync_12}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#deletemessagesasync_16}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;) {#deletemessagesasync_44}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;) {#deletemessagesasync_48}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessagesasync_13}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
