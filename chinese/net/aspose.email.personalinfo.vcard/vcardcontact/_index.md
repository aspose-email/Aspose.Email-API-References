---
title: VCardContact
second_title: Aspose.Email for .NET API 参考
description: 表示 vCard 联系人
type: docs
weight: 19570
url: /zh/net/aspose.email.personalinfo.vcard/vcardcontact/
---
## VCardContact class

表示 vCard 联系人

```csharp
public sealed class VCardContact
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [VCardContact](vcardcontact)() | 初始化[`VCardContact`](../vcardcontact) class |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [DeliveryAddresses](../../aspose.email.personalinfo.vcard/vcardcontact/deliveryaddresses) { get; set; } | 获取或设置收货地址 |
| [Emails](../../aspose.email.personalinfo.vcard/vcardcontact/emails) { get; set; } | 获取或设置联系人的电子邮件地址 |
| [ExplanatoryInfo](../../aspose.email.personalinfo.vcard/vcardcontact/explanatoryinfo) { get; set; } | 获取或设置vCard说明信息 |
| [ExtendedProperties](../../aspose.email.personalinfo.vcard/vcardcontact/extendedproperties) { get; set; } | 获取或设置扩展属性 |
| [Geo](../../aspose.email.personalinfo.vcard/vcardcontact/geo) { get; set; } | 获取或设置一个全球定位 |
| [IdentificationInfo](../../aspose.email.personalinfo.vcard/vcardcontact/identificationinfo) { get; set; } | 获取或设置标识属性 |
| [Labels](../../aspose.email.personalinfo.vcard/vcardcontact/labels) { get; set; } | 获取或设置收货地址 |
| [Mailer](../../aspose.email.personalinfo.vcard/vcardcontact/mailer) { get; set; } | 获取或设置邮件程序 |
| [Organization](../../aspose.email.personalinfo.vcard/vcardcontact/organization) { get; set; } | 获取或设置组织信息 |
| [Security](../../aspose.email.personalinfo.vcard/vcardcontact/security) { get; set; } | 获取或设置安全属性 |
| [TelephoneNumbers](../../aspose.email.personalinfo.vcard/vcardcontact/telephonenumbers) { get; set; } | 获取或设置联系人的电话号码 |
| [TimeZone](../../aspose.email.personalinfo.vcard/vcardcontact/timezone) { get; set; } | 获取或设置 timeZone |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load)(Stream) | 读取[`VCardContact`](../vcardcontact)来自包含 vCard 的指定流。 支持的 vCard 版本为 2.1 和 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_4)(string) | 读取[`VCardContact`](../vcardcontact)从指定的 vCard 文件 支持的 vCard 版本为 2.1 和 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_3)(Stream, CancellationToken) | 读取[`VCardContact`](../vcardcontact)来自包含 vCard 的指定流。 支持的 vCard 版本为 2.1 和 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_1)(Stream, Encoding) | 读取[`VCardContact`](../vcardcontact)来自包含 vCard 的指定流。 支持的 vCard 版本为 2.1 和 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_7)(string, CancellationToken) | 读取[`VCardContact`](../vcardcontact)从指定的 vCard 文件 支持的 vCard 版本为 2.1 和 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_5)(string, Encoding) | 读取[`VCardContact`](../vcardcontact)从指定的 vCard 文件 支持的 vCard 版本为 2.1 和 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_2)(Stream, Encoding, CancellationToken) | 读取[`VCardContact`](../vcardcontact)来自包含 vCard 的指定流。 支持的 vCard 版本为 2.1 和 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_6)(string, Encoding, CancellationToken) | 读取[`VCardContact`](../vcardcontact)从指定的 vCard 文件 支持的 vCard 版本为 2.1 和 3.0 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save)(Stream) | 保存这个[`MapiContact`](../../aspose.email.mapi/mapicontact)进入具有 vCard 格式的给定流。 支持的 vCard 版本是 2.1 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_3)(string) | 保存这个[`MapiContact`](../../aspose.email.mapi/mapicontact)到带有默认选项的 vCard 文件。 支持的 vCard 版本是 2.1 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_1)(Stream, ContactSaveFormat) | 保存这个[`MapiContact`](../../aspose.email.mapi/mapicontact)使用默认选项的格式保存到给定的流。 支持的保存格式是vCard |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_2)(Stream, ContactSaveOptions) | 保存这个[`MapiContact`](../../aspose.email.mapi/mapicontact)使用指定的保存选项到给定的流。 支持的保存选项是[`VCardSaveOptions`](../vcardsaveoptions) |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_4)(string, ContactSaveFormat) | 保存这个[`MapiContact`](../../aspose.email.mapi/mapicontact)以使用默认选项的格式保存到指定文件。 支持的保存格式为 vCard。 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_5)(string, ContactSaveOptions) | 保存这个[`MapiContact`](../../aspose.email.mapi/mapicontact)使用指定的保存选项进入文件。 支持的保存选项是[`VCardSaveOptions`](../vcardsaveoptions) |
| static [IsMultiContacts](../../aspose.email.personalinfo.vcard/vcardcontact/ismulticontacts)(Stream) | 检查源流是否包含多个联系人。 |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple)(Stream, Encoding) | 从多联系人流中加载联系人列表。 |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_2)(string, Encoding) | 从多联系人文件中加载联系人列表。 |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_1)(Stream, Encoding, CancellationToken) | 从多联系人流中加载联系人列表。 |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_3)(string, Encoding, CancellationToken) | 从多联系人流中加载联系人列表。 |

### 也可以看看

* 命名空间 [Aspose.Email.PersonalInfo.VCard](../../aspose.email.personalinfo.vcard)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
