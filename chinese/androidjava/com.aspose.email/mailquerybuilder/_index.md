---
title: MailQueryBuilder
second_title: Aspose.Email for Android via Java API 参考
description: 表示搜索表达式的构建器。
type: docs
weight: 197
url: /zh/androidjava/com.aspose.email/mailquerybuilder/
---

**Inheritance:**
java.lang.Object
```
public class MailQueryBuilder
```

表示搜索表达式的构建器。

--------------------

注意：默认情况下，结果是所有匹配这些键的消息的交集（AND 函数）。若要通过 OR 函数连接键，请使用此类的 Or() 方法。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MailQueryBuilder()](#MailQueryBuilder--) | 初始化一个新的 [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) 类的实例。 |
| [MailQueryBuilder(Charset defaultEncoding)](#MailQueryBuilder-java.nio.charset.Charset-) | 初始化一个新的 [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBcc()](#getBcc--) | 获取允许在信封结构的 BCC 字段中查找包含指定字符串的邮件的字段。 |
| [getBody()](#getBody--) | 获取允许在邮件正文中查找包含指定字符串的邮件的字段。 |
| [getCc()](#getCc--) | 获取允许在信封结构的 CC 字段中查找包含指定字符串的邮件的字段。 |
| [getClass()](#getClass--) |  |
| [getDefaultEncoding()](#getDefaultEncoding--) | 获取查询构建器的默认编码（字符集）。 |
| [getFrom()](#getFrom--) | 获取允许在信封结构的 FROM 字段中查找包含指定字符串的邮件的字段。 |
| [getInternalDate()](#getInternalDate--) | 获取允许按内部日期查找邮件的字段。 |
| [getQuery()](#getQuery--) | 获取查询。 |
| [getSentDate()](#getSentDate--) | 获取允许按发送日期查找邮件的字段。 |
| [getSubject()](#getSubject--) | 获取允许在信封结构的 SUBJECT 字段中包含指定字符串的邮件的字段。 |
| [getText()](#getText--) | 获取允许在邮件的标题（subject、from、to、cc）和正文中包含指定字符串的邮件的字段。 |
| [getTo()](#getTo--) | 获取允许在信封结构的 TO 字段中包含指定字符串的邮件的字段。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | 搜索匹配任一搜索键的邮件。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailQueryBuilder() {#MailQueryBuilder--}
```
public MailQueryBuilder()
```


初始化一个新的 [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) 类的实例。

### MailQueryBuilder(Charset defaultEncoding) {#MailQueryBuilder-java.nio.charset.Charset-}
```
public MailQueryBuilder(Charset defaultEncoding)
```


初始化一个新的 [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| defaultEncoding | java.nio.charset.Charset | 包含查询构建器的默认编码（字符集）。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBcc() {#getBcc--}
```
public final StringComparisonField getBcc()
```


获取允许在信封结构的 BCC 字段中查找包含指定字符串的邮件的字段。

值：表示 BCC 搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getBody() {#getBody--}
```
public final StringComparisonField getBody()
```


获取允许在邮件正文中查找包含指定字符串的邮件的字段。

值：表示正文搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getCc() {#getCc--}
```
public final StringComparisonField getCc()
```


获取允许在信封结构的 CC 字段中查找包含指定字符串的邮件的字段。

值：表示 cc 搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultEncoding() {#getDefaultEncoding--}
```
public final Charset getDefaultEncoding()
```


获取查询构建器的默认编码（字符集）。

**Returns:**
java.nio.charset.Charset
### getFrom() {#getFrom--}
```
public final StringComparisonField getFrom()
```


获取允许在信封结构的 FROM 字段中查找包含指定字符串的邮件的字段。

值：表示 from 搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getInternalDate() {#getInternalDate--}
```
public final DateComparisonField getInternalDate()
```


获取允许按内部日期查找邮件的字段。

值：表示内部日期搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getQuery() {#getQuery--}
```
public MailQuery getQuery()
```


获取查询。

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
### getSentDate() {#getSentDate--}
```
public final DateComparisonField getSentDate()
```


获取允许按发送日期查找邮件的字段。

值：表示发送日期搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getSubject() {#getSubject--}
```
public final StringComparisonField getSubject()
```


获取允许在信封结构的 SUBJECT 字段中包含指定字符串的邮件的字段。

值：表示主题搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getText() {#getText--}
```
public final StringComparisonField getText()
```


获取允许在邮件的标题（subject、from、to、cc）和正文中包含指定字符串的邮件的字段。

值：表示文本标题或正文搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getTo() {#getTo--}
```
public final StringComparisonField getTo()
```


获取允许在信封结构的 TO 字段中包含指定字符串的邮件的字段。

值：表示 TO 搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### or(MailQuery query1, MailQuery query2) {#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-}
```
public MailQuery or(MailQuery query1, MailQuery query2)
```


搜索匹配任一搜索键的邮件。提供两个表达式之间的析取（OR）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| query1 | [MailQuery](../../com.aspose.email/mailquery) | 查询1。 |
| query2 | [MailQuery](../../com.aspose.email/mailquery) | 查询2。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

