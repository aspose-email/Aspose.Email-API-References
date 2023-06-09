---
title: MboxrdStorageReader.ReadNextMessage
second_title: Aspose.Email for .NET API Reference
description: MboxrdStorageReader method. Reads the next message from underlying storage stream
type: docs
weight: 40
url: /net/aspose.email.storage.mbox/mboxrdstoragereader/readnextmessage/
---
## ReadNextMessage(out string) {#readnextmessage_2}

Reads the next message from underlying storage stream.

```csharp
public override MailMessage ReadNextMessage(out string fromMarker)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fromMarker | String& | Gets the From Marker while parsing the MBox Storage file. |

### Return Value

A [`MailMessage`](../../../aspose.email/mailmessage/) object if it can be read or **null** if no more messages are available.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [MboxrdStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxrdstoragereader/)
* assembly [Aspose.Email](../../../)

---

## ReadNextMessage(EmlLoadOptions) {#readnextmessage_1}

Reads the next message from underlying storage stream.

```csharp
public override MailMessage ReadNextMessage(EmlLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | EmlLoadOptions | Specifies [`EmlLoadOptions`](../../../aspose.email/emlloadoptions/) when reading message from Mbox storage. |

### Return Value

A [`MailMessage`](../../../aspose.email/mailmessage/) object if it can be read or **null** if no more messages are available.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [EmlLoadOptions](../../../aspose.email/emlloadoptions/)
* class [MboxrdStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxrdstoragereader/)
* assembly [Aspose.Email](../../../)

---

## ReadNextMessage(out string, EmlLoadOptions) {#readnextmessage_3}

Reads the next message from underlying storage stream.

```csharp
public override MailMessage ReadNextMessage(out string fromMarker, EmlLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fromMarker | String& | Gets the From Marker while parsing the MBox Storage file. |
| options | EmlLoadOptions | Specifies [`EmlLoadOptions`](../../../aspose.email/emlloadoptions/) when reading message from Mbox storage. |

### Return Value

A [`MailMessage`](../../../aspose.email/mailmessage/) object if it can be read or **null** if no more messages are available.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [EmlLoadOptions](../../../aspose.email/emlloadoptions/)
* class [MboxrdStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxrdstoragereader/)
* assembly [Aspose.Email](../../../)

---

## ReadNextMessage() {#readnextmessage}

Reads the next message from underlying storage stream.

```csharp
public override MailMessage ReadNextMessage()
```

### Return Value

A [`MailMessage`](../../../aspose.email/mailmessage/) object if it can be read or **null** if no more messages are available.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [MboxrdStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxrdstoragereader/)
* assembly [Aspose.Email](../../../)


