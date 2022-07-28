---
title: ListMessagesAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Ottiene lelenco dei messaggi nella cartella corrente.
type: docs
weight: 880
url: /it/net/aspose.email.clients.imap/imapclient/listmessagesasync/
---
## ListMessagesAsync(int, CancellationToken) {#listmessagesasync_28}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* è negativo. |

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_17}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |
| modificationSequence | Int64 | Sequenza di modifica |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |
| messageExtraFields | IEnumerable`1 | Elenco di parametri extra per un messaggio che verrà richiesto. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string) {#listmessagesasync_12}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_6}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long) {#listmessagesasync_10}

Ottiene l'elenco dei messaggi nella cartella corrente che hanno una sequenza di modifica maggiore del valore specificato. Per favore, vedere di più https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| modificationSequence | Int64 | Sequenza di modifica |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool) {#listmessagesasync_15}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync()
```

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;) {#listmessagesasync_31}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Elenco di parametri extra per un messaggio che verrà richiesto. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_25}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string) {#listmessagesasync_33}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool) {#listmessagesasync_36}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_37}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |
| messageExtraFields | IEnumerable`1 | Elenco di parametri extra per un messaggio che verrà richiesto. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(long) {#listmessagesasync_29}

Ottiene l'elenco dei messaggi nella cartella corrente che hanno una sequenza di modifica maggiore del valore specificato. Per favore, vedere di più https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modificationSequence | Int64 | Sequenza di modifica |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int) {#listmessagesasync_13}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Posizione dei messaggi |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_2}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int) {#listmessagesasync_3}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_21}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int) {#listmessagesasync_34}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Posizione dei messaggi |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int) {#listmessagesasync_22}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int) {#listmessagesasync_8}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* è negativo. |

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(int) {#listmessagesasync_27}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* è negativo. |

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_18}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |
| modificationSequence | Int64 | Sequenza di modifica |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |
| messageExtraFields | IEnumerable`1 | Elenco di parametri extra per un messaggio che verrà richiesto. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_20}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, CancellationToken) {#listmessagesasync_19}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_7}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long, CancellationToken) {#listmessagesasync_11}

Ottiene l'elenco dei messaggi nella cartella corrente che hanno una sequenza di modifica maggiore del valore specificato. Per favore, vedere di più https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| modificationSequence | Int64 | Sequenza di modifica |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool, CancellationToken) {#listmessagesasync_16}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_41}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_32}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Elenco di parametri extra per un messaggio che verrà richiesto. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_26}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, CancellationToken) {#listmessagesasync_40}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, CancellationToken) {#listmessagesasync_39}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_38}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |
| messageExtraFields | IEnumerable`1 | Elenco di parametri extra per un messaggio che verrà richiesto. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(long, CancellationToken) {#listmessagesasync_30}

Ottiene l'elenco dei messaggi nella cartella corrente che hanno una sequenza di modifica maggiore del valore specificato. Per favore, vedere di più https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modificationSequence | Int64 | Sequenza di modifica |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int, CancellationToken) {#listmessagesasync_14}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Posizione dei messaggi |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_5}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int, CancellationToken) {#listmessagesasync_4}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_24}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int, CancellationToken) {#listmessagesasync_35}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Posizione dei messaggi |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int, CancellationToken) {#listmessagesasync_23}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int, CancellationToken) {#listmessagesasync_9}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* è negativo. |

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
