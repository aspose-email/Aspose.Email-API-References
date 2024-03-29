---
title: IEWSClient.FindMessageTrackingReport
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Finds messages that meet the specified criteria
type: docs
weight: 850
url: /net/aspose.email.clients.exchange.webservice/iewsclient/findmessagetrackingreport/
---
## IEWSClient.FindMessageTrackingReport method

Finds messages that meet the specified criteria.

```csharp
public MessageTrackingReportInfo[] FindMessageTrackingReport(
    FindMessageTrackingReportOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | FindMessageTrackingReportOptions | Options specifying a search criteria |

### Return Value

An array of [`MessageTrackingReportInfo`](../../messagetrackingreportinfo/) that represents message tracking report information

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | throws when *options* is `null` |

### See Also

* class [MessageTrackingReportInfo](../../messagetrackingreportinfo/)
* class [FindMessageTrackingReportOptions](../../findmessagetrackingreportoptions/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


