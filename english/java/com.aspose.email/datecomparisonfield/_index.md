---
title: DateComparisonField
second_title: Aspose.Email for Java API Reference
description: Represents the date search field.
type: docs
weight: 143
url: /java/com.aspose.email/datecomparisonfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.QueryField](../../com.aspose.email/queryfield), [com.aspose.email.ComparisonField](../../com.aspose.email/comparisonfield)
```
public final class DateComparisonField extends ComparisonField
```

Represents the date search field.
## Methods

| Method | Description |
| --- | --- |
| [before(Date value)](#before-java.util.Date-) | Indicates that the date in message must be earlier than the specified date. |
| [before(Date value, int comparisonType)](#before-java.util.Date-int-) | Indicates that the date in message must be earlier than the specified date. |
| [beforeOrEqual(Date value)](#beforeOrEqual-java.util.Date-) | Indicates that the date in message must be earlier or equel to the specified date. |
| [beforeOrEqual(Date value, int comparisonType)](#beforeOrEqual-java.util.Date-int-) | Indicates that the date in message must be earlier or equel to the specified date. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [greater(Date value)](#greater-java.util.Date-) | Indicates that date in message must be later than the specified date. |
| [greater(Date value, int comparisonType)](#greater-java.util.Date-int-) | Indicates that date in message must be later than the specified date. |
| [hashCode()](#hashCode--) |  |
| [notOn(Date value)](#notOn-java.util.Date-) | Indicates that the date in message must not be in the specified date. |
| [notOn(Date value, int comparisonType)](#notOn-java.util.Date-int-) | Indicates that the date in message must not be in the specified date. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [on(Date value)](#on-java.util.Date-) | Indicates that the date in message must be within the specified date. |
| [on(Date value, int comparisonType)](#on-java.util.Date-int-) | Indicates that the date in message must be within the specified date. |
| [orderBy(boolean ascending)](#orderBy-boolean-) | Sets value which indicates if client uses ascending or descending sorting on the Field. |
| [since(Date value)](#since-java.util.Date-) | Indicates that date in message must be within or later than the specified date. |
| [since(Date value, int comparisonType)](#since-java.util.Date-int-) | Indicates that date in message must be within or later than the specified date. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### before(Date value) {#before-java.util.Date-}
```
public final MailQuery before(Date value)
```


Indicates that the date in message must be earlier than the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### before(Date value, int comparisonType) {#before-java.util.Date-int-}
```
public final MailQuery before(Date value, int comparisonType)
```


Indicates that the date in message must be earlier than the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |
| comparisonType | int | Specifies a type of comparison |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### beforeOrEqual(Date value) {#beforeOrEqual-java.util.Date-}
```
public final MailQuery beforeOrEqual(Date value)
```


Indicates that the date in message must be earlier or equel to the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### beforeOrEqual(Date value, int comparisonType) {#beforeOrEqual-java.util.Date-int-}
```
public final MailQuery beforeOrEqual(Date value, int comparisonType)
```


Indicates that the date in message must be earlier or equel to the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |
| comparisonType | int | Specifies a type of comparison |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### greater(Date value) {#greater-java.util.Date-}
```
public final MailQuery greater(Date value)
```


Indicates that date in message must be later than the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### greater(Date value, int comparisonType) {#greater-java.util.Date-int-}
```
public final MailQuery greater(Date value, int comparisonType)
```


Indicates that date in message must be later than the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |
| comparisonType | int | Specifies a type of comparison |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notOn(Date value) {#notOn-java.util.Date-}
```
public final MailQuery notOn(Date value)
```


Indicates that the date in message must not be in the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notOn(Date value, int comparisonType) {#notOn-java.util.Date-int-}
```
public final MailQuery notOn(Date value, int comparisonType)
```


Indicates that the date in message must not be in the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |
| comparisonType | int | Specifies a type of comparison |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### on(Date value) {#on-java.util.Date-}
```
public final MailQuery on(Date value)
```


Indicates that the date in message must be within the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### on(Date value, int comparisonType) {#on-java.util.Date-int-}
```
public final MailQuery on(Date value, int comparisonType)
```


Indicates that the date in message must be within the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |
| comparisonType | int | Specifies a type of comparison |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### orderBy(boolean ascending) {#orderBy-boolean-}
```
public final void orderBy(boolean ascending)
```


Sets value which indicates if client uses ascending or descending sorting on the Field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ascending | boolean | Set true if you want to use ascending sorting, otherwise set false. |

### since(Date value) {#since-java.util.Date-}
```
public final MailQuery since(Date value)
```


Indicates that date in message must be within or later than the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### since(Date value, int comparisonType) {#since-java.util.Date-int-}
```
public final MailQuery since(Date value, int comparisonType)
```


Indicates that date in message must be within or later than the specified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value. |
| comparisonType | int | Specifies a type of comparison |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
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

