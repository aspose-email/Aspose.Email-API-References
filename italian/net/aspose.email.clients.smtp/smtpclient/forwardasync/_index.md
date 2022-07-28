---
title: ForwardAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Inoltra il messaggio specificato al destinatario
type: docs
weight: 140
url: /it/net/aspose.email.clients.smtp/smtpclient/forwardasync/
---
## ForwardAsync(IConnection, string, string, MailMessage) {#forwardasync_4}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sender | String | Mittente del messaggio inoltrato. |
| recipient | String | Destinatario del messaggio inoltrato. |
| message | MailMessage | Il messaggio per un inoltro. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage) {#forwardasync}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sender | String | Mittente del messaggio inoltrato. |
| recipients | MailAddressCollection | Destinatari del messaggio inoltrato. |
| message | MailMessage | Il messaggio per un inoltro. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage) {#forwardasync_10}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sender | String | Mittente del messaggio inoltrato. |
| recipient | String | Destinatario del messaggio inoltrato. |
| message | MailMessage | Il messaggio per un inoltro. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage) {#forwardasync_6}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sender | String | Mittente del messaggio inoltrato. |
| recipients | MailAddressCollection | Destinatari del messaggio inoltrato. |
| message | MailMessage | Il messaggio per un inoltro. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream) {#forwardasync_2}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sender | String | Mittente del messaggio inoltrato. |
| recipients | MailAddressCollection | Destinatari del messaggio inoltrato. |
| messageStream | Stream | Il flusso che rappresenta il messaggio in formato eml. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream) {#forwardasync_8}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sender | String | Mittente del messaggio inoltrato. |
| recipients | MailAddressCollection | Destinatari del messaggio inoltrato. |
| messageStream | Stream | Il flusso che rappresenta il messaggio in formato eml. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, string, MailMessage, CancellationToken) {#forwardasync_5}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sender | String | Mittente del messaggio inoltrato. |
| recipient | String | Destinatario del messaggio inoltrato. |
| message | MailMessage | Il messaggio per un inoltro. |
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

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_1}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sender | String | Mittente del messaggio inoltrato. |
| recipients | MailAddressCollection | Destinatari del messaggio inoltrato. |
| message | MailMessage | Il messaggio per un inoltro. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage, CancellationToken) {#forwardasync_11}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sender | String | Mittente del messaggio inoltrato. |
| recipient | String | Destinatario del messaggio inoltrato. |
| message | MailMessage | Il messaggio per un inoltro. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_7}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sender | String | Mittente del messaggio inoltrato. |
| recipients | MailAddressCollection | Destinatari del messaggio inoltrato. |
| message | MailMessage | Il messaggio per un inoltro. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_3}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sender | String | Mittente del messaggio inoltrato. |
| recipients | MailAddressCollection | Destinatari del messaggio inoltrato. |
| messageStream | Stream | Il flusso che rappresenta il messaggio in formato eml. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_9}

Inoltra il messaggio specificato al destinatario

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sender | String | Mittente del messaggio inoltrato. |
| recipients | MailAddressCollection | Destinatari del messaggio inoltrato. |
| messageStream | Stream | Il flusso che rappresenta il messaggio in formato eml. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
