---
title: SetQuotaAsync
second_title: Справочник по Aspose.Email для .NET API
description: Устанавливает информацию о квоте
type: docs
weight: 350
url: /ru/net/aspose.email.clients.imap/iasyncimapclient/setquotaasync/
---
## IAsyncImapClient.SetQuotaAsync method

Устанавливает информацию о квоте

```csharp
public Task<ImapQuota[]> SetQuotaAsync(string quotaRootName, string resourceName, 
    int resourceLimit, IConnection connection = null, CancellationToken token = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | String | Подключение к серверу |
| quotaRootName | String | имя корня квоты |
| resourceName | Int32 | имя ресурса |
| resourceLimit | IConnection | лимит ресурсов |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Информация о квоте

### Смотрите также

* class [ImapQuota](../../imapquota)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
