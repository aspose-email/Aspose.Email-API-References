---
title: IFormatter
second_title: Aspose.Email for Android via Java API 参考
description: 表示用于格式化日志条目消息的接口。
type: docs
weight: 455
url: /zh/androidjava/com.aspose.email/iformatter/
---
```
public interface IFormatter
```

表示用于格式化日志条目消息的接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [format(LogEntry entry)](#format-com.aspose.email.LogEntry-) | 格式化日志条目并返回要输出的字符串。 |
| [format(Date datatime)](#format-java.util.Date-) | 格式化日期时间并返回要输出的字符串。 |
| [getFooter()](#getFooter--) | 获取页脚字符串。 |
| [getHeader()](#getHeader--) | 获取标题字符串。 |
| [getLogHeader()](#getLogHeader--) | 表示起始日志标题 |
### format(LogEntry entry) {#format-com.aspose.email.LogEntry-}
```
public abstract String format(LogEntry entry)
```


格式化日志条目并返回要输出的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | 要格式化的日志条目。 |

**Returns:**
java.lang.String - 表示日志条目的字符串。
### format(Date datatime) {#format-java.util.Date-}
```
public abstract String format(Date datatime)
```


格式化日期时间并返回要输出的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 日期时间 | java.util.Date | 用于格式化为字符串的日期时间值 |

**Returns:**
java.lang.String - 表示日志条目的字符串。
### getFooter() {#getFooter--}
```
public abstract String getFooter()
```


获取页脚字符串。

**Returns:**
java.lang.String
### getHeader() {#getHeader--}
```
public abstract String getHeader()
```


获取标题字符串。

**Returns:**
java.lang.String
### getLogHeader() {#getLogHeader--}
```
public abstract String getLogHeader()
```


表示起始日志标题

**Returns:**
java.lang.String
