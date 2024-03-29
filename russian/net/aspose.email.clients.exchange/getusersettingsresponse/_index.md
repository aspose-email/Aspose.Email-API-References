---
title: GetUserSettingsResponse
second_title: Справочник по Aspose.Email для .NET API
description: Представляет ответ на вызов GetUsersSettings для отдельного пользователя.
type: docs
weight: 3470
url: /ru/net/aspose.email.clients.exchange/getusersettingsresponse/
---
## GetUserSettingsResponse class

Представляет ответ на вызов GetUsersSettings для отдельного пользователя.

```csharp
public sealed class GetUserSettingsResponse : AutodiscoverResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GetUserSettingsResponse](getusersettingsresponse)() | Инициализирует новый экземпляр[`GetUserSettingsResponse`](../getusersettingsresponse) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ErrorCode](../../aspose.email.clients.exchange/autodiscoverresponse/errorcode) { get; } | Получает код ошибки, возвращенный службой. |
| [ErrorMessage](../../aspose.email.clients.exchange/autodiscoverresponse/errormessage) { get; } | Получает сообщение об ошибке, возвращенное службой. |
| [RedirectTarget](../../aspose.email.clients.exchange/getusersettingsresponse/redirecttarget) { get; } | Получает цель перенаправления (URL или адрес электронной почты) |
| [Settings](../../aspose.email.clients.exchange/getusersettingsresponse/settings) { get; } | Получает запрошенные настройки для пользователя. |
| [SmtpAddress](../../aspose.email.clients.exchange/getusersettingsresponse/smtpaddress) { get; } | Получает SMTP-адрес, к которому относится этот ответ. |
| [UserSettingErrors](../../aspose.email.clients.exchange/getusersettingsresponse/usersettingerrors) { get; } | Получает информацию об ошибках для настроек, которые не удалось вернуть. |

## Методы

| Имя | Описание |
| --- | --- |
| [TryGetSettingValue&lt;T&gt;](../../aspose.email.clients.exchange/getusersettingsresponse/trygetsettingvalue)(UserSettingName, out T) | Пытается получить значение настройки пользователя. |

### Смотрите также

* class [AutodiscoverResponse](../autodiscoverresponse)
* пространство имен [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
