---
title: SimpleFormatter
second_title: Aspose.Email for Java API Reference
description:  Represents the default implementation of IFormatter interface.
type: docs
weight: 630
url: /java/com.aspose.email/simpleformatter/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.Formatter](../../com.aspose.email/formatter)
```
public final class SimpleFormatter extends Formatter
```

Represents the default implementation of IFormatter interface.
## Constructors

| Constructor | Description |
| --- | --- |
| [SimpleFormatter()](#SimpleFormatter--) | Creates a new SimpleFormatter instance. |
| [SimpleFormatter(String header, String footer)](#SimpleFormatter-java.lang.String-java.lang.String-) | Creates a new SimpleFormatter instance. |
## Methods

| Method | Description |
| --- | --- |
| [format(LogEntry entry)](#format-com.aspose.email.LogEntry-) | Formats a log entry and return a string to be outputted. |
| [format(Date datatime)](#format-java.util.Date-) | Formats a datetime and return a string to be outputted. |
### SimpleFormatter() {#SimpleFormatter--}
```
public SimpleFormatter()
```


Creates a new SimpleFormatter instance.

### SimpleFormatter(String header, String footer) {#SimpleFormatter-java.lang.String-java.lang.String-}
```
public SimpleFormatter(String header, String footer)
```


Creates a new SimpleFormatter instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | java.lang.String | The header. |
| footer | java.lang.String | The footer. |

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
