---
title: SendAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Crea e invia il messaggio specificato.
type: docs
weight: 180
url: /it/net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SendAsync(string, string, string, string) {#sendasync_18}

Crea e invia il messaggio specificato.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| from | String | Una stringa che contiene l'indirizzo del mittente del messaggio. |
| recipients | String | Una stringa che contiene l'indirizzo dei destinatari. |
| subject | String | Un oggetto del messaggio. |
| body | String | Un corpo di messaggio. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(MailMessage) {#sendasync_11}

Invia il messaggio specificato.

```csharp
public Task SendAsync(MailMessage message)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | MailMessage | Il MailMessage che rappresenta un messaggio di posta elettronica. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(params MailMessage[]) {#sendasync_15}

Invia il messaggio specificato.

```csharp
public Task SendAsync(params MailMessage[] messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messages | MailMessage[] | L'array di MailMessage che rappresenta un messaggio di posta elettronica da inviare. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection) {#sendasync_13}

Invia la raccolta di messaggi specificata.

```csharp
public Task SendAsync(MailMessageCollection messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messages | MailMessageCollection | La raccolta di messaggi. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;) {#sendasync_16}

Invia i messaggi specificati.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator che supporta un'iterazione del messaggio. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string) {#sendasync_7}

Crea e invia il messaggio specificato.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| from | String | Una stringa che contiene l'indirizzo del mittente del messaggio. |
| recipients | String | Una stringa che contiene l'indirizzo dei destinatari. |
| subject | String | Un oggetto del messaggio. |
| body | String | Un corpo di messaggio. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage) {#sendasync}

Invia il messaggio specificato.

```csharp
public Task SendAsync(IConnection connection, MailMessage message)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| message | MailMessage | Il MailMessage che rappresenta un messaggio di posta elettronica. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, params MailMessage[]) {#sendasync_4}

Invia il messaggio specificato.

```csharp
public Task SendAsync(IConnection connection, params MailMessage[] messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messages | MailMessage[] | L'array di MailMessage che rappresenta un messaggio di posta elettronica da inviare. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection) {#sendasync_2}

Invia la raccolta di messaggi specificata.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messages | MailMessageCollection | La raccolta di messaggi. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#sendasync_5}

Invia i messaggi specificati.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messages | IEnumerable`1 | IEnumerator che supporta un'iterazione del messaggio. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(string, string, string, string, CancellationToken) {#sendasync_19}

Crea e invia il messaggio specificato.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| from | String | Una stringa che contiene l'indirizzo del mittente del messaggio. |
| recipients | String | Una stringa che contiene l'indirizzo dei destinatari. |
| subject | String | Un oggetto del messaggio. |
| body | String | Un corpo di messaggio. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(MailMessage, CancellationToken) {#sendasync_12}

Invia il messaggio specificato.

```csharp
public Task SendAsync(MailMessage message, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | MailMessage | Il MailMessage che rappresenta un messaggio di posta elettronica. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(CancellationToken, params MailMessage[]) {#sendasync_20}

Invia il messaggio specificato.

```csharp
public Task SendAsync(CancellationToken token, params MailMessage[] messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |
| messages | MailMessage[] | L'array di MailMessage che rappresenta un messaggio di posta elettronica da inviare. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection, CancellationToken) {#sendasync_14}

Invia la raccolta di messaggi specificata.

```csharp
public Task SendAsync(MailMessageCollection messages, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messages | MailMessageCollection | La raccolta di messaggi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_17}

Invia i messaggi specificati.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator che supporta un'iterazione del messaggio. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string, CancellationToken) {#sendasync_8}

Crea e invia il messaggio specificato.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| from | String | Una stringa che contiene l'indirizzo del mittente del messaggio. |
| recipients | String | Una stringa che contiene l'indirizzo dei destinatari. |
| subject | String | Un oggetto del messaggio. |
| body | String | Un corpo di messaggio. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage, CancellationToken) {#sendasync_1}

Invia il messaggio specificato.

```csharp
public Task SendAsync(IConnection connection, MailMessage message, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| message | MailMessage | Il MailMessage che rappresenta un messaggio di posta elettronica. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, CancellationToken, params MailMessage[]) {#sendasync_9}

Invia il messaggio specificato.

```csharp
public Task SendAsync(IConnection connection, CancellationToken token, 
    params MailMessage[] messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |
| messages | MailMessage[] | L'array di MailMessage che rappresenta un messaggio di posta elettronica da inviare. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection, CancellationToken) {#sendasync_3}

Invia la raccolta di messaggi specificata.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messages | MailMessageCollection | La raccolta di messaggi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_6}

Invia i messaggi specificati.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messages | IEnumerable`1 | IEnumerator che supporta un'iterazione del messaggio. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## SendAsync(SmtpSend) {#sendasync_10}

```csharp
public Task SendAsync(SmtpSend parameters)
```

### Guarda anche

* class [SmtpSend](../../../aspose.email.clients.smtp.models/smtpsend)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
