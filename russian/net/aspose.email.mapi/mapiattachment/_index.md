---
title: MapiAttachment
second_title: Справочник по Aspose.Email для .NET API
description: Представляет вложение в сообщении электронной почты.
type: docs
weight: 17880
url: /ru/net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

Представляет вложение в сообщении электронной почты.

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata) { get; set; } | Получает или задает двоичные данные вложения. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Получает кодовую страницу. |
| [Content](../../aspose.email.mapi/mapiattachment/content) { get; } | Получает содержимое. |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname) { get; } | Получает отображаемое имя объекта ole во вложении. |
| [Extension](../../aspose.email.mapi/mapiattachment/extension) { get; } | Получает расширение имени файла, указывающее тип документа вложения. |
| [FileName](../../aspose.email.mapi/mapiattachment/filename) { get; } | Получает базовое имя файла и расширение вложения, исключая путь. |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid) { get; } | Идентификатор элемента, используется с сервером |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename) { get; } | Получает длинное имя файла и расширение вложения, исключая путь. |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag) { get; } | Получает информацию о форматировании вложения Многоцелевые расширения почты Интернета (MIME). |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties) { get; } | Получает именованные свойства сообщения. |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata) { get; } | Получает объект вложения, доступ к которому обычно осуществляется через интерфейс OLE IStorage. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Получает коллекцию свойств. |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream) { get; } | Получает поток свойств. |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages) { get; } | Получает вспомогательные хранилища. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty)(PropertyDescriptor) | Получает свойство MAPI по дескриптору свойства. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Получает значение свойства, указанного тегом, как булев тип. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Получает строковое значение свойства, указанного тегом. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Получает значение свойства, указанного тегом, как тип DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Получает значение int32 свойства, указанного тегом. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Получает значение свойства, указанного тегом, типа Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Получает значение свойства, указанного тегом, типа Short. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Получает строковое значение свойства, указанного тегом. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Получает строковое значение свойства, указанного тегом. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Определяет, закодированы ли строковые свойства в Unicode или нет. |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty)(long) | Обеспечивает корректное удаление свойства из всех коллекций. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save)(Stream) | Сохранить содержимое вложения. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save_1)(string) | Сохранить содержимое вложения. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty)(MapiProperty) | Устанавливает свойство. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty_1)(PropertyDescriptor, object) | Устанавливает свойство MAPI. |
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
* пространство имен [Aspose.Email.Mapi](../../aspose.email.mapi)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
