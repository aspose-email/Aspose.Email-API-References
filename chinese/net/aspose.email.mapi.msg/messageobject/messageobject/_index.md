---
title: MessageObject
second_title: Aspose.Email for .NET API 参考
description: 初始化MessageObjectaspose.email.mapi.msg/messageobject类.
type: docs
weight: 10
url: /zh/net/aspose.email.mapi.msg/messageobject/messageobject/
---
## MessageObject(Stream, MessageObjectLoadFormat) {#constructor}

初始化[`MessageObject`](../../messageobject)类.

```csharp
public MessageObject(Stream stream, MessageObjectLoadFormat loadFormat)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于初始化此对象的流。 |
| loadFormat | MessageObjectLoadFormat | 源格式消息对象存储在一起。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 如果给定的流为空。 |
| ArgumentOutOfRangeException | 如果指定*loadFormat*不支持。 |

### 也可以看看

* enum [MessageObjectLoadFormat](../../messageobjectloadformat)
* class [MessageObject](../../messageobject)
* 命名空间 [Aspose.Email.Mapi.Msg](../../messageobject)
* 部件 [Aspose.Email](../../../)

---

## MessageObject(string, MessageObjectLoadFormat) {#constructor_1}

初始化[`MessageObject`](../../messageobject)类.

```csharp
public MessageObject(string fileName, MessageObjectLoadFormat loadFormat)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 要读取的文件的名称。 |
| loadFormat | MessageObjectLoadFormat | 源格式消息对象存储在一起。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | 如果指定*loadFormat*不支持。 |

### 评论

此外，可能会引发与FileMode)呼叫.

### 也可以看看

* enum [MessageObjectLoadFormat](../../messageobjectloadformat)
* class [MessageObject](../../messageobject)
* 命名空间 [Aspose.Email.Mapi.Msg](../../messageobject)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
