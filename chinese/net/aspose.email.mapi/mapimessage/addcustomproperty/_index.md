---
title: AddCustomProperty
second_title: Aspose.Email for .NET API 参考
description: 添加自定义属性
type: docs
weight: 310
url: /zh/net/aspose.email.mapi/mapimessage/addcustomproperty/
---
## AddCustomProperty(MapiProperty, string) {#addcustomproperty}

添加自定义属性。

```csharp
public void AddCustomProperty(MapiProperty property, string stringNameId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| property | MapiProperty | 该物业[`MapiProperty`](../../mapiproperty). |
| stringNameId | String | 物业名称String. |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 如果*property*一片空白。 |
| ArgumentException | 如果属性数据为空。 |
| NotSupportedException | 如果尚不支持数据类型。 |

### 也可以看看

* class [MapiProperty](../../mapiproperty)
* class [MapiMessage](../../mapimessage)
* 命名空间 [Aspose.Email.Mapi](../../mapimessage)
* 部件 [Aspose.Email](../../../)

---

## AddCustomProperty(MapiPropertyType, byte[], string) {#addcustomproperty_1}

添加自定义属性。

```csharp
public void AddCustomProperty(MapiPropertyType type, byte[] data, string stringNameId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | MapiPropertyType | MapiProperty 类型[`MapiPropertyType`](../../mapipropertytype) |
| data | Byte[] | MapiProperty 数据。Byte |
| stringNameId | String | 物业名称String. |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果属性数据为空。 |
| NotSupportedException | 如果尚不支持数据类型。 |

### 也可以看看

* enum [MapiPropertyType](../../mapipropertytype)
* class [MapiMessage](../../mapimessage)
* 命名空间 [Aspose.Email.Mapi](../../mapimessage)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
