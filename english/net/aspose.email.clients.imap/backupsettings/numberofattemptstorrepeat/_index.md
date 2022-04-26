---
title: NumberOfAttemptsToRrepeat
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 40
url: /net/aspose.email.clients.imap/backupsettings/numberofattemptstorrepeat/
---
## BackupSettings.NumberOfAttemptsToRrepeat property

Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again.

```csharp
public int NumberOfAttemptsToRrepeat { get; set; }
```

### See Also

* class [BackupSettings](../../backupsettings)
* namespace [Aspose.Email.Clients.Imap](../../backupsettings)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->