---
title: Restore
second_title: Справочник по Aspose.Email для .NET API
description: Восстанавливает папки обмена из указанного файла личного хранилища.
type: docs
weight: 350
url: /ru/net/aspose.email.clients.exchange.dav/exchangeclient/restore/
---
## Restore(string, RestoreOptions) {#restore_5}

Восстанавливает папки обмена из указанного файла личного хранилища.

```csharp
public void Restore(string fileName, RestoreOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Путь к файлу личного хранилища. |
| options | RestoreOptions | Параметры восстановления. |

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* не указано. |

### Смотрите также

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## Restore(Stream, RestoreOptions) {#restore_3}

Восстанавливает папки обмена из указанного личного хранилища.

```csharp
public void Restore(Stream stream, RestoreOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, содержащий личное хранилище. |
| options | RestoreOptions | Параметры восстановления. |

### Исключения

| исключение | условие |
| --- | --- |
| NotSupportedException | *stream* не поддерживает чтение. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream* является`нулевой`. |

### Смотрите также

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## Restore(PersonalStorage, RestoreOptions) {#restore_1}

Восстанавливает папки обмена из указанного личного хранилища.

```csharp
public void Restore(PersonalStorage pst, RestoreOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pst | PersonalStorage | Личное хранилище, содержащее резервные копии папок imap. |
| options | RestoreOptions | Параметры восстановления. |

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst* является`нулевой`. |

### Смотрите также

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## Restore(string, ExchangeFolderInfoCollection, RestoreOptions) {#restore_4}

Восстанавливает указанные папки обмена из указанного файла личного хранилища.

```csharp
public void Restore(string fileName, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Путь к файлу личного хранилища. |
| folders | ExchangeFolderInfoCollection | Папки для восстановления. |
| options | RestoreOptions | Параметры восстановления. |

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* не указано. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* является`нулевой`. |

### Смотрите также

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## Restore(Stream, ExchangeFolderInfoCollection, RestoreOptions) {#restore_2}

Восстанавливает указанные папки обмена из заданного личного хранилища.

```csharp
public void Restore(Stream stream, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, содержащий личное хранилище. |
| folders | ExchangeFolderInfoCollection | Папки для восстановления. |
| options | RestoreOptions | Параметры восстановления. |

### Исключения

| исключение | условие |
| --- | --- |
| NotSupportedException | *stream* не поддерживает чтение. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream*или же*folders* является`нулевой`. |

### Смотрите также

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## Restore(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) {#restore}

Восстанавливает указанные папки обмена из заданного личного хранилища.

```csharp
public void Restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, 
    RestoreOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pst | PersonalStorage | Личное хранилище, содержащее резервные копии папок обмена. |
| folders | ExchangeFolderInfoCollection | Папки для восстановления. |
| options | RestoreOptions | Параметры восстановления. |

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst*или же*folders* является`нулевой`. |

### Смотрите также

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
