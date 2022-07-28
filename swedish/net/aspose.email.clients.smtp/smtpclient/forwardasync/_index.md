---
title: ForwardAsync
second_title: Aspose.Email för .NET API-referens
description: Vidarebefordrar specificerat meddelande till recipient
type: docs
weight: 140
url: /sv/net/aspose.email.clients.smtp/smtpclient/forwardasync/
---
## ForwardAsync(IConnection, string, string, MailMessage) {#forwardasync_4}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipient | String | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage) {#forwardasync}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage) {#forwardasync_10}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipient | String | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage) {#forwardasync_6}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream) {#forwardasync_2}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| messageStream | Stream | Strömmen som representerar meddelande i eml-format. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream) {#forwardasync_8}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| messageStream | Stream | Strömmen som representerar meddelande i eml-format. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, string, MailMessage, CancellationToken) {#forwardasync_5}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipient | String | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |
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

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_1}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage, CancellationToken) {#forwardasync_11}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipient | String | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_7}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_3}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| messageStream | Stream | Strömmen som representerar meddelande i eml-format. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_9}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| messageStream | Stream | Strömmen som representerar meddelande i eml-format. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
