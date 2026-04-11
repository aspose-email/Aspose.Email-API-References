---
title: DateComparisonField
second_title: Aspose.Email for Android via Java API 参考
description: 表示日期搜索字段。
type: docs
weight: 102
url: /zh/androidjava/com.aspose.email/datecomparisonfield/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.QueryField](../../com.aspose.email/queryfield), [com.aspose.email.ComparisonField](../../com.aspose.email/comparisonfield)
```
public final class DateComparisonField extends ComparisonField
```

表示日期搜索字段。
## 方法

| 方法 | 描述 |
| --- | --- |
| [before(Date value)](#before-java.util.Date-) | 指示消息中的日期必须早于指定日期。 |
| [before(Date value, int comparisonType)](#before-java.util.Date-int-) | 指示消息中的日期必须早于指定日期。 |
| [beforeOrEqual(Date value)](#beforeOrEqual-java.util.Date-) | 指示消息中的日期必须早于或等于指定日期。 |
| [beforeOrEqual(Date value, int comparisonType)](#beforeOrEqual-java.util.Date-int-) | 指示消息中的日期必须早于或等于指定日期。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [greater(Date value)](#greater-java.util.Date-) | 指示消息中的日期必须晚于指定日期。 |
| [greater(Date value, int comparisonType)](#greater-java.util.Date-int-) | 指示消息中的日期必须晚于指定日期。 |
| [hashCode()](#hashCode--) |  |
| [notOn(Date value)](#notOn-java.util.Date-) | 指示消息中的日期不得在指定日期内。 |
| [notOn(Date value, int comparisonType)](#notOn-java.util.Date-int-) | 指示消息中的日期不得在指定日期内。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [on(Date value)](#on-java.util.Date-) | 指示消息中的日期必须在指定日期范围内。 |
| [on(Date value, int comparisonType)](#on-java.util.Date-int-) | 指示消息中的日期必须在指定日期范围内。 |
| [orderBy(boolean ascending)](#orderBy-boolean-) | 设置值，以指示客户端在字段上使用升序还是降序排序。 |
| [since(Date value)](#since-java.util.Date-) | 指示消息中的日期必须在指定日期范围内或晚于该日期。 |
| [since(Date value, int comparisonType)](#since-java.util.Date-int-) | 指示消息中的日期必须在指定日期范围内或晚于该日期。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### before(Date value) {#before-java.util.Date-}
```
public final MailQuery before(Date value)
```


指示消息中的日期必须早于指定日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### before(Date value, int comparisonType) {#before-java.util.Date-int-}
```
public final MailQuery before(Date value, int comparisonType)
```


指示消息中的日期必须早于指定日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |
| comparisonType | int | 指定比较类型 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### beforeOrEqual(Date value) {#beforeOrEqual-java.util.Date-}
```
public final MailQuery beforeOrEqual(Date value)
```


指示消息中的日期必须早于或等于指定日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### beforeOrEqual(Date value, int comparisonType) {#beforeOrEqual-java.util.Date-int-}
```
public final MailQuery beforeOrEqual(Date value, int comparisonType)
```


指示消息中的日期必须早于或等于指定日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |
| comparisonType | int | 指定比较类型 |

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


指示消息中的日期必须晚于指定日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### greater(Date value, int comparisonType) {#greater-java.util.Date-int-}
```
public final MailQuery greater(Date value, int comparisonType)
```


指示消息中的日期必须晚于指定日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |
| comparisonType | int | 指定比较类型 |

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


指示消息中的日期不得在指定日期内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notOn(Date value, int comparisonType) {#notOn-java.util.Date-int-}
```
public final MailQuery notOn(Date value, int comparisonType)
```


指示消息中的日期不得在指定日期内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |
| comparisonType | int | 指定比较类型 |

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


指示消息中的日期必须在指定日期范围内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### on(Date value, int comparisonType) {#on-java.util.Date-int-}
```
public final MailQuery on(Date value, int comparisonType)
```


指示消息中的日期必须在指定日期范围内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |
| comparisonType | int | 指定比较类型 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### orderBy(boolean ascending) {#orderBy-boolean-}
```
public final void orderBy(boolean ascending)
```


设置值，以指示客户端在字段上使用升序还是降序排序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 升序 | boolean | 如果想使用升序排序，请设为 true，否则设为 false。 |

### since(Date value) {#since-java.util.Date-}
```
public final MailQuery since(Date value)
```


指示消息中的日期必须在指定日期范围内或晚于该日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### since(Date value, int comparisonType) {#since-java.util.Date-int-}
```
public final MailQuery since(Date value, int comparisonType)
```


指示消息中的日期必须在指定日期范围内或晚于该日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 该值。 |
| comparisonType | int | 指定比较类型 |

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

