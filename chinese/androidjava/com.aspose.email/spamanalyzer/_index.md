---
title: SpamAnalyzer
second_title: Aspose.Email for Android via Java API 参考
description: 允许应用程序使用自学习贝叶斯过滤器检测垃圾邮件的类。
type: docs
weight: 388
url: /zh/androidjava/com.aspose.email/spamanalyzer/
---

**Inheritance:**
java.lang.Object
```
public class SpamAnalyzer
```

允许应用程序使用自学习贝叶斯过滤器检测垃圾邮件的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SpamAnalyzer()](#SpamAnalyzer--) | 初始化 [SpamAnalyzer](../../com.aspose.email/spamanalyzer) 类的新实例。 |
| [SpamAnalyzer(InputStream stream)](#SpamAnalyzer-java.io.InputStream-) | 初始化 [SpamAnalyzer](../../com.aspose.email/spamanalyzer) 类的新实例。 |
| [SpamAnalyzer(String filePath)](#SpamAnalyzer-java.lang.String-) | 初始化 [SpamAnalyzer](../../com.aspose.email/spamanalyzer) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [loadDatabase(InputStream stream)](#loadDatabase-java.io.InputStream-) | 从流中加载贝叶斯数据库。 |
| [loadDatabase(String filePath)](#loadDatabase-java.lang.String-) | 从文件中加载贝叶斯数据库。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | 清除所有统计信息（贝叶斯数据库）。 |
| [saveDatabase(OutputStream stream)](#saveDatabase-java.io.OutputStream-) | 将贝叶斯数据库保存到流中。 |
| [saveDatabase(String filePath)](#saveDatabase-java.lang.String-) | 将贝叶斯数据库保存到文件。 |
| [test(MailMessage message)](#test-com.aspose.email.MailMessage-) | 分析该消息并返回该消息为垃圾邮件的概率。 |
| [toString()](#toString--) |  |
| [trainFilter(MailMessage message, boolean isSpam)](#trainFilter-com.aspose.email.MailMessage-boolean-) | 从指定的消息中学习，判断其来源是垃圾邮件还是非垃圾邮件。 |
| [trainFilter(MailMessage[] ham, MailMessage[] spam)](#trainFilter-com.aspose.email.MailMessage---com.aspose.email.MailMessage---) | 从指定的多条消息中学习，判断其来源是垃圾邮件还是非垃圾邮件。 |
| [trainFilter(String text, boolean isSpam)](#trainFilter-java.lang.String-boolean-) | 从指定的字符串中学习，判断其来源是垃圾邮件还是非垃圾邮件。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SpamAnalyzer() {#SpamAnalyzer--}
```
public SpamAnalyzer()
```


初始化 [SpamAnalyzer](../../com.aspose.email/spamanalyzer) 类的新实例。

### SpamAnalyzer(InputStream stream) {#SpamAnalyzer-java.io.InputStream-}
```
public SpamAnalyzer(InputStream stream)
```


初始化 [SpamAnalyzer](../../com.aspose.email/spamanalyzer) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含贝叶斯数据库的输入流。 |

### SpamAnalyzer(String filePath) {#SpamAnalyzer-java.lang.String-}
```
public SpamAnalyzer(String filePath)
```


初始化 [SpamAnalyzer](../../com.aspose.email/spamanalyzer) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 包含贝叶斯数据库的文件的完整或相对路径。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadDatabase(InputStream stream) {#loadDatabase-java.io.InputStream-}
```
public final void loadDatabase(InputStream stream)
```


从流中加载贝叶斯数据库。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含贝叶斯数据库的输入流。 |

### loadDatabase(String filePath) {#loadDatabase-java.lang.String-}
```
public final void loadDatabase(String filePath)
```


从文件中加载贝叶斯数据库。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 包含贝叶斯数据库的文件的完整或相对路径。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public final void reset()
```


清除所有统计信息（贝叶斯数据库）。

### saveDatabase(OutputStream stream) {#saveDatabase-java.io.OutputStream-}
```
public final void saveDatabase(OutputStream stream)
```


将贝叶斯数据库保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 包含贝叶斯数据库的输出流。 |

### saveDatabase(String filePath) {#saveDatabase-java.lang.String-}
```
public final void saveDatabase(String filePath)
```


将贝叶斯数据库保存到文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 包含贝叶斯数据库的文件的完整或相对路径。 |

### test(MailMessage message) {#test-com.aspose.email.MailMessage-}
```
public final double test(MailMessage message)
```


分析该消息并返回该消息为垃圾邮件的概率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | 用于测试该消息为垃圾邮件概率的 MailMessage。 |

**Returns:**
double - 0 到 1 范围的双精度值，其中 0 表示“绝对非垃圾邮件”（垃圾邮件概率 0%），1 表示“绝对垃圾邮件”（垃圾邮件概率 100%）。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### trainFilter(MailMessage message, boolean isSpam) {#trainFilter-com.aspose.email.MailMessage-boolean-}
```
public final void trainFilter(MailMessage message, boolean isSpam)
```


从指定的消息中学习，判断其来源是垃圾邮件还是非垃圾邮件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | 指向表示用于训练贝叶斯过滤器的消息的 MailMessage 对象的引用。 |
| isSpam | boolean | 如果消息是垃圾邮件则为 True；如果是合法消息则为 false。 |

### trainFilter(MailMessage[] ham, MailMessage[] spam) {#trainFilter-com.aspose.email.MailMessage---com.aspose.email.MailMessage---}
```
public final void trainFilter(MailMessage[] ham, MailMessage[] spam)
```


从指定的多条消息中学习，判断其来源是垃圾邮件还是非垃圾邮件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ham | [MailMessage\[\]](../../com.aspose.email/mailmessage) | 用于训练贝叶斯过滤器的非垃圾邮件 MailMessage 对象数组。 |
| spam | [MailMessage\[\]](../../com.aspose.email/mailmessage) | 用于训练贝叶斯过滤器的垃圾邮件 MailMessage 对象数组。 |

### trainFilter(String text, boolean isSpam) {#trainFilter-java.lang.String-boolean-}
```
public final void trainFilter(String text, boolean isSpam)
```


从指定的字符串中学习，判断其来源是垃圾邮件还是非垃圾邮件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 用于训练贝叶斯过滤器的字符串值。 |
| isSpam | boolean | 如果指定的文本是垃圾邮件则为 True；如果是合法文本则为 false。 |

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

