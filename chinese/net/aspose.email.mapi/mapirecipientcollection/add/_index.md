---
title: Add
second_title: Aspose.Email for .NET API 参考
description: 添加新的收件人
type: docs
weight: 20
url: /zh/net/aspose.email.mapi/mapirecipientcollection/add/
---
## Add(string, string, MapiRecipientType) {#add_2}

添加新的收件人。

```csharp
public void Add(string address, string displayName, MapiRecipientType recipientType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| address | String | 收件人的邮件地址。 |
| displayName | String | 收件人的显示名称。 |
| recipientType | MapiRecipientType | 收件人的类型。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 如果收件人地址为空或为空，则抛出。 |
| ArgumentException | 如果收件人地址不是可识别的格式，则抛出。 |

### 评论

添加新收件人时， MapiMessage.DisplayTo 或 MapiMessage.DisplayBcc 或 MapiMessage.DisplayCC 的值也会根据收件人的类型进行更新。

### 也可以看看

* enum [MapiRecipientType](../../mapirecipienttype)
* class [MapiRecipientCollection](../../mapirecipientcollection)
* 命名空间 [Aspose.Email.Mapi](../../mapirecipientcollection)
* 部件 [Aspose.Email](../../../)

---

## Add(string, string, string, MapiRecipientType) {#add_3}

添加新的收件人。

```csharp
public void Add(string address, string addressType, string displayName, 
    MapiRecipientType recipientType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| address | String | 收件人的邮件地址。 |
| addressType | String | 地址的类型。 |
| displayName | String | 收件人的显示名称。 |
| recipientType | MapiRecipientType | 收件人的类型。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 如果收件人地址为空或为空，则抛出。 |
| ArgumentException | 如果收件人地址不是可识别的格式，则抛出。 |

### 评论

添加新收件人时， MapiMessage.DisplayTo 或 MapiMessage.DisplayBcc 或 MapiMessage.DisplayCC 的值也会根据收件人的类型进行更新。

### 也可以看看

* enum [MapiRecipientType](../../mapirecipienttype)
* class [MapiRecipientCollection](../../mapirecipientcollection)
* 命名空间 [Aspose.Email.Mapi](../../mapirecipientcollection)
* 部件 [Aspose.Email](../../../)

---

## Add(MapiRecipient) {#add}

在末尾添加一个对象Collection.

```csharp
public void Add(MapiRecipient item)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | MapiRecipient | 要添加到末尾的对象Collection.对于引用类型，该值可以为 null。 |

### 也可以看看

* class [MapiRecipient](../../mapirecipient)
* class [MapiRecipientCollection](../../mapirecipientcollection)
* 命名空间 [Aspose.Email.Mapi](../../mapirecipientcollection)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
