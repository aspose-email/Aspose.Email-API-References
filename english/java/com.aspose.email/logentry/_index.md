---
title: LogEntry
second_title: Aspose.Email for Java API Reference
description: Represents a log message.
type: docs
weight: 355
url: /java/com.aspose.email/logentry/
---
**Inheritance:**
java.lang.Object
```
public class LogEntry
```

Represents a log message. Contains the common properties that are required for all log messages.
## Constructors

| Constructor | Description |
| --- | --- |
| [LogEntry()](#LogEntry--) | Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class. |
| [LogEntry(String message)](#LogEntry-java.lang.String-) | Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class. |
| [LogEntry(String message, Date time)](#LogEntry-java.lang.String-java.util.Date-) | Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class. |
| [LogEntry(String message, Throwable innerException)](#LogEntry-java.lang.String-java.lang.Throwable-) | Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class. |
| [LogEntry(String message, LogLevel severity)](#LogEntry-java.lang.String-com.aspose.email.LogLevel-) | Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class. |
| [LogEntry(String message, Throwable innerException, LogLevel severity)](#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-) | Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class. |
| [LogEntry(String message, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters |
| [LogEntry(byte[] binaryDataMessage)](#LogEntry-byte---) | Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters |
| [LogEntry(byte[] binaryDataMessage, Charset messageEncoding)](#LogEntry-byte---java.nio.charset.Charset-) | Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters |
| [LogEntry(byte[] binaryDataMessage, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-byte---com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters |
| [LogEntry(byte[] binaryDataMessage, Charset messageEncoding, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-byte---java.nio.charset.Charset-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters |
| [LogEntry(String message, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-java.lang.String-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters |
| [LogEntry(String message, Throwable innerException, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)](#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters |
## Methods

| Method | Description |
| --- | --- |
| [getMessage()](#getMessage--) | Message body to log. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Message body to log. |
| [getBinaryDataMessage()](#getBinaryDataMessage--) | Binary message body to log. |
| [setBinaryDataMessage(byte[] value)](#setBinaryDataMessage-byte---) | Binary message body to log. |
| [getMessageEncoding()](#getMessageEncoding--) | Encoding for binary message body |
| [setMessageEncoding(Charset value)](#setMessageEncoding-java.nio.charset.Charset-) | Encoding for binary message body |
| [getCategory()](#getCategory--) | Category name used to route the log entry to a one or more sinks. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Category name used to route the log entry to a one or more sinks. |
| [getEventId()](#getEventId--) | Event number or identifier. |
| [setEventId(int value)](#setEventId-int-) | Event number or identifier. |
| [getSeverity()](#getSeverity--) | Log entry severity as a  Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) enumeration. |
| [setSeverity(LogLevel value)](#setSeverity-com.aspose.email.LogLevel-) | Log entry severity as a  Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) enumeration. |
| [getTitle()](#getTitle--) | Additional description of the log entry message. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Additional description of the log entry message. |
| [getTimeStamp()](#getTimeStamp--) | Date and time of the log entry message. |
| [setTimeStamp(Date value)](#setTimeStamp-java.util.Date-) | Date and time of the log entry message. |
| [getMachineName()](#getMachineName--) | Name of the computer. |
| [setMachineName(String value)](#setMachineName-java.lang.String-) | Name of the computer. |
| [getAppDomainName()](#getAppDomainName--) | The AppDomain in which we are running |
| [setAppDomainName(String value)](#setAppDomainName-java.lang.String-) | The AppDomain in which we are running |
| [getThreadName()](#getThreadName--) | The name of the thread. |
| [setThreadName(String value)](#setThreadName-java.lang.String-) | The name of the thread. |
| [getContextualProperties()](#getContextualProperties--) | Dictionary of key/value pairs to record. |
| [setContextualProperties(System.Collections.Generic.IGenericDictionary<String,String> value)](#setContextualProperties-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--) | Dictionary of key/value pairs to record. |
| [deepClone()](#deepClone--) | Creates a new [LogEntry](../../com.aspose.email/logentry) that is a copy of the current instance. |
| [addErrorMessage(String message)](#addErrorMessage-java.lang.String-) | Add an error or warning message to the start of the messages string builder. |
| [getErrorMessages()](#getErrorMessages--) | Gets the error message with the [LogEntry](../../com.aspose.email/logentry) |
| [getSequenceId()](#getSequenceId--) | The unique identifier of log event which is automatically generated and monotonously increasing. |
| [getInnerException()](#getInnerException--) | Gets or sets the inner exception object. |
| [setInnerException(Throwable value)](#setInnerException-java.lang.Throwable-) | Gets or sets the inner exception object. |
| [toString()](#toString--) |  |
### LogEntry() {#LogEntry--}
```
public LogEntry()
```


Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class.

### LogEntry(String message) {#LogEntry-java.lang.String-}
```
public LogEntry(String message)
```


Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |

### LogEntry(String message, Date time) {#LogEntry-java.lang.String-java.util.Date-}
```
public LogEntry(String message, Date time)
```


Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |
| time | java.util.Date | The time. |

### LogEntry(String message, Throwable innerException) {#LogEntry-java.lang.String-java.lang.Throwable-}
```
public LogEntry(String message, Throwable innerException)
```


Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Message body to log. Value from ToString() method from message object. |
| innerException | java.lang.Throwable | The inner exception to log. |

### LogEntry(String message, LogLevel severity) {#LogEntry-java.lang.String-com.aspose.email.LogLevel-}
```
public LogEntry(String message, LogLevel severity)
```


Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Message body to log. Value from ToString() method from message object. |
| severity | [LogLevel](../../com.aspose.email/loglevel) | Log entry severity as a  Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) enumeration. (Unspecified, Information, Warning or Error). |

### LogEntry(String message, Throwable innerException, LogLevel severity) {#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-}
```
public LogEntry(String message, Throwable innerException, LogLevel severity)
```


Initialize a new instance of a [LogEntry](../../com.aspose.email/logentry) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Message body to log. Value from ToString() method from message object. |
| innerException | java.lang.Throwable | The inner exception to log. |
| severity | [LogLevel](../../com.aspose.email/loglevel) | Log entry severity as a  Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) enumeration. (Unspecified, Information, Warning or Error). |

### LogEntry(String message, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(String message, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Message body to log. Value from ToString() method from message object. |
| properties | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | Dictionary of key/value pairs to record. |

### LogEntry(byte[] binaryDataMessage) {#LogEntry-byte---}
```
public LogEntry(byte[] binaryDataMessage)
```


Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryDataMessage | byte[] | Binary message body to log. |

### LogEntry(byte[] binaryDataMessage, Charset messageEncoding) {#LogEntry-byte---java.nio.charset.Charset-}
```
public LogEntry(byte[] binaryDataMessage, Charset messageEncoding)
```


Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryDataMessage | byte[] | Binary message body to log. |
| messageEncoding | java.nio.charset.Charset | Encoding for binary message |

### LogEntry(byte[] binaryDataMessage, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-byte---com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(byte[] binaryDataMessage, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryDataMessage | byte[] | Binary message body to log. |
| properties | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | Dictionary of key/value pairs to record. |

### LogEntry(byte[] binaryDataMessage, Charset messageEncoding, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-byte---java.nio.charset.Charset-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(byte[] binaryDataMessage, Charset messageEncoding, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryDataMessage | byte[] | Binary message body to log. |
| messageEncoding | java.nio.charset.Charset | Encoding for binary message |
| properties | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | Dictionary of key/value pairs to record. |

### LogEntry(String message, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-java.lang.String-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(String message, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Message body to log. Value from ToString() method from message object. |
| severity | [LogLevel](../../com.aspose.email/loglevel) | Log entry severity as a  Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) enumeration. (Unspecified, Information, Warning or Error). |
| category | java.lang.String | Category name used to route the log entry to a one or more sinks. |
| eventId | int | Event number or identifier. |
| title | java.lang.String | Additional description of the log entry message. |
| properties | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | Dictionary of key/value pairs to record. |

### LogEntry(String message, Throwable innerException, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties) {#LogEntry-java.lang.String-java.lang.Throwable-com.aspose.email.LogLevel-java.lang.String-int-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public LogEntry(String message, Throwable innerException, LogLevel severity, String category, int eventId, String title, System.Collections.Generic.IGenericDictionary<String,String> properties)
```


Create a new instance of [LogEntry](../../com.aspose.email/logentry) with a full set of constructor parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Message body to log. Value from ToString() method from message object. |
| innerException | java.lang.Throwable | The inner exception to log. |
| severity | [LogLevel](../../com.aspose.email/loglevel) | Log entry severity as a  Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) enumeration. (Unspecified, Information, Warning or Error). |
| category | java.lang.String | Category name used to route the log entry to a one or more sinks. |
| eventId | int | Event number or identifier. |
| title | java.lang.String | Additional description of the log entry message. |
| properties | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> | Dictionary of key/value pairs to record. |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Message body to log. Value from ToString() method from message object.

**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Message body to log. Value from ToString() method from message object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryDataMessage() {#getBinaryDataMessage--}
```
public final byte[] getBinaryDataMessage()
```


Binary message body to log.

**Returns:**
byte[]
### setBinaryDataMessage(byte[] value) {#setBinaryDataMessage-byte---}
```
public final void setBinaryDataMessage(byte[] value)
```


Binary message body to log.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getMessageEncoding() {#getMessageEncoding--}
```
public final Charset getMessageEncoding()
```


Encoding for binary message body

**Returns:**
java.nio.charset.Charset
### setMessageEncoding(Charset value) {#setMessageEncoding-java.nio.charset.Charset-}
```
public final void setMessageEncoding(Charset value)
```


Encoding for binary message body

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```


Category name used to route the log entry to a one or more sinks.

**Returns:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Category name used to route the log entry to a one or more sinks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEventId() {#getEventId--}
```
public final int getEventId()
```


Event number or identifier.

**Returns:**
int
### setEventId(int value) {#setEventId-int-}
```
public final void setEventId(int value)
```


Event number or identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSeverity() {#getSeverity--}
```
public final LogLevel getSeverity()
```


Log entry severity as a  Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) enumeration. (Unspecified, Information, Warning or Error).

**Returns:**
[LogLevel](../../com.aspose.email/loglevel)
### setSeverity(LogLevel value) {#setSeverity-com.aspose.email.LogLevel-}
```
public final void setSeverity(LogLevel value)
```


Log entry severity as a  Severity (\#getSeverity.getSeverity/\#setSeverity(LogLevel).setSeverity(LogLevel)) enumeration. (Unspecified, Information, Warning or Error).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [LogLevel](../../com.aspose.email/loglevel) |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Additional description of the log entry message.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Additional description of the log entry message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTimeStamp() {#getTimeStamp--}
```
public final Date getTimeStamp()
```


Date and time of the log entry message.

**Returns:**
java.util.Date
### setTimeStamp(Date value) {#setTimeStamp-java.util.Date-}
```
public final void setTimeStamp(Date value)
```


Date and time of the log entry message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getMachineName() {#getMachineName--}
```
public final String getMachineName()
```


Name of the computer.

**Returns:**
java.lang.String
### setMachineName(String value) {#setMachineName-java.lang.String-}
```
public final void setMachineName(String value)
```


Name of the computer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAppDomainName() {#getAppDomainName--}
```
public final String getAppDomainName()
```


The AppDomain in which we are running

**Returns:**
java.lang.String
### setAppDomainName(String value) {#setAppDomainName-java.lang.String-}
```
public final void setAppDomainName(String value)
```


The AppDomain in which we are running

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getThreadName() {#getThreadName--}
```
public final String getThreadName()
```


The name of the thread.

**Returns:**
java.lang.String
### setThreadName(String value) {#setThreadName-java.lang.String-}
```
public final void setThreadName(String value)
```


The name of the thread.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContextualProperties() {#getContextualProperties--}
```
public final System.Collections.Generic.IGenericDictionary<String,String> getContextualProperties()
```


Dictionary of key/value pairs to record.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String>
### setContextualProperties(System.Collections.Generic.IGenericDictionary<String,String> value) {#setContextualProperties-com.aspose.ms.System.Collections.Generic.IGenericDictionary-java.lang.String-java.lang.String--}
```
public final void setContextualProperties(System.Collections.Generic.IGenericDictionary<String,String> value)
```


Dictionary of key/value pairs to record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String> |  |

### deepClone() {#deepClone--}
```
public final LogEntry deepClone()
```


Creates a new [LogEntry](../../com.aspose.email/logentry) that is a copy of the current instance.

**Returns:**
[LogEntry](../../com.aspose.email/logentry) - A new  LogEntry  that is a copy of the current instance.
### addErrorMessage(String message) {#addErrorMessage-java.lang.String-}
```
public void addErrorMessage(String message)
```


Add an error or warning message to the start of the messages string builder. Used by the distributor to record problems.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Message to be added to this instance |

### getErrorMessages() {#getErrorMessages--}
```
public final String getErrorMessages()
```


Gets the error message with the [LogEntry](../../com.aspose.email/logentry)

**Returns:**
java.lang.String
### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


The unique identifier of log event which is automatically generated and monotonously increasing.

**Returns:**
int
### getInnerException() {#getInnerException--}
```
public final Throwable getInnerException()
```


Gets or sets the inner exception object.

**Returns:**
java.lang.Throwable
### setInnerException(Throwable value) {#setInnerException-java.lang.Throwable-}
```
public final void setInnerException(Throwable value)
```


Gets or sets the inner exception object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Throwable |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
