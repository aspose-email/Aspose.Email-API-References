---
title: ImapClient.DeleteMessageAsync
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please read more https//tools.ietf.org/html/rfc4315
type: docs
weight: 580
url: /net/aspose.email.clients.imap/imapclient/deletemessageasync/
---
## DeleteMessageAsync(IConnection, string, long, bool, CancellationToken) {#deletemessageasync_9}

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

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | Sequence number of a message |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_4}

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_12}

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequence number of a message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_16}

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long) {#deletemessageasync_1}

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

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long) {#deletemessageasync_7}

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long) {#deletemessageasync_13}

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequence number of a message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long) {#deletemessageasync_19}

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool) {#deletemessageasync_17}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool) {#deletemessageasync_5}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool) {#deletemessageasync_20}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool) {#deletemessageasync_8}

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

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_3}

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | Sequence number of a message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_11}

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_15}

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequence number of a message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_23}

Marks a message with the specified sequence number as deleted

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long, CancellationToken) {#deletemessageasync_2}

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

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, CancellationToken) {#deletemessageasync_10}

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

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long, CancellationToken) {#deletemessageasync_14}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, CancellationToken) {#deletemessageasync_22}

Marks a message with the specified unique identifier as deleted

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool, CancellationToken) {#deletemessageasync_18}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool, CancellationToken) {#deletemessageasync_6}

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

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool, CancellationToken) {#deletemessageasync_21}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


