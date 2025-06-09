---
title: IAppender
second_title: Aspose.Email for Java API Reference
description: Implement this interface for your own strategies for printing log entries.
type: docs
weight: 771
url: /java/com.aspose.email/iappender/
---
```
public interface IAppender
```

Implement this interface for your own strategies for printing log entries.
## Methods

| Method | Description |
| --- | --- |
| [append(LogEntry entry)](#append-com.aspose.email.LogEntry-) | Log the specified log entry in Appender specific way. |
| [appendHeader()](#appendHeader--) | Starts log file with specific header. |
| [getFormatter()](#getFormatter--) | Gets or sets the IFormatter. |
| [setFormatter(IFormatter value)](#setFormatter-com.aspose.email.IFormatter-) | Gets or sets the IFormatter. |
### append(LogEntry entry) {#append-com.aspose.email.LogEntry-}
```
public abstract void append(LogEntry entry)
```


Log the specified log entry in Appender specific way.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | Contains a log message. |

### appendHeader() {#appendHeader--}
```
public abstract void appendHeader()
```


Starts log file with specific header.

### getFormatter() {#getFormatter--}
```
public abstract IFormatter getFormatter()
```


Gets or sets the IFormatter.

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### setFormatter(IFormatter value) {#setFormatter-com.aspose.email.IFormatter-}
```
public abstract void setFormatter(IFormatter value)
```


Gets or sets the IFormatter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

