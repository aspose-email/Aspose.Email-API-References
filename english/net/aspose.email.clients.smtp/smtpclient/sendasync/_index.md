---
title: SendAsync
second_title: Aspose.Email for .NET API Reference
description: Creates and sends the specified message.
type: docs
weight: 180
url: /net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SendAsync(string, string, string, string) {#sendasync_18}

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

## SendAsync(MailMessage) {#sendasync_11}

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

## SendAsync(params MailMessage[]) {#sendasync_15}

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

## SendAsync(MailMessageCollection) {#sendasync_13}

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

## SendAsync(IEnumerable&lt;MailMessage&gt;) {#sendasync_16}

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

## SendAsync(IConnection, string, string, string, string) {#sendasync_7}

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

## SendAsync(IConnection, MailMessage) {#sendasync}

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

## SendAsync(IConnection, params MailMessage[]) {#sendasync_4}

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

## SendAsync(IConnection, MailMessageCollection) {#sendasync_2}

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

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#sendasync_5}

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

## SendAsync(string, string, string, string, CancellationToken) {#sendasync_19}

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

## SendAsync(MailMessage, CancellationToken) {#sendasync_12}

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

## SendAsync(CancellationToken, params MailMessage[]) {#sendasync_20}

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

## SendAsync(MailMessageCollection, CancellationToken) {#sendasync_14}

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

## SendAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_17}

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

## SendAsync(IConnection, string, string, string, string, CancellationToken) {#sendasync_8}

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

## SendAsync(IConnection, MailMessage, CancellationToken) {#sendasync_1}

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

## SendAsync(IConnection, CancellationToken, params MailMessage[]) {#sendasync_9}

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

## SendAsync(IConnection, MailMessageCollection, CancellationToken) {#sendasync_3}

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

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_6}

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

---

## SendAsync(SmtpSend) {#sendasync_10}

```csharp
public Task SendAsync(SmtpSend parameters)
```

### See Also

* class [SmtpSend](../../../aspose.email.clients.smtp.models/smtpsend)
* class [SmtpClient](../../smtpclient)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
