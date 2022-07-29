---
title: ListAppointmentsAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Ruft die Terminliste für den angegebenen Kalenderordner ab
type: docs
weight: 400
url: /de/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsasync/
---
## IAsyncEwsClient.ListAppointmentsAsync method

Ruft die Terminliste für den angegebenen Kalenderordner ab

```csharp
public Task<Appointment[]> ListAppointmentsAsync(string folderUri, MailQuery query, bool recursive, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderUri | String | Ein Ordner zum Suchen von Terminen. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) das Suchkriterien für Termine darstellt. |
| recursive | Boolean | Gibt an, ob rekursive Auflistung oder nicht. |
| cancellationToken | CancellationToken | Das Abbruchtoken. |

### Rückgabewert

Gibt ein Array von Terminen zurück

### Siehe auch

* class [Appointment](../../../aspose.email.calendar/appointment)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->