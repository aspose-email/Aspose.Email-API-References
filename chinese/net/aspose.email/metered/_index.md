---
title: Metered
second_title: Aspose.Email for .NET API 参考
description: 提供设置计量键的方法
type: docs
weight: 19030
url: /zh/net/aspose.email/metered/
---
## Metered class

提供设置计量键的方法。

```csharp
public class Metered
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Metered](metered)() | 初始化此类的新实例。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [SetMeteredKey](../../aspose.email/metered/setmeteredkey)(string, string) | 设置计量公钥和私钥 |
| static [GetConsumptionCredit](../../aspose.email/metered/getconsumptioncredit)() | 获取消费信用 |
| static [GetConsumptionQuantity](../../aspose.email/metered/getconsumptionquantity)() | 获取消费文件大小 |

### 例子

在本例中，将尝试设置计量公钥和私钥

```csharp
[C#]

Metered mated = new Metered ();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

组件 jar 文件:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 也可以看看

* 命名空间 [Aspose.Email](../../aspose.email)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->