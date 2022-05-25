---
title: SendAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 180
url: /net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SmtpClient.SendAsync method (1 of 20)

Creates and sends the specified message.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body)
```

| Parameter | Type | Description |
| --- | --- | --- |
| from | String | A String that contains the address of message sender. |
| recipients | String | A String that contains the address of recipients. |
| subject | String | A subject of message. |
| body | String | A body of message. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (2 of 20)

Send the specified message.

```csharp
public Task SendAsync(MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | The MailMessage that represents an email-message. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (3 of 20)

Send the specified message.

```csharp
public Task SendAsync(params MailMessage[] messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | MailMessage[] | The array of MailMessage that represents an email-messages to send. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (4 of 20)

Send the specified message collection.

```csharp
public Task SendAsync(MailMessageCollection messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | MailMessageCollection | The collection of messages. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (5 of 20)

Send the specified messages.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | IEnumerable`1 | The IEnumerator that supports a message iteration. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (6 of 20)

Creates and sends the specified message.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| from | String | A String that contains the address of message sender. |
| recipients | String | A String that contains the address of recipients. |
| subject | String | A subject of message. |
| body | String | A body of message. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (7 of 20)

Send the specified message.

```csharp
public Task SendAsync(IConnection connection, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| message | MailMessage | The MailMessage that represents an email-message. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (8 of 20)

Send the specified message.

```csharp
public Task SendAsync(IConnection connection, params MailMessage[] messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | MailMessage[] | The array of MailMessage that represents an email-messages to send. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (9 of 20)

Send the specified message collection.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | MailMessageCollection | The collection of messages. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (10 of 20)

Send the specified messages.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | IEnumerable`1 | The IEnumerator that supports a message iteration. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (11 of 20)

Creates and sends the specified message.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| from | String | A String that contains the address of message sender. |
| recipients | String | A String that contains the address of recipients. |
| subject | String | A subject of message. |
| body | String | A body of message. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (12 of 20)

Send the specified message.

```csharp
public Task SendAsync(MailMessage message, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | The MailMessage that represents an email-message. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (13 of 20)

Send the specified message.

```csharp
public Task SendAsync(CancellationToken token, params MailMessage[] messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| token | CancellationToken | Propagates notification that operations should be canceled. |
| messages | MailMessage[] | The array of MailMessage that represents an email-messages to send. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (14 of 20)

Send the specified message collection.

```csharp
public Task SendAsync(MailMessageCollection messages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | MailMessageCollection | The collection of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (15 of 20)

Send the specified messages.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | IEnumerable`1 | The IEnumerator that supports a message iteration. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (16 of 20)

Creates and sends the specified message.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| from | String | A String that contains the address of message sender. |
| recipients | String | A String that contains the address of recipients. |
| subject | String | A subject of message. |
| body | String | A body of message. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (17 of 20)

Send the specified message.

```csharp
public Task SendAsync(IConnection connection, MailMessage message, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| message | MailMessage | The MailMessage that represents an email-message. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (18 of 20)

Send the specified message.

```csharp
public Task SendAsync(IConnection connection, CancellationToken token, 
    params MailMessage[] messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |
| messages | MailMessage[] | The array of MailMessage that represents an email-messages to send. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (19 of 20)

Send the specified message collection.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | MailMessageCollection | The collection of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

---

## SmtpClient.SendAsync method (20 of 20)

Send the specified messages.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | IEnumerable`1 | The IEnumerator that supports a message iteration. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
