---
title: INamedPropertyTagProvider
second_title: Aspose.Email for Android via Java API 参考
description: 具名 MAPI 属性标签提供程序的接口。
type: docs
weight: 462
url: /zh/androidjava/com.aspose.email/inamedpropertytagprovider/
---
```
public interface INamedPropertyTagProvider
```

具名 MAPI 属性标签提供程序的接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [generateNamedPropertyTag(long dataType)](#generateNamedPropertyTag-long-) | 生成命名属性标签 |
| [getTagFromNamedProperty(String name)](#getTagFromNamedProperty-java.lang.String-) | 获取已命名属性的标签。 |
| [getTagFromNamedProperty(long LId)](#getTagFromNamedProperty-long-) | 获取已命名属性的标签。 |
### generateNamedPropertyTag(long dataType) {#generateNamedPropertyTag-long-}
```
public abstract long generateNamedPropertyTag(long dataType)
```


生成命名属性标签

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataType | long | 命名属性的数据类型 |

**Returns:**
long - 返回当前标签提供程序的命名属性标签
### getTagFromNamedProperty(String name) {#getTagFromNamedProperty-java.lang.String-}
```
public abstract long getTagFromNamedProperty(String name)
```


获取已命名属性的标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 属性名称 |

**Returns:**
long - 属性标签值。
### getTagFromNamedProperty(long LId) {#getTagFromNamedProperty-long-}
```
public abstract long getTagFromNamedProperty(long LId)
```


获取已命名属性的标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| LId | long | 属性 ID。 |

**Returns:**
long - 属性标签值。
