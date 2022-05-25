---
title: ListMessages
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 870
url: /net/aspose.email.clients.imap/imapclient/listmessages/
---
## ImapClient.ListMessages method (1 of 27)

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

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (2 of 27)

Gets the list of messages in the current folder

```csharp
public ImapMessageInfoCollection ListMessages()
```

### Return Value

Collection of ImapMessageInfo objects

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (3 of 27)

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

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (4 of 27)

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

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (5 of 27)

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

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (6 of 27)

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

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (7 of 27)

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

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (8 of 27)

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| modificationSequence | Int64 | Modification sequence |

### Return Value

Collection of [`ImapMessageInfo`](../../imapmessageinfo) representing the messages information.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (9 of 27)

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (10 of 27)

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (11 of 27)

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (12 of 27)

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (13 of 27)

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Messages location |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (14 of 27)

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search query. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (15 of 27)

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of [`ImapMessageInfo`](../../imapmessageinfo) representing the messages information.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (16 of 27)

Gets the list of messages in the current folder.

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maximum number of messages. |

### Return Value

Collection of [`ImapMessageInfo`](../../imapmessageinfo) representing the messages information.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* is negative. |

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (17 of 27)

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

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (18 of 27)

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

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (19 of 27)

Lists the messages. Gets an information for earch message

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| uniqueIdLst | IEnumerable`1 | UniqueId list for [`ImapMessageInfo`](../../imapmessageinfo) to retrieve from a server. |

### Return Value

ImapMessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (20 of 27)

Lists the messages. Gets an information for earch message

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder to retrieve messages. |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber list for [`ImapMessageInfo`](../../imapmessageinfo) to retrieve from a server. |

### Return Value

ImapMessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (21 of 27)

Lists the messages. Gets an information for earch message

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| uniqueIdLst | IEnumerable`1 | UniqueId list for [`ImapMessageInfo`](../../imapmessageinfo) to retrieve from a server. |

### Return Value

ImapMessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (22 of 27)

Lists the messages. Gets an information for earch message

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder to retrieve messages. |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber list for [`ImapMessageInfo`](../../imapmessageinfo) to retrieve from a server. |

### Return Value

ImapMessageInfoCollection

### Remarks

Note that messages marked as deleted are not listed

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (23 of 27)

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

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (24 of 27)

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

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (25 of 27)

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

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (26 of 27)

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

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListMessages method (27 of 27)

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| modificationSequence | Int64 | Modification sequence |

### Return Value

Collection of [`ImapMessageInfo`](../../imapmessageinfo) representing the messages information.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
