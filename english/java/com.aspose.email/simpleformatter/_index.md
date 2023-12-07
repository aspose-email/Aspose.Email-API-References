---
title: SimpleFormatter
second_title: Aspose.Email for Java API Reference
description: Represents the default implementation of IFormatter interface.
type: docs
weight: 647
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(LogEntry entry)](#format-com.aspose.email.LogEntry-) | Formats a log entry and return a string to be outputted. |
| [format(Date datatime)](#format-java.util.Date-) | Formats a datetime and return a string to be outputted. |
| [getClass()](#getClass--) |  |
| [getDefaultFormatter()](#getDefaultFormatter--) | Gets or sets default formatter |
| [getFooter()](#getFooter--) | Gets or sets the footer. |
| [getHeader()](#getHeader--) | Gets or sets the header. |
| [getLogHeader()](#getLogHeader--) | Gets or sets the log header |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFormatter(IFormatter value)](#setDefaultFormatter-com.aspose.email.IFormatter-) | Gets or sets default formatter |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Gets or sets the footer.

**Returns:**
java.lang.String
### getHeader() {#getHeader--}
```
public String getHeader()
```


Gets or sets the header.

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

