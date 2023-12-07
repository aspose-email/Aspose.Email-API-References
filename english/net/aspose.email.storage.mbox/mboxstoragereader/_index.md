---
title: Class MboxStorageReader
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Mbox.MboxStorageReader class. A base class for any mboxbased mail storage reader
type: docs
weight: 20110
url: /net/aspose.email.storage.mbox/mboxstoragereader/
---
## MboxStorageReader class

A base class for any mbox-based mail storage reader.

```csharp
public abstract class MboxStorageReader : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [BaseStream](../../aspose.email.storage.mbox/mboxstoragereader/basestream/) { get; } | Gets the base stream. |
| [CurrentDataSize](../../aspose.email.storage.mbox/mboxstoragereader/currentdatasize/) { get; } | Gets the number of bytes that is read by ReadNextMessage method. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateReader](../../aspose.email.storage.mbox/mboxstoragereader/createreader/#createreader)(Stream, MboxLoadOptions) | Creates the instance of reader. |
| static [CreateReader](../../aspose.email.storage.mbox/mboxstoragereader/createreader/#createreader_2)(string, MboxLoadOptions) | Creates the instance of reader. |
| static [CreateReader](../../aspose.email.storage.mbox/mboxstoragereader/createreader/#createreader_1)(Stream, MboxLoadOptions, CancellationToken) | Creates the instance of reader. |
| static [CreateReader](../../aspose.email.storage.mbox/mboxstoragereader/createreader/#createreader_3)(string, MboxLoadOptions, CancellationToken) | Creates the instance of reader. |
| [Dispose](../../aspose.email.storage.mbox/mboxstoragereader/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessageInfo](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessageinfo/)() | Exposes the enumerator, which supports an iteration of messages in storage. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/#enumeratemessages)() | Exposes the enumerator, which supports an iteration of messages in storage. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/#enumeratemessages_1)(EmlLoadOptions) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [ExtractMessage](../../aspose.email.storage.mbox/mboxstoragereader/extractmessage/)(string, EmlLoadOptions) | Get the message from MBOX. |
| abstract [GetTotalItemsCount](../../aspose.email.storage.mbox/mboxstoragereader/gettotalitemscount/)() | Returns the number of messages in a storage. |
| abstract [NextMessage](../../aspose.email.storage.mbox/mboxstoragereader/nextmessage/)() | Gets the next message info. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage/#readnextmessage)() | Reads the next message from underlying storage stream. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage/#readnextmessage_1)(EmlLoadOptions) | Reads the next message from underlying storage stream. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage/#readnextmessage_2)(out string) | Reads the next message from underlying storage stream. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage/#readnextmessage_3)(out string, EmlLoadOptions) | Reads the next message from underlying storage stream. |
| [SplitInto](../../aspose.email.storage.mbox/mboxstoragereader/splitinto/#splitinto)(long, string) | Splits the mbox storage into less sized parts. |
| [SplitInto](../../aspose.email.storage.mbox/mboxstoragereader/splitinto/#splitinto_1)(long, string, string) |  |

## Events

| Name | Description |
| --- | --- |
| event [EmlCopied](../../aspose.email.storage.mbox/mboxstoragereader/emlcopied/) | Event that occurs after successful copy of a [`MailMessage`](../../aspose.email/mailmessage/) object within the [`SplitInto`](./splitinto/) method. |
| event [EmlCopying](../../aspose.email.storage.mbox/mboxstoragereader/emlcopying/) | Event that occurs before the [`MailMessage`](../../aspose.email/mailmessage/) object copy process, within the [`SplitInto`](./splitinto/) method. |
| event [MboxFileCreated](../../aspose.email.storage.mbox/mboxstoragereader/mboxfilecreated/) | Event that occurs when a new MBOX file is created during the [`SplitInto`](./splitinto/) method. |
| event [MboxFileFilled](../../aspose.email.storage.mbox/mboxstoragereader/mboxfilefilled/) | Event that occurs after filling an MBOX file with data within the [`SplitInto`](./splitinto/) method. |

### See Also

* namespace [Aspose.Email.Storage.Mbox](../../aspose.email.storage.mbox/)
* assembly [Aspose.Email](../../)


