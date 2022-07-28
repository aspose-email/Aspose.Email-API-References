---
title: AppendMessagesAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Carica i messaggi di posta nella cartella corrente
type: docs
weight: 390
url: /it/net/aspose.email.clients.imap/imapclient/appendmessagesasync/
---
## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_2}

Carica i messaggi di posta nella cartella corrente

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella che riceverà il messaggio di posta |
| messages | IEnumerable`1 | Enumerazione dei messaggi di posta elettronica da caricare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_4}

Carica il messaggio di posta nella cartella corrente Se la cartella corrente non è stata specificata viene utilizzata la cartella predefinita.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messages | IEnumerable`1 | Enumerazione dei messaggi di posta elettronica da caricare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_6}

Carica i messaggi di posta nella cartella corrente

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella che riceverà il messaggio di posta |
| messages | IEnumerable`1 | Enumerazione dei messaggi di posta elettronica da caricare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_1}

Carica i messaggi di posta nella cartella corrente Se la cartella corrente non è stata specificata viene utilizzata la cartella predefinita.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messages | IEnumerable`1 | Enumerazione dei messaggi di posta elettronica da caricare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_3}

Carica i messaggi di posta nella cartella corrente

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella che riceverà il messaggio di posta |
| messages | IEnumerable`1 | Enumerazione dei messaggi di posta elettronica da caricare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_5}

Carica il messaggio di posta nella cartella corrente Se la cartella corrente non è stata specificata viene utilizzata la cartella predefinita.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messages | IEnumerable`1 | Enumerazione dei messaggi di posta elettronica da caricare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_7}

Carica i messaggi di posta nella cartella corrente

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella che riceverà il messaggio di posta |
| messages | IEnumerable`1 | Enumerazione dei messaggi di posta elettronica da caricare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync}

Carica i messaggi di posta nella cartella corrente Se la cartella corrente non è stata specificata viene utilizzata la cartella predefinita.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messages | IEnumerable`1 | Enumerazione dei messaggi di posta elettronica da caricare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
