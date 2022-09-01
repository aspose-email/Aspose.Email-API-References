---
title: SaveMessageAsync
second_title: Aspose.Email for .NET API Reference
description: Fetches and save the message as a stream
type: docs
weight: 360
url: /net/aspose.email.clients.pop3/pop3client/savemessageasync/
---
## SaveMessageAsync(IConnection, string, Stream) {#savemessageasync_4}

Fetches and save the message as a stream

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| outputStream | Stream | Stream where message will be saved |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string) {#savemessageasync_6}

Fetches and save the message into a file

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| fileName | String | File name for message |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream) {#savemessageasync}

Fetches and save the message as a stream

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| outputStream | Stream | Stream where message will be saved |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string) {#savemessageasync_2}

Fetches and save the message into a file

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| fileName | String | File name for message |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream) {#savemessageasync_12}

Fetches and save the message as a stream

```csharp
public Task SaveMessageAsync(string uniqueId, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| outputStream | Stream | Stream where message will be saved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string) {#savemessageasync_14}

Fetches and save the message into a file

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| fileName | String | File name for message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream) {#savemessageasync_8}

Fetches and save the message as a stream

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| outputStream | Stream | Stream where message will be saved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string) {#savemessageasync_10}

Fetches and save the message into a file

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| fileName | String | File name for message |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream, CancellationToken) {#savemessageasync_5}

Fetches and save the message as a stream

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream outputStream, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| outputStream | Stream | Stream where message will be saved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string, CancellationToken) {#savemessageasync_7}

Fetches and save the message into a file

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| fileName | String | File name for message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream, CancellationToken) {#savemessageasync_1}

Fetches and save the message as a stream

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream outputStream, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| outputStream | Stream | Stream where message will be saved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string, CancellationToken) {#savemessageasync_3}

Fetches and save the message into a file

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| fileName | String | File name for message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream, CancellationToken) {#savemessageasync_13}

Fetches and save the message as a stream

```csharp
public Task SaveMessageAsync(string uniqueId, Stream outputStream, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| outputStream | Stream | Stream where message will be saved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string, CancellationToken) {#savemessageasync_15}

Fetches and save the message into a file

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| fileName | String | File name for message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream, CancellationToken) {#savemessageasync_9}

Fetches and save the message as a stream

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream outputStream, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| outputStream | Stream | Stream where message will be saved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string, CancellationToken) {#savemessageasync_11}

Fetches and save the message into a file

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| fileName | String | File name for message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
