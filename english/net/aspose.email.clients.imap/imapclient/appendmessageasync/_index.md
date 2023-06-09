---
title: ImapClient.AppendMessageAsync
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Uploads the mail message to the current folder If current folder hasnt been specified default folder is used
type: docs
weight: 380
url: /net/aspose.email.clients.imap/imapclient/appendmessageasync/
---
## AppendMessageAsync(IConnection, MailMessage) {#appendmessageasync}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| message | MailMessage | Mail message to be upload |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, MailMessage) {#appendmessageasync_3}

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, 
    MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder that will receive the mail message |
| message | MailMessage | Mail message to be upload |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string) {#appendmessageasync_2}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, string) {#appendmessageasync_5}

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder that will receive the mail message |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(MailMessage) {#appendmessageasync_8}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | Mail message to be upload |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(string, MailMessage) {#appendmessageasync_11}

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(string folderName, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder that will receive the mail message |
| message | MailMessage | Mail message to be upload |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(string) {#appendmessageasync_10}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(string, string) {#appendmessageasync_13}

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(string folderName, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder that will receive the mail message |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, MailMessage, CancellationToken) {#appendmessageasync_1}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, MailMessage message, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| message | MailMessage | Mail message to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, MailMessage, CancellationToken) {#appendmessageasync_4}

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, 
    MailMessage message, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder that will receive the mail message |
| message | MailMessage | Mail message to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, CancellationToken) {#appendmessageasync_7}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string fileName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, string, CancellationToken) {#appendmessageasync_6}

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, string fileName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder that will receive the mail message |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(MailMessage, CancellationToken) {#appendmessageasync_9}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(MailMessage message, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | Mail message to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(string, MailMessage, CancellationToken) {#appendmessageasync_12}

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(string folderName, MailMessage message, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder that will receive the mail message |
| message | MailMessage | Mail message to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(string, CancellationToken) {#appendmessageasync_15}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(string fileName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(string, string, CancellationToken) {#appendmessageasync_14}

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(string folderName, string fileName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder that will receive the mail message |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


