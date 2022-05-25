---
title: MoveMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 960
url: /net/aspose.email.clients.imap/imapclient/movemessagesasync/
---
## ImapClient.MoveMessagesAsync method (1 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (2 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
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

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (3 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (4 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, bool commitDeletions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (5 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (6 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (7 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (8 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (9 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (10 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
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

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (11 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (12 of 40)

Moves the messaeg

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (13 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (14 of 40)

Moves the messaeg

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
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

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (15 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
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

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (16 of 40)

Moves the messaeg

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (17 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (18 of 40)

Moves the messaeg

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (19 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
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

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (20 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (21 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (22 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
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

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (23 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
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

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (24 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uidSet | IEnumerable`1 | The set of UID for messages |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (25 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | The set of UID for messages |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (26 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
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

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (27 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, 
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

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (28 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (29 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | The set of ImapMessageInfo |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (30 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
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

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (31 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
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

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (32 of 40)

Moves the messaeg

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (33 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (34 of 40)

Moves the messaeg

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
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

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (35 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startSequence | Int32 | The starting sequence number of a message list |
| endSequence | Int32 | The ending sequence number of a message list |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (36 of 40)

Moves the messaeg

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, bool commitDeletions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (37 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (38 of 40)

Moves the messaeg

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (39 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | The set of sequence numbers for messages |
| folderName | String | Folder name where a message is to be moved |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.MoveMessagesAsync method (40 of 40)

Moves the message

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, bool commitDeletions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| startUid | String | The starting UID of a message list |
| endUid | String | The ending UID of a message list |
| folderName | String | Folder name where a message is to be moved |
| commitDeletions | Boolean | Specifies whether deletions should be committed. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
