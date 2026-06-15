---
title: StringComparisonField
second_title: Aspose.Email for Android via Java API Reference
description: Представляет поле поиска строки.
type: docs
weight: 393
url: /ru/androidjava/com.aspose.email/stringcomparisonfield/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.QueryField](../../com.aspose.email/queryfield), [com.aspose.email.ComparisonField](../../com.aspose.email/comparisonfield)
```
public final class StringComparisonField extends ComparisonField
```

Представляет поле поиска строки.
## Methods

| Method | Описание |
| --- | --- |
| [contains(String value)](#contains-java.lang.String-) | Указывает, что поле в сообщении должно содержать указанное значение. |
| [contains(String value, boolean ignoreCase)](#contains-java.lang.String-boolean-) | Указывает, что поле в сообщении должно содержать указанное значение. |
| [empty()](#empty--) | Указывает, что поле в сообщении должно быть пустым. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [equals(String value)](#equals-java.lang.String-) | Указывает, что поле в сообщении должно быть равно указанному значению. |
| [equals(String value, boolean ignoreCase)](#equals-java.lang.String-boolean-) | Указывает, что поле в сообщении должно быть равно указанному значению. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | hashCode. |
| [notContains(String value)](#notContains-java.lang.String-) | Указывает, что поле в сообщении не должно содержать указанное значение. |
| [notContains(String value, boolean ignoreCase)](#notContains-java.lang.String-boolean-) | Указывает, что поле в сообщении не должно содержать указанное значение. |
| [notEmpty()](#notEmpty--) | Указывает, что поле в сообщении не должно быть пустым. |
| [notEquals(String value)](#notEquals-java.lang.String-) | Указывает, что поле в сообщении не должно быть равно указанному значению. |
| [notEquals(String value, boolean ignoreCase)](#notEquals-java.lang.String-boolean-) | Указывает, что поле в сообщении не должно быть равно указанному значению. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [orderBy(boolean ascending)](#orderBy-boolean-) | Устанавливает значение, указывающее, использует ли клиент сортировку по возрастанию или убыванию по полю. |
| [setKQL(boolean isKQL)](#setKQL-boolean-) | Получает или задает значение, определяющее, используется ли свойство для Keyword Query Language |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### contains(String value) {#contains-java.lang.String-}
```
public final MailQuery contains(String value)
```


Указывает, что поле в сообщении должно содержать указанное значение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### contains(String value, boolean ignoreCase) {#contains-java.lang.String-boolean-}
```
public final MailQuery contains(String value, boolean ignoreCase)
```


Указывает, что поле в сообщении должно содержать указанное значение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение. |
| ignoreCase | boolean | true — игнорировать регистр при сравнении; иначе false. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### empty() {#empty--}
```
public final MailQuery empty()
```


Указывает, что поле в сообщении должно быть пустым.

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
### equals(String value) {#equals-java.lang.String-}
```
public final MailQuery equals(String value)
```


Указывает, что поле в сообщении должно быть равно указанному значению.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### equals(String value, boolean ignoreCase) {#equals-java.lang.String-boolean-}
```
public final MailQuery equals(String value, boolean ignoreCase)
```


Указывает, что поле в сообщении должно быть равно указанному значению.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение. |
| ignoreCase | boolean | true — игнорировать регистр при сравнении; иначе false. |

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
int - целое число.
### notContains(String value) {#notContains-java.lang.String-}
```
public final MailQuery notContains(String value)
```


Указывает, что поле в сообщении не должно содержать указанное значение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notContains(String value, boolean ignoreCase) {#notContains-java.lang.String-boolean-}
```
public final MailQuery notContains(String value, boolean ignoreCase)
```


Указывает, что поле в сообщении не должно содержать указанное значение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение. |
| ignoreCase | boolean | true — игнорировать регистр при сравнении; иначе false. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notEmpty() {#notEmpty--}
```
public final MailQuery notEmpty()
```


Указывает, что поле в сообщении не должно быть пустым.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notEquals(String value) {#notEquals-java.lang.String-}
```
public final MailQuery notEquals(String value)
```


Указывает, что поле в сообщении не должно быть равно указанному значению.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### notEquals(String value, boolean ignoreCase) {#notEquals-java.lang.String-boolean-}
```
public final MailQuery notEquals(String value, boolean ignoreCase)
```


Указывает, что поле в сообщении не должно быть равно указанному значению.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение. |
| ignoreCase | boolean | true — игнорировать регистр при сравнении; иначе false. |

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


Устанавливает значение, указывающее, использует ли клиент сортировку по возрастанию или убыванию по полю.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ascending | boolean | Установите true, если хотите использовать сортировку по возрастанию, иначе установите false. |

### setKQL(boolean isKQL) {#setKQL-boolean-}
```
public final StringComparisonField setKQL(boolean isKQL)
```


Получает или задает значение, определяющее, используется ли свойство для Keyword Query Language

**Parameters:**
| Parameter | Type | Описание |
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

