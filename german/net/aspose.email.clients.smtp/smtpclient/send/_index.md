---
title: Send
second_title: Aspose.Email für .NET-API-Referenz
description: Erstellt und sendet die angegebene Nachricht.
type: docs
weight: 170
url: /de/net/aspose.email.clients.smtp/smtpclient/send/
---
## Send(string, string, string, string) {#send_9}

Erstellt und sendet die angegebene Nachricht.

```csharp
public void Send(string from, string recipients, string subject, string body)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| from | String | Ein String, der die Adresse des Absenders der Nachricht enthält. |
| recipients | String | Ein String, der die Adresse von Empfängern enthält. |
| subject | String | Ein Betreff der Nachricht. |
| body | String | Ein Nachrichtentext. |

### Siehe auch

* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Send(MailMessage) {#send_5}

Senden Sie die angegebene Nachricht.

```csharp
public void Send(MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | MailMessage | Die MailMessage, die eine E-Mail-Nachricht darstellt. |

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Send(params MailMessage[]) {#send_7}

Senden Sie die angegebene Nachricht.

```csharp
public void Send(params MailMessage[] messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | MailMessage[] | Das Array von MailMessage, das eine zu sendende E-Mail-Nachricht darstellt. |

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Send(MailMessageCollection) {#send_6}

Sendet die angegebene Nachrichtensammlung.

```csharp
public void Send(MailMessageCollection messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | MailMessageCollection | Die Sammlung von Nachrichten. |

### Siehe auch

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Send(IEnumerable&lt;MailMessage&gt;) {#send_8}

Senden Sie die angegebenen Nachrichten.

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | IEnumerable`1 | Der IEnumerator, der eine Nachrichteniteration unterstützt. |

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Send(IConnection, string, string, string, string) {#send_4}

Erstellt und sendet die angegebene Nachricht.

```csharp
public void Send(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| from | String | Ein String, der die Adresse des Absenders der Nachricht enthält. |
| recipients | String | Ein String, der die Adresse von Empfängern enthält. |
| subject | String | Ein Betreff der Nachricht. |
| body | String | Ein Nachrichtentext. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Send(IConnection, MailMessage) {#send}

Senden Sie die angegebene Nachricht.

```csharp
public void Send(IConnection connection, MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| message | MailMessage | Die MailMessage, die eine E-Mail-Nachricht darstellt. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Send(IConnection, params MailMessage[]) {#send_2}

Senden Sie die angegebene Nachricht.

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messages | MailMessage[] | Das Array von MailMessage, das eine zu sendende E-Mail-Nachricht darstellt. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Send(IConnection, MailMessageCollection) {#send_1}

Sendet die angegebene Nachrichtensammlung.

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messages | MailMessageCollection | Die Sammlung von Nachrichten. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Send(IConnection, IEnumerable&lt;MailMessage&gt;) {#send_3}

Senden Sie die angegebenen Nachrichten.

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messages | IEnumerable`1 | Der IEnumerator, der eine Nachrichteniteration unterstützt. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
