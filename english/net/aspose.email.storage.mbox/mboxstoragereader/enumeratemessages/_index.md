---
title: MboxStorageReader.EnumerateMessages
second_title: Aspose.Email for .NET API Reference
description: MboxStorageReader method. Exposes the enumerator which supports an iteration of messages in storage
type: docs
weight: 100
url: /net/aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/
---
## EnumerateMessages() {#enumeratemessages}

Exposes the enumerator, which supports an iteration of messages in storage.

```csharp
public IEnumerable<MailMessage> EnumerateMessages()
```

### Return Value

IEnumerable, that represents an enumerator that iterates through a messages in storage.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(MailQuery) {#enumeratemessages_4}

Enumerates the mail messages that match the specified query.

```csharp
public IEnumerable<MailMessage> EnumerateMessages(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) used to filter messages. |

### Return Value

An enumerable collection of [`MailMessage`](../../../aspose.email/mailmessage/) instances that match the specified query. The collection may be empty if no messages match.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(int, int) {#enumeratemessages_5}

Enumerates a specified number of mail messages, starting from the given index.

```csharp
public IEnumerable<MailMessage> EnumerateMessages(int startIndex, int count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | Int32 | The zero-based index of the first message to retrieve. If *startIndex* is greater than or equal to the total number of items, an ArgumentOutOfRangeException is thrown. |
| count | Int32 | The maximum number of messages to retrieve. If set to -1, all messages from the start index will be read. |

### Return Value

An enumerable collection of [`MailMessage`](../../../aspose.email/mailmessage/) instances starting from the specified index. The collection may be empty if there are no messages in the specified range.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when *startIndex* is greater than or equal to the total number of available messages. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(EmlLoadOptions) {#enumeratemessages_1}

Exposes the enumerator, which supports an iteration of messages in storage.

```csharp
public IEnumerable<MailMessage> EnumerateMessages(EmlLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | EmlLoadOptions | Specifies [`EmlLoadOptions`](../../../aspose.email/emlloadoptions/) when reading message from Mbox storage. |

### Return Value

IEnumerable, that represents an enumerator that iterates through a messages in storage.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [EmlLoadOptions](../../../aspose.email/emlloadoptions/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(EmlLoadOptions, MailQuery) {#enumeratemessages_2}

Enumerates the mail messages that match the specified query, using the provided load options.

```csharp
public IEnumerable<MailMessage> EnumerateMessages(EmlLoadOptions options, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | EmlLoadOptions | The [`EmlLoadOptions`](../../../aspose.email/emlloadoptions/) specifying how EML should be read. |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) used to filter messages. |

### Return Value

An enumerable collection of [`MailMessage`](../../../aspose.email/mailmessage/) instances that match the specified query. The collection may be empty if no messages match.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [EmlLoadOptions](../../../aspose.email/emlloadoptions/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## EnumerateMessages(EmlLoadOptions, int, int) {#enumeratemessages_3}

Enumerates a specified number of mail messages, starting from the given index, using the provided load options.

```csharp
public IEnumerable<MailMessage> EnumerateMessages(EmlLoadOptions options, int startIndex, int count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | EmlLoadOptions | The [`EmlLoadOptions`](../../../aspose.email/emlloadoptions/) specifying how EML files should be loaded. |
| startIndex | Int32 | The zero-based index of the first message to retrieve. If *startIndex* is greater than or equal to the total number of items, an ArgumentOutOfRangeException is thrown. |
| count | Int32 | The maximum number of messages to retrieve. If set to -1, all messages from the start index will be read. |

### Return Value

An enumerable collection of [`MailMessage`](../../../aspose.email/mailmessage/) instances starting from the specified index. The collection may be empty if there are no messages in the specified range.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when *startIndex* is greater than or equal to the total number of available messages. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [EmlLoadOptions](../../../aspose.email/emlloadoptions/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)


