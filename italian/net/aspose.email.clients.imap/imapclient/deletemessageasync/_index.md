---
title: DeleteMessageAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Contrassegna un messaggio con il numero di sequenza specificato come eliminato
type: docs
weight: 570
url: /it/net/aspose.email.clients.imap/imapclient/deletemessageasync/
---
## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_4}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_12}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_16}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long) {#deletemessageasync_1}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long) {#deletemessageasync_7}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long) {#deletemessageasync_13}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long) {#deletemessageasync_19}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool) {#deletemessageasync_17}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool) {#deletemessageasync_5}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool) {#deletemessageasync_20}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool) {#deletemessageasync_8}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
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

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_3}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_11}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_15}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_23}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long, CancellationToken) {#deletemessageasync_2}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |
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

## DeleteMessageAsync(IConnection, string, long, CancellationToken) {#deletemessageasync_10}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
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

## DeleteMessageAsync(int, long, CancellationToken) {#deletemessageasync_14}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, CancellationToken) {#deletemessageasync_22}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool, CancellationToken) {#deletemessageasync_18}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool, CancellationToken) {#deletemessageasync_6}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
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

## DeleteMessageAsync(string, long, bool, CancellationToken) {#deletemessageasync_21}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
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

## DeleteMessageAsync(IConnection, string, long, bool, CancellationToken) {#deletemessageasync_9}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
