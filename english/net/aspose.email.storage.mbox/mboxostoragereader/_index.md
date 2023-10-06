---
title: Class MboxoStorageReader
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Mbox.MboxoStorageReader class. Represents mboxo format storage reader this format is being used by Eudora
type: docs
weight: 20120
url: /net/aspose.email.storage.mbox/mboxostoragereader/
---
## MboxoStorageReader class

Represents mboxo format storage reader, this format is being used by Eudora.

```csharp
public sealed class MboxoStorageReader : MboxStorageReader
```

## Constructors

| Name | Description |
| --- | --- |
| [MboxoStorageReader](mboxostoragereader/#constructor)(Stream, MboxLoadOptions) | Initializes a new instance of the `MboxoStorageReader` class. |
| [MboxoStorageReader](mboxostoragereader/#constructor_1)(string, MboxLoadOptions) | Initializes a new instance of the [`MboxrdStorageReader`](../mboxrdstoragereader/) class. |

## Properties

| Name | Description |
| --- | --- |
| [BaseStream](../../aspose.email.storage.mbox/mboxstoragereader/basestream/) { get; } | Gets the base stream. |
| [CurrentDataSize](../../aspose.email.storage.mbox/mboxstoragereader/currentdatasize/) { get; } | Gets the number of bytes that is read by ReadNextMessage method. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.email.storage.mbox/mboxstoragereader/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessageInfo](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessageinfo/)() | Exposes the enumerator, which supports an iteration of messages in storage. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/)() | Exposes the enumerator, which supports an iteration of messages in storage. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/)(EmlLoadOptions) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [ExtractMessage](../../aspose.email.storage.mbox/mboxstoragereader/extractmessage/)(string, EmlLoadOptions) | Get the message from MBOX. |
| override [GetTotalItemsCount](../../aspose.email.storage.mbox/mboxostoragereader/gettotalitemscount/)() | Returns the number of messages in a storage. |
| override [NextMessage](../../aspose.email.storage.mbox/mboxostoragereader/nextmessage/)() | Gets the next message info. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxostoragereader/readnextmessage/#readnextmessage)() | Reads the next message from underlying storage stream. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxostoragereader/readnextmessage/#readnextmessage_1)(EmlLoadOptions) | Reads the next message from underlying storage stream. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxostoragereader/readnextmessage/#readnextmessage_2)(out string) | Reads the next message from underlying storage stream. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxostoragereader/readnextmessage/#readnextmessage_3)(out string, EmlLoadOptions) | Reads the next message from underlying storage stream. |

### See Also

* class [MboxStorageReader](../mboxstoragereader/)
* namespace [Aspose.Email.Storage.Mbox](../../aspose.email.storage.mbox/)
* assembly [Aspose.Email](../../)


