---
title: IAppender
second_title: Aspose.Email for Android via Java API Reference
description: Реализуйте этот интерфейс для собственных стратегий печати записей журнала.
type: docs
weight: 452
url: /ru/androidjava/com.aspose.email/iappender/
---
```
public interface IAppender
```

Реализуйте этот интерфейс для собственных стратегий печати записей журнала.
## Methods

| Method | Описание |
| --- | --- |
| [append(LogEntry entry)](#append-com.aspose.email.LogEntry-) | Записать указанную запись журнала специфическим для Appender способом. |
| [appendHeader()](#appendHeader--) | Начинает файл журнала с определённого заголовка. |
| [getFormatter()](#getFormatter--) | Получает или задаёт IFormatter. |
| [setFormatter(IFormatter value)](#setFormatter-com.aspose.email.IFormatter-) | Получает или задаёт IFormatter. |
### append(LogEntry entry) {#append-com.aspose.email.LogEntry-}
```
public abstract void append(LogEntry entry)
```


Записать указанную запись журнала специфическим для Appender способом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | Содержит сообщение журнала. |

### appendHeader() {#appendHeader--}
```
public abstract void appendHeader()
```


Начинает файл журнала с определённого заголовка.

### getFormatter() {#getFormatter--}
```
public abstract IFormatter getFormatter()
```


Получает или задаёт IFormatter.

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### setFormatter(IFormatter value) {#setFormatter-com.aspose.email.IFormatter-}
```
public abstract void setFormatter(IFormatter value)
```


Получает или задаёт IFormatter.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

