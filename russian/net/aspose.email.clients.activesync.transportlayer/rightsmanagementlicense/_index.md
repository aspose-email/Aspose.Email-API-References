---
title: RightsManagementLicense
second_title: Справочник по Aspose.Email для .NET API
description: Содержит параметры шаблона политики прав для шаблона примененного к синхронизируемому сообщению электронной почты.
type: docs
weight: 1900
url: /ru/net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/
---
## RightsManagementLicense class

Содержит параметры шаблона политики прав для шаблона, примененного к синхронизируемому сообщению электронной почты.

```csharp
public class RightsManagementLicense
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RightsManagementLicense](rightsmanagementlicense)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ContentExpiryDate](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentexpirydate) { get; set; } | Указывает дату истечения срока действия лицензии. Элементу ContentExpiryDate присваивается значение «9999-12-30T23:59:59.999Z», если срок действия лицензии на управление правами не установлен. |
| [ContentOwner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentowner) { get; set; } | Указывает, может ли пользователь изменять содержимое исходного сообщения электронной почты, когда пользователь пересылает, отвечает или отвечает всем на сообщение электронной почты. Значение равно TRUE, если сообщение электронной почты может быть изменено пользователем; в противном случае FALSE. Значение FALSE требует, чтобы клиент ДОЛЖЕН исключить исходное сообщение электронной почты с управляемыми правами из запроса SmartForward или SmartReply. Следовательно, встроенные ответы не допускаются, если для элемента EditAllowed установлено значение FALSE. Если для параметра EditAllowed установлено значение FALSE, а ReplaceMime отсутствует в запросе SmartForward или SmartReply, сервер добавит исходное сообщение электронной почты с управляемыми правами в качестве вложения к новому сообщению. И наоборот, если присутствует ReplaceMime, сервер не будет прикреплять исходное сообщение электронной почты с управляемыми правами в качестве вложения. |
| [EditAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/editallowed) { get; set; } | Указывает, может ли пользователь изменять содержимое исходного сообщения электронной почты, когда пользователь пересылает, отвечает или отвечает всем на сообщение электронной почты. Значение равно TRUE, если сообщение электронной почты может быть изменено пользователем; в противном случае FALSE. Значение FALSE требует, чтобы клиент ДОЛЖЕН исключить исходное сообщение электронной почты с управляемыми правами из запроса SmartForward или SmartReply. Следовательно, встроенные ответы не допускаются, если для элемента EditAllowed установлено значение FALSE. Если для параметра EditAllowed установлено значение FALSE, а ReplaceMime отсутствует в запросе SmartForward или SmartReply, сервер добавит исходное сообщение электронной почты с управляемыми правами в качестве вложения к новому сообщению. И наоборот, если composemail:ReplaceMime присутствует, сервер не будет прикреплять исходное сообщение электронной почты с управляемыми правами в качестве вложения. |
| [ExportAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/exportallowed) { get; set; } | Указывает, может ли пользователь удалить защиту IRM для сообщения электронной почты. Значение равно TRUE, если пользователь может удалить защиту IRM, когда пользователь пересылает, отвечает или отвечает на все сообщения электронной почты; в противном случае — FALSE. Если сообщение электронной почты с управлением правами пересылается или на него отвечает команда SmartForward или SmartReply, оцениваются следующие условия: для сообщения установлен шаблон «Нет ограничений» (значение TemplateID «00000000-0000-0000-0000-000000000000») Если выполняются оба условия, защита IRM снимается с исходящего сообщения. Исходное сообщение сохраняет защиту IRM. |
| [ExtractAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/extractallowed) { get; set; } | Указывает, может ли пользователь копировать содержимое сообщения электронной почты. Значение равно TRUE, если содержимое сообщения электронной почты можно вырезать, копировать или сделать снимок экрана; в противном случае ЛОЖЬ. |
| [ForwardAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/forwardallowed) { get; set; } | Указывает, может ли пользователь пересылать сообщение электронной почты. Значение TRUE, если пользователь может пересылать сообщение электронной почты; в противном случае ЛОЖЬ. |
| [ModifyRecipientsAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/modifyrecipientsallowed) { get; set; } | Указывает, может ли пользователь изменять список получателей, когда пользователь пересылает или отвечает на сообщение электронной почты. Значение TRUE, если пользователь может изменять список получателей (1); в противном случае ЛОЖЬ. |
| [Owner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/owner) { get; set; } | Указывает, является ли пользователь владельцем сообщения электронной почты. Значение TRUE, если пользователь является владельцем сообщения электронной почты; в противном случае ЛОЖЬ. Значение TRUE указывает, что аутентифицированный пользователь имеет права владельца на это сообщение. Этот элемент используется только для целей представления информации. Элементы Allowed (EditAllowed, ReplyAllowed и т. д.) используются для оценки того, разрешено или ограничено определенное действие. |
| [PrintAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/printallowed) { get; set; } | Указывает, может ли пользователь распечатать сообщение электронной почты. Этот элемент не указывает на поддержку клиентом печати сообщения электронной почты; он только указывает, может ли сообщение электронной почты быть распечатано, если клиент поддерживает печать. Значение равно TRUE, если сообщение электронной почты может быть распечатано пользователем; в противном случае ЛОЖЬ. |
| [ProgrammaticAccessAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/programmaticaccessallowed) { get; set; } | Указывает, может ли стороннее приложение получать программный доступ к содержимому сообщения электронной почты. Значение равно TRUE, если сторонние приложения могут программно получать доступ к содержимому сообщения электронной почты; в противном случае ЛОЖЬ. Значение TRUE указывает, доступен ли защищенный контент другим приложениям. Защищенное содержимое состоит из тела сообщения и вложений. |
| [ReplyAllAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallallowed) { get; set; } | Указывает, может ли пользователь отвечать всем получателям (1) исходного сообщения электронной почты. Значение равно TRUE, если пользователь может отвечать всем получателям сообщения электронной почты; в противном случае ЛОЖЬ. |
| [ReplyAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallowed) { get; set; } | Указывает, разрешено ли пользователю отвечать на сообщение электронной почты. Значение TRUE, если пользователь может ответить на сообщение электронной почты; в противном случае ЛОЖЬ. |
| [TemplateDescription](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatedescription) { get; set; } | Содержит описание шаблона политики прав, представленного родительским элементом RightsManagementLicense. Этот элемент используется только в целях представления информации. Максимальная длина элемента TemplateDescription составляет 10240 символов. |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templateid) { get; set; } | Содержит строку, идентифицирующую шаблон политики прав, представленный родительским элементом RightsManagementLicense. |
| [TemplateName](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatename) { get; set; } | Задает имя шаблона политики прав, представленного родительским элементом RightsManagementLicense. Этот элемент используется только в целях представления информации. Максимальная длина элемента TemplateName составляет 256 символов. |

### Смотрите также

* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
