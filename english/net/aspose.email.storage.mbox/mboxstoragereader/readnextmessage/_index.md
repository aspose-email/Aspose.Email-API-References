---
title: MboxStorageReader.ReadNextMessage
second_title: Aspose.Email for .NET API Reference
description: MboxStorageReader method. Reads the next message from underlying storage stream
type: docs
weight: 140
url: /net/aspose.email.storage.mbox/mboxstoragereader/readnextmessage/
---
## ReadNextMessage() {#readnextmessage}

Reads the next message from underlying storage stream.

```csharp
public abstract MailMessage ReadNextMessage()
```

### Return Value

A [`MailMessage`](../../../aspose.email/mailmessage/) object if it can be read or **null** if no more messages are available.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## ReadNextMessage(out string) {#readnextmessage_2}

Reads the next message from underlying storage stream.

```csharp
public abstract MailMessage ReadNextMessage(out string fromMarker)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fromMarker | String& | Gets the From Marker while parsing the MBox Storage file. |

### Return Value

A [`MailMessage`](../../../aspose.email/mailmessage/) object if it can be read or **null** if no more messages are available.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## ReadNextMessage(EmlLoadOptions) {#readnextmessage_1}

Reads the next message from underlying storage stream.

```csharp
public abstract MailMessage ReadNextMessage(EmlLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | EmlLoadOptions | Specifies [`EmlLoadOptions`](../../../aspose.email/emlloadoptions/) when reading message from Mbox storage. |

### Return Value

A [`MailMessage`](../../../aspose.email/mailmessage/) object if it can be read or **null** if no more messages are available.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [EmlLoadOptions](../../../aspose.email/emlloadoptions/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## ReadNextMessage(out string, EmlLoadOptions) {#readnextmessage_3}

Reads the next message from underlying storage stream.

```csharp
public abstract MailMessage ReadNextMessage(out string fromMarker, EmlLoadOptions options)
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
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)


