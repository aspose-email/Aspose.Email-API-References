---
title: ValidateMessage
second_title: Aspose.Email for .NET API 参考
description: 验证 eml 消息是否符合 mime 规范
type: docs
weight: 590
url: /zh/net/aspose.email/mailmessage/validatemessage/
---
## ValidateMessage(string) {#validatemessage_1}

验证 eml 消息是否符合 mime 规范。

```csharp
public static EmlValidationErrorCollection ValidateMessage(string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 文件名 (eml)。 |

### 返回值

一个[`EmlValidationErrorCollection`](../../emlvalidationerrorcollection)包含找到的验证错误消息。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | *fileName*是`无效的`或者`空的`. |
| FileNotFoundException | 指定的*fileName*不存在。 |

### 也可以看看

* class [EmlValidationErrorCollection](../../emlvalidationerrorcollection)
* class [MailMessage](../../mailmessage)
* 命名空间 [Aspose.Email](../../mailmessage)
* 部件 [Aspose.Email](../../../)

---

## ValidateMessage(Stream) {#validatemessage}

验证 eml 消息是否符合 mime 规范。

```csharp
public static EmlValidationErrorCollection ValidateMessage(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 包含 eml 格式消息的流。 |

### 返回值

一个[`EmlValidationErrorCollection`](../../emlvalidationerrorcollection)包含找到的验证错误消息。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *stream*是`无效的`. |

### 也可以看看

* class [EmlValidationErrorCollection](../../emlvalidationerrorcollection)
* class [MailMessage](../../mailmessage)
* 命名空间 [Aspose.Email](../../mailmessage)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
