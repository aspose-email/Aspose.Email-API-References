---
title: ListMessagesAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Elenca i messaggi. Ottiene uninformazione per ogni messaggio
type: docs
weight: 300
url: /it/net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_8}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_6}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |

### Valore di ritorno

Raccolta di oggetti Pop3MessageInfo.

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields) {#listmessagesasync_2}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| fields | Pop3ListFields | I campi che vogliamo ottenere |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery) {#listmessagesasync_3}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| fields | Pop3ListFields | I campi che vogliamo ottenere |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_17}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_15}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |

### Valore di ritorno

Raccolta di oggetti Pop3MessageInfo.

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields) {#listmessagesasync_11}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fields | Pop3ListFields | I campi che vogliamo ottenere |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery) {#listmessagesasync_12}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fields | Pop3ListFields | I campi che vogliamo ottenere |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_10}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_9}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_7}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Raccolta di oggetti Pop3MessageInfo.

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, CancellationToken) {#listmessagesasync_5}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| fields | Pop3ListFields | I campi che vogliamo ottenere |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_4}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| fields | Pop3ListFields | I campi che vogliamo ottenere |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_19}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_18}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_16}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Raccolta di oggetti Pop3MessageInfo.

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, CancellationToken) {#listmessagesasync_14}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fields | Pop3ListFields | I campi che vogliamo ottenere |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_13}

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fields | Pop3ListFields | I campi che vogliamo ottenere |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
