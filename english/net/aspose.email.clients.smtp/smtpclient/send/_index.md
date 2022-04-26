---
title: Send
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 170
url: /net/aspose.email.clients.smtp/smtpclient/send/
---
## SmtpClient.Send method (1 of 10)

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

* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.Send method (2 of 10)

Send the specified message.

```csharp
public void Send(MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | The MailMessage that represents an email-message. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.Send method (3 of 10)

Send the specified message.

```csharp
public void Send(params MailMessage[] messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | MailMessage[] | The array of MailMessage that represents an email-messages to send. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.Send method (4 of 10)

Send the specified message collection.

```csharp
public void Send(MailMessageCollection messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | MailMessageCollection | The collection of messages. |

### See Also

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.Send method (5 of 10)

Send the specified messages.

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | IEnumerable`1 | The IEnumerator that supports a message iteration. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.Send method (6 of 10)

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

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.Send method (7 of 10)

Send the specified message.

```csharp
public void Send(IConnection connection, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| message | MailMessage | The MailMessage that represents an email-message. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.Send method (8 of 10)

Send the specified message.

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | MailMessage[] | The array of MailMessage that represents an email-messages to send. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.Send method (9 of 10)

Send the specified message collection.

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | MailMessageCollection | The collection of messages. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.Send method (10 of 10)

Send the specified messages.

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | IEnumerable`1 | The IEnumerator that supports a message iteration. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
