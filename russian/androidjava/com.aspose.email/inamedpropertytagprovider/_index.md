---
title: INamedPropertyTagProvider
second_title: Aspose.Email for Android via Java API Reference
description: Интерфейс поставщика именованных тегов свойства MAPI.
type: docs
weight: 462
url: /ru/androidjava/com.aspose.email/inamedpropertytagprovider/
---
```
public interface INamedPropertyTagProvider
```

Интерфейс поставщика именованных тегов свойства MAPI.
## Methods

| Method | Описание |
| --- | --- |
| [generateNamedPropertyTag(long dataType)](#generateNamedPropertyTag-long-) | Генерирует тег именованного свойства |
| [getTagFromNamedProperty(String name)](#getTagFromNamedProperty-java.lang.String-) | Возвращает тег из именованного свойства. |
| [getTagFromNamedProperty(long LId)](#getTagFromNamedProperty-long-) | Возвращает тег из именованного свойства. |
### generateNamedPropertyTag(long dataType) {#generateNamedPropertyTag-long-}
```
public abstract long generateNamedPropertyTag(long dataType)
```


Генерирует тег именованного свойства

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| dataType | long | Тип данных именованного свойства |

**Returns:**
long - Возвращает тег для именованного свойства текущего поставщика тегов
### getTagFromNamedProperty(String name) {#getTagFromNamedProperty-java.lang.String-}
```
public abstract long getTagFromNamedProperty(String name)
```


Возвращает тег из именованного свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |

**Returns:**
long - Значение тега свойства.
### getTagFromNamedProperty(long LId) {#getTagFromNamedProperty-long-}
```
public abstract long getTagFromNamedProperty(long LId)
```


Возвращает тег из именованного свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| LId | long | Идентификатор свойства. |

**Returns:**
long - Значение тега свойства.
