---
title: Class Metered
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Metered class. Licenses the product with a metered payperuse key and reports the consumption
type: docs
weight: 17940
url: /net/aspose.email/metered/
---
## Metered class

Licenses the product with a metered (pay-per-use) key and reports the consumption.

```csharp
public class Metered
```

## Constructors

| Name | Description |
| --- | --- |
| [Metered](metered/)() | Initializes a new instance of the `Metered` class. |

## Properties

| Name | Description |
| --- | --- |
| static [IsBillingServiceRun](../../aspose.email/metered/isbillingservicerun/) { get; } | Gets a value indicating whether the metered billing service is running. |

## Methods

| Name | Description |
| --- | --- |
| [GetBillingStatus](../../aspose.email/metered/getbillingstatus/)() | Checks whether the billing service is available. |
| [GetProductName](../../aspose.email/metered/getproductname/)() | Gets the name of the product the metered license is for. |
| [SetMeteredKey](../../aspose.email/metered/setmeteredkey/)(string, string) | Activates the metered license with the public and private keys. |
| static [GetConsumptionCredit](../../aspose.email/metered/getconsumptioncredit/)() | Gets the number of credits consumed. |
| static [GetConsumptionQuantity](../../aspose.email/metered/getconsumptionquantity/)() | Gets the amount of data processed under the metered license. |
| static [IsMeteredLicensed](../../aspose.email/metered/ismeteredlicensed/)() | Gets a value indicating whether a metered license is active. |

## Examples

In this example, an attempt will be made to set metered public and private key

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

the component jar file:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


