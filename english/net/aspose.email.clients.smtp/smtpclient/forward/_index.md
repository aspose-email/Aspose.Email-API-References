---
title: SmtpClient.Forward
second_title: Aspose.Email for .NET API Reference
description: SmtpClient method. Forwards specified message to recipient
type: docs
weight: 130
url: /net/aspose.email.clients.smtp/smtpclient/forward/
---
## Forward(IConnection, string, string, MailMessage) {#forward_2}

Forwards specified message to recipient

```csharp
public void Forward(IConnection connection, string sender, string recipient, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sender | String | Sender of the forwarded message. |
| recipient | String | Recipient of the forwarded message. |
| message | MailMessage | The message for a forwarding. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Forward(IConnection, string, MailAddressCollection, MailMessage) {#forward}

Forwards specified message to recipient

```csharp
public void Forward(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| message | MailMessage | The message for a forwarding. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Forward(string, string, MailMessage) {#forward_5}

Forwards specified message to recipient

```csharp
public void Forward(string sender, string recipient, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | String | Sender of the forwarded message. |
| recipient | String | Recipient of the forwarded message. |
| message | MailMessage | The message for a forwarding. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Forward(string, MailAddressCollection, MailMessage) {#forward_3}

Forwards specified message to recipient

```csharp
public void Forward(string sender, MailAddressCollection recipients, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| message | MailMessage | The message for a forwarding. |

### See Also

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Forward(IConnection, string, MailAddressCollection, Stream) {#forward_1}

Forwards specified message to recipient

```csharp
public void Forward(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| messageStream | Stream | The stream that represents message in eml format. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Forward(string, MailAddressCollection, Stream) {#forward_4}

Forwards specified message to recipient

```csharp
public void Forward(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| messageStream | Stream | The stream that represents message in eml format. |

### See Also

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)


