---
title: LogEntry
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 100
url: /email/python-net/aspose.email.tools.logging/logentry/
---

## LogEntry class

Represents a log message.  Contains the common properties that are required for all log messages.

The LogEntry type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|LogEntry()|Initialize a new instance of a|
|LogEntry(message)|Initializes a new instance of the LogEntry class|
|LogEntry(message, time)|Initializes a new instance of the LogEntry class|
|LogEntry(message, severity)|Initializes a new instance of the LogEntry class|
|LogEntry(binary_data_message)|Initializes a new instance of the LogEntry class|
|LogEntry(binary_data_message, message_encoding)|Initializes a new instance of the LogEntry class|
## Properties
| Name | Description |
| :- | :- |
|message|Message body to log.  Value from ToString() method from message object.|
|binary_data_message|Binary message body to log.|
|message_encoding|Encoding for binary message body|
|category|Category name used to route the log entry to a one or more sinks.|
|event_id|Event number or identifier.|
|severity|Log entry severity as a|
|title|Additional description of the log entry message.|
|time_stamp|Date and time of the log entry message.|
|machine_name|Name of the computer.|
|app_domain_name|The AppDomain in which we are running|
|thread_name|The name of the .NET thread.|
|error_messages|Gets the error message with the|
|sequence_id|The unique identifier of log event which is automatically generated<br/>            and monotonously increasing.|
## Methods
| Name | Description |
| :- | :- |
|clone()|Creates a new|
|add_error_message(message)|  |

### See Also

* namespace [aspose.email.tools.logging](/email/python-net/aspose.email.tools.logging/)
* assembly [Aspose.Email](/slides/python-net/)

