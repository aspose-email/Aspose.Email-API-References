---
title: MhtSaveOptions
second_title: Aspose.Email for .NET API 参考
description: 允许在将 MailMessage 保存为 Mhtml 格式时指定其他选项
type: docs
weight: 19080
url: /zh/net/aspose.email/mhtsaveoptions/
---
## MhtSaveOptions class

允许在将 MailMessage 保存为 Mhtml 格式时指定其他选项。

```csharp
public class MhtSaveOptions : HeadersFormattingOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MhtSaveOptions](mhtsaveoptions)() | 初始化此类的新实例，该实例可用于以 Mhtml 格式保存 MailMessage。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AfterHeadersFormat](../../aspose.email/headersformattingoptions/afterheadersformat) { get; set; } | 标头格式后。 |
| [BeforeHeadersFormat](../../aspose.email/headersformattingoptions/beforeheadersformat) { get; set; } | 在标头格式之前。 |
| [CheckBodyContentEncoding](../../aspose.email/mhtsaveoptions/checkbodycontentencoding) { get; set; } | 定义保存时是否需要检查消息体内容编码。 |
| [CssStyles](../../aspose.email/headersformattingoptions/cssstyles) { get; set; } | 获取或设置格式化程序的附加 css 样式。 |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler) { get; set; } | 表示通常由调用方提供并处理进度事件的方法。 |
| [DefaultHeaderFormat](../../aspose.email/headersformattingoptions/defaultheaderformat) { get; set; } | 默认标题行格式。 |
| [DefaultPageHeaderFormat](../../aspose.email/headersformattingoptions/defaultpageheaderformat) { get; set; } | 默认页眉格式。 |
| [FormatTemplates](../../aspose.email/headersformattingoptions/formattemplates) { get; } | 获取格式模板。 |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype) { get; set; } | 表示邮件消息保存类型。可以是eml,msg(ASCII or Unicode),mhtml 或html 格式。 默认值为Eml。 |
| [MhtFormatOptions](../../aspose.email/mhtsaveoptions/mhtformatoptions) { get; set; } | 以 MHTML 格式保存时定义附加选项。 默认值为 MhtFormatOptions.WriteHeader &#x7C; MhtFormatOptions.WriteOutlineAttachments. |
| [PreserveOriginalBoundaries](../../aspose.email/mhtsaveoptions/preserveoriginalboundaries) { get; set; } | 定义保存时是否需要保留邮件消息中的原始边界。 |
| [PreserveOriginalDate](../../aspose.email/mhtsaveoptions/preserveoriginaldate) { get; set; } | 定义保存时是否需要在邮件消息中保留原始日期。 默认值为true。 |
| [RenderedContactFields](../../aspose.email/headersformattingoptions/renderedcontactfields) { get; set; } | 定义将包含在输出 mhtml 中的联系人字段组。 默认值为 ContactFieldsSet.AllExisting. |
| [RenderingHeaders](../../aspose.email/headersformattingoptions/renderingheaders) { get; } | 获取用于渲染的标题列表。 |
| [SaveAttachments](../../aspose.email/mhtsaveoptions/saveattachments) { get; set; } | 获取或设置是否保存附件的值。 |
| [SkipInlineImages](../../aspose.email/mhtsaveoptions/skipinlineimages) { get; set; } | 定义是否在保存为 mhtml 时跳过对图像的引用。 默认值为 false。 |
| [Timeout](../../aspose.email/mhtsaveoptions/timeout) { get; set; } | 以毫秒为单位限制格式化消息的时间，同时保存在 Mht. 默认值 3 sek. |

### 也可以看看

* class [HeadersFormattingOptions](../headersformattingoptions)
* 命名空间 [Aspose.Email](../../aspose.email)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
