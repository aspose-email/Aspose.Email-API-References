---
title: Class Appender
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Tools.Logging.Appender class. Represents the base class for Appender
type: docs
weight: 20750
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
| [Formatter](../../aspose.email.tools.logging/appender/formatter/) { get; set; } | Gets or sets the formatter. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Append](../../aspose.email.tools.logging/appender/append/)(LogEntry) | Appends the specified log entry to the appender. |
| virtual [AppendHeader](../../aspose.email.tools.logging/appender/appendheader/)() | Starts log file with specific header. |
| virtual [Close](../../aspose.email.tools.logging/appender/close/)() | Closes the appender. |
| [Dispose](../../aspose.email.tools.logging/appender/dispose/)() | Releases the unmanaged resources used by the Appender. |
| virtual [Initialize](../../aspose.email.tools.logging/appender/initialize/)() | Initializes the appender instance. |

### See Also

* interface [IAppender](../iappender/)
* namespace [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging/)
* assembly [Aspose.Email](../../)


