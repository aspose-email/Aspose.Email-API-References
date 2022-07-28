---
title: Send
second_title: Aspose.Email för .NET API-referens
description: Skapar och skickar det angivna meddelandet.
type: docs
weight: 170
url: /sv/net/aspose.email.clients.smtp/smtpclient/send/
---
## Send(string, string, string, string) {#send_9}

Skapar och skickar det angivna meddelandet.

```csharp
public void Send(string from, string recipients, string subject, string body)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| from | String | En sträng som innehåller adressen till meddelandeavsändaren. |
| recipients | String | En sträng som innehåller adressen till mottagarna. |
| subject | String | Ett ämne för meddelande. |
| body | String | Ett budskap. |

### Se även

* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Send(MailMessage) {#send_5}

Skicka det angivna meddelandet.

```csharp
public void Send(MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | MailMessage | MailMessage som representerar ett e-postmeddelande. |

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Send(params MailMessage[]) {#send_7}

Skicka det angivna meddelandet.

```csharp
public void Send(params MailMessage[] messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | MailMessage[] | Matrisen av MailMessage som representerar ett e-postmeddelande att skicka. |

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Send(MailMessageCollection) {#send_6}

Skicka den angivna meddelandesamlingen.

```csharp
public void Send(MailMessageCollection messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | MailMessageCollection | Samlingen av meddelanden. |

### Se även

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Send(IEnumerable&lt;MailMessage&gt;) {#send_8}

Skicka de angivna meddelandena.

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumeratorn som stöder en meddelandeiteration. |

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Send(IConnection, string, string, string, string) {#send_4}

Skapar och skickar det angivna meddelandet.

```csharp
public void Send(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| from | String | En sträng som innehåller adressen till meddelandeavsändaren. |
| recipients | String | En sträng som innehåller adressen till mottagarna. |
| subject | String | Ett ämne för meddelande. |
| body | String | Ett budskap. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Send(IConnection, MailMessage) {#send}

Skicka det angivna meddelandet.

```csharp
public void Send(IConnection connection, MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| message | MailMessage | MailMessage som representerar ett e-postmeddelande. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Send(IConnection, params MailMessage[]) {#send_2}

Skicka det angivna meddelandet.

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messages | MailMessage[] | Matrisen av MailMessage som representerar ett e-postmeddelande att skicka. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Send(IConnection, MailMessageCollection) {#send_1}

Skicka den angivna meddelandesamlingen.

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messages | MailMessageCollection | Samlingen av meddelanden. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Send(IConnection, IEnumerable&lt;MailMessage&gt;) {#send_3}

Skicka de angivna meddelandena.

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messages | IEnumerable`1 | IEnumeratorn som stöder en meddelandeiteration. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
