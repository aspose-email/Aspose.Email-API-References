---
title: IAttachment
second_title: Aspose.Email for Android via Java API Reference
description: Представляет общий интерфейс вложения
type: docs
weight: 454
url: /ru/androidjava/com.aspose.email/iattachment/
---
```
public interface IAttachment
```

Представляет общий интерфейс вложения
## Methods

| Method | Описание |
| --- | --- |
| [getName()](#getName--) | Получает или задает имя вложения |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет вложение в поток |
| [save(String fileName)](#save-java.lang.String-) | Сохраняет вложение в файл |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя вложения |
### getName() {#getName--}
```
public abstract String getName()
```


Получает или задает имя вложения

**Returns:**
java.lang.String
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


Сохраняет вложение в поток

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |

### save(String fileName) {#save-java.lang.String-}
```
public abstract void save(String fileName)
```


Сохраняет вложение в файл

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла |

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Получает или задает имя вложения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

