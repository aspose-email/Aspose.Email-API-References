---
title: ImapMonitoringErrorEventArgs
second_title: Aspose.Email for Java API Reference
description:  Class contains monitoring error event data.
type: docs
weight: 318
url: /java/com.aspose.email/imapmonitoringerroreventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ImapMonitoringErrorEventArgs extends System.EventArgs
```

Class contains monitoring error event data.
## Methods

| Method | Description |
| --- | --- |
| [getFolderName()](#getFolderName--) | Specified folder for monitoring operation. |
| [getError()](#getError--) | IMAP monitoring error. |
| [getMonitoringState()](#getMonitoringState--) | Holds folder monitoring state. |
### getFolderName() {#getFolderName--}
```
public final String getFolderName()
```


Specified folder for monitoring operation.

**Returns:**
java.lang.String
### getError() {#getError--}
```
public final Throwable getError()
```


IMAP monitoring error.

**Returns:**
java.lang.Throwable
### getMonitoringState() {#getMonitoringState--}
```
public final IImapMonitoringState getMonitoringState()
```


Holds folder monitoring state. This object can be used to resume folder monitoring from place where it stopped when error occured. Use ImapClient.resumeMonitoring method.

**Returns:**
[IImapMonitoringState](../../com.aspose.email/iimapmonitoringstate)
