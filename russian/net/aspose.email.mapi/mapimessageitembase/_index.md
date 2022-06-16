---
title: MapiMessageItemBase
second_title: Справочник по Aspose.Email для .NET API
description: Представляет базовый класс для всех классов MapiMessageItem и содержит общие наборы свойств mapi вложений и получателей.
type: docs
weight: 18440
url: /ru/net/aspose.email.mapi/mapimessageitembase/
---
## MapiMessageItemBase class

Представляет базовый класс для всех классов MapiMessageItem и содержит общие наборы свойств mapi, вложений и получателей.

```csharp
public abstract class MapiMessageItemBase : MapiPropertyContainer, IDisposable, IMapiMessageItem
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Получает вложения в сообщении. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Содержит платежную информацию, связанную с элементом. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Получает текст сообщения. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Получает[`BodyRtf`](./bodyrtf)сообщения, преобразованного в HTML, если он присутствует, иначе пустая строка . |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Получает или задает текст сообщения в формате RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Получает тип тела. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Содержит ключевые слова или категории для объекта сообщения. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Получает кодовую страницу. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Содержит названия компаний, связанных с элементом. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Идентификатор элемента, используется с сервером |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Получает строку с учетом регистра, которая идентифицирует определенный отправителем класс сообщений, например IPM.Note. Класс сообщения определяет тип, цель или содержание сообщения. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Содержит информацию о пробеге, связанную с элементом. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Получает именованные свойства сообщения. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Получает сопоставление именованного свойства. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Получает коллекцию свойств. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Получает поток свойств. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Получает получателей сообщения. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Получает чувствительность. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Получает или задает тему сообщения. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Получает префикс темы, который обычно указывает на какое-либо действие над сообщением, например "FW:" для пересылки. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Получает вспомогательные хранилища. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Выполняет определяемые приложением задачи, связанные с освобождением, освобождением или сбросом неуправляемых ресурсов. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Получает свойство MAPI по дескриптору свойства. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Получает значение свойства, указанного тегом, как булев тип. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Получает строковое значение свойства, указанного тегом. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Получает значение свойства, указанного тегом, как тип DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Получает значение int32 свойства, указанного тегом. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Получает значение свойства, указанного тегом, типа Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Получает значение свойства, указанного тегом, типа Short. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Получает строковое значение свойства, указанного тегом. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Получает строковое значение свойства, указанного тегом. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Определяет, закодированы ли строковые свойства в Unicode или нет. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Обеспечивает корректное удаление свойства из всех коллекций. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent#setbodycontent)(string, BodyContentType) | Устанавливает содержимое тела. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent#setbodycontent_1)(string, BodyContentType, bool) | Устанавливает содержимое тела. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Получает или задает текст сообщения в формате RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Устанавливает флаги сообщения. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Устанавливает свойство. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty#setproperty_1)(PropertyDescriptor, object) | Устанавливает свойство MAPI. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Попытаться получить данные свойства с указанным ключом тега. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Получает значение указанного свойства как тип DateTime. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Получает значение указанного свойства как тип Int32. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Получает значение указанного свойства как тип Long. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Попытаться получить данные свойства в виде строки с указанным тегом. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Попытаться получить данные свойства в виде строки с указанным тегом и кодовой страницей. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Получает значение указанного свойства как тип String. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Получает значение указанного свойства как тип String. Возвращаемое значение указывает, успешно ли выполнена операция. |

### Смотрите также

* class [MapiPropertyContainer](../mapipropertycontainer)
* interface [IMapiMessageItem](../imapimessageitem)
* пространство имен [Aspose.Email.Mapi](../../aspose.email.mapi)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
