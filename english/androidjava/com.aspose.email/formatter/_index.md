---
title: Formatter
second_title: Aspose.Email for Android via Java API Reference
description:  Represents the interface for formatting log entry messsages.
type: docs
weight: 150
url: /java/com.aspose.email/formatter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IFormatter](../../com.aspose.email/iformatter)
```
public abstract class Formatter implements IFormatter
```

Represents the interface for formatting log entry messsages.
## Methods

| Method | Description |
| --- | --- |
| [getDefaultFormatter()](#getDefaultFormatter--) | Gets or sets default formatter |
| [setDefaultFormatter(IFormatter value)](#setDefaultFormatter-com.aspose.email.IFormatter-) | Gets or sets default formatter |
| [format(LogEntry entry)](#format-com.aspose.email.LogEntry-) | Formats a log entry and return a string to be outputted. |
| [format(Date datatime)](#format-java.util.Date-) | Formats a datetime and return a string to be outputted. |
| [getHeader()](#getHeader--) | Gets or sets the header. |
| [getFooter()](#getFooter--) | Gets or sets the footer. |
| [getLogHeader()](#getLogHeader--) | Gets or sets the log header |
### getDefaultFormatter() {#getDefaultFormatter--}
```
public static IFormatter getDefaultFormatter()
```


Gets or sets default formatter

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### setDefaultFormatter(IFormatter value) {#setDefaultFormatter-com.aspose.email.IFormatter-}
```
public static void setDefaultFormatter(IFormatter value)
```


Gets or sets default formatter

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

### format(LogEntry entry) {#format-com.aspose.email.LogEntry-}
```
public String format(LogEntry entry)
```


Formats a log entry and return a string to be outputted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | Log entry to format. |

**Returns:**
java.lang.String - String representing the log entry.
### format(Date datatime) {#format-java.util.Date-}
```
public String format(Date datatime)
```


Formats a datetime and return a string to be outputted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| datatime | java.util.Date | The datetime value for formatting to string |

**Returns:**
java.lang.String
### getHeader() {#getHeader--}
```
public String getHeader()
```


Gets or sets the header.

**Returns:**
java.lang.String
### getFooter() {#getFooter--}
```
public String getFooter()
```


Gets or sets the footer.

**Returns:**
java.lang.String
### getLogHeader() {#getLogHeader--}
```
public String getLogHeader()
```


Gets or sets the log header

**Returns:**
java.lang.String
