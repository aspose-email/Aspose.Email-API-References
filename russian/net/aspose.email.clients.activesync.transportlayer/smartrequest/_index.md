---
title: SmartRequest
second_title: Справочник по Aspose.Email для .NET API
description: Содержит информацию об интеллектуальном запросе
type: docs
weight: 2090
url: /ru/net/aspose.email.clients.activesync.transportlayer/smartrequest/
---
## SmartRequest class

Содержит информацию об интеллектуальном запросе

```csharp
public class SmartRequest
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SmartRequest](smartrequest)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AccountId](../../aspose.email.clients.activesync.transportlayer/smartrequest/accountid) { get; set; } | Идентифицирует учетную запись, с которой отправляется электронное письмо. Если AccountId имеет значение null, сервер отправляет электронное письмо, используя учетную запись, указанную параметром settings:PrimarySmtpAddress, возвращаемым в ответе на команду Settings. Если AccountId включен в запрос, значение ДОЛЖНО равняться одному из значений элемента settings:AccountId, включенных в ответ на команду Settings. Сервер ДОЛЖЕН подтвердить, что предоставленное значение элемента AccountId допустимо для отправки электронной почты. Значение состояния 166 возвращается, если значение элемента AccountId недопустимо. Значение элемента Status, равное 167, возвращается, если учетная запись не поддерживает отправку электронной почты. Примечание. Сервер отправляет электронное письмо, используя учетную запись, указанную в AccountId, а не учетную запись, указанную в параметре From. Элемент AccountId не поддерживается, если используется версия протокола 12.1 или 14.0. Exchange 2007 возвращает значение состояния 103, если элемент AccountId включен в запрос команды SendMail, запрос команды SmartForward или запрос команды SmartReply. |
| [ClientId](../../aspose.email.clients.activesync.transportlayer/smartrequest/clientid) { get; set; } | Указывает уникальный идентификатор сообщения клиента (MID). Значение ClientId может иметь длину до 40 символов и ДОЛЖНО быть уникальным для каждого сообщения, поскольку сервер будет использовать значение ClientId для идентификации повторяющихся сообщений. Значение ClientId может быть простым счетчиком, увеличивающимся для каждого нового сообщения. |
| [Mime](../../aspose.email.clients.activesync.transportlayer/smartrequest/mime) { get; set; } | Содержит сообщение в кодировке MIME. Содержимое Mime передается как непрозрачный BLOB внутри тегов WBXML, как указано в [WBXML1.2]. Если сообщение содержит приглашение на собрание, элемент Mime содержит сведения о собрании в формате iCalendar [MS-OXCICAL] или в формате Transport Neutral Encapsulation Format (TNEF) [MS-OXTNEF]. Как указано в разделе 3.4 [RFC2447], приглашения на собрания iCalendar имеют тип содержимого "текст/календарь" с параметром метода, установленным на "ЗАПРОС". |
| [ReplaceMime](../../aspose.email.clients.activesync.transportlayer/smartrequest/replacemime) { get; set; } | Указывает, отправляет ли клиент сообщение целиком. Когда ReplaceMime имеет значение TRUE, сервер НЕ ДОЛЖЕН включать тело или вложения исходного пересылаемого сообщения. Когда ReplaceMime имеет значение FALSE, клиент ДОЛЖЕН добавить тело исходного сообщения в качестве вложения к исходящему сообщению. Клиент может использовать это свойство, чтобы указать, было ли сообщение отредактировано встроенным или текст ответа/пересылки был добавлен перед исходным сообщением. Если ReplaceMime имеет значение TRUE, сообщение было отредактировано. |
| [SaveInSentItems](../../aspose.email.clients.activesync.transportlayer/smartrequest/saveinsentitems) { get; set; } | Указывает, будет ли копия сообщения храниться в папке "Отправленные". |
| [Source](../../aspose.email.clients.activesync.transportlayer/smartrequest/source) { get; set; } | Содержит информацию об исходном сообщении. |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/smartrequest/templateid) { get; set; } | Содержит строку, идентифицирующую шаблон политики прав, представленный родительским элементом RightsManagementLicense. |

### Смотрите также

* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->