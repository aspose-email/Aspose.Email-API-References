---
title: Pop3Client.ListMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: Pop3Client method. Lists the messages. Gets an information for earch message
type: docs
weight: 300
url: /net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_8}

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_6}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) object. |

### Return Value

Collection of Pop3MessageInfo objects.

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields) {#listmessagesasync_2}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| fields | Pop3ListFields | The fields that we want get |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* enum [Pop3ListFields](../../pop3listfields/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery) {#listmessagesasync_3}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| fields | Pop3ListFields | The fields that we want get |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) object. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* enum [Pop3ListFields](../../pop3listfields/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_17}

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_15}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) object. |

### Return Value

Collection of Pop3MessageInfo objects.

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields) {#listmessagesasync_11}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fields | Pop3ListFields | The fields that we want get |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* enum [Pop3ListFields](../../pop3listfields/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery) {#listmessagesasync_12}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fields | Pop3ListFields | The fields that we want get |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) object. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* enum [Pop3ListFields](../../pop3listfields/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_10}

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_9}

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_7}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) object. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of Pop3MessageInfo objects.

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, CancellationToken) {#listmessagesasync_5}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| fields | Pop3ListFields | The fields that we want get |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* enum [Pop3ListFields](../../pop3listfields/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_4}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| fields | Pop3ListFields | The fields that we want get |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) object. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* enum [Pop3ListFields](../../pop3listfields/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_19}

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_18}

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_16}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) object. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of Pop3MessageInfo objects.

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, CancellationToken) {#listmessagesasync_14}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fields | Pop3ListFields | The fields that we want get |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* enum [Pop3ListFields](../../pop3listfields/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_13}

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fields | Pop3ListFields | The fields that we want get |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) object. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* enum [Pop3ListFields](../../pop3listfields/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)


