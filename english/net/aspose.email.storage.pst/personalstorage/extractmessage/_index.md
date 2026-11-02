---
title: PersonalStorage.ExtractMessage
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Loads the full message that a MessageInfo describes
type: docs
weight: 210
url: /net/aspose.email.storage.pst/personalstorage/extractmessage/
---
## ExtractMessage(MessageInfo) {#extractmessage}

Loads the full message that a [`MessageInfo`](../../messageinfo/) describes.

```csharp
public MapiMessage ExtractMessage(MessageInfo messageInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | MessageInfo | Information about the message, from `FolderInfo.GetContents` or `FolderInfo.EnumerateMessages`. |

### Return Value

The message with its body, recipients and attachments.

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *messageInfo* was not obtained from a [`PersonalStorage`](../). |

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [MessageInfo](../../messageinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## ExtractMessage(byte[]) {#extractmessage_1}

Loads the full message with the specified entry ID.

```csharp
public MapiMessage ExtractMessage(byte[] entryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | Byte[] | The entry ID of the message. |

### Return Value

The message with its body, recipients and attachments.

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## ExtractMessage(string) {#extractmessage_2}

Loads the full message with the specified entry ID.

```csharp
public MapiMessage ExtractMessage(string entryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the message, as a string. |

### Return Value

The message with its body, recipients and attachments.

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


