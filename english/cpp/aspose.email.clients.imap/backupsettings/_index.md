---
title: "Aspose::Email::Clients::Imap::BackupSettings class"
linktitle: "BackupSettings"
articleTitle: "BackupSettings"
second_title: "Aspose.Email for C++"
description: "Class contains options for backup operation"
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/backupsettings/
---

## BackupSettings class

Class contains options for backup operation

## Constructors

| Name | Description |
| --- | --- |
| [BackupSettings (3 overloads)](./backupsettings/) | Initializes a new instance of the BackupSettings class |

## Methods

| Name | Description |
| --- | --- |
| [get_Default](./get_default/) | Gets BackupSettings class with settings by default |
| [get_ExecuteRecursively](./get_executerecursively/) | Gets value which defines if backup should be executed recursively |
| [get_NumberOfAttemptsToRrepeat](./get_numberofattemptstorrepeat/) | Gets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again. |
| [get_RestoreConnection](./get_restoreconnection/) | Gets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [get_TimeoutBetweenAttempts](./get_timeoutbetweenattempts/) | Gets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [set_ExecuteRecursively](./set_executerecursively/) | Sets value which defines if backup should be executed recursively |
| [set_NumberOfAttemptsToRrepeat](./set_numberofattemptstorrepeat/) | Sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again. |
| [set_RestoreConnection](./set_restoreconnection/) | Sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [set_TimeoutBetweenAttempts](./set_timeoutbetweenattempts/) | Sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [to_BackupSettings](./to_backupsettings/) | Converts enumerable options to class |

