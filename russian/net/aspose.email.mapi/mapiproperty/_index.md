---
title: MapiProperty
second_title: Справочник по Aspose.Email для .NET API
description: Представляет свойство mapi.
type: docs
weight: 18560
url: /ru/net/aspose.email.mapi/mapiproperty/
---
## MapiProperty class

Представляет свойство mapi.

```csharp
public class MapiProperty
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MapiProperty](mapiproperty#constructor_2)(long) | Инициализирует новый экземпляр класса MapiProperty. |
| [MapiProperty](mapiproperty#constructor_3)(long, byte[]) | Инициализирует новый экземпляр класса MapiProperty. |
| [MapiProperty](mapiproperty#constructor_5)(long, IList&lt;object&gt;) | Инициализирует новый экземпляр[`MapiProperty`](../mapiproperty) class. Эта перегрузка используется для создания свойства с несколькими значениями, PT_MV_*. |
| [MapiProperty](mapiproperty#constructor)(PidLidPropertyDescriptor, object) | Инициализирует новый экземпляр класса MapiProperty. |
| [MapiProperty](mapiproperty#constructor_1)(PidTagPropertyDescriptor, object) | Инициализирует новый экземпляр класса MapiProperty. |
| [MapiProperty](mapiproperty#constructor_4)(long, long, byte[]) | Инициализирует новый экземпляр[`MapiProperty`](../mapiproperty) класс. |
| [MapiProperty](mapiproperty#constructor_6)(string, long, long, byte[]) | Инициализирует новый экземпляр класса MapiProperty. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data) { get; } | Получает двоичные данные. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype) { get; } | Получает тип данных. |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor) { get; } | Получает дескриптор свойства MAPI |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier) { get; } | Получает индикатор. |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed) { get; } | Указывает, является ли свойство именованным свойством. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned) { get; set; } | Указывает, подписаны ли двоичные данные. |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries) { get; } | Получает список записей MV. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name) { get; } | Получает имя. |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname) { get; } | Получает имя свойства. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag) { get; } | Получает тег. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateMapiPropertyFromBytes](../../aspose.email.mapi/mapiproperty/createmapipropertyfrombytes)(long, byte[]) | Создает свойство mapi из байтов. |
| static [CreateMapiPropertyFromDateTime](../../aspose.email.mapi/mapiproperty/createmapipropertyfromdatetime)(long, DateTime) | Создает свойство mapi из даты и времени. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong)(long, long) | Создает свойство mapi из long. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong_1)(long, long, long) | Создает свойство mapi из long. |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean)() | Получает первые байты двоичных данных как логическое значение. |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency)() | Получает валюту в виде строки с использованием указанной кодовой страницы. |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime)() | Получает первые байты двоичных данных в виде даты и времени. |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble)() | Получает байты двоичных данных как double. |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat)() | Получает байты двоичных данных в виде числа с плавающей запятой. |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate)() | Получает байты двоичных данных как DateTime. |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid)() | Получает байты двоичных данных в виде Guid. |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32)() | Получает первые 4 байта двоичных данных как int32. |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong)() | Получает первые 8 байтов двоичных данных такой длины. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort)() | Получает первые 2 байта двоичных данных как короткие. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring)() | Получает двоичные данные в виде строки. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring_1)(int) | Получает двоичные данные в виде строки с использованием указанной кодовой страницы. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue)() | Получает значение как object |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring)() | ВозвращаетString который представляет текущийObject . |

### Смотрите также

* пространство имен [Aspose.Email.Mapi](../../aspose.email.mapi)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
