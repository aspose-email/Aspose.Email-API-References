---
title: ImapClient.CopyMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Copy messages
type: docs
weight: 520
url: /net/aspose.email.clients.imap/imapclient/copymessagesasync/
---
## CopyMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) {#copymessagesasync_7}

Copy messages

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| folderName | String | Folder name where a message is to be moved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;string&gt;, string, CancellationToken) {#copymessagesasync_18}

Copy messages

```csharp
public Task CopyMessagesAsync(IEnumerable<string> uidSet, string folderName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| folderName | String | Folder name where a message is to be moved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#copymessagesasync_3}

Copy messages

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| folderName | String | Folder name where a message is to be moved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#copymessagesasync_13}

Copy messages

```csharp
public Task CopyMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| folderName | String | Folder name where a message is to be moved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, int, int, string) {#copymessagesasync}

Copy the messaeg

```csharp
public Task CopyMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(int, int, string) {#copymessagesasync_10}

Copy messages

```csharp
public Task CopyMessagesAsync(int startSequence, int endSequence, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, string, string, string) {#copymessagesasync_8}

Copy messages

```csharp
public Task CopyMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(string, string, string) {#copymessagesasync_19}

Copy messages

```csharp
public Task CopyMessagesAsync(string startUid, string endUid, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string) {#copymessagesasync_4}

Copy the messaeg

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;int&gt;, string) {#copymessagesasync_14}

Copy messages

```csharp
public Task CopyMessagesAsync(IEnumerable<int> sequenceSet, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string) {#copymessagesasync_6}

Copy messages

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;string&gt;, string) {#copymessagesasync_17}

Copy messages

```csharp
public Task CopyMessagesAsync(IEnumerable<string> uidSet, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessagesasync_2}

Copy messages

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessagesasync_12}

Copy messages

```csharp
public Task CopyMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, int, int, string, CancellationToken) {#copymessagesasync_1}

Copy the messaeg

```csharp
public Task CopyMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| folderName | String | Folder name where a message is to be moved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(int, int, string, CancellationToken) {#copymessagesasync_11}

Copy messages

```csharp
public Task CopyMessagesAsync(int startSequence, int endSequence, string folderName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| folderName | String | Folder name where a message is to be moved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, string, string, string, CancellationToken) {#copymessagesasync_9}

Copy messages

```csharp
public Task CopyMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| folderName | String | Folder name where a message is to be moved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(string, string, string, CancellationToken) {#copymessagesasync_20}

Copy messages

```csharp
public Task CopyMessagesAsync(string startUid, string endUid, string folderName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| folderName | String | Folder name where a message is to be moved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) {#copymessagesasync_5}

Copy the messaeg

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| folderName | String | Folder name where a message is to be moved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;int&gt;, string, CancellationToken) {#copymessagesasync_16}

Copy messages

```csharp
public Task CopyMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| folderName | String | Folder name where a message is to be moved |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


