---
title: Contact
second_title: Aspose.Email for .NET API 参考
description: 代表联系信息
type: docs
weight: 19320
url: /zh/net/aspose.email.personalinfo/contact/
---
## Contact class

代表联系信息。

```csharp
public class Contact : IPreferredTextEncodingProvider
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Contact](contact)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Account](../../aspose.email.personalinfo/contact/account) { get; set; } | 包含通讯簿对象的别名，它是可用于识别对象的替代名称。 |
| [AssociatedPersons](../../aspose.email.personalinfo/contact/associatedpersons) { get; } | 获取相关人员列表 |
| [Attachments](../../aspose.email.personalinfo/contact/attachments) { get; } | 获取附件集合 |
| [CompanyName](../../aspose.email.personalinfo/contact/companyname) { get; set; } | 获取或设置公司名称。 |
| [ComputerNetworkName](../../aspose.email.personalinfo/contact/computernetworkname) { get; set; } | 获取或设置邮件用户计算机网络的名称。 |
| [CustomerId](../../aspose.email.personalinfo/contact/customerid) { get; set; } | 获取或设置客户 id |
| [DepartmentName](../../aspose.email.personalinfo/contact/departmentname) { get; set; } | 获取或设置部门名称。 |
| [DisplayName](../../aspose.email.personalinfo/contact/displayname) { get; set; } | 获取或设置显示名称 |
| [EmailAddresses](../../aspose.email.personalinfo/contact/emailaddresses) { get; } | 获取电子邮件地址列表 |
| [Events](../../aspose.email.personalinfo/contact/events) { get; } | 获取事件列表 |
| [FileAs](../../aspose.email.personalinfo/contact/fileas) { get; set; } | 获取或设置用于排序的名称。 |
| [FileAsMapping](../../aspose.email.personalinfo/contact/fileasmapping) { get; set; } | 获取或设置一个值，该值指定如何在其他联系人姓名属性更改时生成和重新计算 FileAs 属性 的值。 |
| [FreeBusyLocation](../../aspose.email.personalinfo/contact/freebusylocation) { get; set; } | 获取或设置 URL 路径，客户端可以从中检索联系人的忙/闲信息作为 iCal 文件 |
| [Gender](../../aspose.email.personalinfo/contact/gender) { get; set; } | 获取或设置一个人的性别。 |
| [GivenName](../../aspose.email.personalinfo/contact/givenname) { get; set; } | 获取或设置一个名字，它是一个人全名的一部分。 名字也被称为个人名字、名字、名字或教名。 |
| [GovernmentIdNumber](../../aspose.email.personalinfo/contact/governmentidnumber) { get; set; } | 获取或设置一个政府标识号 |
| [Hobbies](../../aspose.email.personalinfo/contact/hobbies) { get; set; } | 获取或设置一个爱好 |
| [Id](../../aspose.email.personalinfo/contact/id) { get; } | 获取对象标识信息 |
| [Initials](../../aspose.email.personalinfo/contact/initials) { get; set; } | 获取或设置一个缩写 |
| [InstantMessengers](../../aspose.email.personalinfo/contact/instantmessengers) { get; } | 获取即时通讯地址列表 |
| [JobTitle](../../aspose.email.personalinfo/contact/jobtitle) { get; set; } | 获取或设置职位。 |
| [Language](../../aspose.email.personalinfo/contact/language) { get; set; } | 获取或设置语言 |
| [Location](../../aspose.email.personalinfo/contact/location) { get; set; } | 获取或设置位置 |
| [MiddleName](../../aspose.email.personalinfo/contact/middlename) { get; set; } | 获取或设置一个中间名，它是一个人全名的一部分。 在某些国家，人们有一个额外的（中间名）。 |
| [Nickname](../../aspose.email.personalinfo/contact/nickname) { get; set; } | 获取或设置一个人的昵称。 |
| [Notes](../../aspose.email.personalinfo/contact/notes) { get; set; } | 获取或设置注释 |
| [NotesFormat](../../aspose.email.personalinfo/contact/notesformat) { get; set; } | 获取或设置注释字段的格式。 |
| [OfficeLocation](../../aspose.email.personalinfo/contact/officelocation) { get; set; } | 获取或设置办公地点 |
| [OrganizationalIdNumber](../../aspose.email.personalinfo/contact/organizationalidnumber) { get; set; } | 包含在邮件用户的组织中使用的邮件用户的标识符。 |
| [PhoneNumbers](../../aspose.email.personalinfo/contact/phonenumbers) { get; } | 获取电话号码列表 |
| [Photo](../../aspose.email.personalinfo/contact/photo) { get; set; } | 获取或设置联系人的图像 |
| [PhysicalAddresses](../../aspose.email.personalinfo/contact/physicaladdresses) { get; } | 获取邮政地址列表 |
| [PreferredTextEncoding](../../aspose.email.personalinfo/contact/preferredtextencoding) { get; set; } | 获取或设置所有文本属性的首选编码 |
| [Prefix](../../aspose.email.personalinfo/contact/prefix) { get; set; } | 获取或设置全名前缀，如先生（先生）、博士（医生）等。 |
| [Profession](../../aspose.email.personalinfo/contact/profession) { get; set; } | 获取或设置一个人在公司的职位。 |
| [Suffix](../../aspose.email.personalinfo/contact/suffix) { get; set; } | 获取或设置全名的后缀，如Jr.(junior)、Sr.(senior)等。 |
| [Surname](../../aspose.email.personalinfo/contact/surname) { get; set; } | 获取或设置作为人全名一部分的姓氏。 姓氏也称为姓氏或姓氏。 |
| [Urls](../../aspose.email.personalinfo/contact/urls) { get; } | 获取 url 列表 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Load](../../aspose.email.personalinfo/contact/load#load)(Stream) | 加载联系人数据 |
| static [Load](../../aspose.email.personalinfo/contact/load#load_2)(string) | 加载联系人数据 |
| static [Load](../../aspose.email.personalinfo/contact/load#load_1)(Stream, ContactLoadFormat) | 加载联系人数据 |
| static [Load](../../aspose.email.personalinfo/contact/load#load_3)(string, ContactLoadFormat) | 加载联系人数据 |
| [Save](../../aspose.email.personalinfo/contact/save#save)(Stream) | 保存这个[`MapiContact`](../../aspose.email.mapi/mapicontact)进入具有 vCard 格式的给定流。 支持的 vCard 版本是 2.1 |
| [Save](../../aspose.email.personalinfo/contact/save#save_3)(string) | 保存这个[`MapiContact`](../../aspose.email.mapi/mapicontact)到带有默认选项的 vCard 文件。 支持的 vCard 版本是 2.1 |
| [Save](../../aspose.email.personalinfo/contact/save#save_1)(Stream, ContactSaveFormat) | 保存这个[`Contact`](../contact)使用默认选项的格式到给定的流。 |
| [Save](../../aspose.email.personalinfo/contact/save#save_2)(Stream, ContactSaveOptions) | 保存这个[`Contact`](../contact)使用指定的保存选项到给定的流。 |
| [Save](../../aspose.email.personalinfo/contact/save#save_4)(string, ContactSaveFormat) | 保存这个[`MapiContact`](../../aspose.email.mapi/mapicontact)以使用默认选项的格式保存到指定文件。 支持的保存格式为 vCard。 |
| [Save](../../aspose.email.personalinfo/contact/save#save_5)(string, ContactSaveOptions) | 保存这个[`MapiContact`](../../aspose.email.mapi/mapicontact)使用指定的保存选项进入文件。 支持的保存选项是[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| override [ToString](../../aspose.email.personalinfo/contact/tostring)() | 返回代表当前对象的字符串。 |
| [implicit operator](../../aspose.email.personalinfo/contact/op_implicit#op_implicit) | 转换[`Contact`](../contact)至[`MapiContact`](../../aspose.email.mapi/mapicontact)object (2 operators) |

### 也可以看看

* interface [IPreferredTextEncodingProvider](../../aspose.email/ipreferredtextencodingprovider)
* 命名空间 [Aspose.Email.PersonalInfo](../../aspose.email.personalinfo)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
