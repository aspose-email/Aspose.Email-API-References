---
title: Class MboxrdStorageReader
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Mbox.MboxrdStorageReader class. Represents mboxrd format storage reader this format is being used by Thunderbird and other mail clients
type: docs
weight: 20280
url: /net/aspose.email.storage.mbox/mboxrdstoragereader/
---
## MboxrdStorageReader class

Represents mboxrd format storage reader, this format is being used by Thunderbird and other mail clients.

```csharp
public sealed class MboxrdStorageReader : MboxStorageReader
```

## Constructors

| Name | Description |
| --- | --- |
| [MboxrdStorageReader](mboxrdstoragereader/#constructor)(Stream, MboxLoadOptions) |  |
| [MboxrdStorageReader](mboxrdstoragereader/#constructor_1)(string, MboxLoadOptions) | Initializes a new instance of the `MboxrdStorageReader` class. |

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
| override [GetTotalItemsCount](../../aspose.email.storage.mbox/mboxrdstoragereader/gettotalitemscount/)() | Returns the number of messages in a storage. |
| override [NextMessage](../../aspose.email.storage.mbox/mboxrdstoragereader/nextmessage/)() | Gets the next message info. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxrdstoragereader/readnextmessage/#readnextmessage)() | Reads the next message from underlying storage stream. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxrdstoragereader/readnextmessage/#readnextmessage_1)(EmlLoadOptions) | Reads the next message from underlying storage stream. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxrdstoragereader/readnextmessage/#readnextmessage_2)(out string) | Reads the next message from underlying storage stream. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxrdstoragereader/readnextmessage/#readnextmessage_3)(out string, EmlLoadOptions) | Reads the next message from underlying storage stream. |
| [SplitInto](../../aspose.email.storage.mbox/mboxstoragereader/splitinto/)(long, string) | Splits the mbox storage into less sized parts. |
| [SplitInto](../../aspose.email.storage.mbox/mboxstoragereader/splitinto/)(long, string, CancellationToken) | Splits the mbox storage into less sized parts. |
| [SplitInto](../../aspose.email.storage.mbox/mboxstoragereader/splitinto/)(long, string, string) |  |
| [SplitInto](../../aspose.email.storage.mbox/mboxstoragereader/splitinto/)(long, string, string, CancellationToken) | Splits the mbox storage into less sized parts. |

## Events

| Name | Description |
| --- | --- |
| event [EmlCopied](../../aspose.email.storage.mbox/mboxstoragereader/emlcopied/) | Event that occurs after successful copy of a [`MailMessage`](../../aspose.email/mailmessage/) object within the [`SplitInto`](../mboxstoragereader/splitinto/) method. |
| event [EmlCopying](../../aspose.email.storage.mbox/mboxstoragereader/emlcopying/) | Event that occurs before the [`MailMessage`](../../aspose.email/mailmessage/) object copy process, within the [`SplitInto`](../mboxstoragereader/splitinto/) method. |
| event [MboxFileCreated](../../aspose.email.storage.mbox/mboxstoragereader/mboxfilecreated/) | Event that occurs when a new MBOX file is created during the [`SplitInto`](../mboxstoragereader/splitinto/) method. |
| event [MboxFileFilled](../../aspose.email.storage.mbox/mboxstoragereader/mboxfilefilled/) | Event that occurs after filling an MBOX file with data within the [`SplitInto`](../mboxstoragereader/splitinto/) method. |

### See Also

* class [MboxStorageReader](../mboxstoragereader/)
* namespace [Aspose.Email.Storage.Mbox](../../aspose.email.storage.mbox/)
* assembly [Aspose.Email](../../)


