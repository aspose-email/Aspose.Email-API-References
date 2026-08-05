---
title: "Aspose::Email::Clients::Imap::ImapClient::StartMonitoring method"
linktitle: "StartMonitoring"
articleTitle: "StartMonitoring"
second_title: "Aspose.Email for C++"
description: "Starts monitoring of message changes for specified folder."
type: docs
weight: 2060
url: /cpp/aspose.email.clients.imap/imapclient/startmonitoring/
---

## StartMonitoring {#startmonitoring}

Starts monitoring of message changes for specified folder.

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
StartMonitoring(ImapMonitoringEventHandler callback, ImapMonitoringErrorEventHandler errorCallback, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| callback | The callback function for monitoring operation. |
| errorCallback | The callback function for monitoring error handling. Monitoring of specified folder is stopped when this callback is called. The callback also provides a state holder so folder monitoring could be resumed using ResumeMonitoring method. |
| folderName | The folder for monitoring operation. |

