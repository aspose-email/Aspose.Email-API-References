---
title: LogLevel
second_title: Aspose.Email for Java API Reference
description:  Defines available log levels.
type: docs
weight: 356
url: /java/com.aspose.email/loglevel/
---
**Inheritance:**
java.lang.Object
```
public class LogLevel
```

Defines available log levels.
## Fields

| Field | Description |
| --- | --- |
| [Trace](#Trace) | The Trace level. |
| [Debug](#Debug) | The Debug level. |
| [Information](#Information) | The Info level. |
| [Warning](#Warning) | The Warn level. |
| [Error](#Error) | The Error level. |
| [Fatal](#Fatal) | The Fatal level. |
## Methods

| Method | Description |
| --- | --- |
| [op_LessThanOrEqual(LogLevel l1, LogLevel l2)](#op-LessThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is less than or equal to the second one. |
| [op_GreaterThanOrEqual(LogLevel l1, LogLevel l2)](#op-GreaterThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is greater than or equal to the second one. |
| [op_LessThan(LogLevel l1, LogLevel l2)](#op-LessThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is less than the second one. |
| [op_GreaterThan(LogLevel l1, LogLevel l2)](#op-GreaterThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is greater than the second one. |
| [toString()](#toString--) | Returns a string representation of the log level. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares the level to the other [LogLevel](../../com.aspose.email/loglevel) object. |
### Trace {#Trace}
```
public static final LogLevel Trace
```


The Trace level.

### Debug {#Debug}
```
public static final LogLevel Debug
```


The Debug level.

### Information {#Information}
```
public static final LogLevel Information
```


The Info level.

### Warning {#Warning}
```
public static final LogLevel Warning
```


The Warn level.

### Error {#Error}
```
public static final LogLevel Error
```


The Error level.

### Fatal {#Fatal}
```
public static final LogLevel Fatal
```


The Fatal level.

### op_LessThanOrEqual(LogLevel l1, LogLevel l2) {#op-LessThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_LessThanOrEqual(LogLevel l1, LogLevel l2)
```


Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is less than or equal to the second one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | The first level. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | The second level. |

**Returns:**
boolean - The value of \`\`\` l1.Ordinal <= l2.Ordinal \`\`\`
### op_GreaterThanOrEqual(LogLevel l1, LogLevel l2) {#op-GreaterThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_GreaterThanOrEqual(LogLevel l1, LogLevel l2)
```


Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is greater than or equal to the second one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | The first level. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | The second level. |

**Returns:**
boolean - The value of \`\`\` l1.Ordinal >= l2.Ordinal \`\`\`
### op_LessThan(LogLevel l1, LogLevel l2) {#op-LessThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_LessThan(LogLevel l1, LogLevel l2)
```


Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is less than the second one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | The first level. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | The second level. |

**Returns:**
boolean - The value of \`\`\` l1.Ordinal < l2.Ordinal \`\`\`
### op_GreaterThan(LogLevel l1, LogLevel l2) {#op-GreaterThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_GreaterThan(LogLevel l1, LogLevel l2)
```


Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is greater than the second one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | The first level. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | The second level. |

**Returns:**
boolean - The value of \`\`\` l1.Ordinal > l2.Ordinal \`\`\`
### toString() {#toString--}
```
public String toString()
```


Returns a string representation of the log level.

**Returns:**
java.lang.String - Log level name.
### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Compares the level to the other [LogLevel](../../com.aspose.email/loglevel) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | the object object |

**Returns:**
int - a value less than zero when this logger's \`\`\` Ordinal \`\`\`(\#getOrdinal) is less than the other logger's ordinal, 0 when they are equal and greater than zero when this ordinal is greater than the other ordinal.
