---
title: MapiAttachment
second_title: Aspose.Email for .NET API 参考
description: 表示电子邮件中的附件
type: docs
weight: 17880
url: /zh/net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

表示电子邮件中的附件。

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata) { get; set; } | 获取或设置二进制附件数据。 |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | 获取代码页。 |
| [Content](../../aspose.email.mapi/mapiattachment/content) { get; } | 获取内容。 |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname) { get; } | 获取附件中 ole 对象的显示名称。 |
| [Extension](../../aspose.email.mapi/mapiattachment/extension) { get; } | 获取指示附件文档类型的文件扩展名。 |
| [FileName](../../aspose.email.mapi/mapiattachment/filename) { get; } | 获取附件的基本文件名和扩展名，不包括路径。 |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid) { get; } | 项目 ID，与服务器一起使用 |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename) { get; } | 获取附件的长文件名和扩展名，不包括路径。 |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag) { get; } | 获取有关 多用途 Internet 邮件扩展 (MIME) 附件的格式信息。 |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties) { get; } | 获取消息的命名属性。 |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata) { get; } | 获取通常通过 OLE IStorage 接口访问 的附件对象。 |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | 获取属性的集合。 |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream) { get; } | 获取属性流。 |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages) { get; } | 获取子存储。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty)(PropertyDescriptor) | 通过属性描述符获取 MAPI 属性。 |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | 获取tag指定的属性值为布尔类型。 |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | 获取tag指定的属性的字符串值。 |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | 获取 tag 指定的属性值为 DateTime 类型。 |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | 获取tag指定的属性的int32值。 |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | 获取tag指定的属性值为Long(int64)类型。 |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | 获取 tag 指定的属性值为 Short 类型。 |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | 获取tag指定的属性的字符串值。 |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | 获取tag指定的属性的字符串值。 |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | 确定字符串属性是否为 Unicode 编码。 |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty)(long) | 提供从所有集合中正确删除的属性。 |
| [Save](../../aspose.email.mapi/mapiattachment/save#save)(Stream) | 保存附件内容。 |
| [Save](../../aspose.email.mapi/mapiattachment/save#save_1)(string) | 保存附件内容。 |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty)(MapiProperty) | 设置属性。 |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty_1)(PropertyDescriptor, object) | 设置 MAPI 属性。 |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | 尝试获取指定标签键的属性数据。 |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | 获取指定属性的值作为 DateTime 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | 获取指定属性的值作为 Int32 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | 获取指定属性的值作为 Long 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | 尝试获取属性数据作为带有指定标签的字符串。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | 尝试将属性数据作为具有指定标签和代码页的字符串获取。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | 以字符串类型获取指定属性的值。 返回值表示操作是否成功。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | 以字符串类型获取指定属性的值。 返回值表示操作是否成功。 |

### 也可以看看

* class [MapiPropertyContainer](../mapipropertycontainer)
* 命名空间 [Aspose.Email.Mapi](../../aspose.email.mapi)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
