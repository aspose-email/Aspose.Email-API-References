---
title: CommitDeletesAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 470
url: /net/aspose.email.clients.imap/imapclient/commitdeletesasync/
---
## ImapClient.CommitDeletesAsync method (1 of 20)

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid)
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

## ImapClient.CommitDeletesAsync method (2 of 20)

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | Set of unique identifiers for messages |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (3 of 20)

Commit the deletions

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of a message |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (4 of 20)

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid)
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

## ImapClient.CommitDeletesAsync method (5 of 20)

Commit the deletions

```csharp
public Task CommitDeletesAsync(IConnection connection, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (6 of 20)

Commit the deletions

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sleep | Int32 | Wait time complete the operation in milliseconds |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (7 of 20)

Commit the deletions

```csharp
public Task CommitDeletesAsync(CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (8 of 20)

Commit the deletions

```csharp
public Task CommitDeletesAsync(int sleep, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sleep | Int32 | Wait time complete the operation in milliseconds |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (9 of 20)

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Set of unique identifiers for messages |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (10 of 20)

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of a message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (11 of 20)

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid, CancellationToken token)
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

## ImapClient.CommitDeletesAsync method (12 of 20)

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | Set of unique identifiers for messages |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (13 of 20)

Commit the deletions

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of a message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (14 of 20)

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid, 
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

## ImapClient.CommitDeletesAsync method (15 of 20)

Commit the deletions

```csharp
public Task CommitDeletesAsync(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (16 of 20)

Commit the deletions

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sleep | Int32 | Wait time complete the operation in milliseconds |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (17 of 20)

Commit the deletions

```csharp
public Task CommitDeletesAsync()
```

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (18 of 20)

Commit the deletions

```csharp
public Task CommitDeletesAsync(int sleep)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sleep | Int32 | Wait time complete the operation in milliseconds |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (19 of 20)

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Set of unique identifiers for messages |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.CommitDeletesAsync method (20 of 20)

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of a message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
