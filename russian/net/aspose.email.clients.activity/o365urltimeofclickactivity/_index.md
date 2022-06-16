---
title: O365URLTimeOfClickActivity
second_title: Справочник по Aspose.Email для .NET API
description: Дополняет общую схему свойствами характерными для данных Office 365 Advanced Threat Protection и Threat Intelligence. События Office 365 Advanced Threat Protection ATP и Threat Intelligence доступны для клиентов Office 365 у которых есть подписка ATP Threat Intelligence или E5. Каждое событие в канале ATP и Threat Intelligence соответствует URL-адресам  по которым щелкнул пользователь в организации которые были обнаружены как вредоносные во время щелчка на основе Office 365 ATP. Защита безопасных ссылок.
type: docs
weight: 2670
url: /ru/net/aspose.email.clients.activity/o365urltimeofclickactivity/
---
## O365URLTimeOfClickActivity class

Дополняет общую схему свойствами, характерными для данных Office 365 Advanced Threat Protection и Threat Intelligence. События Office 365 Advanced Threat Protection (ATP) и Threat Intelligence доступны для клиентов Office 365, у которых есть подписка ATP, Threat Intelligence или E5. Каждое событие в канале ATP и Threat Intelligence соответствует URL-адресам , по которым щелкнул пользователь в организации, которые были обнаружены как вредоносные во время щелчка на основе Office 365 ATP. Защита безопасных ссылок.

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
| [AppName](../../aspose.email.clients.activity/o365urltimeofclickactivity/appname) { get; set; } | Служба Office 365, из которой был выбран URL-адрес (например, Почта). Обязательно:Да |
| [Blocked](../../aspose.email.clients.activity/o365urltimeofclickactivity/blocked) { get; set; } | Это верно, если щелчок по URL-адресу заблокирован защитой Office 365 ATP Safe Links. Обязательно:Да |
| [ClickedThrough](../../aspose.email.clients.activity/o365urltimeofclickactivity/clickedthrough) { get; set; } | Это верно, если пользователь щелкает (переопределяет) блок URL-адресов на основе политик организации для защиты безопасных ссылок Office 365 ATP . Обязательно:Да |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | IP-адрес устройства, которое использовалось при регистрации активности. IP-адрес отображается в формате адреса IPv4 или IPv6. Обязательно:Да |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | Дата и время в формате всемирного координированного времени (UTC), когда пользователь выполнил действие. Обязательно:Да |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Уникальный идентификатор записи аудита. Обязательно:Да |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Для активности SharePoint и OneDrive для бизнеса — полное имя файла или папки, к которым обращается пользователь. Для ведения журнала аудита администратора Exchange имя объекта, который был изменен командлетом. Обязательно:Нет |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Имя активности пользователя или администратора. Описание наиболее распространенных операций/действий см. в разделе Поиск в журнале аудита в Центре защиты Office 365. Для действий администратора Exchange это свойство определяет имя запущенного командлета. Для событий Dlp это может быть "DlpRuleMatch", "DlpRuleUndo" или "DlpInfo", которые описаны в разделе "Схема DLP" ниже. Обязательно:Да |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | GUID для клиента Office 365 вашей организации. Это значение всегда будет одинаковым для вашей организации, независимо от службы Office 365, в которой оно встречается. Обязательно:Да |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Тип операции, указанный в записи. Обязательно:Да |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Указывает, было ли действие (указанное в свойстве Operation) успешным или нет. Возможные значения:успешно, частично успешно или не удалось. Для действия администратора Exchange значение равно True или False. Обязательно:Нет |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Было ли это событие создано размещенной службой O365 или локальным сервером? Возможные значения:"в сети" и "на месте". Обратите внимание, что SharePoint — это единственная рабочая нагрузка, которая в настоящее время отправляет события из локальной среды в O365. Обязательно:Нет |
| [SourceId](../../aspose.email.clients.activity/o365urltimeofclickactivity/sourceid) { get; set; } | Идентификатор службы Office 365, из которой был выбран URL-адрес (например, для почты это идентификатор сетевого сообщения Exchange Online). Обязательно:Да |
| [TimeOfClick](../../aspose.email.clients.activity/o365urltimeofclickactivity/timeofclick) { get; set; } | Дата и время в формате всемирного координированного времени (UTC), когда пользователь щелкнул URL-адрес. Обязательно:Да |
| [URL](../../aspose.email.clients.activity/o365urltimeofclickactivity/url) { get; set; } | URL, по которому щелкнул пользователь. Обязательно:Да |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | UPN (имя участника-пользователя) пользователя, выполнившего действие (указанное в свойстве Operation), в результате которого запись была зарегистрирована; например, my_name@my_domain_name. Обратите внимание, что также включены записи о действиях, выполняемых системными учетными записями (такими как SHAREPOINT\system или NT AUTHORITY\SYSTEM). Обязательно:Да |
| [UserIp](../../aspose.email.clients.activity/o365urltimeofclickactivity/userip) { get; set; } | IP-адрес пользователя, который щелкнул URL-адрес. IP-адрес отображается в формате адреса IPv4 или IPv6. Обязательно:Да |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Альтернативный идентификатор пользователя, указанного в свойстве UserId. Например, это свойство заполняется уникальным идентификатором паспорта (PUID) для событий, выполняемых пользователями в SharePoint, OneDrive для бизнеса и Exchange. Это свойство также может указывать то же значение, что и свойство UserID, для событий, происходящих в других службах, и событий, выполняемых системными учетными записями. Обязательно:Да |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Тип пользователя, выполнившего операцию. Обязательно:Да |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Служба Office 365, в которой произошло действие в строке рабочей нагрузки. Возможные значения этого свойства: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Обязательно:Нет |

### Смотрите также

* class [Content](../content)
* пространство имен [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
