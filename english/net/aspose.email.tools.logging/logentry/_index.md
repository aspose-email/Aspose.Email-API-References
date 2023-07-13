---
title: Class LogEntry
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Tools.Logging.LogEntry class. Represents a log message. Contains the common properties that are required for all log messages
type: docs
weight: 20340
url: /net/aspose.email.tools.logging/logentry/
---
## LogEntry class

Represents a log message. Contains the common properties that are required for all log messages.

```csharp
public class LogEntry
```

## Constructors

| Name | Description |
| --- | --- |
| [LogEntry](logentry/#constructor)() | Initialize a new instance of a `LogEntry` class. |
| [LogEntry](logentry/#constructor_1)(byte[]) | Create a new instance of `LogEntry` with a full set of constructor parameters |
| [LogEntry](logentry/#constructor_5)(string) | Initialize a new instance of a `LogEntry` class. |
| [LogEntry](logentry/#constructor_3)(byte[], Encoding) | Create a new instance of `LogEntry` with a full set of constructor parameters |
| [LogEntry](logentry/#constructor_2)(byte[], IDictionary&lt;string, string&gt;) | Create a new instance of `LogEntry` with a full set of constructor parameters |
| [LogEntry](logentry/#constructor_9)(string, DateTime) | Initialize a new instance of a `LogEntry` class. |
| [LogEntry](logentry/#constructor_10)(string, Exception) | Initialize a new instance of a `LogEntry` class. |
| [LogEntry](logentry/#constructor_8)(string, IDictionary&lt;string, string&gt;) | Create a new instance of `LogEntry` with a full set of constructor parameters |
| [LogEntry](logentry/#constructor_6)(string, LogLevel) | Initialize a new instance of a `LogEntry` class. |
| [LogEntry](logentry/#constructor_4)(byte[], Encoding, IDictionary&lt;string, string&gt;) | Create a new instance of `LogEntry` with a full set of constructor parameters |
| [LogEntry](logentry/#constructor_11)(string, Exception, LogLevel) | Initialize a new instance of a `LogEntry` class. |
| [LogEntry](logentry/#constructor_7)(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Create a new instance of `LogEntry` with a full set of constructor parameters |
| [LogEntry](logentry/#constructor_12)(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Create a new instance of `LogEntry` with a full set of constructor parameters |

## Properties

| Name | Description |
| --- | --- |
| [AppDomainName](../../aspose.email.tools.logging/logentry/appdomainname/) { get; set; } | The AppDomain in which we are running |
| [BinaryDataMessage](../../aspose.email.tools.logging/logentry/binarydatamessage/) { get; set; } | Binary message body to log. |
| [Category](../../aspose.email.tools.logging/logentry/category/) { get; set; } | Category name used to route the log entry to a one or more sinks. |
| [ContextualProperties](../../aspose.email.tools.logging/logentry/contextualproperties/) { get; set; } | Dictionary of key/value pairs to record. |
| [ErrorMessages](../../aspose.email.tools.logging/logentry/errormessages/) { get; } | Gets the error message with the `LogEntry` |
| [EventId](../../aspose.email.tools.logging/logentry/eventid/) { get; set; } | Event number or identifier. |
| [InnerException](../../aspose.email.tools.logging/logentry/innerexception/) { get; set; } | Gets or sets the inner exception object. |
| [MachineName](../../aspose.email.tools.logging/logentry/machinename/) { get; set; } | Name of the computer. |
| [Message](../../aspose.email.tools.logging/logentry/message/) { get; set; } | Message body to log. Value from ToString() method from message object. |
| [MessageEncoding](../../aspose.email.tools.logging/logentry/messageencoding/) { get; set; } | Encoding for binary message body |
| [SequenceId](../../aspose.email.tools.logging/logentry/sequenceid/) { get; } | The unique identifier of log event which is automatically generated and monotonously increasing. |
| [Severity](../../aspose.email.tools.logging/logentry/severity/) { get; set; } | Log entry severity as a [`Severity`](./severity/) enumeration. (Unspecified, Information, Warning or Error). |
| [ThreadName](../../aspose.email.tools.logging/logentry/threadname/) { get; set; } | The name of the .NET thread. |
| [TimeStamp](../../aspose.email.tools.logging/logentry/timestamp/) { get; set; } | Date and time of the log entry message. |
| [Title](../../aspose.email.tools.logging/logentry/title/) { get; set; } | Additional description of the log entry message. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddErrorMessage](../../aspose.email.tools.logging/logentry/adderrormessage/)(string) | Add an error or warning message to the start of the messages string builder. Used by the distributor to record problems. |
| [Clone](../../aspose.email.tools.logging/logentry/clone/)() | Creates a new `LogEntry` that is a copy of the current instance. |
| override [ToString](../../aspose.email.tools.logging/logentry/tostring/)() |  |

### See Also

* namespace [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging/)
* assembly [Aspose.Email](../../)


