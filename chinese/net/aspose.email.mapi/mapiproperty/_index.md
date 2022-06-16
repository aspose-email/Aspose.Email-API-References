---
title: MapiProperty
second_title: Aspose.Email for .NET API 参考
description: 表示 mapi 属性
type: docs
weight: 18530
url: /zh/net/aspose.email.mapi/mapiproperty/
---
## MapiProperty class

表示 mapi 属性。

```csharp
public class MapiProperty
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MapiProperty](mapiproperty#constructor_2)(long) | 初始化 MapiProperty 类的新实例。 |
| [MapiProperty](mapiproperty#constructor_3)(long, byte[]) | 初始化 MapiProperty 类的新实例。 |
| [MapiProperty](mapiproperty#constructor_5)(long, IList&lt;object&gt;) | 初始化[`MapiProperty`](../mapiproperty)类的新实例。 此重载用于创建多值属性 PT_MV_*。 |
| [MapiProperty](mapiproperty#constructor)(PidLidPropertyDescriptor, object) | 初始化 MapiProperty 类的新实例。 |
| [MapiProperty](mapiproperty#constructor_1)(PidTagPropertyDescriptor, object) | 初始化 MapiProperty 类的新实例。 |
| [MapiProperty](mapiproperty#constructor_4)(long, long, byte[]) | 初始化[`MapiProperty`](../mapiproperty)类的新实例。 |
| [MapiProperty](mapiproperty#constructor_6)(string, long, long, byte[]) | 初始化 MapiProperty 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data) { get; } | 获取二进制数据。 |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype) { get; } | 获取数据类型。 |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor) { get; } | 获取 MAPI 属性的描述符 |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier) { get; } | 获取指示符。 |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed) { get; } | 指示属性是否为命名属性。 |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned) { get; set; } | 表示二进制数据是否有符号。 |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries) { get; } | 获取MV条目列表。 |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name) { get; } | 获取名称。 |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname) { get; } | 获取 PropertyName。 |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag) { get; } | 获取标签。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [CreateMapiPropertyFromBytes](../../aspose.email.mapi/mapiproperty/createmapipropertyfrombytes)(long, byte[]) | 从字节创建 mapi 属性。 |
| static [CreateMapiPropertyFromDateTime](../../aspose.email.mapi/mapiproperty/createmapipropertyfromdatetime)(long, DateTime) | 从日期时间创建 mapi 属性。 |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong)(long, long) | 从 long 创建 mapi 属性。 |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong_1)(long, long, long) | 从 long 创建 mapi 属性。 |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean)() | 获取二进制数据的第一个字节作为布尔值。 |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency)() | 使用指定的代码页以字符串形式获取货币。 |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime)() | 获取二进制数据的第一个字节作为日期时间。 |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble)() | 获取二进制数据的字节为 double。 |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat)() | 获取二进制数据的字节为浮点数。 |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate)() | 获取二进制数据的字节为 DateTime。 |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid)() | 获取二进制数据的字节作为 Guid。 |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32)() | 获取二进制数据的前 4 个字节为 int32。 |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong)() | 获取二进制数据的前 8 个字节。 |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort)() | 获取二进制数据的前 2 个字节作为短字节。 |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring)() | 以字符串形式获取二进制数据。 |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring_1)(int) | 使用指定的代码页获取二进制数据作为字符串。 |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue)() | 获取值作为对象 |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring)() | 返回代表当前Object的String。 |

### 也可以看看

* 命名空间 [Aspose.Email.Mapi](../../aspose.email.mapi)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->