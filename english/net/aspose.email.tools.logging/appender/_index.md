---
title: Appender
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 18560
url: /net/aspose.email.tools.logging/appender/
---
## Appender class

Represents the base class for Appender.

```csharp
public abstract class Appender : IAppender, IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Formatter](formatter) { get; set; } | Gets or sets the formatter. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Append](append)(LogEntry) | Appends the specified log entry to the appender. |
| virtual [AppendHeader](appendheader)() | Starts log file with specific header. |
| virtual [Close](close)() | Closes the appender. |
| [Dispose](dispose)() | Releases the unmanaged resources used by the Appender. |
| virtual [Initialize](initialize)() | Initializes the appender instance. |

### See Also

* interface [IAppender](../iappender)
* namespace [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->