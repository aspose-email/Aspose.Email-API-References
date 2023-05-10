---
title: Class RestoreSettings
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Imap.RestoreSettings class. The settings for the ImapClient.Restore method
type: docs
weight: 16670
url: /net/aspose.email.clients.imap/restoresettings/
---
## RestoreSettings class

The settings for the ImapClient.Restore method

```csharp
public class RestoreSettings
```

## Constructors

| Name | Description |
| --- | --- |
| [RestoreSettings](restoresettings/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BeforeItemCallback](../../aspose.email.clients.imap/restoresettings/beforeitemcallback/) { get; set; } | The callback called when the next item (message or folder) is processed. |
| [Connection](../../aspose.email.clients.imap/restoresettings/connection/) { get; set; } | Connection to a server. |
| [Folders](../../aspose.email.clients.imap/restoresettings/folders/) { get; set; } | A folders to be restored. |
| [NumberOfAttemptsToRrepeat](../../aspose.email.clients.imap/restoresettings/numberofattemptstorrepeat/) { get; set; } | Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again. |
| [Options](../../aspose.email.clients.imap/restoresettings/options/) { get; set; } | Restore options. |
| [Recursive](../../aspose.email.clients.imap/restoresettings/recursive/) { get; set; } | Indicates that nested folders should be also restored |
| [RemoveNonexistentFolders](../../aspose.email.clients.imap/restoresettings/removenonexistentfolders/) { get; set; } | Indicates that mail folders, which do not have the equal folders in the personal storage, should be removed |
| [RemoveNonexistentItems](../../aspose.email.clients.imap/restoresettings/removenonexistentitems/) { get; set; } | Indicates that mail items, which do not have the equal items in the personal storage, should be removed |
| [RestoreConnection](../../aspose.email.clients.imap/restoresettings/restoreconnection/) { get; set; } | Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [TimeoutBetweenAttempts](../../aspose.email.clients.imap/restoresettings/timeoutbetweenattempts/) { get; set; } | Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option. |

## Methods

| Name | Description |
| --- | --- |
| [implicit operator](../../aspose.email.clients.imap/restoresettings/op_implicit/) | Converts enumerable options to class |

### See Also

* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap/)
* assembly [Aspose.Email](../../)


