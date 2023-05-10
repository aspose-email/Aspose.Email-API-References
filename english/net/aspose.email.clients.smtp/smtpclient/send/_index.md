---
title: SmtpClient.Send
second_title: Aspose.Email for .NET API Reference
description: SmtpClient method. Creates and sends the specified message
type: docs
weight: 170
url: /net/aspose.email.clients.smtp/smtpclient/send/
---
## Send(string, string, string, string) {#send_9}

Creates and sends the specified message.

```csharp
public void Send(string from, string recipients, string subject, string body)
```

| Parameter | Type | Description |
| --- | --- | --- |
| from | String | A String that contains the address of message sender. |
| recipients | String | A String that contains the address of recipients. |
| subject | String | A subject of message. |
| body | String | A body of message. |

### See Also

* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Send(MailMessage) {#send_5}

Send the specified message.

```csharp
public void Send(MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | The MailMessage that represents an email-message. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Send(params MailMessage[]) {#send_7}

Send the specified message.

```csharp
public void Send(params MailMessage[] messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | MailMessage[] | The array of MailMessage that represents an email-messages to send. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Send(MailMessageCollection) {#send_6}

Send the specified message collection.

```csharp
public void Send(MailMessageCollection messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | MailMessageCollection | The collection of messages. |

### See Also

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Send(IEnumerable&lt;MailMessage&gt;) {#send_8}

Send the specified messages.

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | IEnumerable`1 | The IEnumerator that supports a message iteration. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Send(IConnection, string, string, string, string) {#send_4}

Creates and sends the specified message.

```csharp
public void Send(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| from | String | A String that contains the address of message sender. |
| recipients | String | A String that contains the address of recipients. |
| subject | String | A subject of message. |
| body | String | A body of message. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Send(IConnection, MailMessage) {#send}

Send the specified message.

```csharp
public void Send(IConnection connection, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| message | MailMessage | The MailMessage that represents an email-message. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Send(IConnection, params MailMessage[]) {#send_2}

Send the specified message.

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | MailMessage[] | The array of MailMessage that represents an email-messages to send. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Send(IConnection, MailMessageCollection) {#send_1}

Send the specified message collection.

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | MailMessageCollection | The collection of messages. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)

---

## Send(IConnection, IEnumerable&lt;MailMessage&gt;) {#send_3}

Send the specified messages.

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | IEnumerable`1 | The IEnumerator that supports a message iteration. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)


