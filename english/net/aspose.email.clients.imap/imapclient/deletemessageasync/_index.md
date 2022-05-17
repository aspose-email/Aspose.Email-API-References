---
title: DeleteMessageAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 570
url: /net/aspose.email.clients.imap/imapclient/deletemessageasync/
---
## ImapClient.DeleteMessageAsync method (1 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | Sequence number of a message |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (2 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (3 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequence number of a message |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (4 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (5 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | Sequence number of a message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (6 of 24)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (7 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequence number of a message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (8 of 24)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (9 of 24)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (10 of 24)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (11 of 24)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (12 of 24)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (13 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | Sequence number of a message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (14 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (15 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequence number of a message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (16 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (17 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | Sequence number of a message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (18 of 24)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (19 of 24)

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequence number of a message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (20 of 24)

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (21 of 24)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (22 of 24)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (23 of 24)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessageAsync method (24 of 24)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
