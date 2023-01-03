---
title: StringComparisonField
second_title: Aspose.Email for Java API Reference
description: Represents the string search field.
type: docs
weight: 652
url: /java/com.aspose.email/stringcomparisonfield/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.QueryField](../../com.aspose.email/queryfield), [com.aspose.email.ComparisonField](../../com.aspose.email/comparisonfield)
```
public final class StringComparisonField extends ComparisonField
```

Represents the string search field.
## Methods

| Method | Description |
| --- | --- |
| [contains(String value)](#contains-java.lang.String-) | Indicates that field in message must contain the specified value. |
| [contains(String value, boolean ignoreCase)](#contains-java.lang.String-boolean-) | Indicates that field in message must contain the specified value. |
| [empty()](#empty--) | Indicates that field in message must be empty. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [equals(String value)](#equals-java.lang.String-) | Indicates that field in message must be equal to the specified value. |
| [equals(String value, boolean ignoreCase)](#equals-java.lang.String-boolean-) | Indicates that field in message must be equal to the specified value. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | hashCode. |
| [notContains(String value)](#notContains-java.lang.String-) | Indicates that field in message must not contain the specified value. |
| [notContains(String value, boolean ignoreCase)](#notContains-java.lang.String-boolean-) | Indicates that field in message must not contain the specified value. |
| [notEmpty()](#notEmpty--) | Indicates that field in message must not be empty. |
| [notEquals(String value)](#notEquals-java.lang.String-) | Indicates that field in message must not be equal to the specified value. |
| [notEquals(String value, boolean ignoreCase)](#notEquals-java.lang.String-boolean-) | Indicates that field in message must not be equal to the specified value. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [orderBy(boolean ascending)](#orderBy-boolean-) | Sets value which indicates if client uses ascending or descending sorting on the Field. |
| [setKQL(boolean isKQL)](#setKQL-boolean-) | Gets or sets value which defines whether property is used for Keyword Query Language |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### contains(String value) {#contains-java.lang.String-}
```
public final MailQuery contains(String value)
```


Indicates that field in message must contain the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### contains(String value, boolean ignoreCase) {#contains-java.lang.String-boolean-}
```
public final MailQuery contains(String value, boolean ignoreCase)
```


Indicates that field in message must contain the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |
| ignoreCase | boolean | true to ignore case during the comparison; otherwise, false. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### empty() {#empty--}
```
public final MailQuery empty()
```


Indicates that field in message must be empty.

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
### equals(String value) {#equals-java.lang.String-}
```
public final MailQuery equals(String value)
```


Indicates that field in message must be equal to the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### equals(String value, boolean ignoreCase) {#equals-java.lang.String-boolean-}
```
public final MailQuery equals(String value, boolean ignoreCase)
```


Indicates that field in message must be equal to the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |
| ignoreCase | boolean | true to ignore case during the comparison; otherwise, false. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


hashCode.

**Returns:**
int - a int.
### notContains(String value) {#notContains-java.lang.String-}
```
public final MailQuery notContains(String value)
```


Indicates that field in message must not contain the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notContains(String value, boolean ignoreCase) {#notContains-java.lang.String-boolean-}
```
public final MailQuery notContains(String value, boolean ignoreCase)
```


Indicates that field in message must not contain the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |
| ignoreCase | boolean | true to ignore case during the comparison; otherwise, false. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notEmpty() {#notEmpty--}
```
public final MailQuery notEmpty()
```


Indicates that field in message must not be empty.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notEquals(String value) {#notEquals-java.lang.String-}
```
public final MailQuery notEquals(String value)
```


Indicates that field in message must not be equal to the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notEquals(String value, boolean ignoreCase) {#notEquals-java.lang.String-boolean-}
```
public final MailQuery notEquals(String value, boolean ignoreCase)
```


Indicates that field in message must not be equal to the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |
| ignoreCase | boolean | true to ignore case during the comparison; otherwise, false. |

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

### setKQL(boolean isKQL) {#setKQL-boolean-}
```
public final StringComparisonField setKQL(boolean isKQL)
```


Gets or sets value which defines whether property is used for Keyword Query Language

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isKQL | boolean |  |

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - 
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

