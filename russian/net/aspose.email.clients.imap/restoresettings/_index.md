---
title: RestoreSettings
second_title: Справочник по Aspose.Email для .NET API
description: Настройки метода ImapClient.Restore
type: docs
weight: 16670
url: /ru/net/aspose.email.clients.imap/restoresettings/
---
## RestoreSettings class

Настройки метода ImapClient.Restore

```csharp
public class RestoreSettings
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RestoreSettings](restoresettings)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BeforeItemCallback](../../aspose.email.clients.imap/restoresettings/beforeitemcallback) { get; set; } | Обратный вызов, вызываемый при обработке следующего элемента (сообщения или папки). |
| [Connection](../../aspose.email.clients.imap/restoresettings/connection) { get; set; } | Подключение к серверу. |
| [Folders](../../aspose.email.clients.imap/restoresettings/folders) { get; set; } | Папки для восстановления. |
| [NumberOfAttemptsToRrepeat](../../aspose.email.clients.imap/restoresettings/numberofattemptstorrepeat) { get; set; } | Получает или задает значение, которое определяет количество попыток повторить неудачную операцию В случае, если какая-то команда IMAP внутри операции резервного копирования возвращает неудачный результат, клиент IMAP пытается повторить эту операцию снова в соответствии с заданным количеством раз. Например, если операция FETCH возвращает error AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] Служба FETCH временно недоступна Клиент пытается выполнить ее снова. |
| [Options](../../aspose.email.clients.imap/restoresettings/options) { get; set; } | Параметры восстановления. |
| [Recursive](../../aspose.email.clients.imap/restoresettings/recursive) { get; set; } | Указывает, что вложенные папки также должны быть восстановлены |
| [RemoveNonexistentFolders](../../aspose.email.clients.imap/restoresettings/removenonexistentfolders) { get; set; } | Указывает, что почтовые папки, не имеющие аналогов в личном хранилище, должны быть удалены |
| [RemoveNonexistentItems](../../aspose.email.clients.imap/restoresettings/removenonexistentitems) { get; set; } | Указывает, что почтовые отправления, не имеющие себе равных в личном хранилище, должны быть удалены |
| [RestoreConnection](../../aspose.email.clients.imap/restoresettings/restoreconnection) { get; set; } | Получает или задает значение, определяющее, нужно ли восстанавливать соединение в случае, если сервер принудительно закрывает соединение. Эта опция должна использоваться вместе с опцией NumberOfAttemptsToRrepeat. |
| [TimeoutBetweenAttempts](../../aspose.email.clients.imap/restoresettings/timeoutbetweenattempts) { get; set; } | Получает или задает значение, определяющее тайм-аут (в миллисекундах) между попытками выполнить операцию снова Этот параметр должен использоваться вместе с параметром NumberOfAttemptsToRrepeat. |

## Методы

| Имя | Описание |
| --- | --- |
| [implicit operator](../../aspose.email.clients.imap/restoresettings/op_implicit) | Преобразует перечисляемые параметры в class |

### Смотрите также

* пространство имен [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
