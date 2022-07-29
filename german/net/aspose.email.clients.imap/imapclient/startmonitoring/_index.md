---
title: StartMonitoring
second_title: Aspose.Email für .NET-API-Referenz
description: Startet die Überwachung von Nachrichtenänderungen für den angegebenen Ordner.
type: docs
weight: 1170
url: /de/net/aspose.email.clients.imap/imapclient/startmonitoring/
---
## ImapClient.StartMonitoring method

Startet die Überwachung von Nachrichtenänderungen für den angegebenen Ordner.

```csharp
public void StartMonitoring(ImapMonitoringEventHandler callback, 
    ImapMonitoringErrorEventHandler errorCallback, string folderName = "Inbox")
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | ImapMonitoringEventHandler | Die Callback-Funktion zur Überwachung des Betriebs. |
| errorCallback | ImapMonitoringErrorEventHandler | Die Callback-Funktion zur Überwachung der Fehlerbehandlung. Die Überwachung des angegebenen Ordners wird gestoppt, wenn dieser Callback aufgerufen wird. Der Callback stellt auch einen Zustandshalter bereit, damit die Ordnerüberwachung fortgesetzt werden kann mit[`ResumeMonitoring`](../resumemonitoring) Methode. |
| folderName | String | Der Ordner für die Betriebsüberwachung. |

### Siehe auch

* delegate [ImapMonitoringEventHandler](../../imapmonitoringeventhandler)
* delegate [ImapMonitoringErrorEventHandler](../../imapmonitoringerroreventhandler)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->