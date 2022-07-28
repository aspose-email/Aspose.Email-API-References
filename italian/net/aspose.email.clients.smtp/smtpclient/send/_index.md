---
title: Send
second_title: Aspose.Email per riferimento all'API .NET
description: Crea e invia il messaggio specificato.
type: docs
weight: 170
url: /it/net/aspose.email.clients.smtp/smtpclient/send/
---
## Send(string, string, string, string) {#send_9}

Crea e invia il messaggio specificato.

```csharp
public void Send(string from, string recipients, string subject, string body)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| from | String | Una stringa che contiene l'indirizzo del mittente del messaggio. |
| recipients | String | Una stringa che contiene l'indirizzo dei destinatari. |
| subject | String | Un oggetto del messaggio. |
| body | String | Un corpo di messaggio. |

### Guarda anche

* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## Send(MailMessage) {#send_5}

Invia il messaggio specificato.

```csharp
public void Send(MailMessage message)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | MailMessage | Il MailMessage che rappresenta un messaggio di posta elettronica. |

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## Send(params MailMessage[]) {#send_7}

Invia il messaggio specificato.

```csharp
public void Send(params MailMessage[] messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messages | MailMessage[] | L'array di MailMessage che rappresenta un messaggio di posta elettronica da inviare. |

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## Send(MailMessageCollection) {#send_6}

Invia la raccolta di messaggi specificata.

```csharp
public void Send(MailMessageCollection messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messages | MailMessageCollection | La raccolta di messaggi. |

### Guarda anche

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## Send(IEnumerable&lt;MailMessage&gt;) {#send_8}

Invia i messaggi specificati.

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator che supporta un'iterazione del messaggio. |

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## Send(IConnection, string, string, string, string) {#send_4}

Crea e invia il messaggio specificato.

```csharp
public void Send(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| from | String | Una stringa che contiene l'indirizzo del mittente del messaggio. |
| recipients | String | Una stringa che contiene l'indirizzo dei destinatari. |
| subject | String | Un oggetto del messaggio. |
| body | String | Un corpo di messaggio. |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## Send(IConnection, MailMessage) {#send}

Invia il messaggio specificato.

```csharp
public void Send(IConnection connection, MailMessage message)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| message | MailMessage | Il MailMessage che rappresenta un messaggio di posta elettronica. |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## Send(IConnection, params MailMessage[]) {#send_2}

Invia il messaggio specificato.

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messages | MailMessage[] | L'array di MailMessage che rappresenta un messaggio di posta elettronica da inviare. |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## Send(IConnection, MailMessageCollection) {#send_1}

Invia la raccolta di messaggi specificata.

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messages | MailMessageCollection | La raccolta di messaggi. |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

---

## Send(IConnection, IEnumerable&lt;MailMessage&gt;) {#send_3}

Invia i messaggi specificati.

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messages | IEnumerable`1 | IEnumerator che supporta un'iterazione del messaggio. |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* spazio dei nomi [Aspose.Email.Clients.Smtp](../../smtpclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
