---
title: StringComparisonField
second_title: Aspose.Email for Android via Java API 参考
description: 表示字符串搜索字段。
type: docs
weight: 393
url: /zh/androidjava/com.aspose.email/stringcomparisonfield/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.QueryField](../../com.aspose.email/queryfield), [com.aspose.email.ComparisonField](../../com.aspose.email/comparisonfield)
```
public final class StringComparisonField extends ComparisonField
```

表示字符串搜索字段。
## 方法

| 方法 | 描述 |
| --- | --- |
| [contains(String value)](#contains-java.lang.String-) | 指示消息中的字段必须包含指定的值。 |
| [contains(String value, boolean ignoreCase)](#contains-java.lang.String-boolean-) | 指示消息中的字段必须包含指定的值。 |
| [empty()](#empty--) | 指示消息中的字段必须为空。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [equals(String value)](#equals-java.lang.String-) | 指示消息中的字段必须等于指定的值。 |
| [equals(String value, boolean ignoreCase)](#equals-java.lang.String-boolean-) | 指示消息中的字段必须等于指定的值。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | hashCode。 |
| [notContains(String value)](#notContains-java.lang.String-) | 指示消息中的字段不得包含指定的值。 |
| [notContains(String value, boolean ignoreCase)](#notContains-java.lang.String-boolean-) | 指示消息中的字段不得包含指定的值。 |
| [notEmpty()](#notEmpty--) | 指示消息中的字段不得为空。 |
| [notEquals(String value)](#notEquals-java.lang.String-) | 指示消息中的字段不得等于指定的值。 |
| [notEquals(String value, boolean ignoreCase)](#notEquals-java.lang.String-boolean-) | 指示消息中的字段不得等于指定的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [orderBy(boolean ascending)](#orderBy-boolean-) | 设置值，以指示客户端在字段上使用升序还是降序排序。 |
| [setKQL(boolean isKQL)](#setKQL-boolean-) | 获取或设置定义属性是否用于关键字查询语言的值 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### contains(String value) {#contains-java.lang.String-}
```
public final MailQuery contains(String value)
```


指示消息中的字段必须包含指定的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 该值。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### contains(String value, boolean ignoreCase) {#contains-java.lang.String-boolean-}
```
public final MailQuery contains(String value, boolean ignoreCase)
```


指示消息中的字段必须包含指定的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 该值。 |
| ignoreCase | boolean | true 表示在比较时忽略大小写；否则为 false。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### empty() {#empty--}
```
public final MailQuery empty()
```


指示消息中的字段必须为空。

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### equals(String value) {#equals-java.lang.String-}
```
public final MailQuery equals(String value)
```


指示消息中的字段必须等于指定的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 该值。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### equals(String value, boolean ignoreCase) {#equals-java.lang.String-boolean-}
```
public final MailQuery equals(String value, boolean ignoreCase)
```


指示消息中的字段必须等于指定的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 该值。 |
| ignoreCase | boolean | true 表示在比较时忽略大小写；否则为 false。 |

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


hashCode。

**Returns:**
int - 一个整数。
### notContains(String value) {#notContains-java.lang.String-}
```
public final MailQuery notContains(String value)
```


指示消息中的字段不得包含指定的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 该值。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notContains(String value, boolean ignoreCase) {#notContains-java.lang.String-boolean-}
```
public final MailQuery notContains(String value, boolean ignoreCase)
```


指示消息中的字段不得包含指定的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 该值。 |
| ignoreCase | boolean | true 表示在比较时忽略大小写；否则为 false。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notEmpty() {#notEmpty--}
```
public final MailQuery notEmpty()
```


指示消息中的字段不得为空。

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notEquals(String value) {#notEquals-java.lang.String-}
```
public final MailQuery notEquals(String value)
```


指示消息中的字段不得等于指定的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 该值。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notEquals(String value, boolean ignoreCase) {#notEquals-java.lang.String-boolean-}
```
public final MailQuery notEquals(String value, boolean ignoreCase)
```


指示消息中的字段不得等于指定的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 该值。 |
| ignoreCase | boolean | true 表示在比较时忽略大小写；否则为 false。 |

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


设置值，以指示客户端在字段上使用升序还是降序排序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 升序 | boolean | 如果想使用升序排序，请设为 true，否则设为 false。 |

### setKQL(boolean isKQL) {#setKQL-boolean-}
```
public final StringComparisonField setKQL(boolean isKQL)
```


获取或设置定义属性是否用于关键字查询语言的值

**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

