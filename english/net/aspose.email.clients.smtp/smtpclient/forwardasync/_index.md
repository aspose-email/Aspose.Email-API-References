---
title: SmtpClient.ForwardAsync
second_title: Aspose.Email for .NET API Reference
description: SmtpClient method. Forwards specified message to recipient
type: docs
weight: 140
url: /net/aspose.email.clients.smtp/smtpclient/forwardasync/
---
## ForwardAsync(IConnection, string, string, MailMessage) {#forwardasync_4}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sender | String | Sender of the forwarded message. |
| recipient | String | Recipient of the forwarded message. |
| message | MailMessage | The message for a forwarding. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage) {#forwardasync}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| message | MailMessage | The message for a forwarding. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage) {#forwardasync_10}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | String | Sender of the forwarded message. |
| recipient | String | Recipient of the forwarded message. |
| message | MailMessage | The message for a forwarding. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage) {#forwardasync_6}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| message | MailMessage | The message for a forwarding. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream) {#forwardasync_2}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| messageStream | Stream | The stream that represents message in eml format. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream) {#forwardasync_8}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| messageStream | Stream | The stream that represents message in eml format. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, string, MailMessage, CancellationToken) {#forwardasync_5}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sender | String | Sender of the forwarded message. |
| recipient | String | Recipient of the forwarded message. |
| message | MailMessage | The message for a forwarding. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_1}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| message | MailMessage | The message for a forwarding. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage, CancellationToken) {#forwardasync_11}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | String | Sender of the forwarded message. |
| recipient | String | Recipient of the forwarded message. |
| message | MailMessage | The message for a forwarding. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_7}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| message | MailMessage | The message for a forwarding. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_3}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| messageStream | Stream | The stream that represents message in eml format. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_9}

Forwards specified message to recipient

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | String | Sender of the forwarded message. |
| recipients | MailAddressCollection | Recipients of the forwarded message. |
| messageStream | Stream | The stream that represents message in eml format. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)


