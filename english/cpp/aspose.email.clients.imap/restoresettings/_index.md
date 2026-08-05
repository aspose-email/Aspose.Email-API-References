---
title: "Aspose::Email::Clients::Imap::RestoreSettings class"
linktitle: "RestoreSettings"
articleTitle: "RestoreSettings"
second_title: "Aspose.Email for C++"
description: "The settings for the ImapClient.Restore method"
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/restoresettings/
---

## RestoreSettings class

The settings for the ImapClient.Restore method

## Constructors

| Name | Description |
| --- | --- |
| [RestoreSettings](./restoresettings/) |  |

## Methods

| Name | Description |
| --- | --- |
| [BeforeItemCallbackExecutor](./beforeitemcallbackexecutor/) |  |
| [get_BeforeItemCallback](./get_beforeitemcallback/) | The callback called when the next item (message or folder) is processed. |
| [get_Connection](./get_connection/) | Connection to a server. |
| [get_Folders](./get_folders/) | A folders to be restored. |
| [get_NumberOfAttemptsToRrepeat](./get_numberofattemptstorrepeat/) | Gets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again. |
| [get_Options](./get_options/) | Restore options. |
| [get_Recursive](./get_recursive/) | Indicates that nested folders should be also restored |
| [get_RemoveNonexistentFolders](./get_removenonexistentfolders/) | Indicates that mail folders, which do not have the equal folders in the personal storage, should be removed |
| [get_RemoveNonexistentItems](./get_removenonexistentitems/) | Indicates that mail items, which do not have the equal items in the personal storage, should be removed |
| [get_RestoreConnection](./get_restoreconnection/) | Gets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [get_TimeoutBetweenAttempts](./get_timeoutbetweenattempts/) | Gets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [set_BeforeItemCallback](./set_beforeitemcallback/) | The callback called when the next item (message or folder) is processed. |
| [set_Connection](./set_connection/) | Connection to a server. |
| [set_Folders](./set_folders/) | A folders to be restored. |
| [set_NumberOfAttemptsToRrepeat](./set_numberofattemptstorrepeat/) | Sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again. |
| [set_Options](./set_options/) | Restore options. |
| [set_Recursive](./set_recursive/) | Indicates that nested folders should be also restored |
| [set_RemoveNonexistentFolders](./set_removenonexistentfolders/) | Indicates that mail folders, which do not have the equal folders in the personal storage, should be removed |
| [set_RemoveNonexistentItems](./set_removenonexistentitems/) | Indicates that mail items, which do not have the equal items in the personal storage, should be removed |
| [set_RestoreConnection](./set_restoreconnection/) | Sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [set_TimeoutBetweenAttempts](./set_timeoutbetweenattempts/) | Sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [to_RestoreSettings](./to_restoresettings/) | Converts enumerable options to class |

