---
title: MapiAttachmentCollection.Add
second_title: Aspose.Email for .NET API Reference
description: MapiAttachmentCollection method. Adds the new attachment as embedded message
type: docs
weight: 20
url: /net/aspose.email.mapi/mapiattachmentcollection/add/
---
## Add(string, MapiMessage) {#add_2}

Adds the new attachment as embedded message.

```csharp
public void Add(string name, MapiMessage msg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of attachment. |
| msg | MapiMessage | The [`MapiMessage`](../../mapimessage/) that represents the attached message. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if message is null. |

### See Also

* class [MapiMessage](../../mapimessage/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(string, byte[]) {#add_3}

Adds the new attachment.

```csharp
public void Add(string name, byte[] data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of attachment. |
| data | Byte[] | The attachment data. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if attachment name is null or empty. |
| ArgumentNullException | throws if attachment data is null. |

### See Also

* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Add(MapiAttachment) {#add}

Adds an object to the end of the Collection.

```csharp
public void Add(MapiAttachment item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | MapiAttachment | The object to be added to the end of the Collection. The value can be null for reference types. |

### See Also

* class [MapiAttachment](../../mapiattachment/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)


