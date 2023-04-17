---
title: OlmFolder.EnumerateMessages
second_title: Aspose.Email for .NET API Reference
description: OlmFolder method. Exposes the enumerator which supports an iteration of messages in folder
type: docs
weight: 70
url: /net/aspose.email.storage.olm/olmfolder/enumeratemessages/
---
## EnumerateMessages() {#enumeratemessages}

Exposes the enumerator, which supports an iteration of messages in folder.

```csharp
public IEnumerable<OlmMessageInfo> EnumerateMessages()
```

### Return Value

IEnumerable, that represents an enumerator that iterates through a messages in folder.

### See Also

* class [OlmMessageInfo](../../olmmessageinfo/)
* class [OlmFolder](../)
* namespace [Aspose.Email.Storage.Olm](../../olmfolder/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(int, int) {#enumeratemessages_2}

Exposes the enumerator, which supports an iteration of messages in folder.

```csharp
public IEnumerable<OlmMessageInfo> EnumerateMessages(int startIndex, int count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | Int32 | The start message index. |
| count | Int32 | The number of messages that will be retrieved. |

### Return Value

IEnumerable, that represents an enumerator that iterates through a messages in folder.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | throws, if startIndex less than 0. |
| ArgumentOutOfRangeException | throws, if startIndex more or equal to total message count that folder contains. |

## Remarks

If "count" param is less than 0 or more than remained message count then remained message count will be returned.

### See Also

* class [OlmMessageInfo](../../olmmessageinfo/)
* class [OlmFolder](../)
* namespace [Aspose.Email.Storage.Olm](../../olmfolder/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(MailQuery) {#enumeratemessages_1}

Exposes the enumerator, which supports an iteration of messages in folder.

```csharp
public IEnumerable<OlmMessageInfo> EnumerateMessages(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |

### Return Value

IEnumerable, that represents an enumerator that iterates through a messages in folder.

### See Also

* class [OlmMessageInfo](../../olmmessageinfo/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [OlmFolder](../)
* namespace [Aspose.Email.Storage.Olm](../../olmfolder/)
* assembly [Aspose.Email](../../../)


