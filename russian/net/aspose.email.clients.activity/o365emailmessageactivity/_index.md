---
title: O365EmailMessageActivity
second_title: Справочник по Aspose.Email для .NET API
description: Дополняет общую схему свойствами характерными для данных Office 365 Advanced Threat Protection и Threat Intelligence. События Office 365 Advanced Threat Protection ATP и Threat Intelligence доступны для клиентов Office 365 у которых есть подписка ATP Threat Intelligence или E5. Каждое событие в ленте ATP и Threat Intelligence соответствует Сообщению электронной почты отправленному или полученному пользователем в организации с обнаружениями сделанными в сообщениях во время доставки и с нуля часовая автоочистка.
type: docs
weight: 2660
url: /ru/net/aspose.email.clients.activity/o365emailmessageactivity/
---
## O365EmailMessageActivity class

Дополняет общую схему свойствами, характерными для данных Office 365 Advanced Threat Protection и Threat Intelligence. События Office 365 Advanced Threat Protection (ATP) и Threat Intelligence доступны для клиентов Office 365, у которых есть подписка ATP, Threat Intelligence или E5. Каждое событие в ленте ATP и Threat Intelligence соответствует Сообщению электронной почты, отправленному или полученному пользователем в организации с обнаружениями, сделанными в сообщениях во время доставки и с нуля часовая автоочистка.

```csharp
public class O365EmailMessageActivity : Content
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [O365EmailMessageActivity](o365emailmessageactivity)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AttachmentData](../../aspose.email.clients.activity/o365emailmessageactivity/attachmentdata) { get; set; } | Данные о вложениях в сообщении электронной почты, вызвавшем событие. Обязательно:Нет |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | IP-адрес устройства, которое использовалось при регистрации активности. IP-адрес отображается в формате адреса IPv4 или IPv6. Обязательно:Да |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | Дата и время в формате всемирного координированного времени (UTC), когда пользователь выполнил действие. Обязательно:Да |
| [DetectionMethod](../../aspose.email.clients.activity/o365emailmessageactivity/detectionmethod) { get; set; } | Метод или технология, используемые Office 365 ATP для обнаружения. Обязательно:Да |
| [DetectionType](../../aspose.email.clients.activity/o365emailmessageactivity/detectiontype) { get; set; } | Тип обнаружения. Обязательно:Да |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Уникальный идентификатор записи аудита. Обязательно:Да |
| [InternetMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/internetmessageid) { get; set; } | Идентификатор интернет-сообщения. Обязательно:Да |
| [NetworkMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/networkmessageid) { get; set; } | Идентификатор сетевого сообщения Exchange Online. Обязательно:Да |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Для активности SharePoint и OneDrive для бизнеса — полное имя файла или папки, к которым обращается пользователь. Для ведения журнала аудита администратора Exchange имя объекта, который был изменен командлетом. Обязательно:Нет |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Имя активности пользователя или администратора. Описание наиболее распространенных операций/действий см. в разделе Поиск в журнале аудита в Центре защиты Office 365. Для действий администратора Exchange это свойство определяет имя запущенного командлета. Для событий Dlp это может быть "DlpRuleMatch", "DlpRuleUndo" или "DlpInfo", которые описаны в разделе "Схема DLP" ниже. Обязательно:Да |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | GUID для клиента Office 365 вашей организации. Это значение всегда будет одинаковым для вашей организации, независимо от службы Office 365, в которой оно встречается. Обязательно:Да |
| [P1Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p1sender) { get; set; } | Обратный путь отправителя сообщения электронной почты. Обязательно:Да |
| [P2Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p2sender) { get; set; } | Отправитель сообщения электронной почты. Обязательно:Да |
| [Recipients](../../aspose.email.clients.activity/o365emailmessageactivity/recipients) { get; set; } | Массив получателей сообщения электронной почты. Обязательно:Да |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Тип операции, указанный в записи. Обязательно:Да |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Указывает, было ли действие (указанное в свойстве Operation) успешным или нет. Возможные значения:успешно, частично успешно или не удалось. Для действия администратора Exchange значение равно True или False. Обязательно:Нет |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Было ли это событие создано размещенной службой O365 или локальным сервером? Возможные значения:"в сети" и "на месте". Обратите внимание, что SharePoint — это единственная рабочая нагрузка, которая в настоящее время отправляет события из локальной среды в O365. Обязательно:Нет |
| [SenderIp](../../aspose.email.clients.activity/o365emailmessageactivity/senderip) { get; set; } | IP-адрес, с которого было отправлено электронное письмо Office 365. IP-адрес отображается в формате адреса IPv4 или IPv6. Обязательно:Да |
| [Subject](../../aspose.email.clients.activity/o365emailmessageactivity/subject) { get; set; } | Строка темы сообщения. Обязательно:Да |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | UPN (имя участника-пользователя) пользователя, выполнившего действие (указанное в свойстве Operation), в результате которого запись была зарегистрирована; например, my_name@my_domain_name. Обратите внимание, что также включены записи о действиях, выполняемых системными учетными записями (такими как SHAREPOINT\system или NT AUTHORITY\SYSTEM). Обязательно:Да |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Альтернативный идентификатор пользователя, указанного в свойстве UserId. Например, это свойство заполняется уникальным идентификатором паспорта (PUID) для событий, выполняемых пользователями в SharePoint, OneDrive для бизнеса и Exchange. Это свойство также может указывать то же значение, что и свойство UserID, для событий, происходящих в других службах, и событий, выполняемых системными учетными записями. Обязательно:Да |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Тип пользователя, выполнившего операцию. Обязательно:Да |
| [Verdict](../../aspose.email.clients.activity/o365emailmessageactivity/verdict) { get; set; } | Вердикт сообщения. Обязательно:Да |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Служба Office 365, в которой произошло действие в строке рабочей нагрузки. Возможные значения этого свойства: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Обязательно:Нет |

### Смотрите также

* class [Content](../content)
* пространство имен [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
