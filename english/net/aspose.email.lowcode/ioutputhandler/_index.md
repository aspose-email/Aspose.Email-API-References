---
title: Interface IOutputHandler
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.LowCode.IOutputHandler interface. Defines an interface for handling output streams by name. Implementations may write to files memory or other destinations
type: docs
weight: 16350
url: /net/aspose.email.lowcode/ioutputhandler/
---
## IOutputHandler interface

Defines an interface for handling output streams by name. Implementations may write to files, memory, or other destinations.

```csharp
public interface IOutputHandler
```

## Methods

| Name | Description |
| --- | --- |
| [AddOutputStream](../../aspose.email.lowcode/ioutputhandler/addoutputstream/#addoutputstream_1)(string, Action&lt;Stream&gt;) | Adds a named output stream using a synchronous write action. |
| [AddOutputStream](../../aspose.email.lowcode/ioutputhandler/addoutputstream/#addoutputstream)(string, Func&lt;Stream, Task&gt;) | Adds a named output stream using an asynchronous write action. |

## Remarks

For a file-based implementation, see [`FolderOutputHandler`](../folderoutputhandler/).

## Examples

Example usage with a file-based handler:

```csharp
IOutputHandler handler = new FolderOutputHandler("C:\\Output");
await handler.AddOutputStream("example.txt", async stream =>
{
    using var writer = new StreamWriter(stream);
    await writer.WriteLineAsync("Example text");
});
```

### See Also

* namespace [Aspose.Email.LowCode](../../aspose.email.lowcode/)
* assembly [Aspose.Email](../../)


