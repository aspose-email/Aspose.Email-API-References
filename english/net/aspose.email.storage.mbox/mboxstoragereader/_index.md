---
title: Class MboxStorageReader
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Mbox.MboxStorageReader class. Represents an MBOX file and provides methods for reading and extracting messages. The MBOX file format is used for storing a collection of email messages
type: docs
weight: 20340
url: /net/aspose.email.storage.mbox/mboxstoragereader/
---
## MboxStorageReader class

Represents an MBOX file and provides methods for reading and extracting messages. The MBOX file format is used for storing a collection of email messages.

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
| [EnumerateMessageInfo](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessageinfo/#enumeratemessageinfo)() | Exposes the enumerator, which supports an iteration of messages in storage. |
| [EnumerateMessageInfo](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessageinfo/#enumeratemessageinfo_1)(MailQuery) | Enumerates the message information that matches the specified query. |
| [EnumerateMessageInfo](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessageinfo/#enumeratemessageinfo_2)(int, int) | Enumerates a specified number of message information entries, starting from the given index. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/#enumeratemessages)() | Exposes the enumerator, which supports an iteration of messages in storage. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/#enumeratemessages_1)(EmlLoadOptions) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/#enumeratemessages_4)(MailQuery) | Enumerates the mail messages that match the specified query. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/#enumeratemessages_2)(EmlLoadOptions, MailQuery) | Enumerates the mail messages that match the specified query, using the provided load options. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/#enumeratemessages_5)(int, int) | Enumerates a specified number of mail messages, starting from the given index. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/#enumeratemessages_3)(EmlLoadOptions, int, int) | Enumerates a specified number of mail messages, starting from the given index, using the provided load options. |
| [ExtractMessage](../../aspose.email.storage.mbox/mboxstoragereader/extractmessage/)(string, EmlLoadOptions) | Get the message from MBOX. |
| abstract [GetTotalItemsCount](../../aspose.email.storage.mbox/mboxstoragereader/gettotalitemscount/)() | Returns the number of messages in a storage. |
| abstract [NextMessage](../../aspose.email.storage.mbox/mboxstoragereader/nextmessage/)() | Gets the next message info. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage/#readnextmessage)() | Reads the next message from underlying storage stream. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage/#readnextmessage_1)(EmlLoadOptions) | Reads the next message from underlying storage stream. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage/#readnextmessage_2)(out string) | Reads the next message from underlying storage stream. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage/#readnextmessage_3)(out string, EmlLoadOptions) | Reads the next message from underlying storage stream. |
| [SplitInto](../../aspose.email.storage.mbox/mboxstoragereader/splitinto/#splitinto_2)(long, string) | Splits the mbox storage into less sized parts. |
| [SplitInto](../../aspose.email.storage.mbox/mboxstoragereader/splitinto/#splitinto_1)(long, string, CancellationToken) | Splits the mbox storage into less sized parts. |
| [SplitInto](../../aspose.email.storage.mbox/mboxstoragereader/splitinto/#splitinto_3)(long, string, string) |  |
| [SplitInto](../../aspose.email.storage.mbox/mboxstoragereader/splitinto/#splitinto)(long, string, string, CancellationToken) | Splits the mbox storage into less sized parts. |

## Events

| Name | Description |
| --- | --- |
| event [EmlCopied](../../aspose.email.storage.mbox/mboxstoragereader/emlcopied/) | Event that occurs after successful copy of a [`MailMessage`](../../aspose.email/mailmessage/) object within the [`SplitInto`](./splitinto/) method. |
| event [EmlCopying](../../aspose.email.storage.mbox/mboxstoragereader/emlcopying/) | Event that occurs before the [`MailMessage`](../../aspose.email/mailmessage/) object copy process, within the [`SplitInto`](./splitinto/) method. |
| event [MboxFileCreated](../../aspose.email.storage.mbox/mboxstoragereader/mboxfilecreated/) | Event that occurs when a new MBOX file is created during the [`SplitInto`](./splitinto/) method. |
| event [MboxFileFilled](../../aspose.email.storage.mbox/mboxstoragereader/mboxfilefilled/) | Event that occurs after filling an MBOX file with data within the [`SplitInto`](./splitinto/) method. |

## Examples

The following code provided is intended for processing email messages stored in an MBOX file using the MboxStorageReader class.

[C#]

```csharp
// Create an instance of the MboxStorageReader using the factory method 'CreateReader'.
var mbox = MboxStorageReader.CreateReader("storage.mbox", new MboxLoadOptions());

// Iterate through each message info object in the mbox storage.
foreach (var mboxMessageInfo in mbox.EnumerateMessageInfo())
{
    Console.WriteLine($"Subject: {mboxMessageInfo.Subject}");
    Console.WriteLine($"From: {mboxMessageInfo.From}");
    Console.WriteLine($"To: {mboxMessageInfo.To}");

    // Extract the full MIME message object from the MBOX storage using the message's unique entry ID.
    var eml = mbox.ExtractMessage(mboxMessageInfo.EntryId, new EmlLoadOptions());
    
    // Save the extracted MIME message as an .eml file.
    eml.Save($"{eml.Subject}.eml");
}
```

[Visual Basic]

```csharp
' Create an instance of the MboxStorageReader using the factory method 'CreateReader'.
Dim mbox As MboxStorageReader = MboxStorageReader.CreateReader("storage.mbox", New MboxLoadOptions())

' Iterate through each message info object in the mbox storage.
For Each mboxMessageInfo As var In mbox.EnumerateMessageInfo()
    Console.WriteLine($"Subject: {mboxMessageInfo.Subject}")
    Console.WriteLine($"From: {mboxMessageInfo.From}")
    Console.WriteLine($"To: {mboxMessageInfo.To}")

    ' Extract the full MIME message object from the MBOX storage using the message's unique entry ID.
    Dim eml As var = mbox.ExtractMessage(mboxMessageInfo.EntryId, New EmlLoadOptions())

    ' Save the extracted MIME message as an .eml file.
    eml.Save($"{eml.Subject}.eml")
Next
```

### See Also

* namespace [Aspose.Email.Storage.Mbox](../../aspose.email.storage.mbox/)
* assembly [Aspose.Email](../../)


