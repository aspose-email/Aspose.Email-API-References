---
title: Class SendGridClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.DeliveryService.SendGrid.SendGridClient class. Represents the SendGrid client
type: docs
weight: 3000
url: /net/aspose.email.clients.deliveryservice.sendgrid/sendgridclient/
---
## SendGridClient class

Represents the SendGrid client

```csharp
public class SendGridClient : IDeliveryServiceClient
```

## Constructors

| Name | Description |
| --- | --- |
| [SendGridClient](sendgridclient/)(string, bool, SendGridRegion) | Initializes a new instance of the `SendGridClient` class |

## Properties

| Name | Description |
| --- | --- |
| [EndPoint](../../aspose.email.clients.deliveryservice.sendgrid/sendgridclient/endpoint/) { get; set; } | Gets or sets SendGridClient endpoint. If not specified, the default is "https://api.sendgrid.com". |

## Methods

| Name | Description |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients.deliveryservice.sendgrid/sendgridclient/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [Send](../../aspose.email.clients.deliveryservice.sendgrid/sendgridclient/send/)(MailMessage, List&lt;string&gt;, CancellationToken?) | Sends email synchronously |
| [SendAsync](../../aspose.email.clients.deliveryservice.sendgrid/sendgridclient/sendasync/)(MailMessage, List&lt;string&gt;, CancellationToken?) | Sends email asynchronously |

### See Also

* interface [IDeliveryServiceClient](../../aspose.email.clients.deliveryservice/ideliveryserviceclient/)
* namespace [Aspose.Email.Clients.DeliveryService.SendGrid](../../aspose.email.clients.deliveryservice.sendgrid/)
* assembly [Aspose.Email](../../)


