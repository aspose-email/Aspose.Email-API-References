---
title: Appender
second_title: Aspose.Email for Java API Reference
description:  Represents the base class for Appender.
type: docs
weight: 29
url: /java/com.aspose.email/appender/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IAppender](../../com.aspose.email/iappender), com.aspose.ms.System.IDisposable
```
public abstract class Appender implements IAppender, System.IDisposable
```

Represents the base class for Appender.
## Methods

| Method | Description |
| --- | --- |
| [appendHeader()](#appendHeader--) | Starts log file with specific header. |
| [append(LogEntry entry)](#append-com.aspose.email.LogEntry-) | Appends the specified log entry to the appender. |
| [close()](#close--) | Closes the appender. |
| [initialize()](#initialize--) | Initializes the appender instance. |
| [getFormatter()](#getFormatter--) | Gets or sets the formatter. |
| [setFormatter(IFormatter value)](#setFormatter-com.aspose.email.IFormatter-) | Gets or sets the formatter. |
| [dispose()](#dispose--) | Releases the unmanaged resources used by the Appender. |
### appendHeader() {#appendHeader--}
```
public void appendHeader()
```


Starts log file with specific header.

### append(LogEntry entry) {#append-com.aspose.email.LogEntry-}
```
public abstract void append(LogEntry entry)
```


Appends the specified log entry to the appender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | The log entry. |

### close() {#close--}
```
public void close()
```


Closes the appender.

### initialize() {#initialize--}
```
public void initialize()
```


Initializes the appender instance.

### getFormatter() {#getFormatter--}
```
public final IFormatter getFormatter()
```


Gets or sets the formatter.

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### setFormatter(IFormatter value) {#setFormatter-com.aspose.email.IFormatter-}
```
public final void setFormatter(IFormatter value)
```


Gets or sets the formatter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Releases the unmanaged resources used by the Appender.

