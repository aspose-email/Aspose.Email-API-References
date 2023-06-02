---
title: StandardFormatter
second_title: Aspose.Email for Java API Reference
description: Represents the class for formatting log entry messsages.
type: docs
weight: 650
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(LogEntry entry)](#format-com.aspose.email.LogEntry-) | Formats a log entry and return a string to be outputted. |
| [format(Date datatime)](#format-java.util.Date-) | Formats a datetime and return a string to be outputted. |
| [getClass()](#getClass--) |  |
| [getDefaultFormatter()](#getDefaultFormatter--) | Gets or sets default formatter |
| [getFooter()](#getFooter--) | Gest the footer string. |
| [getHeader()](#getHeader--) | Gets the log header. |
| [getLogHeader()](#getLogHeader--) | Gets or sets the log header |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFormatter(IFormatter value)](#setDefaultFormatter-com.aspose.email.IFormatter-) | Gets or sets default formatter |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFormatter() {#getDefaultFormatter--}
```
public static IFormatter getDefaultFormatter()
```


Gets or sets default formatter

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### getFooter() {#getFooter--}
```
public String getFooter()
```


Gest the footer string.

**Returns:**
java.lang.String
### getHeader() {#getHeader--}
```
public String getHeader()
```


Gets the log header.

Value:

**Returns:**
java.lang.String
### getLogHeader() {#getLogHeader--}
```
public String getLogHeader()
```


Gets or sets the log header

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDefaultFormatter(IFormatter value) {#setDefaultFormatter-com.aspose.email.IFormatter-}
```
public static void setDefaultFormatter(IFormatter value)
```


Gets or sets default formatter

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

