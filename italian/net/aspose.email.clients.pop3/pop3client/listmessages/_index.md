---
title: ListMessages
second_title: Aspose.Email per riferimento all'API .NET
description: Elenca i messaggi. Ottiene uninformazione per ogni messaggio
type: docs
weight: 290
url: /it/net/aspose.email.clients.pop3/pop3client/listmessages/
---
## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_13}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<string> uniqueIdLst)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueIdLst | IEnumerable`1 | Elenco di ID univoci per[`Pop3MessageInfo`](../../pop3messageinfo) per recuperare da un server. |

### Valore di ritorno

Pop3MessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;int&gt;) {#listmessages_12}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<int> sequenceNumberLst)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumberLst | IEnumerable`1 | sequenzaNumero elenco per[`Pop3MessageInfo`](../../pop3messageinfo) per recuperare da un server. |

### Valore di ritorno

Pop3MessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;string&gt;) {#listmessages_7}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<string> uniqueIdLst)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueIdLst | IEnumerable`1 | Elenco di ID univoci per[`Pop3MessageInfo`](../../pop3messageinfo) per recuperare da un server. |

### Valore di ritorno

Pop3MessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;int&gt;) {#listmessages_6}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<int> sequenceNumberLst)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumberLst | IEnumerable`1 | sequenzaNumero elenco per[`Pop3MessageInfo`](../../pop3messageinfo) per recuperare da un server. |

### Valore di ritorno

Pop3MessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |

### Valore di ritorno

Pop3MessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_5}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, bool closeTransaction)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |

### Valore di ritorno

Pop3MessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_4}

Elenca i messaggi.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, MailQuery query)
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

## ListMessages(IConnection, Pop3ListFields) {#listmessages_2}

Elenca i messaggi.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| fields | Pop3ListFields | I campi che vogliamo ottenere |

### Valore di ritorno

Pop3MessageInfoCollection

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

## ListMessages(IConnection, Pop3ListFields, bool, MailQuery) {#listmessages_3}

Elenca i messaggi.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| fields | Pop3ListFields | I campi che vogliamo ottenere |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |

### Valore di ritorno

Pop3MessageInfoCollection

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Pop3MessageInfoCollection ListMessages()
```

### Valore di ritorno

Pop3MessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_11}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public Pop3MessageInfoCollection ListMessages(bool closeTransaction)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |

### Valore di ritorno

Pop3MessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_10}

Elenca i messaggi.

```csharp
public Pop3MessageInfoCollection ListMessages(MailQuery query)
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

## ListMessages(Pop3ListFields) {#listmessages_8}

Elenca i messaggi.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fields | Pop3ListFields | I campi che vogliamo ottenere |

### Valore di ritorno

Pop3MessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields, bool, MailQuery) {#listmessages_9}

Elenca i messaggi.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields, bool closeTransaction, 
    MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fields | Pop3ListFields | I campi che vogliamo ottenere |
| closeTransaction | Boolean | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |

### Valore di ritorno

Pop3MessageInfoCollection

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../pop3client)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
