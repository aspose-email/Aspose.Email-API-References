---
title: FetchMessageAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Recupera il messaggio
type: docs
weight: 660
url: /it/net/aspose.email.clients.imap/imapclient/fetchmessageasync/
---
## FetchMessageAsync(IConnection, int) {#fetchmessageasync}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool) {#fetchmessageasync_1}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| ignoreAttachment | Boolean | Un valore che definisce se gli allegati non devono essere caricati. Se è impostato su`VERO` , vengono recuperate solo le intestazioni del messaggio, il corpo del messaggio e le informazioni sull'allegato. Il contenuto dell'allegato non è caricato |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(int) {#fetchmessageasync_6}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool) {#fetchmessageasync_7}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| ignoreAttachment | Boolean | Un valore che definisce se gli allegati non devono essere caricati. Se è impostato su`VERO` , vengono recuperate solo le intestazioni del messaggio, il corpo del messaggio e le informazioni sull'allegato. Il contenuto dell'allegato non è caricato |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string) {#fetchmessageasync_4}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | L'ID univoco del messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(string) {#fetchmessageasync_10}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | L'ID univoco del messaggio |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, CancellationToken) {#fetchmessageasync_3}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool, CancellationToken) {#fetchmessageasync_2}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| ignoreAttachment | Boolean | Un valore che definisce se gli allegati non devono essere caricati. Se è impostato su`VERO` , vengono recuperate solo le intestazioni del messaggio, il corpo del messaggio e le informazioni sull'allegato. Il contenuto dell'allegato non è caricato |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(int, CancellationToken) {#fetchmessageasync_9}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool, CancellationToken) {#fetchmessageasync_8}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| ignoreAttachment | Boolean | Un valore che definisce se gli allegati non devono essere caricati. Se è impostato su`VERO` , vengono recuperate solo le intestazioni del messaggio, il corpo del messaggio e le informazioni sull'allegato. Il contenuto dell'allegato non è caricato |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string, CancellationToken) {#fetchmessageasync_5}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | L'ID univoco del messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessageAsync(string, CancellationToken) {#fetchmessageasync_11}

Recupera il messaggio

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | L'ID univoco del messaggio |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
