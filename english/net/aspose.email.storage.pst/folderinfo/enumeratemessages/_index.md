---
title: FolderInfo.EnumerateMessages
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Retrieves MessageInfo objects from the folder
type: docs
weight: 260
url: /net/aspose.email.storage.pst/folderinfo/enumeratemessages/
---
## EnumerateMessages() {#enumeratemessages}

Retrieves [`MessageInfo`](../../messageinfo/) objects from the folder.

```csharp
public IEnumerable<MessageInfo> EnumerateMessages()
```

### Return Value

An enumerable collection of all [`MessageInfo`](../../messageinfo/) objects in the folder, excluding folder associated information (FAI) items.

## Remarks

Use this method to iterate through all messages in the folder without applying any filters or limits. Folder associated information (FAI) items, such as hidden metadata or configuration items, are not included in the returned collection.

### See Also

* class [MessageInfo](../../messageinfo/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(MailQuery) {#enumeratemessages_2}

Retrieves a collection of [`MessageInfo`](../../messageinfo/) objects that match the specified query.

```csharp
public IEnumerable<MessageInfo> EnumerateMessages(MailQuery mailQuery)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailQuery | MailQuery | The query criteria used to filter messages. |

### Return Value

An enumerable collection of [`MessageInfo`](../../messageinfo/) objects matching the query.

## Remarks

Use this method to retrieve messages that satisfy specific conditions, such as sender, subject, or date range, as defined by the *mailQuery*.

### See Also

* class [MessageInfo](../../messageinfo/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(MessageKind) {#enumeratemessages_1}

Retrieves a collection of [`MessageInfo`](../../messageinfo/) objects of the specified kind.

```csharp
public IEnumerable<MessageInfo> EnumerateMessages(MessageKind kind)
```

| Parameter | Type | Description |
| --- | --- | --- |
| kind | MessageKind | The type of items to retrieve, such as normal messages or folder associated information items. |

### Return Value

An enumerable collection of [`MessageInfo`](../../messageinfo/) objects of the specified kind.

## Remarks

Use this method to filter items based on their type, such as distinguishing between messages or Folder Associated Information items.

### See Also

* class [MessageInfo](../../messageinfo/)
* enum [MessageKind](../../messagekind/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(int, int) {#enumeratemessages_3}

Retrieves a collection of [`MessageInfo`](../../messageinfo/) objects starting from a specific index and limited to a specified count.

```csharp
public IEnumerable<MessageInfo> EnumerateMessages(int startIndex, int count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | Int32 | The zero-based index of the first message to retrieve. |
| count | Int32 | The maximum number of messages to retrieve. If set to `-1`, retrieves all messages starting from the specified *startIndex*. |

### Return Value

An enumerable collection of [`MessageInfo`](../../messageinfo/) objects starting at the specified index.

## Remarks

Use this method to fetch a subset of messages from the folder, which is useful for paginated retrieval or scenarios requiring controlled message processing. When *count* is set to `-1`, all messages from *startIndex* to the end of the folder are returned.

### See Also

* class [MessageInfo](../../messageinfo/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


