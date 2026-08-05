---
title: "Aspose::Email::Clients::Imap::RestoreSettings::get_NumberOfAttemptsToRrepeat method"
linktitle: "get_NumberOfAttemptsToRrepeat"
articleTitle: "get_NumberOfAttemptsToRrepeat"
second_title: "Aspose.Email for C++"
description: "Gets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client t"
type: docs
weight: 50
url: /cpp/aspose.email.clients.imap/restoresettings/get_numberofattemptstorrepeat/
---

## get_NumberOfAttemptsToRrepeat {#get_numberofattemptstorrepeat}

Gets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again.

**Returns:** int32_t Aspose::Email::Clients::Imap::

```cpp
get_NumberOfAttemptsToRrepeat()
```

