---
title: Class FolderOutputHandler
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.LowCode.FolderOutputHandler class. An implementation of IOutputHandler that writes output streams to files in a specified folder
type: docs
weight: 16340
url: /net/aspose.email.lowcode/folderoutputhandler/
---
## FolderOutputHandler class

An implementation of [`IOutputHandler`](../ioutputhandler/) that writes output streams to files in a specified folder.

```csharp
public class FolderOutputHandler : IOutputHandler
```

## Constructors

| Name | Description |
| --- | --- |
| [FolderOutputHandler](folderoutputhandler/)(string) | Initializes a new instance of the `FolderOutputHandler` class with the specified output folder path. |

## Properties

| Name | Description |
| --- | --- |
| [Path](../../aspose.email.lowcode/folderoutputhandler/path/) { get; set; } | Gets or sets the target folder path where output files will be written. |

## Methods

| Name | Description |
| --- | --- |
| [AddOutputStream](../../aspose.email.lowcode/folderoutputhandler/addoutputstream/#addoutputstream_1)(string, Action&lt;Stream&gt;) |  |
| [AddOutputStream](../../aspose.email.lowcode/folderoutputhandler/addoutputstream/#addoutputstream)(string, Func&lt;Stream, Task&gt;) |  |

## Examples

Example usage:

```csharp
var outputHandler = new FolderOutputHandler("C:\\Output");
await outputHandler.AddOutputStream("example.txt", async stream =>
{
    using var writer = new StreamWriter(stream);
    await writer.WriteLineAsync("Hello from async!");
});

outputHandler.AddOutputStream("example_sync.txt", stream =>
{
    using var writer = new StreamWriter(stream);
    writer.WriteLine("Hello from sync!");
});
```

### See Also

* interface [IOutputHandler](../ioutputhandler/)
* namespace [Aspose.Email.LowCode](../../aspose.email.lowcode/)
* assembly [Aspose.Email](../../)


