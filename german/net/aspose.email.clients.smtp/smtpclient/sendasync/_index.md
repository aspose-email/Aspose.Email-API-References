---
title: SendAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Erstellt und sendet die angegebene Nachricht.
type: docs
weight: 180
url: /de/net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SendAsync(string, string, string, string) {#sendasync_18}

Erstellt und sendet die angegebene Nachricht.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| from | String | Ein String, der die Adresse des Absenders der Nachricht enthält. |
| recipients | String | Ein String, der die Adresse von Empfängern enthält. |
| subject | String | Ein Betreff der Nachricht. |
| body | String | Ein Nachrichtentext. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(MailMessage) {#sendasync_11}

Senden Sie die angegebene Nachricht.

```csharp
public Task SendAsync(MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | MailMessage | Die MailMessage, die eine E-Mail-Nachricht darstellt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(params MailMessage[]) {#sendasync_15}

Senden Sie die angegebene Nachricht.

```csharp
public Task SendAsync(params MailMessage[] messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | MailMessage[] | Das Array von MailMessage, das eine zu sendende E-Mail-Nachricht darstellt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection) {#sendasync_13}

Sendet die angegebene Nachrichtensammlung.

```csharp
public Task SendAsync(MailMessageCollection messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | MailMessageCollection | Die Sammlung von Nachrichten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;) {#sendasync_16}

Senden Sie die angegebenen Nachrichten.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | IEnumerable`1 | Der IEnumerator, der eine Nachrichteniteration unterstützt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string) {#sendasync_7}

Erstellt und sendet die angegebene Nachricht.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| from | String | Ein String, der die Adresse des Absenders der Nachricht enthält. |
| recipients | String | Ein String, der die Adresse von Empfängern enthält. |
| subject | String | Ein Betreff der Nachricht. |
| body | String | Ein Nachrichtentext. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage) {#sendasync}

Senden Sie die angegebene Nachricht.

```csharp
public Task SendAsync(IConnection connection, MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| message | MailMessage | Die MailMessage, die eine E-Mail-Nachricht darstellt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IConnection, params MailMessage[]) {#sendasync_4}

Senden Sie die angegebene Nachricht.

```csharp
public Task SendAsync(IConnection connection, params MailMessage[] messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messages | MailMessage[] | Das Array von MailMessage, das eine zu sendende E-Mail-Nachricht darstellt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection) {#sendasync_2}

Sendet die angegebene Nachrichtensammlung.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messages | MailMessageCollection | Die Sammlung von Nachrichten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#sendasync_5}

Senden Sie die angegebenen Nachrichten.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messages | IEnumerable`1 | Der IEnumerator, der eine Nachrichteniteration unterstützt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(string, string, string, string, CancellationToken) {#sendasync_19}

Erstellt und sendet die angegebene Nachricht.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| from | String | Ein String, der die Adresse des Absenders der Nachricht enthält. |
| recipients | String | Ein String, der die Adresse von Empfängern enthält. |
| subject | String | Ein Betreff der Nachricht. |
| body | String | Ein Nachrichtentext. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(MailMessage, CancellationToken) {#sendasync_12}

Senden Sie die angegebene Nachricht.

```csharp
public Task SendAsync(MailMessage message, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | MailMessage | Die MailMessage, die eine E-Mail-Nachricht darstellt. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(CancellationToken, params MailMessage[]) {#sendasync_20}

Senden Sie die angegebene Nachricht.

```csharp
public Task SendAsync(CancellationToken token, params MailMessage[] messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |
| messages | MailMessage[] | Das Array von MailMessage, das eine zu sendende E-Mail-Nachricht darstellt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection, CancellationToken) {#sendasync_14}

Sendet die angegebene Nachrichtensammlung.

```csharp
public Task SendAsync(MailMessageCollection messages, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | MailMessageCollection | Die Sammlung von Nachrichten. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_17}

Senden Sie die angegebenen Nachrichten.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | IEnumerable`1 | Der IEnumerator, der eine Nachrichteniteration unterstützt. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string, CancellationToken) {#sendasync_8}

Erstellt und sendet die angegebene Nachricht.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| from | String | Ein String, der die Adresse des Absenders der Nachricht enthält. |
| recipients | String | Ein String, der die Adresse von Empfängern enthält. |
| subject | String | Ein Betreff der Nachricht. |
| body | String | Ein Nachrichtentext. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage, CancellationToken) {#sendasync_1}

Senden Sie die angegebene Nachricht.

```csharp
public Task SendAsync(IConnection connection, MailMessage message, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| message | MailMessage | Die MailMessage, die eine E-Mail-Nachricht darstellt. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IConnection, CancellationToken, params MailMessage[]) {#sendasync_9}

Senden Sie die angegebene Nachricht.

```csharp
public Task SendAsync(IConnection connection, CancellationToken token, 
    params MailMessage[] messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |
| messages | MailMessage[] | Das Array von MailMessage, das eine zu sendende E-Mail-Nachricht darstellt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection, CancellationToken) {#sendasync_3}

Sendet die angegebene Nachrichtensammlung.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messages | MailMessageCollection | Die Sammlung von Nachrichten. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_6}

Senden Sie die angegebenen Nachrichten.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messages | IEnumerable`1 | Der IEnumerator, der eine Nachrichteniteration unterstützt. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## SendAsync(SmtpSend) {#sendasync_10}

```csharp
public Task SendAsync(SmtpSend parameters)
```

### Siehe auch

* class [SmtpSend](../../../aspose.email.clients.smtp.models/smtpsend)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
