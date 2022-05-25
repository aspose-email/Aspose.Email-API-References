---
title: ListMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 300
url: /net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## Pop3Client.ListMessagesAsync method (1 of 20)

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

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (2 of 20)

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
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery) object. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (3 of 20)

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### Return Value

Task object, with delegate for this operation

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (4 of 20)

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

### Return Value

Task object, with delegate for this operation

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (5 of 20)

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery) object. |

### Return Value

Collection of Pop3MessageInfo objects.

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (6 of 20)

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fields | Pop3ListFields | The fields that we want get |

### Return Value

Task object, with delegate for this operation

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (7 of 20)

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fields | Pop3ListFields | The fields that we want get |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery) object. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (8 of 20)

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

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (9 of 20)

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

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (10 of 20)

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery) object. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of Pop3MessageInfo objects.

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (11 of 20)

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

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (12 of 20)

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
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery) object. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (13 of 20)

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (14 of 20)

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

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (15 of 20)

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery) object. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of Pop3MessageInfo objects.

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (16 of 20)

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

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (17 of 20)

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fields | Pop3ListFields | The fields that we want get |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery) object. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (18 of 20)

Lists the messages. Gets an information for earch message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

### Return Value

Task object, with delegate for this operation

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (19 of 20)

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

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessagesAsync method (20 of 20)

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery) object. |

### Return Value

Collection of Pop3MessageInfo objects.

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
