---
title: LogEntry
second_title: Справочник по Aspose.Email для .NET API
description: Представляет сообщение журнала. Содержит общие свойства необходимые для всех сообщений журнала.
type: docs
weight: 20470
url: /ru/net/aspose.email.tools.logging/logentry/
---
## LogEntry class

Представляет сообщение журнала. Содержит общие свойства, необходимые для всех сообщений журнала.

```csharp
public class LogEntry
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LogEntry](logentry#constructor)() | Инициализировать новый экземпляр класса[`LogEntry`](../logentry). |
| [LogEntry](logentry#constructor_1)(byte[]) | Создать новый экземпляр[`LogEntry`](../logentry)с полным набором параметров конструктора |
| [LogEntry](logentry#constructor_5)(string) | Инициализировать новый экземпляр класса[`LogEntry`](../logentry). |
| [LogEntry](logentry#constructor_3)(byte[], Encoding) | Создать новый экземпляр[`LogEntry`](../logentry)с полным набором параметров конструктора |
| [LogEntry](logentry#constructor_2)(byte[], IDictionary&lt;string, string&gt;) | Создать новый экземпляр[`LogEntry`](../logentry)с полным набором параметров конструктора |
| [LogEntry](logentry#constructor_9)(string, DateTime) | Инициализировать новый экземпляр класса[`LogEntry`](../logentry). |
| [LogEntry](logentry#constructor_10)(string, Exception) | Инициализировать новый экземпляр класса[`LogEntry`](../logentry). |
| [LogEntry](logentry#constructor_8)(string, IDictionary&lt;string, string&gt;) | Создать новый экземпляр[`LogEntry`](../logentry)с полным набором параметров конструктора |
| [LogEntry](logentry#constructor_6)(string, LogLevel) | Инициализировать новый экземпляр класса[`LogEntry`](../logentry). |
| [LogEntry](logentry#constructor_4)(byte[], Encoding, IDictionary&lt;string, string&gt;) | Создать новый экземпляр[`LogEntry`](../logentry)с полным набором параметров конструктора |
| [LogEntry](logentry#constructor_11)(string, Exception, LogLevel) | Инициализировать новый экземпляр класса[`LogEntry`](../logentry). |
| [LogEntry](logentry#constructor_7)(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Создать новый экземпляр[`LogEntry`](../logentry)с полным набором параметров конструктора |
| [LogEntry](logentry#constructor_12)(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Создать новый экземпляр[`LogEntry`](../logentry)с полным набором параметров конструктора |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AppDomainName](../../aspose.email.tools.logging/logentry/appdomainname) { get; set; } | AppDomain, в котором мы работаем |
| [BinaryDataMessage](../../aspose.email.tools.logging/logentry/binarydatamessage) { get; set; } | Двоичное тело сообщения для регистрации. |
| [Category](../../aspose.email.tools.logging/logentry/category) { get; set; } | Имя категории, используемое для маршрутизации записи журнала к одному или нескольким приемникам. |
| [ContextualProperties](../../aspose.email.tools.logging/logentry/contextualproperties) { get; set; } | Словарь пар ключ/значение для записи. |
| [ErrorMessages](../../aspose.email.tools.logging/logentry/errormessages) { get; } | Получает сообщение об ошибке с[`LogEntry`](../logentry) |
| [EventId](../../aspose.email.tools.logging/logentry/eventid) { get; set; } | Номер события или идентификатор. |
| [InnerException](../../aspose.email.tools.logging/logentry/innerexception) { get; set; } | Получает или задает внутренний объект исключения. |
| [MachineName](../../aspose.email.tools.logging/logentry/machinename) { get; set; } | Имя компьютера. |
| [Message](../../aspose.email.tools.logging/logentry/message) { get; set; } | Тело сообщения для регистрации. Значение из метода ToString() из объекта сообщения. |
| [MessageEncoding](../../aspose.email.tools.logging/logentry/messageencoding) { get; set; } | Кодировка двоичного тела сообщения |
| [SequenceId](../../aspose.email.tools.logging/logentry/sequenceid) { get; } | Уникальный идентификатор события журнала, который генерируется автоматически и монотонно увеличивается. |
| [Severity](../../aspose.email.tools.logging/logentry/severity) { get; set; } | Серьезность записи журнала в виде перечисления[`Severity`](./severity). (Не указано, Информация, Предупреждение или Ошибка). |
| [ThreadName](../../aspose.email.tools.logging/logentry/threadname) { get; set; } | Имя потока .NET. |
| [TimeStamp](../../aspose.email.tools.logging/logentry/timestamp) { get; set; } | Дата и время сообщения записи журнала. |
| [Title](../../aspose.email.tools.logging/logentry/title) { get; set; } | Дополнительное описание сообщения записи журнала. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [AddErrorMessage](../../aspose.email.tools.logging/logentry/adderrormessage)(string) | Добавить сообщение об ошибке или предупреждение в начало построителя строк сообщений. Используется дистрибьютором для записи проблем. |
| [Clone](../../aspose.email.tools.logging/logentry/clone)() | Создает новый объект[`LogEntry`](../logentry), который является копией текущего экземпляра. |
| override [ToString](../../aspose.email.tools.logging/logentry/tostring)() |  |

### Смотрите также

* пространство имен [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
