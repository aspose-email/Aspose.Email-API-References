---
title: IAttachment
second_title: Aspose.Email for Android via Java API 参考
description: 表示通用附件接口
type: docs
weight: 454
url: /zh/androidjava/com.aspose.email/iattachment/
---
```
public interface IAttachment
```

表示通用附件接口
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 获取或设置附件名称 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将附件保存到流 |
| [save(String fileName)](#save-java.lang.String-) | 将附件保存到文件 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置附件名称 |
### getName() {#getName--}
```
public abstract String getName()
```


获取或设置附件名称

**Returns:**
java.lang.String
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


将附件保存到流

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存的流 |

### save(String fileName) {#save-java.lang.String-}
```
public abstract void save(String fileName)
```


将附件保存到文件

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名 |

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


获取或设置附件名称

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

