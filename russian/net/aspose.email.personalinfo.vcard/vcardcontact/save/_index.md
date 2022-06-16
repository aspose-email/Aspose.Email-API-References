---
title: Save
second_title: Справочник по Aspose.Email для .NET API
description: Сохраняет этоMapiContactaspose.email.mapi/mapicontactв файл vCard с параметрами по умолчанию. Поддерживаемая версия vCard2.1
type: docs
weight: 140
url: /ru/net/aspose.email.personalinfo.vcard/vcardcontact/save/
---
## Save(string) {#save_3}

Сохраняет это[`MapiContact`](../../../aspose.email.mapi/mapicontact)в файл vCard с параметрами по умолчанию. Поддерживаемая версия vCard:2.1

```csharp
public void Save(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Имя файла vCard |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | *filePath*is` null` или` пустой` |

### Смотрите также

* class [VCardContact](../../vcardcontact)
* пространство имен [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* сборка [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

Сохраняет это[`MapiContact`](../../../aspose.email.mapi/mapicontact)в указанный файл в формате с параметрами по умолчанию. Поддерживаемый формат сохранения - vCard.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Имя файла vCard |
| saveFormat | ContactSaveFormat | Формат сохранения |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | *filePath*is` null` или` empty` |
| NotSupportedException | указанный формат не поддерживается |

### Смотрите также

* enum [ContactSaveFormat](../../../aspose.email.mapi/contactsaveformat)
* class [VCardContact](../../vcardcontact)
* пространство имен [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* сборка [Aspose.Email](../../../)

---

## Save(string, ContactSaveOptions) {#save_5}

Сохраняет это[`MapiContact`](../../../aspose.email.mapi/mapicontact)в файл, используя указанные параметры сохранения. Поддерживаемые параметры сохранения:[`VCardSaveOptions`](../../vcardsaveoptions)

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | A Имя файла vCard |
| saveOptions | ContactSaveOptions | Параметры сохранения |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | *filePath*is` null` или` пустой` |
| ArgumentNullException | *saveOptions*is` null` |
| NotSupportedException | некоторые опции сохранения не поддерживаются |

### Смотрите также

* class [ContactSaveOptions](../../../aspose.email.mapi/contactsaveoptions)
* class [VCardContact](../../vcardcontact)
* пространство имен [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* сборка [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Сохраняет это[`MapiContact`](../../../aspose.email.mapi/mapicontact)в указанный поток с форматом vCard. Поддерживаемая версия vCard:2.1

```csharp
public void Save(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для сохранения в |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *stream*is` null` |
| NotSupportedException | *stream*не поддерживает запись |

### Смотрите также

* class [VCardContact](../../vcardcontact)
* пространство имен [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* сборка [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

Сохраняет это[`MapiContact`](../../../aspose.email.mapi/mapicontact)в указанный поток с форматом, использующим параметры по умолчанию. Поддерживаемый формат сохранения:vCard

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для сохранения в |
| saveFormat | ContactSaveFormat | Формат сохранения |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *stream*is` null` |
| NotSupportedException | *stream*не поддерживает запись |
| NotSupportedException | Указанный формат не поддерживается |

### Смотрите также

* enum [ContactSaveFormat](../../../aspose.email.mapi/contactsaveformat)
* class [VCardContact](../../vcardcontact)
* пространство имен [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* сборка [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

Сохраняет это[`MapiContact`](../../../aspose.email.mapi/mapicontact)в указанный поток, используя указанные параметры сохранения. Поддерживаемые параметры сохранения:[`VCardSaveOptions`](../../vcardsaveoptions)

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | A поток для сохранения в |
| saveOptions | ContactSaveOptions | Параметры сохранения |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *stream*или*saveOptions*is` null` |
| NotSupportedException | *stream*не поддерживает запись |
| ArgumentException | неверно*saveOptions* |
| NotSupportedException | некоторые опции сохранения не поддерживаются |

### Смотрите также

* class [ContactSaveOptions](../../../aspose.email.mapi/contactsaveoptions)
* class [VCardContact](../../vcardcontact)
* пространство имен [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
