---
title: SendAsync
second_title: Aspose.Email för .NET API-referens
description: Skapar och skickar det angivna meddelandet.
type: docs
weight: 180
url: /sv/net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SendAsync(string, string, string, string) {#sendasync_18}

Skapar och skickar det angivna meddelandet.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| from | String | En sträng som innehåller adressen till meddelandeavsändaren. |
| recipients | String | En sträng som innehåller adressen till mottagarna. |
| subject | String | Ett ämne för meddelande. |
| body | String | Ett budskap. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(MailMessage) {#sendasync_11}

Skicka det angivna meddelandet.

```csharp
public Task SendAsync(MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | MailMessage | MailMessage som representerar ett e-postmeddelande. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(params MailMessage[]) {#sendasync_15}

Skicka det angivna meddelandet.

```csharp
public Task SendAsync(params MailMessage[] messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | MailMessage[] | Matrisen av MailMessage som representerar ett e-postmeddelande att skicka. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection) {#sendasync_13}

Skicka den angivna meddelandesamlingen.

```csharp
public Task SendAsync(MailMessageCollection messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | MailMessageCollection | Samlingen av meddelanden. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;) {#sendasync_16}

Skicka de angivna meddelandena.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumeratorn som stöder en meddelandeiteration. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string) {#sendasync_7}

Skapar och skickar det angivna meddelandet.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| from | String | En sträng som innehåller adressen till meddelandeavsändaren. |
| recipients | String | En sträng som innehåller adressen till mottagarna. |
| subject | String | Ett ämne för meddelande. |
| body | String | Ett budskap. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage) {#sendasync}

Skicka det angivna meddelandet.

```csharp
public Task SendAsync(IConnection connection, MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| message | MailMessage | MailMessage som representerar ett e-postmeddelande. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IConnection, params MailMessage[]) {#sendasync_4}

Skicka det angivna meddelandet.

```csharp
public Task SendAsync(IConnection connection, params MailMessage[] messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messages | MailMessage[] | Matrisen av MailMessage som representerar ett e-postmeddelande att skicka. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection) {#sendasync_2}

Skicka den angivna meddelandesamlingen.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messages | MailMessageCollection | Samlingen av meddelanden. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#sendasync_5}

Skicka de angivna meddelandena.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messages | IEnumerable`1 | IEnumeratorn som stöder en meddelandeiteration. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(string, string, string, string, CancellationToken) {#sendasync_19}

Skapar och skickar det angivna meddelandet.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| from | String | En sträng som innehåller adressen till meddelandeavsändaren. |
| recipients | String | En sträng som innehåller adressen till mottagarna. |
| subject | String | Ett ämne för meddelande. |
| body | String | Ett budskap. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(MailMessage, CancellationToken) {#sendasync_12}

Skicka det angivna meddelandet.

```csharp
public Task SendAsync(MailMessage message, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | MailMessage | MailMessage som representerar ett e-postmeddelande. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(CancellationToken, params MailMessage[]) {#sendasync_20}

Skicka det angivna meddelandet.

```csharp
public Task SendAsync(CancellationToken token, params MailMessage[] messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |
| messages | MailMessage[] | Matrisen av MailMessage som representerar ett e-postmeddelande att skicka. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection, CancellationToken) {#sendasync_14}

Skicka den angivna meddelandesamlingen.

```csharp
public Task SendAsync(MailMessageCollection messages, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | MailMessageCollection | Samlingen av meddelanden. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_17}

Skicka de angivna meddelandena.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumeratorn som stöder en meddelandeiteration. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string, CancellationToken) {#sendasync_8}

Skapar och skickar det angivna meddelandet.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| from | String | En sträng som innehåller adressen till meddelandeavsändaren. |
| recipients | String | En sträng som innehåller adressen till mottagarna. |
| subject | String | Ett ämne för meddelande. |
| body | String | Ett budskap. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage, CancellationToken) {#sendasync_1}

Skicka det angivna meddelandet.

```csharp
public Task SendAsync(IConnection connection, MailMessage message, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| message | MailMessage | MailMessage som representerar ett e-postmeddelande. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IConnection, CancellationToken, params MailMessage[]) {#sendasync_9}

Skicka det angivna meddelandet.

```csharp
public Task SendAsync(IConnection connection, CancellationToken token, 
    params MailMessage[] messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |
| messages | MailMessage[] | Matrisen av MailMessage som representerar ett e-postmeddelande att skicka. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection, CancellationToken) {#sendasync_3}

Skicka den angivna meddelandesamlingen.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messages | MailMessageCollection | Samlingen av meddelanden. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_6}

Skicka de angivna meddelandena.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messages | IEnumerable`1 | IEnumeratorn som stöder en meddelandeiteration. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## SendAsync(SmtpSend) {#sendasync_10}

```csharp
public Task SendAsync(SmtpSend parameters)
```

### Se även

* class [SmtpSend](../../../aspose.email.clients.smtp.models/smtpsend)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
