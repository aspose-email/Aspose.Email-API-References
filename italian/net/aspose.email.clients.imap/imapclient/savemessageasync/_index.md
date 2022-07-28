---
title: SaveMessageAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in uno stream fornito
type: docs
weight: 1100
url: /it/net/aspose.email.clients.imap/imapclient/savemessageasync/
---
## SaveMessageAsync(IConnection, int, Stream) {#savemessageasync}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in uno stream fornito

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| resultStream | Stream | Stream che riceverà il messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream) {#savemessageasync_4}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in uno stream fornito

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | L'ID univoco del messaggio |
| resultStream | Stream | Stream che riceverà il messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string) {#savemessageasync_6}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in un file locale

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | L'ID univoco del messaggio |
| fileName | String | Il percorso del file locale. Questa non può essere una directory |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string) {#savemessageasync_2}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in un file locale

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| fileName | String | Il percorso del file locale. Questa non può essere una directory |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream) {#savemessageasync_8}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in uno stream fornito

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| resultStream | Stream | Stream che riceverà il messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream) {#savemessageasync_12}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in uno stream fornito

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | L'ID univoco del messaggio |
| resultStream | Stream | Stream che riceverà il messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string) {#savemessageasync_14}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in un file locale

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | L'ID univoco del messaggio |
| fileName | String | Il percorso del file locale. Questa non può essere una directory |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string) {#savemessageasync_10}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in un file locale

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| fileName | String | Il percorso del file locale. Questa non può essere una directory |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream, CancellationToken) {#savemessageasync_1}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in uno stream fornito

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| resultStream | Stream | Stream che riceverà il messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream, CancellationToken) {#savemessageasync_5}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in uno stream fornito

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | L'ID univoco del messaggio |
| resultStream | Stream | Stream che riceverà il messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string, CancellationToken) {#savemessageasync_7}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in un file locale

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | L'ID univoco del messaggio |
| fileName | String | Il percorso del file locale. Questa non può essere una directory |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string, CancellationToken) {#savemessageasync_3}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in un file locale

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| fileName | String | Il percorso del file locale. Questa non può essere una directory |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream, CancellationToken) {#savemessageasync_9}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in uno stream fornito

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| resultStream | Stream | Stream che riceverà il messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream, CancellationToken) {#savemessageasync_13}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in uno stream fornito

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | L'ID univoco del messaggio |
| resultStream | Stream | Stream che riceverà il messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string, CancellationToken) {#savemessageasync_15}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in un file locale

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | L'ID univoco del messaggio |
| fileName | String | Il percorso del file locale. Questa non può essere una directory |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string, CancellationToken) {#savemessageasync_11}

Scarica il messaggio con il numero di sequenza specificato e ne scrive i dati in un file locale

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| fileName | String | Il percorso del file locale. Questa non può essere una directory |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
