---
title: PidTagPropertyDescriptor
second_title: Справочник по Aspose.Email для .NET API
description: Класс содержит информацию об описании свойства.
type: docs
weight: 18990
url: /ru/net/aspose.email.mapi/pidtagpropertydescriptor/
---
## PidTagPropertyDescriptor class

Класс содержит информацию об описании свойства.

```csharp
public class PidTagPropertyDescriptor : PropertyDescriptor
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_1)(long) | Инициализирует новый экземпляр[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Свойство, определяемое 16-битным идентификатором свойства и 16-битным типом свойства. Идентификатор свойства для помеченного свойства находится в диапазоне от 0x001 до 0x7FFF. Идентификаторы свойств в диапазоне 0x8000 – 0x8FFF зарезервированы для присвоения именованным свойствам |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor)(int, PropertyDataType) | Инициализирует новый экземпляр[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Свойство, определяемое 16-битным идентификатором свойства и 16-битным типом свойства. Идентификатор свойства для помеченного свойства находится в диапазоне от 0x001 до 0x7FFF. Идентификаторы свойств в диапазоне 0x8000 – 0x8FFF зарезервированы для присвоения именованным свойствам |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_2)(string, int, PropertyDataType) | Инициализирует новый экземпляр[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Свойство, определяемое 16-битным идентификатором свойства и 16-битным типом свойства. Идентификатор свойства для помеченного свойства находится в диапазоне от 0x001 до 0x7FFF. Идентификаторы свойств в диапазоне 0x8000 – 0x8FFF зарезервированы для присвоения именованным свойствам |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_4)(string, string, long) | Инициализирует новый экземпляр[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Свойство, определяемое 16-битным идентификатором свойства и 16-битным типом свойства. Идентификатор свойства для помеченного свойства находится в диапазоне от 0x001 до 0x7FFF. Идентификаторы свойств в диапазоне 0x8000 – 0x8FFF зарезервированы для присвоения именованным свойствам |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_3)(string, string, int, PropertyDataType) | Инициализирует новый экземпляр[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Свойство, определяемое 16-битным идентификатором свойства и 16-битным типом свойства. Идентификатор свойства для помеченного свойства находится в диапазоне от 0x001 до 0x7FFF. Идентификаторы свойств в диапазоне 0x8000 – 0x8FFF зарезервированы для присвоения именованным свойствам |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | Имя, используемое для ссылки на свойство в документации. Префикс канонического имени идентифицирует основные характеристики свойства для разработчика. Каноническая структура именования использует три категории, которые обозначаются следующими префиксами к имени канонического свойства: * Префикс PidLid: свойства, определяемые беззнаковым 32-битным числом вместе с набором свойств. * Префикс PidName: Свойства, определяемые строковым именем вместе с набором свойств. * Префикс PidTag: Свойства, определяемые 16-битной величиной без знака. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | Тип значения свойства, как описано в [MS-OXCDATA], указывающий тип значений, разрешенных для свойства. |
| [Id](../../aspose.email.mapi/pidtagpropertydescriptor/id) { get; } | Получает 16-битную величину без знака, которая идентифицирует помеченное свойство. Идентификаторы свойств не обязательно должны быть уникальными. За исключением идентификаторов свойств в диапазоне от 0x6800 до 0x7BFF, комбинация идентификатора свойства и типа данных уникальна. Идентификаторы свойств в диапазоне от 0x6800 до 0x7BFF определяются классом сообщений. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | Указывает, содержит ли тип данных несколько значений |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | Получает строку, идентифицирующую свойство. |
| [Tag](../../aspose.email.mapi/pidtagpropertydescriptor/tag) { get; } | Тег свойства — это 32-битное число, которое содержит уникальный идентификатор свойства в битах с 16 по 31 и тип свойства в битах с 0 по 15. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals_1)(object) | Определяет, равен ли указанный System.Object текущему System.Object. |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals)(PropertyDescriptor) | Указывает, равен ли текущий объект другому объекту того же типа. |
| override [GetHashCode](../../aspose.email.mapi/pidtagpropertydescriptor/gethashcode)() | Служит хеш-функцией для типа. |
| override [ToString](../../aspose.email.mapi/pidtagpropertydescriptor/tostring)() | Возвращает строку, представляющую описание свойства. |
| [operator ==](../../aspose.email.mapi/pidtagpropertydescriptor/op_equality) | Определяет, равны ли указанные объекты друг другу. |
| [explicit operator](../../aspose.email.mapi/pidtagpropertydescriptor/op_explicit) | Преобразует значение тега в помеченное свойство |
| [operator !=](../../aspose.email.mapi/pidtagpropertydescriptor/op_inequality) | Определяет, не равны ли указанные объекты друг другу. |

### Смотрите также

* class [PropertyDescriptor](../propertydescriptor)
* пространство имен [Aspose.Email.Mapi](../../aspose.email.mapi)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
