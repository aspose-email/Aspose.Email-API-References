---
title: FolderInfo.GetContents
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Gets information about the messages in the folder optionally reading a damaged message list
type: docs
weight: 280
url: /net/aspose.email.storage.pst/folderinfo/getcontents/
---
## GetContents(bool) {#getcontents_4}

Gets information about the messages in the folder, optionally reading a damaged message list.

```csharp
public MessageInfoCollection GetContents(bool tryToReadCorruptedContents)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tryToReadCorruptedContents | Boolean | `true` to try to read the list of messages even if parts of it are damaged; use it when `GetContents()` fails because the file is corrupted. `false` gives the same result as `GetContents()`. |

### Return Value

Information about the messages. Use `PersonalStorage.ExtractMessage` to load a full message.

### See Also

* class [MessageInfoCollection](../../messageinfocollection/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## GetContents() {#getcontents}

Gets information about all messages in the folder.

```csharp
public MessageInfoCollection GetContents()
```

### Return Value

Information about the messages. Use `PersonalStorage.ExtractMessage` to load a full message.

## Remarks

The whole list is read into memory. For a large folder, `EnumerateMessages` reads the messages one at a time.

### See Also

* class [MessageInfoCollection](../../messageinfocollection/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## GetContents(MessageKind) {#getcontents_1}

Gets information about the messages of the specified kind.

```csharp
public MessageInfoCollection GetContents(MessageKind kind)
```

| Parameter | Type | Description |
| --- | --- | --- |
| kind | MessageKind | Normal messages, folder associated information (FAI) items, or both. |

### Return Value

Information about the messages. Use `PersonalStorage.ExtractMessage` to load a full message.

### See Also

* class [MessageInfoCollection](../../messageinfocollection/)
* enum [MessageKind](../../messagekind/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## GetContents(MailQuery) {#getcontents_2}

Gets information about the messages that match a query.

```csharp
public MessageInfoCollection GetContents(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | The search query, built with [`PersonalStorageQueryBuilder`](../../personalstoragequerybuilder/). |

### Return Value

Information about the messages. Use `PersonalStorage.ExtractMessage` to load a full message.

### See Also

* class [MessageInfoCollection](../../messageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## GetContents(MailQuery, int, int) {#getcontents_3}

Gets information about a range of the messages that match a query.

```csharp
public MessageInfoCollection GetContents(MailQuery query, int startIndex, int count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | The search query, built with [`PersonalStorageQueryBuilder`](../../personalstoragequerybuilder/). |
| startIndex | Int32 | The zero-based index of the first message to return. |
| count | Int32 | The maximum number of messages to return. |

### Return Value

Information about the messages. Use `PersonalStorage.ExtractMessage` to load a full message.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *startIndex* is less than 0. |
| ArgumentOutOfRangeException | *startIndex* is greater than or equal to the number of messages in the folder, which includes any start index in an empty folder. |

## Remarks

If *count* is negative or greater than the number of remaining messages, all remaining messages are returned.

### See Also

* class [MessageInfoCollection](../../messageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## GetContents(int, int) {#getcontents_5}

Gets information about a range of the messages in the folder.

```csharp
public MessageInfoCollection GetContents(int startIndex, int count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | Int32 | The zero-based index of the first message to return. |
| count | Int32 | The maximum number of messages to return. |

### Return Value

Information about the messages. Use `PersonalStorage.ExtractMessage` to load a full message.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *startIndex* is less than 0. |
| ArgumentOutOfRangeException | *startIndex* is greater than or equal to the number of messages in the folder, which includes any start index in an empty folder. |

## Remarks

If *count* is negative or greater than the number of remaining messages, all remaining messages are returned.

### See Also

* class [MessageInfoCollection](../../messageinfocollection/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


