---
title: ImapClient.ListMessages
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Lists the messages. Gets an information for earch message
type: docs
weight: 880
url: /net/aspose.email.clients.imap/imapclient/listmessages/
---
## ListMessages(IConnection, string, ImapListFields, int) {#listmessages_8}

Lists the messages. Gets an information for earch message

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    ImapListFields fieldsList, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| fieldsList | ImapListFields | Fields that may be retrieved from the server. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

ImapMessageInfoCollection

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* enum [ImapListFields](../../imaplistfields/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;string&gt;) {#listmessages_26}

Lists the messages. Gets an information for earch message

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| uniqueIdLst | IEnumerable`1 | UniqueId list for [`ImapMessageInfo`](../../imapmessageinfo/) to retrieve from a server. |

### Return Value

ImapMessageInfoCollection

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;int&gt;) {#listmessages_25}

Lists the messages. Gets an information for earch message

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber list for [`ImapMessageInfo`](../../imapmessageinfo/) to retrieve from a server. |

### Return Value

ImapMessageInfoCollection

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;string&gt;) {#listmessages_13}

Lists the messages. Gets an information for earch message

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| uniqueIdLst | IEnumerable`1 | UniqueId list for [`ImapMessageInfo`](../../imapmessageinfo/) to retrieve from a server. |

### Return Value

ImapMessageInfoCollection

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;int&gt;) {#listmessages_12}

Lists the messages. Gets an information for earch message

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber list for [`ImapMessageInfo`](../../imapmessageinfo/) to retrieve from a server. |

### Return Value

ImapMessageInfoCollection

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessages_11}

Gets the list of messages in the specified folder

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| modificationSequence | Int64 | Modification sequence |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Gets the list of messages in the current folder

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, string) {#listmessages_7}

Gets the list of messages in the specified folder

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_4}

Gets the list of messages in the current folder

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, long) {#listmessages_6}

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| modificationSequence | Int64 | Modification sequence |

### Return Value

Collection of [`ImapMessageInfo`](../../imapmessageinfo/) representing the messages information.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, bool) {#listmessages_10}

Gets the list of messages in the specified folder

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Gets the list of messages in the current folder

```csharp
public ImapMessageInfoCollection ListMessages()
```

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_19}

Gets the list of messages in the current folder

```csharp
public ImapMessageInfoCollection ListMessages(IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_16}

Gets the list of messages in the current folder

```csharp
public ImapMessageInfoCollection ListMessages(bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string) {#listmessages_20}

Gets the list of messages in the specified folder

```csharp
public ImapMessageInfoCollection ListMessages(string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_23}

Gets the list of messages in the specified folder

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, bool, IEnumerable&lt;string&gt;) {#listmessages_24}

Gets the list of messages in the specified folder

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively, 
    IEnumerable<string> messageExtraFields)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| retrieveRecursively | Boolean | Indicates, if messages have to be retrieved recursively. |
| messageExtraFields | IEnumerable`1 | List of extra parameters for a message wich will be requested. |

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(long) {#listmessages_18}

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| modificationSequence | Int64 | Modification sequence |

### Return Value

Collection of [`ImapMessageInfo`](../../imapmessageinfo/) representing the messages information.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, MailQuery, int) {#listmessages_9}

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_2}

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery, int) {#listmessages_3}

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_14}

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, int) {#listmessages_22}

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(MailQuery, int) {#listmessages_15}

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IConnection, int) {#listmessages_5}

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of [`ImapMessageInfo`](../../imapmessageinfo/) representing the messages information.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(int) {#listmessages_17}

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of [`ImapMessageInfo`](../../imapmessageinfo/) representing the messages information.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, ImapListFields, int) {#listmessages_21}

Lists the messages. Gets an information for earch message

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, ImapListFields fieldsList, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| fieldsList | ImapListFields | Fields that may be retrieved from the server. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

ImapMessageInfoCollection

## Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* enum [ImapListFields](../../imaplistfields/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


