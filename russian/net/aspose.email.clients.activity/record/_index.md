---
title: Record
second_title: Справочник по Aspose.Email для .NET API
description: Запись журнала аудита
type: docs
weight: 2720
url: /ru/net/aspose.email.clients.activity/record/
---
## Record class

Запись журнала аудита

```csharp
public class Record
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Record](record)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AzureActiveDirectoryEventType](../../aspose.email.clients.activity/record/azureactivedirectoryeventtype) { get; set; } | Получает или задает тип события Azure AD. Обязательно: Yes |
| [Client](../../aspose.email.clients.activity/record/client) { get; set; } | Получает или задает сведения о клиентском устройстве, ОС устройства и браузере устройства, которые использовались для события входа в учетную запись. Обязательно: No |
| [ClientIP](../../aspose.email.clients.activity/record/clientip) { get; set; } | Получает или задает IP-адрес устройства, которое использовалось при регистрации активности. IP-адрес отображается в формате адреса IPv4 или IPv6. Обязательно: Да |
| [CreationTime](../../aspose.email.clients.activity/record/creationtime) { get; set; } | Получает или задает дату и время по всемирному координированному времени (UTC), когда пользователь выполнял действие. Обязательно: Yes |
| [ExtendedProperties](../../aspose.email.clients.activity/record/extendedproperties) { get; set; } | Получает или задает список расширенных свойств для изменяемого параметра. Каждое свойство будет иметь Имя и Значение. Обязательно: No |
| [Id](../../aspose.email.clients.activity/record/id) { get; set; } | Получает или задает уникальный идентификатор записи аудита. Обязательно: Yes |
| [LoginStatus](../../aspose.email.clients.activity/record/loginstatus) { get; set; } | Получает или устанавливает статус входа в систему Обязательно: Да |
| [ObjectId](../../aspose.email.clients.activity/record/objectid) { get; set; } | Получает или задает идентификатор объекта. Для действий SharePoint и OneDrive для бизнеса — полное имя файла или папки, к которым обращается пользователь. Для ведения журнала аудита администратора Exchange имя объекта, измененного командлетом. Обязательно: No |
| [Operation](../../aspose.email.clients.activity/record/operation) { get; set; } | Получает или задает имя действия пользователя или администратора. Описание наиболее распространенных операций/действий см. в разделе Поиск в журнале аудита в Центре защиты Office 365. Для действия администратора Exchange это свойство определяет имя запущенного командлета. Для событий Dlp это может быть "DlpRuleMatch", "DlpRuleUndo" или "DlpInfo", которые описаны в разделе "Схема DLP" ниже. Обязательно: Yes |
| [OrganizationId](../../aspose.email.clients.activity/record/organizationid) { get; set; } | Получает или задает GUID для клиента Office 365 вашей организации. Это значение всегда будет одинаковым для вашей организации, независимо от службы Office 365, в которой оно используется. Обязательно: Yes |
| [RecordType](../../aspose.email.clients.activity/record/recordtype) { get; set; } | Получает или задает тип операции, указанный в записи. Обязательно: Да |
| [ResultStatus](../../aspose.email.clients.activity/record/resultstatus) { get; set; } | Получает или задает значение, указывающее, было ли действие (указанное в свойстве Operation) успешным или нет. Обязательно: No |
| [UserDomain](../../aspose.email.clients.activity/record/userdomain) { get; set; } | Получает или задает идентификационную информацию арендатора (TII). Обязательно: Yes |
| [UserId](../../aspose.email.clients.activity/record/userid) { get; set; } | Получает или задает UPN (имя участника-пользователя) пользователя, выполнившего действие (указанное в свойстве Operation), в результате которого запись была зарегистрирована; например, my_name@my_domain_name. Обратите внимание, что также включены записи о действиях, выполняемых системными учетными записями (например, SHAREPOINT\system или NT AUTHORITY\SYSTEM). Обязательно: Yes |
| [UserKey](../../aspose.email.clients.activity/record/userkey) { get; set; } | Получает или задает альтернативный идентификатор для пользователя, указанного в свойстве UserId. Например, это свойство заполняется уникальным идентификатором паспорта (PUID) для событий, выполняемых пользователями в SharePoint, OneDrive для бизнеса и Exchange. Это свойство также может указывать то же значение, что и свойство UserID для событий, происходящих в других службах, и событий, выполняемых системными учетными записями. Обязательно: Yes |
| [UserType](../../aspose.email.clients.activity/record/usertype) { get; set; } | Получает или задает тип пользователя, выполнившего операцию. Обязательно: Да |
| [Workload](../../aspose.email.clients.activity/record/workload) { get; set; } | Получает или задает службу Office 365, в которой произошло действие. Обязательно: No |

### Смотрите также

* пространство имен [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
