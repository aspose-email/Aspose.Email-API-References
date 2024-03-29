---
title: MapiNamedProperty
second_title: Aspose.Email for .NET API 参考
description: 表示命名属性的数据类型
type: docs
weight: 18510
url: /zh/net/aspose.email.mapi/mapinamedproperty/
---
## MapiNamedProperty class

表示命名属性的数据类型。

```csharp
public sealed class MapiNamedProperty : MapiProperty
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MapiNamedProperty](mapinamedproperty#constructor)() | 初始化[`MapiNamedProperty`](../mapinamedproperty)类. |
| [MapiNamedProperty](mapinamedproperty#constructor_1)(INamedPropertyTagProvider, PidLidPropertyDescriptor, object) | 初始化[`MapiNamedProperty`](../mapinamedproperty)类. |
| [MapiNamedProperty](mapinamedproperty#constructor_2)(INamedPropertyTagProvider, PidNamePropertyDescriptor, object) | 初始化[`MapiNamedProperty`](../mapinamedproperty)类. |
| [MapiNamedProperty](mapinamedproperty#constructor_3)(long, long, Guid, byte[]) | 初始化[`MapiNamedProperty`](../mapinamedproperty)类. |
| [MapiNamedProperty](mapinamedproperty#constructor_4)(long, string, Guid, byte[]) | 初始化[`MapiNamedProperty`](../mapinamedproperty)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data) { get; } | 获取二进制数据。 |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype) { get; } | 获取数据类型。 |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor) { get; } | 获取 MAPI 属性的描述符 |
| [Guid](../../aspose.email.mapi/mapinamedproperty/guid) { get; } | 获取命名属性 GUID |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier) { get; } | 获取标识符。 |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed) { get; } | 指示属性是否为命名属性。 |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned) { get; set; } | 表示二进制数据是否有符号。 |
| [Kind](../../aspose.email.mapi/mapinamedproperty/kind) { get; } | 获得命名属性 kind |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries) { get; } | 获取 MV 条目列表。 |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name) { get; } | 获取名称。 |
| [NameId](../../aspose.email.mapi/mapinamedproperty/nameid) { get; } | 获得命名属性 ID |
| [Oom](../../aspose.email.mapi/mapinamedproperty/oom) { get; } | 获取 OOM 值 |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname) { get; } | 获取属性名称。 |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag) { get; } | 获取标签。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean)() | 获取二进制数据的第一个字节作为布尔值。 |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency)() | 使用指定的代码页获取货币字符串。 |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime)() | 获取二进制数据的第一个字节作为日期时间。 |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble)() | 以双精度获取二进制数据的字节数。 |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat)() | 获取二进制数据的字节为浮点数。 |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate)() | 获取二进制数据的字节为 DateTime. |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid)() | 获取二进制数据的字节为 Guid. |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32)() | 获取二进制数据的前 4 个字节为 int32. |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong)() | 获取二进制数据的前 8 个字节 as long. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort)() | 获取二进制数据的前 2 个字节为 short. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring)() | 以字符串形式获取二进制数据。 |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring)(int) | 使用指定的代码页获取二进制数据作为字符串。 |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue)() | 获取值作为对象 |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring)() | 返回一个String代表当前Object. |

### 也可以看看

* class [MapiProperty](../mapiproperty)
* 命名空间 [Aspose.Email.Mapi](../../aspose.email.mapi)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
