---
title: ImapClient.DeleteMessages
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Marks a message with the specified sequence number as deleted
type: docs
weight: 590
url: /net/aspose.email.clients.imap/imapclient/deletemessages/
---
## DeleteMessages(IConnection, IEnumerable&lt;int&gt;) {#deletemessages_6}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *sequenceSet* is null or empty. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;) {#deletemessages_8}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *uidSet* is null or empty. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;) {#deletemessages_22}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *sequenceSet* is null or empty. |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;) {#deletemessages_24}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IEnumerable<string> uidSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *uidSet* is null or empty. |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessages_7}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *sequenceSet* is null or empty. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessages_10}

Marks a message with the specified unique identifier as deleted

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *uidSet* is null or empty. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;, long) {#deletemessages_23}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *sequenceSet* is null or empty. |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long) {#deletemessages_26}

Marks a message with the specified unique identifier as deleted

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *uidSet* is null or empty. |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, bool) {#deletemessages_25}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *uidSet* is null or empty. |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessages_9}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *uidSet* is null or empty. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long, bool) {#deletemessages_27}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *uidSet* is null or empty. |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessages_11}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *uidSet* is null or empty. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int) {#deletemessages}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string) {#deletemessages_12}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(int, int) {#deletemessages_16}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(int startSequence, int endSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(string, string) {#deletemessages_28}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(string startUid, string endUid)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int, long) {#deletemessages_1}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long) {#deletemessages_14}

Marks a message with the specified unique identifier as deleted

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(int, int, long) {#deletemessages_17}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(int startSequence, int endSequence, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long) {#deletemessages_30}

Marks a message with the specified unique identifier as deleted

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(string, string, bool) {#deletemessages_29}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, bool) {#deletemessages_13}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long, bool) {#deletemessages_31}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long, bool) {#deletemessages_15}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_2}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *messageInfoSet* is null or empty. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_18}

Marks a message with the specified sequence number as deleted

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *messageInfoSet* is null or empty. |

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_4}

Marks a message with the specified unique identifier as deleted

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *messageInfoSet* is null or empty. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_20}

Marks a message with the specified unique identifier as deleted

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *messageInfoSet* is null or empty. |

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_19}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *messageInfoSet* is null or empty. |

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_3}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *messageInfoSet* is null or empty. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_21}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, 
    bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *messageInfoSet* is null or empty. |

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_5}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo for deletion |
| modificationSequence | Int64 | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | If *messageInfoSet* is null or empty. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


