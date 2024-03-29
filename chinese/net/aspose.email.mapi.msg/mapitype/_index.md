---
title: MapiType
second_title: Aspose.Email for .NET API 参考
description: 包含可以与消息对象一起存储的可能的 MAPI 属性类型
type: docs
weight: 18810
url: /zh/net/aspose.email.mapi.msg/mapitype/
---
## MapiType enumeration

包含可以与消息对象一起存储的可能的 MAPI 属性类型。

```csharp
public enum MapiType
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| None | `0` | 未设置任何值。 |
| PT_SHORT | `2` | 2 个字节，一个 16 位整数 |
| PT_LONG | `3` | 4 个字节，一个 32 位整数 |
| PT_FLOAT | `4` | 4 个字节，一个 32 位浮点数 |
| PT_DOUBLE | `5` | 8 个字节，一个 64 位浮点数 |
| PT_CURRENCY | `6` | 8 个字节，一个 64 位有符号、缩放整数表示的十进制货币值，小数点右侧有 4 位 |
| PT_APPTIME | `7` | 8 个字节，一个 64 位浮点数，其中整数部分表示自 1899 年 12 月 30 日以来的天数，小数部分表示自午夜后一天的小数部分 |
| PT_ERROR | `10` | 4字节，一个32位整数编码错误信息 |
| PT_BOOLEAN | `11` | 1 个字节，限制为 1 或 0 |
| PT_OBJECT | `13` | 属性值为 COM 对象 |
| PT_LONGLONG | `20` | 8 个字节，一个 64 位整数 |
| PT_UNICODE | `31` | 可变大小，UTF-16LE 编码的 Unicode 字符串，以空字符结尾（0x0000） |
| PT_STRING8 | `30` | 可变大小，外部指定编码的多字节字符串，以空字符结尾（单个 0 字节）。 |
| PT_SYSTIME | `64` | 8 个字节，一个 64 位整数，表示自 1601 年 1 月 1 日起 100 纳秒间隔的数量 |
| PT_CLSID | `72` | 16 字节，带有 Data1、Data2 和 Data3 字段的 GUID，采用 little-endian 格式 |
| PT_BINARY | `258` | 可变大小，一个字节数组 |
| PT_MV_SHORT | `4098` | 可变大小，一组PT_SHORT值. |
| PT_MV_LONG | `4099` | 可变大小，一组PT_LONG值. |
| PT_MV_FLOAT | `4100` | 可变大小，一组PT_FLOAT值. |
| PT_MV_DOUBLE | `4101` | 可变大小，一组PT_DOUBLE值. |
| PT_MV_CURRENCY | `4102` | 可变大小，一组PT_CURRENCY值. |
| PT_MV_APPTIME | `4103` | 可变大小，一组PT_APPTIME值. |
| PT_MV_LONGLONG | `4116` | 可变大小，一组PT_LONGLONG值. |
| PT_MV_UNICODE | `4127` | 可变大小，一组PT_UNICODE值. |
| PT_MV_STRING8 | `4126` | 可变大小，一组PT_STRING8值. |
| PT_MV_SYSTIME | `4160` | 可变大小，一组PT_SYSTIME值. |
| PT_MV_CLSID | `4168` | 可变大小，一组PT_CLSID值. |
| PT_MV_BINARY | `4354` | 可变大小，一组PT_BINARY值. |

### 也可以看看

* 命名空间 [Aspose.Email.Mapi.Msg](../../aspose.email.mapi.msg)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
