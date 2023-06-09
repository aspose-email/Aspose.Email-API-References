---
title: IFormatter
second_title: Aspose.Email for Java API Reference
description: Represents the interface for formatting log entry messsages.
type: docs
weight: 741
url: /java/com.aspose.email/iformatter/
---
```
public interface IFormatter
```

Represents the interface for formatting log entry messsages.
## Methods

| Method | Description |
| --- | --- |
| [format(LogEntry entry)](#format-com.aspose.email.LogEntry-) | Formats a log entry and return a string to be outputted. |
| [format(Date datatime)](#format-java.util.Date-) | Formats a datetime and return a string to be outputted. |
| [getFooter()](#getFooter--) | Gest the footer string. |
| [getHeader()](#getHeader--) | Gets the header string. |
| [getLogHeader()](#getLogHeader--) | Represents start log header |
### format(LogEntry entry) {#format-com.aspose.email.LogEntry-}
```
public abstract String format(LogEntry entry)
```


Formats a log entry and return a string to be outputted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | The Log entry to format. |

**Returns:**
java.lang.String - String representing the log entry.
### format(Date datatime) {#format-java.util.Date-}
```
public abstract String format(Date datatime)
```


Formats a datetime and return a string to be outputted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| datatime | java.util.Date | The datetime value for formatting to string |

**Returns:**
java.lang.String - String representing the log entry.
### getFooter() {#getFooter--}
```
public abstract String getFooter()
```


Gest the footer string.

**Returns:**
java.lang.String
### getHeader() {#getHeader--}
```
public abstract String getHeader()
```


Gets the header string.

**Returns:**
java.lang.String
### getLogHeader() {#getLogHeader--}
```
public abstract String getLogHeader()
```


Represents start log header

**Returns:**
java.lang.String
