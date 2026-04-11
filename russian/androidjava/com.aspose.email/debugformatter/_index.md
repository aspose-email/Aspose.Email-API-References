---
title: DebugFormatter
second_title: Aspose.Email for Android via Java API Reference
description: Представляет класс для форматирования сообщений журналов.
type: docs
weight: 109
url: /ru/androidjava/com.aspose.email/debugformatter/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.Formatter](../../com.aspose.email/formatter)
```
public class DebugFormatter extends Formatter
```

Представляет класс для форматирования сообщений журналов.
## Constructors

| Constructor | Описание |
| --- | --- |
| [DebugFormatter()](#DebugFormatter--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(LogEntry entry)](#format-com.aspose.email.LogEntry-) | Форматирует запись журнала и возвращает строку для вывода. |
| [format(Date datatime)](#format-java.util.Date-) | Форматирует дату и время и возвращает строку для вывода. |
| [getClass()](#getClass--) |  |
| [getDefaultFormatter()](#getDefaultFormatter--) | Получает или задает форматтер по умолчанию |
| [getFooter()](#getFooter--) | Получает или задает нижний колонтитул. |
| [getHeader()](#getHeader--) | Получает или задает верхний колонтитул. |
| [getLogHeader()](#getLogHeader--) | Получает или задает заголовок журнала |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFormatter(IFormatter value)](#setDefaultFormatter-com.aspose.email.IFormatter-) | Получает или задает форматтер по умолчанию |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DebugFormatter() {#DebugFormatter--}
```
public DebugFormatter()
```


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
### format(LogEntry entry) {#format-com.aspose.email.LogEntry-}
```
public String format(LogEntry entry)
```


Форматирует запись журнала и возвращает строку для вывода.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | Запись журнала для форматирования. |

**Returns:**
java.lang.String - Строка, представляющая запись журнала.
### format(Date datatime) {#format-java.util.Date-}
```
public String format(Date datatime)
```


Форматирует дату и время и возвращает строку для вывода.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| datatime | java.util.Date | Значение даты и времени для форматирования в строку |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFormatter() {#getDefaultFormatter--}
```
public static IFormatter getDefaultFormatter()
```


Получает или задает форматтер по умолчанию

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### getFooter() {#getFooter--}
```
public String getFooter()
```


Получает или задает нижний колонтитул.

**Returns:**
java.lang.String
### getHeader() {#getHeader--}
```
public String getHeader()
```


Получает или задает верхний колонтитул.

**Returns:**
java.lang.String
### getLogHeader() {#getLogHeader--}
```
public String getLogHeader()
```


Получает или задает заголовок журнала

**Returns:**
java.lang.String
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




### setDefaultFormatter(IFormatter value) {#setDefaultFormatter-com.aspose.email.IFormatter-}
```
public static void setDefaultFormatter(IFormatter value)
```


Получает или задает форматтер по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

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

