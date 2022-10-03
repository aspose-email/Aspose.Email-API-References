---
title: RemoveMessageFlagsAsync
second_title: Aspose.Email for .NET API Reference
description: Removes the flags of the message
type: docs
weight: 1000
url: /net/aspose.email.clients.imap/imapclient/removemessageflagsasync/
---
## RemoveMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_47}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_43}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_19}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_15}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_46}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_42}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_18}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of set of UID for messages |
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_14}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_39}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_11}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_38}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_10}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, 
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

## RemoveMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#removemessageflagsasync}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#removemessageflagsasync_20}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(int, ImapMessageFlags) {#removemessageflagsasync_28}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(string, ImapMessageFlags) {#removemessageflagsasync_48}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#removemessageflagsasync_1}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int sequenceNumber, 
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

## RemoveMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#removemessageflagsasync_21}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence)
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

## RemoveMessageFlagsAsync(int, ImapMessageFlags, long) {#removemessageflagsasync_29}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(string, ImapMessageFlags, long) {#removemessageflagsasync_49}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
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

## RemoveMessageFlagsAsync(string, string, ImapMessageFlags) {#removemessageflagsasync_52}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(int, int, ImapMessageFlags) {#removemessageflagsasync_32}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#removemessageflagsasync_24}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## RemoveMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#removemessageflagsasync_4}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## RemoveMessageFlagsAsync(string, string, ImapMessageFlags, long) {#removemessageflagsasync_53}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(int, int, ImapMessageFlags, long) {#removemessageflagsasync_33}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#removemessageflagsasync_25}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## RemoveMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#removemessageflagsasync_5}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#removemessageflagsasync_44}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#removemessageflagsasync_40}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#removemessageflagsasync_16}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#removemessageflagsasync_12}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#removemessageflagsasync_45}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#removemessageflagsasync_41}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#removemessageflagsasync_17}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of set of UID for messages |
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#removemessageflagsasync_13}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#removemessageflagsasync_36}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#removemessageflagsasync_8}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#removemessageflagsasync_37}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#removemessageflagsasync_9}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, 
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

## RemoveMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_3}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int sequenceNumber, 
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

## RemoveMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_23}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, CancellationToken token)
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

## RemoveMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_31}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_51}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
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

## RemoveMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_2}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int sequenceNumber, 
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

## RemoveMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_22}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
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

## RemoveMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_30}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_50}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_55}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_35}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
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

---

## RemoveMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_27}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## RemoveMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_7}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## RemoveMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_54}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_34}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_26}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## RemoveMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_6}

Removes the flags of the message

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
