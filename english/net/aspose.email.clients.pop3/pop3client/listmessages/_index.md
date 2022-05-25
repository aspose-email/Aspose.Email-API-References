---
title: ListMessages
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 290
url: /net/aspose.email.clients.pop3/pop3client/listmessages/
---
## Pop3Client.ListMessages method (1 of 14)

Lists the messages. Gets an information for earch message

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<string> uniqueIdLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueIdLst | IEnumerable`1 | UniqueId list for [`Pop3MessageInfo`](../../pop3messageinfo) to retrieve from a server. |

### Return Value

Pop3MessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessages method (2 of 14)

Lists the messages. Gets an information for earch message

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<int> sequenceNumberLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber list for [`Pop3MessageInfo`](../../pop3messageinfo) to retrieve from a server. |

### Return Value

Pop3MessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessages method (3 of 14)

Lists the messages. Gets an information for earch message

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<string> uniqueIdLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueIdLst | IEnumerable`1 | UniqueId list for [`Pop3MessageInfo`](../../pop3messageinfo) to retrieve from a server. |

### Return Value

Pop3MessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessages method (4 of 14)

Lists the messages. Gets an information for earch message

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<int> sequenceNumberLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber list for [`Pop3MessageInfo`](../../pop3messageinfo) to retrieve from a server. |

### Return Value

Pop3MessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessages method (5 of 14)

Lists the messages. Gets an information for earch message

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

### Return Value

Pop3MessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessages method (6 of 14)

Lists the messages. Gets an information for earch message

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, bool closeTransaction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

### Return Value

Pop3MessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessages method (7 of 14)

Lists the messages.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, MailQuery query)
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

---

## Pop3Client.ListMessages method (8 of 14)

Lists the messages.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| fields | Pop3ListFields | The fields that we want get |

### Return Value

Pop3MessageInfoCollection

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

## Pop3Client.ListMessages method (9 of 14)

Lists the messages.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| fields | Pop3ListFields | The fields that we want get |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery) object. |

### Return Value

Pop3MessageInfoCollection

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessages method (10 of 14)

Lists the messages. Gets an information for earch message

```csharp
public Pop3MessageInfoCollection ListMessages()
```

### Return Value

Pop3MessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessages method (11 of 14)

Lists the messages. Gets an information for earch message

```csharp
public Pop3MessageInfoCollection ListMessages(bool closeTransaction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

### Return Value

Pop3MessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessages method (12 of 14)

Lists the messages.

```csharp
public Pop3MessageInfoCollection ListMessages(MailQuery query)
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

## Pop3Client.ListMessages method (13 of 14)

Lists the messages.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fields | Pop3ListFields | The fields that we want get |

### Return Value

Pop3MessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

---

## Pop3Client.ListMessages method (14 of 14)

Lists the messages.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields, bool closeTransaction, 
    MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fields | Pop3ListFields | The fields that we want get |
| closeTransaction | Boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery) object. |

### Return Value

Pop3MessageInfoCollection

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
