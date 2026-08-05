---
title: "Aspose::Email::Clients::Imap::ImapClient::ResumeMonitoring method"
linktitle: "ResumeMonitoring"
articleTitle: "ResumeMonitoring"
second_title: "Aspose.Email for C++"
description: "Resumes monitoring of message changes for specified folder."
type: docs
weight: 1720
url: /cpp/aspose.email.clients.imap/imapclient/resumemonitoring/
---

## ResumeMonitoring {#resumemonitoring}

Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method, it will find all missing mailbox changes and call the callback for them.

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ResumeMonitoring(ImapMonitoringEventHandler callback, ImapMonitoringErrorEventHandler errorCallback, System::SharedPtr < IImapMonitoringState > monitoringState)
```

| Parameter | Description |
| --- | --- |
| callback | The callback function for monitoring operation. |
| errorCallback | The callback function for monitoring error handling. Monitoring of specified folder is stopped when this callback is called. |
| monitoringState | The monitoring state to resume folder monitoring from. Can be retrieved from ImapMonitoringErrorEventArgs::MonitoringState . |

