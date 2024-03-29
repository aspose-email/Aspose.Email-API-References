---
title: RestoreAsync
second_title: Справочник по Aspose.Email для .NET API
description: Начинает восстанавливать папки imap из заданного личного хранилища.
type: docs
weight: 320
url: /ru/net/aspose.email.clients.imap/iasyncimapclient/restoreasync/
---
## IAsyncImapClient.RestoreAsync method

Начинает восстанавливать папки imap из заданного личного хранилища.

```csharp
public Task RestoreAsync(PersonalStorage pst, RestoreSettings settings, 
    CancellationToken token = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pst | PersonalStorage | Личное хранилище, содержащее резервные копии папок imap. |
| settings | RestoreSettings | Настройки восстановления |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [RestoreSettings](../../restoresettings)
* interface [IAsyncImapClient](../../iasyncimapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
