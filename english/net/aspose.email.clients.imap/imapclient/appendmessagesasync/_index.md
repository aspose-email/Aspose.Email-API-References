---
title: ImapClient.AppendMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Uploads the mail messages to the current folder
type: docs
weight: 400
url: /net/aspose.email.clients.imap/imapclient/appendmessagesasync/
---
## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_2}

Uploads the mail messages to the current folder

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder that will receive the mail message |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |

### Return Value

Task object, with delegate for this operation

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_4}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |

### Return Value

Task object, with delegate for this operation

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_6}

Uploads the mail messages to the current folder

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder that will receive the mail message |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |

### Return Value

Task object, with delegate for this operation

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_1}

Uploads the mail messages to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_3}

Uploads the mail messages to the current folder

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder that will receive the mail message |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_5}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_7}

Uploads the mail messages to the current folder

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder that will receive the mail message |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync}

Uploads the mail messages to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |

### Return Value

Task object, with delegate for this operation

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


