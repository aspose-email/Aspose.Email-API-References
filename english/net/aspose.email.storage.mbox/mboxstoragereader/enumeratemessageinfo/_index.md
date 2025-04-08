---
title: MboxStorageReader.EnumerateMessageInfo
second_title: Aspose.Email for .NET API Reference
description: MboxStorageReader method. Exposes the enumerator which supports an iteration of messages in storage
type: docs
weight: 90
url: /net/aspose.email.storage.mbox/mboxstoragereader/enumeratemessageinfo/
---
## EnumerateMessageInfo() {#enumeratemessageinfo}

Exposes the enumerator, which supports an iteration of messages in storage.

```csharp
public IEnumerable<MboxMessageInfo> EnumerateMessageInfo()
```

### Return Value

IEnumerable, that represents an enumerator that iterates through a messages in storage.

### See Also

* class [MboxMessageInfo](../../mboxmessageinfo/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessageInfo(MailQuery) {#enumeratemessageinfo_1}

Enumerates the message information that matches the specified query.

```csharp
public IEnumerable<MboxMessageInfo> EnumerateMessageInfo(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) used to filter messages. |

### Return Value

An enumerable collection of [`MboxMessageInfo`](../../mboxmessageinfo/) instances that match the specified query. The collection may be empty if no messages match.

### See Also

* class [MboxMessageInfo](../../mboxmessageinfo/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessageInfo(int, int) {#enumeratemessageinfo_2}

Enumerates a specified number of message information entries, starting from the given index.

```csharp
public IEnumerable<MboxMessageInfo> EnumerateMessageInfo(int startIndex, int count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | Int32 | The zero-based index of the first message to retrieve. If *startIndex* is greater than or equal to the total number of items, an ArgumentOutOfRangeException is thrown. |
| count | Int32 | The maximum number of message information entries to retrieve. If set to -1, all messages from the start index will be read. |

### Return Value

An enumerable collection of [`MboxMessageInfo`](../../mboxmessageinfo/) instances starting from the specified index. The collection may be empty if there are no messages in the specified range.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when *startIndex* is greater than or equal to the total number of available messages. |

### See Also

* class [MboxMessageInfo](../../mboxmessageinfo/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)


