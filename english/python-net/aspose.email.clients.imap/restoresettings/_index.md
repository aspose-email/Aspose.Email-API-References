---
title: RestoreSettings
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 320
url: /python-net/aspose.email.clients.imap/restoresettings/
---

## RestoreSettings class

The settings for the ImapClient.Restore method

The RestoreSettings type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|RestoreSettings()|Initializes a new instance of the RestoreSettings class|
## Properties
| Name | Description |
| :- | :- |
|connection|Connection to a server.|
|options|Restore options.|
|folders|A folders to be restored.|
|restore_connection|Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly<br/>            This option has to be used together with NumberOfAttemptsToRrepeat option.|
|number_of_attempts_to_rrepeat|Gets or sets value which defines number of attempts to repeat failed operation<br/>            In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times.<br/>            For instance if FETCH operation returns error<br/>            AE_1_1_0243 FETCH 219 (BODY) <br/>            AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available<br/>            Client tries to execute it again.|
|timeout_between_attempts|Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again<br/>            This option has to be used together with NumberOfAttemptsToRrepeat option.|
|remove_nonexistent_folders|Indicates that mail folders, which do not have the equal folders in the personal storage, should be removed|
|remove_nonexistent_items|Indicates that mail items, which do not have the equal items in the personal storage, should be removed|
|recursive|Indicates that nested folders should be also restored|

### See Also

* namespace [aspose.email.clients.imap](/email/python-net/aspose.email.clients.imap/)
* assembly [Aspose.Email](/email/python-net/)

