---
title: SortConditions
second_title: Aspose.Email for .NET API 参考
description: 提供 SORT 扩展的搜索条件 与在 https//tools.ietf.org/html/rfc5256
type: docs
weight: 16720
url: /zh/net/aspose.email.clients.imap/sortconditions/
---
## SortConditions class

提供 SORT 扩展的搜索条件。 与在 https://tools.ietf.org/html/rfc5256

```csharp
public sealed class SortConditions : BaseSearchConditions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SortConditions](sortconditions)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Charset](../../aspose.email.clients.imap/basesearchconditions/charset) { get; set; } | 获取或设置字符集。 表示 出现在搜索条件中的字符串的字符集。 |
| [ReverseBy](../../aspose.email.clients.imap/sortconditions/reverseby) { get; set; } | 获取或设置反向排序标准 后跟另一个排序标准，具有该标准的效果，但以反向（降序）顺序。 注意: REVERSE 仅反转单个标准，如果所有其他标准相同，则不会影响隐含的“序列号”排序标准。 因此，REVERSE SUBJECT 排序与 SUBJECT 排序的反向排序不同。 这可以通过使用附加标准来避免，例如，主题日期与反向主题反向日期。 但是，一般来说，最好（如果客户端有“反向当前排序”命令，则更快）在客户端中反转结果而不是发出新的 SORT。 |
| [Since](../../aspose.email.clients.imap/basesearchconditions/since) { get; set; } | 获取或设置搜索条件匹配的自 以来的消息日期。 |
| [SortBy](../../aspose.email.clients.imap/sortconditions/sortby) { get; set; } | 获取或设置排序标准 |
| [Text](../../aspose.email.clients.imap/basesearchconditions/text) { get; set; } | 获取或设置主题文本。 |
| [UseUId](../../aspose.email.clients.imap/basesearchconditions/useuid) { get; set; } | 获取或设置一个值，该值指示 搜索方法是否返回消息的序列号或 UID。 |

### 也可以看看

* class [BaseSearchConditions](../basesearchconditions)
* 命名空间 [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->