---
title: PersonalStorage.Create
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Creates a new PST file
type: docs
weight: 20
url: /net/aspose.email.storage.pst/personalstorage/create/
---
## Create(string, FileFormatVersion) {#create_2}

Creates a new PST file.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file to create. The file must not exist. |
| version | FileFormatVersion | The version of the PST. Only `FileFormatVersion.Unicode` is supported. |

### Return Value

The new PST, open for writing.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | *version* is `FileFormatVersion.ANSI`. |
| ArgumentNullException | *fileName* is `null` or empty. |
| IOException | A file named *fileName* already exists. |

## Remarks

Only Unicode PST files can be created.

## Examples

This example creates a PST, adds the standard Inbox folder and puts a message into it.

[C#]

```csharp
// Create a new PST; the file must not exist yet
using (var pst = PersonalStorage.Create("archive.pst", FileFormatVersion.Unicode))
{
    // Create the standard Inbox folder
    var inbox = pst.CreatePredefinedFolder("Inbox", StandardIpmFolder.Inbox);

    // Add a message loaded from an .msg file
    var message = MapiMessage.Load("message.msg");
    string entryId = inbox.AddMessage(message);

    Console.WriteLine($"Added message {entryId}");
}
```

[Visual Basic]

```csharp
' Create a new PST; the file must not exist yet
Using pst As PersonalStorage = PersonalStorage.Create("archive.pst", FileFormatVersion.Unicode)
    ' Create the standard Inbox folder
    Dim inbox As FolderInfo = pst.CreatePredefinedFolder("Inbox", StandardIpmFolder.Inbox)

    ' Add a message loaded from an .msg file
    Dim message As MapiMessage = MapiMessage.Load("message.msg")
    Dim entryId As String = inbox.AddMessage(message)

    Console.WriteLine($"Added message {entryId}")
End Using
```

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion) {#create}

Creates a new PST in a stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write the PST to. |
| version | FileFormatVersion | The version of the PST. Only `FileFormatVersion.Unicode` is supported. |

### Return Value

The new PST, open for writing.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | *version* is `FileFormatVersion.ANSI`. |
| ArgumentNullException | *stream* is `null`. |

## Remarks

Only Unicode PST files can be created. The stream is closed when the storage is disposed. Use the overload with leaveStreamOpen to keep it open.

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool) {#create_1}

Creates a new PST in a stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write the PST to. |
| version | FileFormatVersion | The version of the PST. Only `FileFormatVersion.Unicode` is supported. |
| leaveStreamOpen | Boolean | `true` to leave *stream* open when the storage is disposed. |

### Return Value

The new PST, open for writing.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | *version* is `FileFormatVersion.ANSI`. |
| ArgumentNullException | *stream* is `null`. |

## Remarks

Only Unicode PST files can be created.

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


