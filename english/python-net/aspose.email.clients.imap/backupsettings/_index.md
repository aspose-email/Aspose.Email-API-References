---
title: BackupSettings
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 40
url: /python-net/aspose.email.clients.imap/backupsettings/
---

## BackupSettings class

Class contains options for backup operation

The BackupSettings type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|BackupSettings()|Initializes a new instance of the [BackupSettings](/email/python-net/aspose.email.clients.imap/backupsettings/) class|
|BackupSettings(options)|Initializes a new instance of the BackupSettings class|
|BackupSettings(execute_recursively, restore_connection, number_of_attempts, timeout_between_attempts)|Initializes a new instance of the BackupSettings class|
## Properties
| Name | Description |
| :- | :- |
|default|Gets [BackupSettings](/email/python-net/aspose.email.clients.imap/backupsettings/) class with settings by default|
|execute_recursively|Gets or sets value which defines if backup should be executed recursively|
|restore_connection|Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly<br/>            This option has to be used together with NumberOfAttemptsToRrepeat option.|
|number_of_attempts_to_rrepeat|Gets or sets value which defines number of attempts to repeat failed operation<br/>            In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times.<br/>            For instance if FETCH operation returns error<br/>            AE_1_1_0243 FETCH 219 (BODY) <br/>            AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available<br/>            Client tries to execute it again.|
|timeout_between_attempts|Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again<br/>            This option has to be used together with NumberOfAttemptsToRrepeat option.|

### See Also

* namespace [aspose.email.clients.imap](/email/python-net/aspose.email.clients.imap/)
* assembly [Aspose.Email](/email/python-net/)

