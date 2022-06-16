---
title: DataContainer
second_title: Справочник по Aspose.Email для .NET API
description: Содержит данные для определенного объекта такого как контакт сообщение электронной почты встреча в календаре или элемент задачи. Контейнер данных можно использовать для изменения элементов добавления элементов или получения элементов на клиентском устройстве или сервере.
type: docs
weight: 1150
url: /ru/net/aspose.email.clients.activesync.transportlayer/datacontainer/
---
## DataContainer class

Содержит данные для определенного объекта, такого как контакт, сообщение электронной почты, встреча в календаре или элемент задачи. Контейнер данных можно использовать для изменения элементов, добавления элементов или получения элементов на клиентском устройстве или сервере.

```csharp
public class DataContainer : IEnumerable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DataContainer](datacontainer#constructor)(string, Namespace) | Инициализирует новый экземпляр класса DataContainer. |
| [DataContainer](datacontainer#constructor_1)(string, Namespace, DataContainer) | Инициализирует новый экземпляр класса DataContainer. |
| [DataContainer](datacontainer#constructor_2)(string, Namespace, DataContainer, string) | Инициализирует новый экземпляр класса DataContainer. |
| [DataContainer](datacontainer#constructor_3)(string, Namespace, DataContainer, string, bool) | Инициализирует новый экземпляр класса DataContainer. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BinaryData](../../aspose.email.clients.activesync.transportlayer/datacontainer/binarydata) { get; set; } | Указывает, являются ли данные двоичными. |
| [ElementName](../../aspose.email.clients.activesync.transportlayer/datacontainer/elementname) { get; } | Имя элемента, данные которого содержатся в контейнере данных. |
| [Item](../../aspose.email.clients.activesync.transportlayer/datacontainer/item) { get; } | Получает DataContainer для выбранного элемента Если количество DataContainer больше одного, возникает AsposeException. (15 indexers) |
| [Namespace](../../aspose.email.clients.activesync.transportlayer/datacontainer/namespace) { get; } | NameSpace элемента, данные которого содержатся в контейнере данных. |
| [Parent](../../aspose.email.clients.activesync.transportlayer/datacontainer/parent) { get; } | Родительский контейнер данных |
| [Prefix](../../aspose.email.clients.activesync.transportlayer/datacontainer/prefix) { get; } | Префикс в узле xml для элемента |
| [SubItems](../../aspose.email.clients.activesync.transportlayer/datacontainer/subitems) { get; } | Копирует подэлементы ApplicationData в новый список. |
| [Value](../../aspose.email.clients.activesync.transportlayer/datacontainer/value) { get; set; } | Значение элемента |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_3)(string) | Добавляет данные элемента в формате xml в DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_4)(XmlNode) | Добавляет данные элемента в формате xml в DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add)(int, Namespace) | Добавляет пустой DataContainer для элемента. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_1)(int, string, Namespace) | Добавляет данные элемента в DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_2)(int, string, bool, Namespace) | Добавляет данные элемента в DataContainer. |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist)(AirSync) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_1)(AirSyncBase) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_2)(Calendar) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_3)(Contacts) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_4)(Contacts2) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_5)(DocumentLibrary) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_6)(Email) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_7)(Email2) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_8)(GAL) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_9)(ItemOperations) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_10)(Notes) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_11)(RightsManagement) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_12)(Search) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_13)(Settings) | Получает список контейнеров данных для выбранного элемента |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_14)(Tasks) | Получает список контейнеров данных для выбранного элемента |
| [GetEnumerator](../../aspose.email.clients.activesync.transportlayer/datacontainer/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/datacontainer/tostring)() | Возвращает строку, представляющую текущий объект. |

### Смотрите также

* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
