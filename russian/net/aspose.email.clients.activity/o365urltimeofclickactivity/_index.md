---
title: O365URLTimeOfClickActivity
second_title: Справочник по Aspose.Email для .NET API
description: Дополняет общую схему свойствами характерными для данных Office 365 Advanced Threat Protection и Threat Intelligence. События Office 365 Advanced Threat Protection ATP и Threat Intelligence доступны для клиентов Office 365 у которых есть подписка ATP Threat Intelligence или E5. . Каждое событие в канале ATP и Threat Intelligence соответствует URL-адресам на которые щелкнул пользователь в организации которые были обнаружены как вредоносные во время щелчка на основе защиты Office 365 ATP Safe Links.
type: docs
weight: 2670
url: /ru/net/aspose.email.clients.activity/o365urltimeofclickactivity/
---
## O365URLTimeOfClickActivity class

Дополняет общую схему свойствами, характерными для данных Office 365 Advanced Threat Protection и Threat Intelligence. События Office 365 Advanced Threat Protection (ATP) и Threat Intelligence доступны для клиентов Office 365, у которых есть подписка ATP, Threat Intelligence или E5. . Каждое событие в канале ATP и Threat Intelligence соответствует URL-адресам, на которые щелкнул пользователь в организации, которые были обнаружены как вредоносные во время щелчка на основе защиты Office 365 ATP Safe Links.

```csharp
public class O365URLTimeOfClickActivity : Content
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [O365URLTimeOfClickActivity](o365urltimeofclickactivity)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AppName](../../aspose.email.clients.activity/o365urltimeofclickactivity/appname) { get; set; } | Служба Office 365, из которой был выбран URL-адрес (например, Почта). Обязательно: Да |
| [Blocked](../../aspose.email.clients.activity/o365urltimeofclickactivity/blocked) { get; set; } | Это верно, если щелчок по URL-адресу заблокирован защитой Office 365 ATP Safe Links. Обязательно: Yes |
| [ClickedThrough](../../aspose.email.clients.activity/o365urltimeofclickactivity/clickedthrough) { get; set; } | Это верно, если блок URL-адресов щелкнут (переопределен) пользователем в соответствии с политиками организации для защиты Office 365 ATP Safe Links. Обязательно: Yes |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | IP-адрес устройства, которое использовалось при регистрации активности. IP-адрес отображается в формате адреса IPv4 или IPv6. Обязательно: Да |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | Дата и время по всемирному координированному времени (UTC), когда пользователь выполнил действие. Обязательно: Yes |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Уникальный идентификатор записи аудита. Обязательно: Да |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Для активности SharePoint и OneDrive для бизнеса — полное имя файла или папки, к которым обращается пользователь. Для ведения журнала аудита администратора Exchange имя объекта, измененного командлетом. Обязательно: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Имя действия пользователя или администратора. Описание наиболее распространенных операций/действий см. в разделе Поиск в журнале аудита в Центре защиты Office 365. Для действия администратора Exchange это свойство определяет имя запущенного командлета. Для событий Dlp это может быть "DlpRuleMatch", "DlpRuleUndo" или "DlpInfo", которые описаны в разделе "Схема DLP" ниже. Обязательно: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | GUID для клиента Office 365 вашей организации. Это значение всегда будет одинаковым для вашей организации, независимо от службы Office 365, в которой оно используется. Обязательно: Yes |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Тип операции, указанный в записи. Обязательно: Да |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Указывает, было ли действие (указанное в свойстве Operation) успешным или нет. Возможные значения: Успешно, Частично Успешно или Сбой. Для действий администратора Exchange значение равно True или False. Обязательно: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Было ли это событие создано размещенной службой O365 или локальным сервером? Возможные значения: онлайн и локально. Обратите внимание, что SharePoint — это единственная рабочая нагрузка, которая в настоящее время отправляет события из локальной среды в O365. Обязательно: No |
| [SourceId](../../aspose.email.clients.activity/o365urltimeofclickactivity/sourceid) { get; set; } | Идентификатор службы Office 365, из которой был выбран URL-адрес (например, для почты, это идентификатор сетевого сообщения Exchange Online). Обязательно: Yes |
| [TimeOfClick](../../aspose.email.clients.activity/o365urltimeofclickactivity/timeofclick) { get; set; } | Дата и время по всемирному координированному времени (UTC), когда пользователь щелкнул URL. Обязательно: Yes |
| [URL](../../aspose.email.clients.activity/o365urltimeofclickactivity/url) { get; set; } | URL, по которому щелкнул пользователь. Обязательно: Yes |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | UPN (имя участника-пользователя) пользователя, выполнившего действие (указанное в свойстве Operation), в результате которого запись была зарегистрирована; например, my_name@my_domain_name. Обратите внимание, что также включены записи о действиях, выполняемых системными учетными записями (например, SHAREPOINT\system или NT AUTHORITY\SYSTEM). Обязательно: Yes |
| [UserIp](../../aspose.email.clients.activity/o365urltimeofclickactivity/userip) { get; set; } | IP-адрес пользователя, который щелкнул URL-адрес. IP-адрес отображается в формате адреса IPv4 или IPv6. Обязательно: Yes |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Альтернативный идентификатор пользователя, указанного в свойстве UserId. Например, это свойство заполняется уникальным идентификатором паспорта (PUID) для событий, выполняемых пользователями в SharePoint, OneDrive для бизнеса и Exchange. Это свойство также может указывать то же значение, что и свойство UserID для событий, происходящих в других службах, и событий, выполняемых системными учетными записями. Обязательно: Yes |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Тип пользователя, выполнившего операцию. Обязательно: Да |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Служба Office 365, в которой произошло действие в строке рабочей нагрузки. Возможные значения этого свойства: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Обязательно: No |

### Смотрите также

* class [Content](../content)
* пространство имен [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
