---
title: DeleteMessage
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 560
url: /net/aspose.email.clients.imap/imapclient/deletemessage/
---
## ImapClient.DeleteMessage method (1 of 12)

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | Sequence number of a message |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (2 of 12)

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessage(IConnection connection, string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (3 of 12)

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessage(int sequenceNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequence number of a message |

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (4 of 12)

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessage(string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (5 of 12)

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | Sequence number of a message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (6 of 12)

Marks a message with the specified unique identifier as deleted

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (7 of 12)

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessage(int sequenceNumber, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | Sequence number of a message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (8 of 12)

Marks a message with the specified unique identifier as deleted

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (9 of 12)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (10 of 12)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (11 of 12)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.DeleteMessage method (12 of 12)

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The uid of the message |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
