---
title: "Aspose::Email::Metered class"
linktitle: "Metered"
articleTitle: "Metered"
second_title: "Aspose.Email for C++"
description: "Provides methods to set metered key."
type: docs
weight: 10
url: /cpp/aspose.email/metered/
---

## Metered class

Provides methods to set metered key.

In this example, an attempt will be made to set metered public and private key

<ms>

```cpp
[C#]
@verbatim 
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");
 
 
[Visual Basic]
 
Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```

</ms>

<java> the component jar file:

```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

</java>

## Constructors

| Name | Description |
| --- | --- |
| [Metered](./metered/) | Initializes a new instance of this class. |

## Methods

| Name | Description |
| --- | --- |
| [get_IsBillingServiceRun](./get_isbillingservicerun/) |  |
| [GetConsumptionCredit](./getconsumptioncredit/) | Gets consumption credit |
| [GetConsumptionQuantity](./getconsumptionquantity/) | Gets consumption file size |
| [GetProductName](./getproductname/) |  |
| [IncreaseCredit](./increasecredit/) | Increases the credit. |
| [IsMeteredLicensed](./ismeteredlicensed/) | Check whether metered is licensed |
| [IsPluginLicensed](./ispluginlicensed/) |  |
| [SetConsumption](./setconsumption/) | Sets the data consumption. |
| [SetMeteredKey](./setmeteredkey/) | Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |

