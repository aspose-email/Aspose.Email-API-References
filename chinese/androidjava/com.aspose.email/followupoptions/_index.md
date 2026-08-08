---
title: FollowUpOptions
second_title: Aspose.Email for Android via Java API 参考
description: 表示在消息中使用跟进标记和提醒的选项。
type: docs
weight: 145
url: /zh/androidjava/com.aspose.email/followupoptions/
---

**Inheritance:**
java.lang.Object
```
public final class FollowUpOptions
```

表示在消息中使用跟进标记和提醒的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FollowUpOptions()](#FollowUpOptions--) | 初始化 [FollowUpOptions](../../com.aspose.email/followupoptions) 类的新实例。 |
| [FollowUpOptions(String flagRequest)](#FollowUpOptions-java.lang.String-) | 初始化 [FollowUpOptions](../../com.aspose.email/followupoptions) 类的新实例。 |
| [FollowUpOptions(String flagRequest, Date startDate, Date dueDate)](#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-) | 初始化 [FollowUpOptions](../../com.aspose.email/followupoptions) 类的新实例。 |
| [FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime)](#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-java.util.Date-) | 初始化 [FollowUpOptions](../../com.aspose.email/followupoptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategories()](#getCategories--) | 获取或设置表示类别列表的字符串，使用分号 (;) 分隔。 |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | 获取或设置代码页。 |
| [getDueDate()](#getDueDate--) | 获取或设置指示已标记消息截止日期的日期。 |
| [getFlagRequest()](#getFlagRequest--) | 获取或设置指示电子邮件消息请求操作的字符串。 |
| [getRecipientsFlagRequest()](#getRecipientsFlagRequest--) | 获取或设置指示电子邮件收件人请求操作的字符串。 |
| [getRecipientsReminderTime()](#getRecipientsReminderTime--) | 获取或设置收件人提醒应发生的日期和时间。 |
| [getReminderTime()](#getReminderTime--) | 获取或设置提醒应发生的日期和时间。 |
| [getStartDate()](#getStartDate--) | 获取或设置指定已标记消息开始日期和时间的日期。 |
| [getVotingButtons()](#getVotingButtons--) | 获取或设置表示投票按钮名称列表的字符串，使用分号 (;) 分隔。 |
| [hashCode()](#hashCode--) |  |
| [isCompleted()](#isCompleted--) | 获取一个值，指示 Message 对象是否已标记为完成。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCategories(String value)](#setCategories-java.lang.String-) | 获取或设置表示类别列表的字符串，使用分号 (;) 分隔。 |
| [setCodePage(int value)](#setCodePage-int-) | 获取或设置代码页。 |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | 获取或设置指示已标记消息截止日期的日期。 |
| [setFlagRequest(String value)](#setFlagRequest-java.lang.String-) | 获取或设置指示电子邮件消息请求操作的字符串。 |
| [setRecipientsFlagRequest(String value)](#setRecipientsFlagRequest-java.lang.String-) | 获取或设置指示电子邮件收件人请求操作的字符串。 |
| [setRecipientsReminderTime(Date value)](#setRecipientsReminderTime-java.util.Date-) | 获取或设置收件人提醒应发生的日期和时间。 |
| [setReminderTime(Date value)](#setReminderTime-java.util.Date-) | 获取或设置提醒应发生的日期和时间。 |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | 获取或设置指定已标记消息开始日期和时间的日期。 |
| [setVotingButtons(String value)](#setVotingButtons-java.lang.String-) | 获取或设置表示投票按钮名称列表的字符串，使用分号 (;) 分隔。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FollowUpOptions() {#FollowUpOptions--}
```
public FollowUpOptions()
```


初始化 [FollowUpOptions](../../com.aspose.email/followupoptions) 类的新实例。

### FollowUpOptions(String flagRequest) {#FollowUpOptions-java.lang.String-}
```
public FollowUpOptions(String flagRequest)
```


初始化 [FollowUpOptions](../../com.aspose.email/followupoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flagRequest | java.lang.String | 标记请求。 |

### FollowUpOptions(String flagRequest, Date startDate, Date dueDate) {#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-}
```
public FollowUpOptions(String flagRequest, Date startDate, Date dueDate)
```


初始化 [FollowUpOptions](../../com.aspose.email/followupoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flagRequest | java.lang.String | 标记请求。 |
| startDate | java.util.Date | 开始日期。 |
| dueDate | java.util.Date | 截止日期。 |

### FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime) {#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-java.util.Date-}
```
public FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime)
```


初始化 [FollowUpOptions](../../com.aspose.email/followupoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flagRequest | java.lang.String | 标记请求。 |
| startDate | java.util.Date | 开始日期。 |
| dueDate | java.util.Date | 截止日期。 |
| reminderTime | java.util.Date | 提醒时间。 |

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
### getCategories() {#getCategories--}
```
public final String getCategories()
```


获取或设置表示类别列表的字符串，使用分号 (;) 分隔。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodePage() {#getCodePage--}
```
public final int getCodePage()
```


获取或设置代码页。

**Returns:**
int
### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


获取或设置指示已标记消息截止日期的日期。

**Returns:**
java.util.Date
### getFlagRequest() {#getFlagRequest--}
```
public final String getFlagRequest()
```


获取或设置指示电子邮件消息请求操作的字符串。

**Returns:**
java.lang.String
### getRecipientsFlagRequest() {#getRecipientsFlagRequest--}
```
public final String getRecipientsFlagRequest()
```


获取或设置指示电子邮件收件人请求操作的字符串。

**Returns:**
java.lang.String
### getRecipientsReminderTime() {#getRecipientsReminderTime--}
```
public final Date getRecipientsReminderTime()
```


获取或设置收件人提醒应发生的日期和时间。

**Returns:**
java.util.Date
### getReminderTime() {#getReminderTime--}
```
public final Date getReminderTime()
```


获取或设置提醒应发生的日期和时间。

**Returns:**
java.util.Date
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


获取或设置指定已标记消息开始日期和时间的日期。

**Returns:**
java.util.Date
### getVotingButtons() {#getVotingButtons--}
```
public final String getVotingButtons()
```


获取或设置表示投票按钮名称列表的字符串，使用分号 (;) 分隔。

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompleted() {#isCompleted--}
```
public final boolean isCompleted()
```


获取一个值，指示 Message 对象是否已标记为完成。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCategories(String value) {#setCategories-java.lang.String-}
```
public final void setCategories(String value)
```


获取或设置表示类别列表的字符串，使用分号 (;) 分隔。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCodePage(int value) {#setCodePage-int-}
```
public final void setCodePage(int value)
```


获取或设置代码页。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


获取或设置指示已标记消息截止日期的日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setFlagRequest(String value) {#setFlagRequest-java.lang.String-}
```
public final void setFlagRequest(String value)
```


获取或设置指示电子邮件消息请求操作的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setRecipientsFlagRequest(String value) {#setRecipientsFlagRequest-java.lang.String-}
```
public final void setRecipientsFlagRequest(String value)
```


获取或设置指示电子邮件收件人请求操作的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setRecipientsReminderTime(Date value) {#setRecipientsReminderTime-java.util.Date-}
```
public final void setRecipientsReminderTime(Date value)
```


获取或设置收件人提醒应发生的日期和时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setReminderTime(Date value) {#setReminderTime-java.util.Date-}
```
public final void setReminderTime(Date value)
```


获取或设置提醒应发生的日期和时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


获取或设置指定已标记消息开始日期和时间的日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setVotingButtons(String value) {#setVotingButtons-java.lang.String-}
```
public final void setVotingButtons(String value)
```


获取或设置表示投票按钮名称列表的字符串，使用分号 (;) 分隔。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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

