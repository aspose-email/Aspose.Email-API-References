---
title: PersonalStorage.EnumerateMessages
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Enumerates the messages of the folder with the specified entry ID
type: docs
weight: 190
url: /net/aspose.email.storage.pst/personalstorage/enumeratemessages/
---
## EnumerateMessages(string) {#enumeratemessages}

Enumerates the messages of the folder with the specified entry ID.

```csharp
public IEnumerable<MessageInfo> EnumerateMessages(string entryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the folder. |

### Return Value

Information about the messages. They are read from the file as the sequence is enumerated.

### See Also

* class [MessageInfo](../../messageinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(string, int, int) {#enumeratemessages_1}

Enumerates a range of the messages of the folder with the specified entry ID.

```csharp
public IEnumerable<MessageInfo> EnumerateMessages(string entryId, int startIndex, int count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the folder. |
| startIndex | Int32 | The zero-based index of the first message to return. |
| count | Int32 | The maximum number of messages to return. |

### Return Value

Information about the messages. They are read from the file as the sequence is enumerated.

### See Also

* class [MessageInfo](../../messageinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


