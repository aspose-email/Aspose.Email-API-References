---
title: ContactFieldsSet
second_title: Справочник по Aspose.Email для .NET API
description: Перечисляет группы полей контактов которые будут включены в результирующий файл mhtml.
type: docs
weight: 17180
url: /ru/net/aspose.email/contactfieldsset/
---
## ContactFieldsSet enumeration

Перечисляет группы полей контактов, которые будут включены в результирующий файл mhtml.

```csharp
[Flags]
public enum ContactFieldsSet
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| None | `0` | Указывает, что ни одно поле не будет включено в результирующий файл mhtml. Только ПРИМЕЧАНИЕ контакта будет отображаться в html body. |
| NameInfo | `1` | Указывает, что поля NameInfo будут включены в результирующий файл mhtml. |
| PersonalInfo | `2` | Указывает, что поля PersonalInfo будут включены в результирующий файл mhtml. |
| ProfessionalInfo | `4` | Указывает, что поля ProfessionalInfo будут включены в результирующий файл mhtml. |
| PhysicalAddresses | `8` | Указывает, что поля PhysicalAddresses будут включены в результирующий файл mhtml. |
| Telephones | `10` | Указывает, что поля "Телефоны" будут включены в результирующий файл mhtml. |
| ElectronicAddresses | `20` | Указывает, что поля ElectronicAddresses будут включены в результирующий файл mhtml. |
| Events | `40` | Указывает, что поля событий будут включены в результирующий файл mhtml. |
| OtherFields | `80` | Указывает, что поля OtherFields будут включены в результирующий файл mhtml. |
| AllExisting | `100` | Указывает, что все существующие поля будут включены в результирующий файл mhtml. |

### Смотрите также

* пространство имен [Aspose.Email](../../aspose.email)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
