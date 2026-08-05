---
title: "Aspose::Email::Clients::Imap::BackupSettings::set_NumberOfAttemptsToRrepeat method"
linktitle: "set_NumberOfAttemptsToRrepeat"
articleTitle: "set_NumberOfAttemptsToRrepeat"
second_title: "Aspose.Email for C++"
description: "Sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client t"
type: docs
weight: 70
url: /cpp/aspose.email.clients.imap/backupsettings/set_numberofattemptstorrepeat/
---

## set_NumberOfAttemptsToRrepeat {#set_numberofattemptstorrepeat}

Sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again.

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
set_NumberOfAttemptsToRrepeat(int32_t value)
```

| Parameter | Description |
| --- | --- |
| value |  |

