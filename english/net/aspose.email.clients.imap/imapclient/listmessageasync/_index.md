---
title: ImapClient.ListMessageAsync
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Gets information about a message
type: docs
weight: 870
url: /net/aspose.email.clients.imap/imapclient/listmessageasync/
---
## ListMessageAsync(int) {#listmessageasync_8}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(int sequenceNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, string, IEnumerable&lt;string&gt;) {#listmessageasync_5}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, string uniqueId, 
    IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, string) {#listmessageasync_4}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(string) {#listmessageasync_12}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(string, IEnumerable&lt;string&gt;) {#listmessageasync_13}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(string uniqueId, 
    IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, int, IEnumerable&lt;string&gt;, CancellationToken) {#listmessageasync_2}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, int sequenceNumber, 
    IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of message |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, int, CancellationToken) {#listmessageasync_3}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, int sequenceNumber, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(int, IEnumerable&lt;string&gt;, CancellationToken) {#listmessageasync_10}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(int sequenceNumber, 
    IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of message |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(int, CancellationToken) {#listmessageasync_11}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(int sequenceNumber, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, string, IEnumerable&lt;string&gt;, CancellationToken) {#listmessageasync_6}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, string uniqueId, 
    IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, string, CancellationToken) {#listmessageasync_7}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, string uniqueId, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(string, CancellationToken) {#listmessageasync_15}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(string uniqueId, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(string, IEnumerable&lt;string&gt;, CancellationToken) {#listmessageasync_14}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(string uniqueId, 
    IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, int, IEnumerable&lt;string&gt;) {#listmessageasync_1}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, int sequenceNumber, 
    IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of message |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, int) {#listmessageasync}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, int sequenceNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(int, IEnumerable&lt;string&gt;) {#listmessageasync_9}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(int sequenceNumber, 
    IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of message |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


