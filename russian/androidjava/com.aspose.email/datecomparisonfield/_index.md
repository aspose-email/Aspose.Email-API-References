---
title: DateComparisonField
second_title: Aspose.Email for Android via Java API Reference
description: Представляет поле поиска даты.
type: docs
weight: 102
url: /ru/androidjava/com.aspose.email/datecomparisonfield/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.QueryField](../../com.aspose.email/queryfield), [com.aspose.email.ComparisonField](../../com.aspose.email/comparisonfield)
```
public final class DateComparisonField extends ComparisonField
```

Представляет поле поиска даты.
## Methods

| Method | Описание |
| --- | --- |
| [before(Date value)](#before-java.util.Date-) | Указывает, что дата в сообщении должна быть раньше указанной даты. |
| [before(Date value, int comparisonType)](#before-java.util.Date-int-) | Указывает, что дата в сообщении должна быть раньше указанной даты. |
| [beforeOrEqual(Date value)](#beforeOrEqual-java.util.Date-) | Указывает, что дата в сообщении должна быть раньше или равна указанной дате. |
| [beforeOrEqual(Date value, int comparisonType)](#beforeOrEqual-java.util.Date-int-) | Указывает, что дата в сообщении должна быть раньше или равна указанной дате. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [greater(Date value)](#greater-java.util.Date-) | Указывает, что дата в сообщении должна быть позже указанной даты. |
| [greater(Date value, int comparisonType)](#greater-java.util.Date-int-) | Указывает, что дата в сообщении должна быть позже указанной даты. |
| [hashCode()](#hashCode--) |  |
| [notOn(Date value)](#notOn-java.util.Date-) | Указывает, что дата в сообщении не должна находиться в указанной дате. |
| [notOn(Date value, int comparisonType)](#notOn-java.util.Date-int-) | Указывает, что дата в сообщении не должна находиться в указанной дате. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [on(Date value)](#on-java.util.Date-) | Указывает, что дата в сообщении должна находиться в пределах указанной даты. |
| [on(Date value, int comparisonType)](#on-java.util.Date-int-) | Указывает, что дата в сообщении должна находиться в пределах указанной даты. |
| [orderBy(boolean ascending)](#orderBy-boolean-) | Устанавливает значение, указывающее, использует ли клиент сортировку по возрастанию или убыванию по полю. |
| [since(Date value)](#since-java.util.Date-) | Указывает, что дата в сообщении должна быть в пределах или позже указанной даты. |
| [since(Date value, int comparisonType)](#since-java.util.Date-int-) | Указывает, что дата в сообщении должна быть в пределах или позже указанной даты. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### before(Date value) {#before-java.util.Date-}
```
public final MailQuery before(Date value)
```


Указывает, что дата в сообщении должна быть раньше указанной даты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### before(Date value, int comparisonType) {#before-java.util.Date-int-}
```
public final MailQuery before(Date value, int comparisonType)
```


Указывает, что дата в сообщении должна быть раньше указанной даты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |
| comparisonType | int | Указывает тип сравнения |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### beforeOrEqual(Date value) {#beforeOrEqual-java.util.Date-}
```
public final MailQuery beforeOrEqual(Date value)
```


Указывает, что дата в сообщении должна быть раньше или равна указанной дате.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### beforeOrEqual(Date value, int comparisonType) {#beforeOrEqual-java.util.Date-int-}
```
public final MailQuery beforeOrEqual(Date value, int comparisonType)
```


Указывает, что дата в сообщении должна быть раньше или равна указанной дате.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |
| comparisonType | int | Указывает тип сравнения |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Описание |
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


Указывает, что дата в сообщении должна быть позже указанной даты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### greater(Date value, int comparisonType) {#greater-java.util.Date-int-}
```
public final MailQuery greater(Date value, int comparisonType)
```


Указывает, что дата в сообщении должна быть позже указанной даты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |
| comparisonType | int | Указывает тип сравнения |

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


Указывает, что дата в сообщении не должна находиться в указанной дате.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notOn(Date value, int comparisonType) {#notOn-java.util.Date-int-}
```
public final MailQuery notOn(Date value, int comparisonType)
```


Указывает, что дата в сообщении не должна находиться в указанной дате.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |
| comparisonType | int | Указывает тип сравнения |

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


Указывает, что дата в сообщении должна находиться в пределах указанной даты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### on(Date value, int comparisonType) {#on-java.util.Date-int-}
```
public final MailQuery on(Date value, int comparisonType)
```


Указывает, что дата в сообщении должна находиться в пределах указанной даты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |
| comparisonType | int | Указывает тип сравнения |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### orderBy(boolean ascending) {#orderBy-boolean-}
```
public final void orderBy(boolean ascending)
```


Устанавливает значение, указывающее, использует ли клиент сортировку по возрастанию или убыванию по полю.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ascending | boolean | Установите true, если хотите использовать сортировку по возрастанию, иначе установите false. |

### since(Date value) {#since-java.util.Date-}
```
public final MailQuery since(Date value)
```


Указывает, что дата в сообщении должна быть в пределах или позже указанной даты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### since(Date value, int comparisonType) {#since-java.util.Date-int-}
```
public final MailQuery since(Date value, int comparisonType)
```


Указывает, что дата в сообщении должна быть в пределах или позже указанной даты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение. |
| comparisonType | int | Указывает тип сравнения |

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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

