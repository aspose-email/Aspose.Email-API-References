---
title: LogLevel
second_title: Aspose.Email for Android via Java API Reference
description: Определяет доступные уровни журналирования.
type: docs
weight: 183
url: /ru/androidjava/com.aspose.email/loglevel/
---

**Inheritance:**
java.lang.Object
```
public class LogLevel
```

Определяет доступные уровни журналирования.
## Поля

| Поле | Описание |
| --- | --- |
| [Debug](#Debug) | Уровень Debug. |
| [Error](#Error) | Уровень Error. |
| [Fatal](#Fatal) | Уровень Fatal. |
| [Information](#Information) | Уровень Info. |
| [Trace](#Trace) | Уровень Trace. |
| [Warning](#Warning) | Уровень Warn. |
## Methods

| Method | Описание |
| --- | --- |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Сравнивает уровень с другим объектом [LogLevel](../../com.aspose.email/loglevel). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_GreaterThan(LogLevel l1, LogLevel l2)](#op-GreaterThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Сравнивает два объекта [LogLevel](../../com.aspose.email/loglevel) и возвращает значение, указывающее, больше ли первый второго. |
| [op_GreaterThanOrEqual(LogLevel l1, LogLevel l2)](#op-GreaterThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Сравнивает два объекта [LogLevel](../../com.aspose.email/loglevel) и возвращает значение, указывающее, больше ли первый или равен второму. |
| [op_LessThan(LogLevel l1, LogLevel l2)](#op-LessThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Сравнивает два объекта [LogLevel](../../com.aspose.email/loglevel) и возвращает значение, указывающее, меньше ли первый второго. |
| [op_LessThanOrEqual(LogLevel l1, LogLevel l2)](#op-LessThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Сравнивает два объекта [LogLevel](../../com.aspose.email/loglevel) и возвращает значение, указывающее, меньше ли первый или равен второму. |
| [toString()](#toString--) | Возвращает строковое представление уровня журнала. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Debug {#Debug}
```
public static final LogLevel Debug
```


Уровень Debug.

### Error {#Error}
```
public static final LogLevel Error
```


Уровень Error.

### Fatal {#Fatal}
```
public static final LogLevel Fatal
```


Уровень Fatal.

### Information {#Information}
```
public static final LogLevel Information
```


Уровень Info.

### Trace {#Trace}
```
public static final LogLevel Trace
```


Уровень Trace.

### Warning {#Warning}
```
public static final LogLevel Warning
```


Уровень Warn.

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Сравнивает уровень с другим объектом [LogLevel](../../com.aspose.email/loglevel).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | java.lang.Object | объект object |

**Returns:**
int - значение меньше нуля, когда Ordinal (\#getOrdinal.getOrdinal) этого логгера меньше Ordinal другого логгера, 0 когда они равны и больше нуля, когда этот Ordinal больше Ordinal другого.
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




### op_GreaterThan(LogLevel l1, LogLevel l2) {#op-GreaterThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_GreaterThan(LogLevel l1, LogLevel l2)
```


Сравнивает два объекта [LogLevel](../../com.aspose.email/loglevel) и возвращает значение, указывающее, больше ли первый второго.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | Первый уровень. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | Второй уровень. |

**Returns:**
boolean - Значение l1.Ordinal > l2.Ordinal
### op_GreaterThanOrEqual(LogLevel l1, LogLevel l2) {#op-GreaterThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_GreaterThanOrEqual(LogLevel l1, LogLevel l2)
```


Сравнивает два объекта [LogLevel](../../com.aspose.email/loglevel) и возвращает значение, указывающее, больше ли первый или равен второму.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | Первый уровень. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | Второй уровень. |

**Returns:**
boolean - Значение l1.Ordinal >= l2.Ordinal
### op_LessThan(LogLevel l1, LogLevel l2) {#op-LessThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_LessThan(LogLevel l1, LogLevel l2)
```


Сравнивает два объекта [LogLevel](../../com.aspose.email/loglevel) и возвращает значение, указывающее, меньше ли первый второго.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | Первый уровень. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | Второй уровень. |

**Returns:**
boolean - Значение l1.Ordinal < l2.Ordinal
### op_LessThanOrEqual(LogLevel l1, LogLevel l2) {#op-LessThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_LessThanOrEqual(LogLevel l1, LogLevel l2)
```


Сравнивает два объекта [LogLevel](../../com.aspose.email/loglevel) и возвращает значение, указывающее, меньше ли первый или равен второму.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | Первый уровень. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | Второй уровень. |

**Returns:**
boolean - Значение l1.Ordinal <= l2.Ordinal
### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление уровня журнала.

**Returns:**
java.lang.String - Имя уровня журнала.
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

