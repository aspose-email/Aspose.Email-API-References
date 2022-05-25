---
title: AddMessageFlagsAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 350
url: /net/aspose.email.clients.imap/imapclient/addmessageflagsasync/
---
## ImapClient.AddMessageFlagsAsync method (1 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| flags | ImapMessageFlags | The flags to be changed |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (2 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| flags | ImapMessageFlags | The flags to be removed |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (3 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (4 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| flags | ImapMessageFlags | The flags to be removed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (5 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (6 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| flags | ImapMessageFlags | The flags to be removed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (7 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| flags | ImapMessageFlags | The flags to be changed |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (8 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| flags | ImapMessageFlags | The flags to be removed |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (9 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| flags | ImapMessageFlags | The flags to be changed |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (10 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| flags | ImapMessageFlags | The flags to be removed |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (11 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (12 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| flags | ImapMessageFlags | The flags to be removed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (13 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (14 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| flags | ImapMessageFlags | The flags to be removed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (15 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| flags | ImapMessageFlags | The flags to be changed |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (16 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| flags | ImapMessageFlags | The flags to be changed |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (17 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (18 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (19 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| flags | ImapMessageFlags | The flags to be added |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (20 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | Unique identifier of a message |
| flags | ImapMessageFlags | The flags to be added |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (21 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| flags | ImapMessageFlags | The flags to be added |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (22 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | Unique identifier of a message |
| flags | ImapMessageFlags | The flags to be added |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (23 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| flags | ImapMessageFlags | The flags to be added |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (24 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | Unique identifier of a message |
| flags | ImapMessageFlags | The flags to be added |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (25 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| flags | ImapMessageFlags | The flags to be added |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (26 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | Unique identifier of a message |
| flags | ImapMessageFlags | The flags to be added |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (27 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| flags | ImapMessageFlags | The flags to be changed |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (28 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| flags | ImapMessageFlags | The flags to be removed |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (29 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| flags | ImapMessageFlags | The flags to be changed |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (30 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| flags | ImapMessageFlags | The flags to be removed |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (31 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (32 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| flags | ImapMessageFlags | The flags to be removed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (33 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (34 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| flags | ImapMessageFlags | The flags to be removed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (35 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| flags | ImapMessageFlags | The flags to be changed |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (36 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| flags | ImapMessageFlags | The flags to be removed |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (37 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| flags | ImapMessageFlags | The flags to be changed |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (38 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| flags | ImapMessageFlags | The flags to be removed |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (39 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (40 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| flags | ImapMessageFlags | The flags to be removed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (41 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (42 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| flags | ImapMessageFlags | The flags to be removed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (43 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| flags | ImapMessageFlags | The flags to be changed |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (44 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| flags | ImapMessageFlags | The flags to be changed |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (45 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (46 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| flags | ImapMessageFlags | The flags to be changed |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (47 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| flags | ImapMessageFlags | The flags to be added |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (48 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | Unique identifier of a message |
| flags | ImapMessageFlags | The flags to be added |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (49 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| flags | ImapMessageFlags | The flags to be added |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (50 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | Unique identifier of a message |
| flags | ImapMessageFlags | The flags to be added |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (51 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| flags | ImapMessageFlags | The flags to be added |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (52 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | Unique identifier of a message |
| flags | ImapMessageFlags | The flags to be added |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (53 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| flags | ImapMessageFlags | The flags to be added |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (54 of 56)

Adds the flags to the message

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | Unique identifier of a message |
| flags | ImapMessageFlags | The flags to be added |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (55 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| flags | ImapMessageFlags | The flags to be changed |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.AddMessageFlagsAsync method (56 of 56)

Adds the flags of the message

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| flags | ImapMessageFlags | The flags to be removed |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
