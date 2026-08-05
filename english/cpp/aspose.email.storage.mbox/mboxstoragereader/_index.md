---
title: "Aspose::Email::Storage::Mbox::MboxStorageReader class"
linktitle: "MboxStorageReader"
articleTitle: "MboxStorageReader"
second_title: "Aspose.Email for C++"
description: "Represents an MBOX file and provides methods for reading and extracting messages."
type: docs
weight: 10
url: /cpp/aspose.email.storage.mbox/mboxstoragereader/
---

## MboxStorageReader class

Represents an MBOX file and provides methods for reading and extracting messages. The MBOX file format is used for storing a collection of email messages.

The following code provided is intended for processing email messages stored in an MBOX file using the MboxStorageReader class.

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

```vb
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

## Constructors

| Name | Description |
| --- | --- |
| [MboxStorageReader (2 overloads)](./mboxstoragereader/) | Initializes a new instance of the MboxStorageReader class. |

## Methods

| Name | Description |
| --- | --- |
| [ByteArrayStartsFromMarker](./bytearraystartsfrommarker/) | Checks whether the array starts from given marker. |
| [Cancel](./cancel/) | This method used to interrupt a split operation. |
| [ContainsAsctime](./containsasctime/) | Determines whether the specified line contains asctime string. |
| [CreateReader (2 overloads)](./createreader/) | Creates the instance of reader. |
| [Dispose (2 overloads)](./dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessageInfo (3 overloads)](./enumeratemessageinfo/) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [EnumerateMessages (6 overloads)](./enumeratemessages/) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [ExtractMessage](./extractmessage/) | Get the message from MBOX. |
| [get_BaseStream](./get_basestream/) | Gets the base stream. |
| [get_CurrentDataSize](./get_currentdatasize/) | Gets the number of bytes that is read by ReadNextMessage method. |
| [GetTotalItemsCount](./gettotalitemscount/) | Returns the number of messages in a storage. |
| [GetVentureLicenseState](./getventurelicensestate/) |  |
| [NextMessage (2 overloads)](./nextmessage/) | Gets the next message info. |
| [ReadLine](./readline/) | Reads the line from stream. |
| [ReadNextMessage (5 overloads)](./readnextmessage/) | Reads the next message from underlying storage stream. |
| [set_CurrentDataSize](./set_currentdatasize/) | Gets the number of bytes that is read by ReadNextMessage method. |
| [SetPositionByIndex](./setpositionbyindex/) | Implemented in Aspose::Email::Storage::Mbox::MboxrdStorageReader , and Aspose::Email::Storage::Mbox::MboxoStorageReader . |
| [SplitInto (2 overloads)](./splitinto/) | Splits the mbox storage into less sized parts. |
| [MboxoStorageReader](./mboxostoragereader/) |  |
| [MboxrdStorageReader](./mboxrdstoragereader/) |  |
| [EmlCopied](./emlcopied/) | Event that occurs after successful copy of a MailMessage object within the SplitInto(long, string) method. |
| [EmlCopying](./emlcopying/) | Event that occurs before the MailMessage object copy process, within the SplitInto(long, string) method. |
| [EmptyFromMarkerCR](./emptyfrommarkercr/) |  |
| [EmptyFromMarkerCRLF](./emptyfrommarkercrlf/) |  |
| [EmptyFromMarkerLF](./emptyfrommarkerlf/) |  |
| [FromMarker](./frommarker/) | "From " signature, indicates a start of the message. |
| [MboxFileCreated](./mboxfilecreated/) | Event that occurs when a new MBOX file is created during the SplitInto(long, string) method. |
| [MboxFileFilled](./mboxfilefilled/) | Event that occurs after filling an MBOX file with data within the SplitInto(long, string) method. |
| [MboxoMarker](./mboxomarker/) | The mbox format uses a single blank line followed by the string 'From ' (with a space) to delimit messages. In mboxo format sender's email address in message delimiter is replaced by the constant string '???@???', i.e. 'From ???@???' |
| [msgCount](./msgcount/) |  |
| [mVentureLicense](./mventurelicense/) |  |
| [preferredTextEncoding](./preferredtextencoding/) |  |

