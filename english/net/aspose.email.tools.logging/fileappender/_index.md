---
title: Class FileAppender
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Tools.Logging.FileAppender class. Reprensents a file appender
type: docs
weight: 20530
url: /net/aspose.email.tools.logging/fileappender/
---
## FileAppender class

Reprensents a file appender.

```csharp
public sealed class FileAppender : Appender
```

## Constructors

| Name | Description |
| --- | --- |
| [FileAppender](fileappender/#constructor)() | Initializes a new instance of the FileAppender class. |
| [FileAppender](fileappender/#constructor_1)(string) | Initializes a new instance of the FileAppender class. |
| [FileAppender](fileappender/#constructor_3)(string, bool) | Initializes a new instance of the FileAppender class. |
| [FileAppender](fileappender/#constructor_2)(string, IFormatter) | Initializes a new instance of the FileAppender class. |
| [FileAppender](fileappender/#constructor_4)(string, bool, IFormatter) | Initializes a new instance of the FileAppender class. |

## Properties

| Name | Description |
| --- | --- |
| [Encoding](../../aspose.email.tools.logging/fileappender/encoding/) { get; set; } | Gets or sets the encoding. |
| [FileName](../../aspose.email.tools.logging/fileappender/filename/) { get; set; } | Gets or sets file name. |
| [Formatter](../../aspose.email.tools.logging/appender/formatter/) { get; set; } | Gets or sets the formatter. |
| [UseDate](../../aspose.email.tools.logging/fileappender/usedate/) { get; set; } | Gets or sets value which indicates whether date is used for logging. |

## Methods

| Name | Description |
| --- | --- |
| override [Append](../../aspose.email.tools.logging/fileappender/append/#append)(LogEntry) | Appends the log entry information to the appender. |
| [Append](../../aspose.email.tools.logging/fileappender/append/#append_1)(LogEntry[]) | Appends a set of log entries to the appender. |
| override [AppendHeader](../../aspose.email.tools.logging/fileappender/appendheader/)() | Starts log file with specific header. |
| override [Close](../../aspose.email.tools.logging/fileappender/close/)() | Closes the appender. |
| [Dispose](../../aspose.email.tools.logging/appender/dispose/)() | Releases the unmanaged resources used by the Appender. |
| virtual [Initialize](../../aspose.email.tools.logging/appender/initialize/)() | Initializes the appender instance. |

### See Also

* class [Appender](../appender/)
* namespace [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging/)
* assembly [Aspose.Email](../../)


