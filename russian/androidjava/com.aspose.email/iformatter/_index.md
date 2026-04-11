---
title: IFormatter
second_title: Aspose.Email for Android via Java API Reference
description: Представляет интерфейс для форматирования сообщений записей журнала.
type: docs
weight: 455
url: /ru/androidjava/com.aspose.email/iformatter/
---
```
public interface IFormatter
```

Представляет интерфейс для форматирования сообщений записей журнала.
## Methods

| Method | Описание |
| --- | --- |
| [format(LogEntry entry)](#format-com.aspose.email.LogEntry-) | Форматирует запись журнала и возвращает строку для вывода. |
| [format(Date datatime)](#format-java.util.Date-) | Форматирует дату и время и возвращает строку для вывода. |
| [getFooter()](#getFooter--) | Получает строку нижнего колонтитула. |
| [getHeader()](#getHeader--) | Gets the header string. |
| [getLogHeader()](#getLogHeader--) | Represents start log header |
### format(LogEntry entry) {#format-com.aspose.email.LogEntry-}
```
public abstract String format(LogEntry entry)
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
public abstract String format(Date datatime)
```


Форматирует дату и время и возвращает строку для вывода.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| datatime | java.util.Date | Значение даты и времени для форматирования в строку |

**Returns:**
java.lang.String - Строка, представляющая запись журнала.
### getFooter() {#getFooter--}
```
public abstract String getFooter()
```


Получает строку нижнего колонтитула.

**Returns:**
java.lang.String
### getHeader() {#getHeader--}
```
public abstract String getHeader()
```


Gets the header string.

**Returns:**
java.lang.String
### getLogHeader() {#getLogHeader--}
```
public abstract String getLogHeader()
```


Represents start log header

**Returns:**
java.lang.String
