---
title: EnumComparisonField
second_title: Aspose.Email for Java API Reference
description:  Represents the enum search field.
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
| [notEquals(int value)](#notEquals-int-) | Indicates that field in message must not be equal to the specified value. |
| [in(Iterable<Integer> values)](#in-java.lang.Iterable-java.lang.Integer--) | Indicates that field vlaue in message must be in list of specified values. |
| [notIn(Iterable<Integer> values)](#notIn-java.lang.Iterable-java.lang.Integer--) | Indicates that field vlaue in message must not be in list of specified values. |
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
