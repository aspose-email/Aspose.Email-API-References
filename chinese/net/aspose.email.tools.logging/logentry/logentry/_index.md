---
title: LogEntry
second_title: Aspose.Email for .NET API 参考
description: 初始化一个新的实例LogEntryaspose.email.tools.logging/logentry类.
type: docs
weight: 10
url: /zh/net/aspose.email.tools.logging/logentry/logentry/
---
## LogEntry() {#constructor}

初始化一个新的实例[`LogEntry`](../../logentry)类.

```csharp
public LogEntry()
```

### 也可以看看

* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(string) {#constructor_5}

初始化一个新的实例[`LogEntry`](../../logentry)类.

```csharp
public LogEntry(string message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 消息。 |

### 也可以看看

* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(string, DateTime) {#constructor_9}

初始化一个新的实例[`LogEntry`](../../logentry)类.

```csharp
public LogEntry(string message, DateTime time)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 消息。 |
| time | DateTime | 时间。 |

### 也可以看看

* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(string, Exception) {#constructor_10}

初始化一个新的实例[`LogEntry`](../../logentry)类.

```csharp
public LogEntry(string message, Exception innerException)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| innerException | Exception | 要记录的内部异常。 |

### 也可以看看

* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(string, LogLevel) {#constructor_6}

初始化一个新的实例[`LogEntry`](../../logentry)类.

```csharp
public LogEntry(string message, LogLevel severity)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| severity | LogLevel | 日志条目严重性作为[`Severity`](../severity)枚举。 （未指定、信息、警告或错误）。 |

### 也可以看看

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(string, Exception, LogLevel) {#constructor_11}

初始化一个新的实例[`LogEntry`](../../logentry)类.

```csharp
public LogEntry(string message, Exception innerException, LogLevel severity)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| innerException | Exception | 要记录的内部异常。 |
| severity | LogLevel | 日志条目严重性作为[`Severity`](../severity)枚举。 （未指定、信息、警告或错误）。 |

### 也可以看看

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(string, IDictionary&lt;string, string&gt;) {#constructor_8}

创建一个新的实例[`LogEntry`](../../logentry)带有全套构造函数参数

```csharp
public LogEntry(string message, IDictionary<string, string> properties)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| properties | IDictionary`2 | 要记录的键/值对字典。 |

### 也可以看看

* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(byte[]) {#constructor_1}

创建一个新的实例[`LogEntry`](../../logentry)带有全套构造函数参数

```csharp
public LogEntry(byte[] binaryDataMessage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| binaryDataMessage | Byte[] | 要记录的二进制消息正文。 |

### 也可以看看

* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(byte[], Encoding) {#constructor_3}

创建一个新的实例[`LogEntry`](../../logentry)带有全套构造函数参数

```csharp
public LogEntry(byte[] binaryDataMessage, Encoding messageEncoding)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| binaryDataMessage | Byte[] | 要记录的二进制消息正文。 |
| messageEncoding | Encoding | 二进制消息的编码 |

### 也可以看看

* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(byte[], IDictionary&lt;string, string&gt;) {#constructor_2}

创建一个新的实例[`LogEntry`](../../logentry)带有全套构造函数参数

```csharp
public LogEntry(byte[] binaryDataMessage, IDictionary<string, string> properties)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| binaryDataMessage | Byte[] | 要记录的二进制消息正文。 |
| properties | IDictionary`2 | 要记录的键/值对字典。 |

### 也可以看看

* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(byte[], Encoding, IDictionary&lt;string, string&gt;) {#constructor_4}

创建一个新的实例[`LogEntry`](../../logentry)带有全套构造函数参数

```csharp
public LogEntry(byte[] binaryDataMessage, Encoding messageEncoding, 
    IDictionary<string, string> properties)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| binaryDataMessage | Byte[] | 要记录的二进制消息正文。 |
| messageEncoding | Encoding | 二进制消息的编码 |
| properties | IDictionary`2 | 要记录的键/值对字典。 |

### 也可以看看

* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) {#constructor_7}

创建一个新的实例[`LogEntry`](../../logentry)带有全套构造函数参数

```csharp
public LogEntry(string message, LogLevel severity, string category, int eventId, string title, 
    IDictionary<string, string> properties)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| severity | LogLevel | 日志条目严重性作为[`Severity`](../severity)枚举。 （未指定、信息、警告或错误）。 |
| category | String | 用于将日志条目路由到一个或多个接收器的类别名称。 |
| eventId | Int32 | 事件编号或标识符。 |
| title | String | 日志条目消息的附加说明。 |
| properties | IDictionary`2 | 要记录的键/值对字典。 |

### 也可以看看

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

---

## LogEntry(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) {#constructor_12}

创建一个新的实例[`LogEntry`](../../logentry)带有全套构造函数参数

```csharp
public LogEntry(string message, Exception innerException, LogLevel severity, string category, 
    int eventId, string title, IDictionary<string, string> properties)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 要记录的消息正文。来自消息对象的 ToString() 方法的值。 |
| innerException | Exception | 要记录的内部异常。 |
| severity | LogLevel | 日志条目严重性作为[`Severity`](../severity)枚举。 （未指定、信息、警告或错误）。 |
| category | String | 用于将日志条目路由到一个或多个接收器的类别名称。 |
| eventId | Int32 | 事件编号或标识符。 |
| title | String | 日志条目消息的附加说明。 |
| properties | IDictionary`2 | 要记录的键/值对字典。 |

### 也可以看看

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* 命名空间 [Aspose.Email.Tools.Logging](../../logentry)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
