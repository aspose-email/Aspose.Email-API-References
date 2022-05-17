---
title: ListMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 880
url: /net/aspose.email.clients.imap/imapclient/listmessagesasync/
---
## ImapClient.ListMessagesAsync method (1 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| modificationSequence | Int64 | Modification sequence |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (2 of 42)

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (3 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (4 of 42)

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (5 of 42)

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| modificationSequence | Int64 | Modification sequence |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (6 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (7 of 42)

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync()
```

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (8 of 42)

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (9 of 42)

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (10 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (11 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (12 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (13 of 42)

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| modificationSequence | Int64 | Modification sequence |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (14 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (15 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (16 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (17 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (18 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (19 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (20 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

## Return Value

Task object, with delegate for this operation

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (21 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

## Return Value

Task object, with delegate for this operation

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (22 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| modificationSequence | Int64 | Modification sequence |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (23 of 42)

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (24 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (25 of 42)

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (26 of 42)

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| modificationSequence | Int64 | Modification sequence |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (27 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (28 of 42)

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (29 of 42)

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (30 of 42)

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (31 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (32 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (33 of 42)

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (34 of 42)

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| modificationSequence | Int64 | Modification sequence |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (35 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (36 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (37 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (38 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (39 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (40 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (41 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessagesAsync method (42 of 42)

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
