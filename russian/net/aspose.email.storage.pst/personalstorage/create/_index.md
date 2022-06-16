---
title: Create
second_title: Справочник по Aspose.Email для .NET API
description: Создает новый файл PST с указанным именем файла.
type: docs
weight: 20
url: /ru/net/aspose.email.storage.pst/personalstorage/create/
---
## Create(string, FileFormatVersion, CancellationToken) {#create_5}

Создает новый файл PST с указанным именем файла.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Полное имя файла. |
| version | FileFormatVersion | Версия файла PST. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект PersonalStorage, представляющий новый PST.

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | выдает, если создается версия файла ANSI |
| ArgumentNullException | выдает, если имя файла равно null или пусто |

### Примечания

Обратите внимание, что теперь поддерживается только создание версии файла Unicode.

### Смотрите также

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* пространство имен [Aspose.Email.Storage.Pst](../../personalstorage)
* сборка [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, CancellationToken) {#create_3}

Создает PST в потоке.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в котором создается PST. |
| version | FileFormatVersion | Версия файла PST. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект PersonalStorage, представляющий новый PST.

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | выдает, если создается версия файла ANSI |
| ArgumentNullException | выдает, если имя файла равно null или пусто |

### Примечания

Обратите внимание, что теперь поддерживается только создание версии файла Unicode.

### Смотрите также

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* пространство имен [Aspose.Email.Storage.Pst](../../personalstorage)
* сборка [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool, CancellationToken) {#create_2}

Создает PST в потоке.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в котором создается PST. |
| version | FileFormatVersion | Версия файла PST. |
| leaveStreamOpen | Boolean | Оставить поток открытым при удалении PersonalStorage. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект PersonalStorage, представляющий новый PST.

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | выдает, если создается версия файла ANSI |
| ArgumentNullException | выдает, если имя файла равно null или пусто |

### Примечания

Обратите внимание, что теперь поддерживается только создание версии файла Unicode.

### Смотрите также

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* пространство имен [Aspose.Email.Storage.Pst](../../personalstorage)
* сборка [Aspose.Email](../../../)

---

## Create(string, FileFormatVersion) {#create_4}

Создает новый файл PST с указанным именем файла.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Полное имя файла. |
| version | FileFormatVersion | Версия файла PST. |

### Возвращаемое значение

Объект PersonalStorage, представляющий новый PST.

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | выдает, если создается версия файла ANSI |
| ArgumentNullException | выдает, если имя файла равно null или пусто |

### Примечания

Обратите внимание, что теперь поддерживается только создание версии файла Unicode.

### Смотрите также

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* пространство имен [Aspose.Email.Storage.Pst](../../personalstorage)
* сборка [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion) {#create}

Создает PST в потоке.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в котором создается PST. |
| version | FileFormatVersion | Версия файла PST. |

### Возвращаемое значение

Объект PersonalStorage, представляющий новый PST.

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | выдает, если создается версия файла ANSI |
| ArgumentNullException | выдает, если поток равен null |

### Примечания

Обратите внимание, что теперь поддерживается только создание версии файла Unicode.

### Смотрите также

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* пространство имен [Aspose.Email.Storage.Pst](../../personalstorage)
* сборка [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool) {#create_1}

Создает PST в потоке.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в котором создается PST. |
| version | FileFormatVersion | Версия файла PST. |
| leaveStreamOpen | Boolean | Оставить поток открытым при удалении PersonalStorage. |

### Возвращаемое значение

Объект PersonalStorage, представляющий новый PST.

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | выдает, если создается версия файла ANSI |
| ArgumentNullException | выдает, если поток равен null |

### Примечания

Обратите внимание, что теперь поддерживается только создание версии файла Unicode.

### Смотрите также

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* пространство имен [Aspose.Email.Storage.Pst](../../personalstorage)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
