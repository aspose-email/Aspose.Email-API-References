---
title: Forward
second_title: Aspose.Email för .NET API-referens
description: Vidarebefordrar specificerat meddelande till recipient
type: docs
weight: 130
url: /sv/net/aspose.email.clients.smtp/smtpclient/forward/
---
## Forward(IConnection, string, string, MailMessage) {#forward_2}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public void Forward(IConnection connection, string sender, string recipient, MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipient | String | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Forward(IConnection, string, MailAddressCollection, MailMessage) {#forward}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public void Forward(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Forward(string, string, MailMessage) {#forward_5}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public void Forward(string sender, string recipient, MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipient | String | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Forward(string, MailAddressCollection, MailMessage) {#forward_3}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public void Forward(string sender, MailAddressCollection recipients, MailMessage message)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| message | MailMessage | Meddelandet för vidarebefordran. |

### Se även

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Forward(IConnection, string, MailAddressCollection, Stream) {#forward_1}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public void Forward(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| messageStream | Stream | Strömmen som representerar meddelande i eml-format. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

---

## Forward(string, MailAddressCollection, Stream) {#forward_4}

Vidarebefordrar specificerat meddelande till recipient

```csharp
public void Forward(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | String | Avsändare av det vidarebefordrade meddelandet. |
| recipients | MailAddressCollection | Mottagare av det vidarebefordrade meddelandet. |
| messageStream | Stream | Strömmen som representerar meddelande i eml-format. |

### Se även

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namnutrymme [Aspose.Email.Clients.Smtp](../../smtpclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
