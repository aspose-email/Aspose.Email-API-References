---
title: StandardFormatter
second_title: Aspose.Email for Java API Reference
description:  Represents the class for formatting log entry messsages.
type: docs
weight: 646
url: /java/com.aspose.email/standardformatter/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.Formatter](../../com.aspose.email/formatter)
```
public class StandardFormatter extends Formatter
```

Represents the class for formatting log entry messsages.
## Constructors

| Constructor | Description |
| --- | --- |
| [StandardFormatter()](#StandardFormatter--) | Initializes a new instance of the [StandardFormatter](../../com.aspose.email/standardformatter) class. |
| [StandardFormatter(StringBuilder headerText)](#StandardFormatter-java.lang.StringBuilder-) | Initializes a new instance of the [StandardFormatter](../../com.aspose.email/standardformatter) class. |
| [StandardFormatter(String headerText)](#StandardFormatter-java.lang.String-) | Initializes a new instance of the [StandardFormatter](../../com.aspose.email/standardformatter) class. |
## Methods

| Method | Description |
| --- | --- |
| [format(LogEntry entry)](#format-com.aspose.email.LogEntry-) | Formats a log entry and return a string to be outputted. |
| [getHeader()](#getHeader--) | Gets the log header. |
| [getFooter()](#getFooter--) | Gest the footer string. |
### StandardFormatter() {#StandardFormatter--}
```
public StandardFormatter()
```


Initializes a new instance of the [StandardFormatter](../../com.aspose.email/standardformatter) class.

### StandardFormatter(StringBuilder headerText) {#StandardFormatter-java.lang.StringBuilder-}
```
public StandardFormatter(StringBuilder headerText)
```


Initializes a new instance of the [StandardFormatter](../../com.aspose.email/standardformatter) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| headerText | java.lang.StringBuilder | The header text. |

### StandardFormatter(String headerText) {#StandardFormatter-java.lang.String-}
```
public StandardFormatter(String headerText)
```


Initializes a new instance of the [StandardFormatter](../../com.aspose.email/standardformatter) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| headerText | java.lang.String | The header text. |

### format(LogEntry entry) {#format-com.aspose.email.LogEntry-}
```
public String format(LogEntry entry)
```


Formats a log entry and return a string to be outputted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | The Log entry to format. |

**Returns:**
java.lang.String - String representing the log entry.
### getHeader() {#getHeader--}
```
public String getHeader()
```


Gets the log header.

Value:

**Returns:**
java.lang.String
### getFooter() {#getFooter--}
```
public String getFooter()
```


Gest the footer string.

**Returns:**
java.lang.String
