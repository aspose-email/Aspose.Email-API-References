---
title: Class Metered
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Metered class. Provides methods to set metered key
type: docs
weight: 17840
url: /net/aspose.email/metered/
---
## Metered class

Provides methods to set metered key.

```csharp
public class Metered
```

## Constructors

| Name | Description |
| --- | --- |
| [Metered](metered/)() | Initializes a new instance of this class. |

## Properties

| Name | Description |
| --- | --- |
| static [IsBillingServiceRun](../../aspose.email/metered/isbillingservicerun/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [GetProductName](../../aspose.email/metered/getproductname/)() |  |
| [SetMeteredKey](../../aspose.email/metered/setmeteredkey/)(string, string) | Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |
| static [GetConsumptionCredit](../../aspose.email/metered/getconsumptioncredit/)() | Gets consumption credit |
| static [GetConsumptionQuantity](../../aspose.email/metered/getconsumptionquantity/)() | Gets consumption file size |
| static [IsMeteredLicensed](../../aspose.email/metered/ismeteredlicensed/)() | Check whether metered is licensed |

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


