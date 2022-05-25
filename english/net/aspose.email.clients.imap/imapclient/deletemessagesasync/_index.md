---
title: DeleteMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 590
url: /net/aspose.email.clients.imap/imapclient/deletemessagesasync/
---
## ImapClient.DeleteMessagesAsync method (1 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (2 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (3 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (4 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (5 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (6 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (7 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (8 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (9 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (10 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (11 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (12 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (13 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (14 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (15 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (16 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (17 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (18 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (19 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (20 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (21 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (22 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (23 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (24 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (25 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (26 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (27 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (28 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (29 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (30 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (31 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (32 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (33 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (34 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (35 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (36 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (37 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (38 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (39 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (40 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (41 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (42 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (43 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (44 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (45 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (46 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (47 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (48 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (49 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (50 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (51 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (52 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (53 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (54 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (55 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (56 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (57 of 64)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (58 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (59 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (60 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (61 of 64)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (62 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (63 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessagesAsync method (64 of 64)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
