---
title: IImapMonitoringState
second_title: Aspose.Email for Java API Reference
description: Holds folder monitoring state.
type: docs
weight: 767
url: /java/com.aspose.email/iimapmonitoringstate/
---
```
public interface IImapMonitoringState
```

Holds folder monitoring state. This can be used to resume folder monitoring from place where it stopped when error occured. Use [ImapClient.resumeMonitoring(ImapMonitoringEventHandler,ImapMonitoringErrorEventHandler,IImapMonitoringState)](../../com.aspose.email/imapclient\#resumeMonitoring-ImapMonitoringEventHandler-ImapMonitoringErrorEventHandler-IImapMonitoringState-) method.
## Methods

| Method | Description |
| --- | --- |
| [getFolderName()](#getFolderName--) | Folder for which monitoring state is held. |
### getFolderName() {#getFolderName--}
```
public abstract String getFolderName()
```


Folder for which monitoring state is held.

**Returns:**
java.lang.String
