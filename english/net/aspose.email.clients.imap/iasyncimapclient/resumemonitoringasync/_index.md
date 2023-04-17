---
title: IAsyncImapClient.ResumeMonitoringAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method it will find all missing mailbox changes and call the callback for them
type: docs
weight: 330
url: /net/aspose.email.clients.imap/iasyncimapclient/resumemonitoringasync/
---
## IAsyncImapClient.ResumeMonitoringAsync method

Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method, it will find all missing mailbox changes and call the callback for them.

```csharp
public Task ResumeMonitoringAsync(ImapMonitoringEventHandler callback, 
    ImapMonitoringErrorEventHandler errorCallback, IImapMonitoringState monitoringState, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | ImapMonitoringEventHandler | The callback function for monitoring operation. |
| errorCallback | ImapMonitoringErrorEventHandler | The callback function for monitoring error handling. Monitoring of specified folder is stopped when this callback is called. The callback also provides a state holder so folder monitoring could be resumed using [`ResumeMonitoringAsync`](../../imapclient/resumemonitoringasync/) method. |
| monitoringState | IImapMonitoringState | The monitoring state to resume folder monitoring from. Can be retrieved from [`MonitoringState`](../../imapmonitoringerroreventargs/monitoringstate/). |
| token | CancellationToken | The cancellation token. |

### See Also

* delegate [ImapMonitoringEventHandler](../../imapmonitoringeventhandler/)
* delegate [ImapMonitoringErrorEventHandler](../../imapmonitoringerroreventhandler/)
* interface [IImapMonitoringState](../../iimapmonitoringstate/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


