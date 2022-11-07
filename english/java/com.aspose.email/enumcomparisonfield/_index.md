---
title: EnumComparisonField
second_title: Aspose.Email for Java API Reference
description: Represents the enum search field.
type: docs
weight: 179
url: /java/com.aspose.email/enumcomparisonfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.QueryField](../../com.aspose.email/queryfield), [com.aspose.email.ComparisonField](../../com.aspose.email/comparisonfield)
```
public final class EnumComparisonField extends ComparisonField
```

Represents the enum search field.
## Methods

| Method | Description |
| --- | --- |
| [equals(int value)](#equals-int-) | Indicates that field in message must be equal to the specified value. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [in(Iterable<Integer> values)](#in-java.lang.Iterable-java.lang.Integer--) | Indicates that field vlaue in message must be in list of specified values. |
| [notEquals(int value)](#notEquals-int-) | Indicates that field in message must not be equal to the specified value. |
| [notIn(Iterable<Integer> values)](#notIn-java.lang.Iterable-java.lang.Integer--) | Indicates that field vlaue in message must not be in list of specified values. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [orderBy(boolean ascending)](#orderBy-boolean-) | Sets value which indicates if client uses ascending or descending sorting on the Field. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(int value) {#equals-int-}
```
public final MailQuery equals(int value)
```


Indicates that field in message must be equal to the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value. |

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### in(Iterable<Integer> values) {#in-java.lang.Iterable-java.lang.Integer--}
```
public final MailQuery in(Iterable<Integer> values)
```


Indicates that field vlaue in message must be in list of specified values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | java.lang.Iterable<java.lang.Integer> | Values . |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notEquals(int value) {#notEquals-int-}
```
public final MailQuery notEquals(int value)
```


Indicates that field in message must not be equal to the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notIn(Iterable<Integer> values) {#notIn-java.lang.Iterable-java.lang.Integer--}
```
public final MailQuery notIn(Iterable<Integer> values)
```


Indicates that field vlaue in message must not be in list of specified values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | java.lang.Iterable<java.lang.Integer> | Values . |

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




### orderBy(boolean ascending) {#orderBy-boolean-}
```
public final void orderBy(boolean ascending)
```


Sets value which indicates if client uses ascending or descending sorting on the Field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ascending | boolean | Set true if you want to use ascending sorting, otherwise set false. |

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

