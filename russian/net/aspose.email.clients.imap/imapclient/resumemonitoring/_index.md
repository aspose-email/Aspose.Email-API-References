---
title: ResumeMonitoring
second_title: Справочник по Aspose.Email для .NET API
description: Возобновляет мониторинг изменений сообщений для указанной папки. В отличие от метода StartMonitoring он найдет все отсутствующие изменения почтового ящика и вызовет обратный вызов для них.
type: docs
weight: 1070
url: /ru/net/aspose.email.clients.imap/imapclient/resumemonitoring/
---
## ImapClient.ResumeMonitoring method

Возобновляет мониторинг изменений сообщений для указанной папки. В отличие от метода StartMonitoring, он найдет все отсутствующие изменения почтового ящика и вызовет обратный вызов для них.

```csharp
public void ResumeMonitoring(ImapMonitoringEventHandler callback, 
    ImapMonitoringErrorEventHandler errorCallback, IImapMonitoringState monitoringState)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | ImapMonitoringEventHandler | Функция обратного вызова для контроля работы. |
| errorCallback | ImapMonitoringErrorEventHandler | Функция обратного вызова для мониторинга обработки ошибок. Мониторинг указанной папки останавливается при вызове этого обратного вызова. |
| monitoringState | IImapMonitoringState | Состояние мониторинга для возобновления мониторинга папки. Можно получить из[`MonitoringState`](../../imapmonitoringerroreventargs/monitoringstate) . |

### Смотрите также

* delegate [ImapMonitoringEventHandler](../../imapmonitoringeventhandler)
* delegate [ImapMonitoringErrorEventHandler](../../imapmonitoringerroreventhandler)
* interface [IImapMonitoringState](../../iimapmonitoringstate)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
