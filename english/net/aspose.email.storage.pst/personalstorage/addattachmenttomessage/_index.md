---
title: PersonalStorage.AddAttachmentToMessage
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Adds an attachment to the specified message using the provided stream as attachment content
type: docs
weight: 130
url: /net/aspose.email.storage.pst/personalstorage/addattachmenttomessage/
---
## AddAttachmentToMessage(MessageInfo, string, Stream) {#addattachmenttomessage_1}

Adds an attachment to the specified message using the provided stream as attachment content.

```csharp
public void AddAttachmentToMessage(MessageInfo messageInfo, string name, Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | MessageInfo | The [`MessageInfo`](../../messageinfo/) object representing the target message. |
| name | String | The name of the attachment to add. |
| stream | Stream | The stream containing the attachment data. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown if *messageInfo*, *name*, or *stream* is `null` or empty. |

## Remarks

The provided *stream* is not closed or disposed by this method.

### See Also

* class [MessageInfo](../../messageinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## AddAttachmentToMessage(MessageInfo, string) {#addattachmenttomessage}

Adds an attachment to the specified message using the file located at the provided path.

```csharp
public void AddAttachmentToMessage(MessageInfo messageInfo, string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | MessageInfo | The [`MessageInfo`](../../messageinfo/) object representing the target message. |
| filePath | String | The full path to the file to be added as an attachment. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown if *messageInfo* or *filePath* is `null` or empty. |
| FileNotFoundException | Thrown if the file specified by *filePath* does not exist. |

### See Also

* class [MessageInfo](../../messageinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## AddAttachmentToMessage(string, string, Stream) {#addattachmenttomessage_3}

Adds an attachment to the message identified by the specified entry ID using the provided stream.

```csharp
public void AddAttachmentToMessage(string entryId, string name, Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the target message. |
| name | String | The name of the attachment to add. |
| stream | Stream | The stream containing the attachment data. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown if *entryId*, *name*, or *stream* is `null` or empty. |

## Remarks

The provided *stream* is not closed or disposed by this method.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## AddAttachmentToMessage(string, string) {#addattachmenttomessage_2}

Adds an attachment to the message identified by the specified entry ID using the file located at the provided path.

```csharp
public void AddAttachmentToMessage(string entryId, string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the target message. |
| filePath | String | The full path to the file to be added as an attachment. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown if *entryId* or *filePath* is `null` or empty. |
| FileNotFoundException | Thrown if the file specified by *filePath* does not exist. |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


