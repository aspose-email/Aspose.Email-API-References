---
title: Class Metered
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Metered class. Provides methods to set metered key
type: docs
weight: 19320
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

## Methods

| Name | Description |
| --- | --- |
| [SetMeteredKey](../../aspose.email/metered/setmeteredkey/)(string, string) | Sets metered public and private key |
| static [GetConsumptionCredit](../../aspose.email/metered/getconsumptioncredit/)() | Gets consumption credit |
| static [GetConsumptionQuantity](../../aspose.email/metered/getconsumptionquantity/)() | Gets consumption file size |

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


