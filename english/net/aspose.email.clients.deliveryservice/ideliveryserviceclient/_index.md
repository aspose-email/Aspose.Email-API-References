---
title: Interface IDeliveryServiceClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.DeliveryService.IDeliveryServiceClient interface. Represents contract for DeliveryServiceClient
type: docs
weight: 1510
url: /net/aspose.email.clients.deliveryservice/ideliveryserviceclient/
---
## IDeliveryServiceClient interface

Represents contract for DeliveryServiceClient

```csharp
public interface IDeliveryServiceClient : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [EndPoint](../../aspose.email.clients.deliveryservice/ideliveryserviceclient/endpoint/) { get; set; } | Gets or sets DeliveryService endpoint. If not specified, the default is https://api.mailgun.net for MailGunClient and https://api.sendgrid.com for SendGridClient. |

## Methods

| Name | Description |
| --- | --- |
| [Send](../../aspose.email.clients.deliveryservice/ideliveryserviceclient/send/)(MailMessage, List&lt;string&gt;, CancellationToken?) | Sends email synchronously |
| [SendAsync](../../aspose.email.clients.deliveryservice/ideliveryserviceclient/sendasync/)(MailMessage, List&lt;string&gt;, CancellationToken?) | Sends email asynchronously |

### See Also

* namespace [Aspose.Email.Clients.DeliveryService](../../aspose.email.clients.deliveryservice/)
* assembly [Aspose.Email](../../)


