---
title: SaveMessageAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1100
url: /net/aspose.email.clients.imap/imapclient/savemessageasync/
---
## ImapClient.SaveMessageAsync method (1 of 16)

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| resultStream | Stream | Stream that will receive the message |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (2 of 16)

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| resultStream | Stream | Stream that will receive the message |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (3 of 16)

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| fileName | String | The path of the local file. This cannot be a directory |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (4 of 16)

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| fileName | String | The path of the local file. This cannot be a directory |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (5 of 16)

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| resultStream | Stream | Stream that will receive the message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (6 of 16)

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| resultStream | Stream | Stream that will receive the message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (7 of 16)

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| fileName | String | The path of the local file. This cannot be a directory |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (8 of 16)

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| fileName | String | The path of the local file. This cannot be a directory |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (9 of 16)

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| resultStream | Stream | Stream that will receive the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (10 of 16)

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| resultStream | Stream | Stream that will receive the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (11 of 16)

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| fileName | String | The path of the local file. This cannot be a directory |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (12 of 16)

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| fileName | String | The path of the local file. This cannot be a directory |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (13 of 16)

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| resultStream | Stream | Stream that will receive the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (14 of 16)

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| resultStream | Stream | Stream that will receive the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (15 of 16)

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| fileName | String | The path of the local file. This cannot be a directory |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.SaveMessageAsync method (16 of 16)

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| fileName | String | The path of the local file. This cannot be a directory |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
