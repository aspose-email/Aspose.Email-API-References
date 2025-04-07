---
title: ImapClient.ListMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Gets the list of messages in the current folder
type: docs
weight: 890
url: /net/aspose.email.clients.imap/imapclient/listmessagesasync/
---
## ListMessagesAsync(MailQuery) {#listmessagesasync_21}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int) {#listmessagesasync_34}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int) {#listmessagesasync_22}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int) {#listmessagesasync_8}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Task object, with delegate for this operation

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(int) {#listmessagesasync_27}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Task object, with delegate for this operation

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_18}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_20}

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, CancellationToken) {#listmessagesasync_19}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_7}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long, CancellationToken) {#listmessagesasync_11}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool, CancellationToken) {#listmessagesasync_16}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_41}

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_32}

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_26}

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(string, CancellationToken) {#listmessagesasync_40}

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, CancellationToken) {#listmessagesasync_39}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_38}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(long, CancellationToken) {#listmessagesasync_30}

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| modificationSequence | Int64 | Modification sequence |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int, CancellationToken) {#listmessagesasync_14}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_5}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int, CancellationToken) {#listmessagesasync_4}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_24}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int, CancellationToken) {#listmessagesasync_35}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int, CancellationToken) {#listmessagesasync_23}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int, CancellationToken) {#listmessagesasync_9}

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

### Return Value

Task object, with delegate for this operation

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(int, CancellationToken) {#listmessagesasync_28}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_17}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string) {#listmessagesasync_12}

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_6}

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long) {#listmessagesasync_10}

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| modificationSequence | Int64 | Modification sequence |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool) {#listmessagesasync_15}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync()
```

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;) {#listmessagesasync_31}

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_25}

Gets the list of messages in the current folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(string) {#listmessagesasync_33}

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool) {#listmessagesasync_36}

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_37}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(long) {#listmessagesasync_29}

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| modificationSequence | Int64 | Modification sequence |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int) {#listmessagesasync_13}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_2}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int) {#listmessagesasync_3}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


