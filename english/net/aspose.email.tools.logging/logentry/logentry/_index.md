---
title: LogEntry
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.email.tools.logging/logentry/logentry/
---
## LogEntry constructor (1 of 13)

Initialize a new instance of a [`LogEntry`](../../logentry) class.

```csharp
public LogEntry()
```

### See Also

* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (2 of 13)

Initialize a new instance of a [`LogEntry`](../../logentry) class.

```csharp
public LogEntry(string message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The message. |

### See Also

* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (3 of 13)

Initialize a new instance of a [`LogEntry`](../../logentry) class.

```csharp
public LogEntry(string message, DateTime time)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The message. |
| time | DateTime | The time. |

### See Also

* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (4 of 13)

Initialize a new instance of a [`LogEntry`](../../logentry) class.

```csharp
public LogEntry(string message, Exception innerException)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | Message body to log. Value from ToString() method from message object. |
| innerException | Exception | The inner exception to log. |

### See Also

* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (5 of 13)

Initialize a new instance of a [`LogEntry`](../../logentry) class.

```csharp
public LogEntry(string message, LogLevel severity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | Message body to log. Value from ToString() method from message object. |
| severity | LogLevel | Log entry severity as a [`Severity`](../severity) enumeration. (Unspecified, Information, Warning or Error). |

### See Also

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (6 of 13)

Initialize a new instance of a [`LogEntry`](../../logentry) class.

```csharp
public LogEntry(string message, Exception innerException, LogLevel severity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | Message body to log. Value from ToString() method from message object. |
| innerException | Exception | The inner exception to log. |
| severity | LogLevel | Log entry severity as a [`Severity`](../severity) enumeration. (Unspecified, Information, Warning or Error). |

### See Also

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (7 of 13)

Create a new instance of [`LogEntry`](../../logentry) with a full set of constructor parameters

```csharp
public LogEntry(string message, IDictionary<string, string> properties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | Message body to log. Value from ToString() method from message object. |
| properties | IDictionary`2 | Dictionary of key/value pairs to record. |

### See Also

* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (8 of 13)

Create a new instance of [`LogEntry`](../../logentry) with a full set of constructor parameters

```csharp
public LogEntry(byte[] binaryDataMessage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Binary message body to log. |

### See Also

* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (9 of 13)

Create a new instance of [`LogEntry`](../../logentry) with a full set of constructor parameters

```csharp
public LogEntry(byte[] binaryDataMessage, Encoding messageEncoding)
```

| Parameter | Type | Description |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Binary message body to log. |
| messageEncoding | Encoding | Encoding for binary message |

### See Also

* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (10 of 13)

Create a new instance of [`LogEntry`](../../logentry) with a full set of constructor parameters

```csharp
public LogEntry(byte[] binaryDataMessage, IDictionary<string, string> properties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Binary message body to log. |
| properties | IDictionary`2 | Dictionary of key/value pairs to record. |

### See Also

* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (11 of 13)

Create a new instance of [`LogEntry`](../../logentry) with a full set of constructor parameters

```csharp
public LogEntry(byte[] binaryDataMessage, Encoding messageEncoding, 
    IDictionary<string, string> properties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Binary message body to log. |
| messageEncoding | Encoding | Encoding for binary message |
| properties | IDictionary`2 | Dictionary of key/value pairs to record. |

### See Also

* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (12 of 13)

Create a new instance of [`LogEntry`](../../logentry) with a full set of constructor parameters

```csharp
public LogEntry(string message, LogLevel severity, string category, int eventId, string title, 
    IDictionary<string, string> properties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | Message body to log. Value from ToString() method from message object. |
| severity | LogLevel | Log entry severity as a [`Severity`](../severity) enumeration. (Unspecified, Information, Warning or Error). |
| category | String | Category name used to route the log entry to a one or more sinks. |
| eventId | Int32 | Event number or identifier. |
| title | String | Additional description of the log entry message. |
| properties | IDictionary`2 | Dictionary of key/value pairs to record. |

### See Also

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

---

## LogEntry constructor (13 of 13)

Create a new instance of [`LogEntry`](../../logentry) with a full set of constructor parameters

```csharp
public LogEntry(string message, Exception innerException, LogLevel severity, string category, 
    int eventId, string title, IDictionary<string, string> properties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | Message body to log. Value from ToString() method from message object. |
| innerException | Exception | The inner exception to log. |
| severity | LogLevel | Log entry severity as a [`Severity`](../severity) enumeration. (Unspecified, Information, Warning or Error). |
| category | String | Category name used to route the log entry to a one or more sinks. |
| eventId | Int32 | Event number or identifier. |
| title | String | Additional description of the log entry message. |
| properties | IDictionary`2 | Dictionary of key/value pairs to record. |

### See Also

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* namespace [Aspose.Email.Tools.Logging](../../logentry)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
