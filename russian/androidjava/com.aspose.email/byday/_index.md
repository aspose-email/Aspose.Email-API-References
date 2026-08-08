---
title: ByDay
second_title: Aspose.Email for Android via Java API Reference
description: Представляет N‑й случай или все случаи указанного дня недели.
type: docs
weight: 62
url: /ru/androidjava/com.aspose.email/byday/
---

**Inheritance:**
java.lang.Object
```
public class ByDay
```

Представляет N‑е (или все) вхождения указанного дня недели.

--------------------



Соответствует одному дню недели, указанному в части BYDAY правила повторения.

 

Можно использовать в месячном или годовом правиле повторения, чтобы указать N‑й (или все) случай указанного дня недели в месяце или году.

 

BYDAY=MO представляет все понедельники месяца или года. Чтобы представить все случаи, установите NthOccurrence в 0.

 

BYDAY=2MO представляет второй понедельник месяца или года.

 

BYDAY=-1MO представляет последний понедельник месяца или года.


## Constructors

| Constructor | Описание |
| --- | --- |
| [ByDay(int dayOfWeek)](#ByDay-int-) | Инициализирует новый экземпляр класса ByDay. |
| [ByDay(int nthOccurrence, int dayOfWeek)](#ByDay-int-int-) | Инициализирует новый экземпляр класса ByDay. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный Object текущему Object. |
| [getClass()](#getClass--) |  |
| [getDayOfWeek()](#getDayOfWeek--) | Получает или задает день недели. |
| [getNthOccurrence()](#getNthOccurrence--) | Получает или задает N‑й случай дня недели. |
| [hashCode()](#hashCode--) | GetHashCode возвращает хеш‑функцию для этого объекта. |
| [isAllOccurrences()](#isAllOccurrences--) | Возвращает True, когда NthOccurrence равно нулю (что означает все случаи этого дня недели). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDayOfWeek(int value)](#setDayOfWeek-int-) | Получает или задает день недели. |
| [setNthOccurrence(int value)](#setNthOccurrence-int-) | Получает или задает N‑й случай дня недели. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ByDay(int dayOfWeek) {#ByDay-int-}
```
public ByDay(int dayOfWeek)
```


Инициализирует новый экземпляр класса ByDay.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| dayOfWeek | int | День недели. |

### ByDay(int nthOccurrence, int dayOfWeek) {#ByDay-int-int-}
```
public ByDay(int nthOccurrence, int dayOfWeek)
```


Инициализирует новый экземпляр класса ByDay.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| nthOccurrence | int | N‑й случай дня недели. |
| dayOfWeek | int | День недели. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный Object текущему Object.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с текущим объектом. |

**Returns:**
boolean - Возвращает логическое значение, указывающее, равен ли переданный объект obj этому.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDayOfWeek() {#getDayOfWeek--}
```
public final int getDayOfWeek()
```


Получает или задает день недели.

**Returns:**
int
### getNthOccurrence() {#getNthOccurrence--}
```
public final int getNthOccurrence()
```


Получает или задает N‑й случай дня недели.

--------------------



Допустимый диапазон для этого свойства от -53 до 53.

 

Положительные значения представляют N‑й случай с начала периода, например NthOccurrence = 1 представляет первый случай дня недели.

 

Отрицательные значения представляют N‑й случай с конца периода, например NthOccurrence = -1 представляет последний случай дня недели.

 

Когда NthOccurrence равно нулю, он представляет все случаи указанного дня недели. Например, BYDAY=MO имеет NthOccurrence равное нулю и представляет все понедельники в наборе.



**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode возвращает хеш‑функцию для этого объекта.

**Returns:**
int - Возвращает хеш-функцию для этого объекта.
### isAllOccurrences() {#isAllOccurrences--}
```
public final boolean isAllOccurrences()
```


Возвращает True, когда NthOccurrence равно нулю (что означает все случаи этого дня недели).

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDayOfWeek(int value) {#setDayOfWeek-int-}
```
public final void setDayOfWeek(int value)
```


Получает или задает день недели.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setNthOccurrence(int value) {#setNthOccurrence-int-}
```
public final void setNthOccurrence(int value)
```


Получает или задает N‑й случай дня недели.

--------------------



Допустимый диапазон для этого свойства от -53 до 53.

 

Положительные значения представляют N‑й случай с начала периода, например NthOccurrence = 1 представляет первый случай дня недели.

 

Отрицательные значения представляют N‑й случай с конца периода, например NthOccurrence = -1 представляет последний случай дня недели.

 

Когда NthOccurrence равно нулю, он представляет все случаи указанного дня недели. Например, BYDAY=MO имеет NthOccurrence равное нулю и представляет все понедельники в наборе.



**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

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

