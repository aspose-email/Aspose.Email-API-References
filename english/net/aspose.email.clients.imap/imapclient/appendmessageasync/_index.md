---
title: AppendMessageAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 370
url: /net/aspose.email.clients.imap/imapclient/appendmessageasync/
---
## ImapClient.AppendMessageAsync method (1 of 16)

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| message | MailMessage | Mail message to be upload |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (2 of 16)

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

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (3 of 16)

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (4 of 16)

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder that will receive the mail message |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (5 of 16)

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | Mail message to be upload |

## Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (6 of 16)

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(string folderName, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder that will receive the mail message |
| message | MailMessage | Mail message to be upload |

## Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (7 of 16)

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (8 of 16)

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(string folderName, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder that will receive the mail message |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (9 of 16)

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

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (10 of 16)

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

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (11 of 16)

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

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (12 of 16)

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

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (13 of 16)

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(MailMessage message, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | Mail message to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (14 of 16)

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

## Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (15 of 16)

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public Task<string> AppendMessageAsync(string fileName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AppendMessageAsync method (16 of 16)

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(string folderName, string fileName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder that will receive the mail message |
| fileName | String | File name (*.eml) of the mail message that will be uploaded |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
