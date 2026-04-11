---
title: IAppender
second_title: Aspose.Email for Android via Java API 参考
description: 实现此接口以自定义日志条目的打印策略。
type: docs
weight: 452
url: /zh/androidjava/com.aspose.email/iappender/
---
```
public interface IAppender
```

实现此接口以自定义日志条目的打印策略。
## 方法

| 方法 | 描述 |
| --- | --- |
| [append(LogEntry entry)](#append-com.aspose.email.LogEntry-) | 以 Appender 特定方式记录指定的日志条目。 |
| [appendHeader()](#appendHeader--) | 使用特定标题启动日志文件。 |
| [getFormatter()](#getFormatter--) | 获取或设置 IFormatter。 |
| [setFormatter(IFormatter value)](#setFormatter-com.aspose.email.IFormatter-) | 获取或设置 IFormatter。 |
### append(LogEntry entry) {#append-com.aspose.email.LogEntry-}
```
public abstract void append(LogEntry entry)
```


以 Appender 特定方式记录指定的日志条目。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | 包含日志消息。 |

### appendHeader() {#appendHeader--}
```
public abstract void appendHeader()
```


使用特定标题启动日志文件。

### getFormatter() {#getFormatter--}
```
public abstract IFormatter getFormatter()
```


获取或设置 IFormatter。

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### setFormatter(IFormatter value) {#setFormatter-com.aspose.email.IFormatter-}
```
public abstract void setFormatter(IFormatter value)
```


获取或设置 IFormatter。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

