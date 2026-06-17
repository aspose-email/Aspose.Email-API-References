---
title: FollowUpManager
second_title: Aspose.Email for Android via Java API 参考
description: 提供设置和处理 Outlook 跟进标记及类别的能力。
type: docs
weight: 144
url: /zh/androidjava/com.aspose.email/followupmanager/
---

**Inheritance:**
java.lang.Object
```
public class FollowUpManager
```

提供设置和处理 Outlook 跟进标记和类别的功能。支持在 [MapiMessage](../../com.aspose.email/mapimessage) 中添加和删除标记的功能，并可将其标记为已完成。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FollowUpManager()](#FollowUpManager--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addCategory(MapiMessage message, String categoryName)](#addCategory-com.aspose.email.MapiMessage-java.lang.String-) | 为消息添加类别。 |
| [addVotingButton(MapiMessage message, String displayName)](#addVotingButton-com.aspose.email.MapiMessage-java.lang.String-) | 添加投票按钮。 |
| [clearCategories(MapiMessage message)](#clearCategories-com.aspose.email.MapiMessage-) | 清除类别。 |
| [clearFlag(MapiMessage message)](#clearFlag-com.aspose.email.MapiMessage-) | 清除跟进标记和提醒。 |
| [clearVotingButtons(MapiMessage message)](#clearVotingButtons-com.aspose.email.MapiMessage-) | 删除投票按钮。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategories(MapiMessage message)](#getCategories-com.aspose.email.MapiMessage-) | 获取可用的消息类别。 |
| [getClass()](#getClass--) |  |
| [getOptions(MapiMessage message)](#getOptions-com.aspose.email.MapiMessage-) | 获取消息的跟进选项。 |
| [getVotingButtons(MapiMessage message)](#getVotingButtons-com.aspose.email.MapiMessage-) | 获取可用的消息投票按钮。 |
| [getVotingButtonsArray(MapiMessage message)](#getVotingButtonsArray-com.aspose.email.MapiMessage-) | 获取可用的消息投票按钮。 |
| [hashCode()](#hashCode--) |  |
| [markAsCompleted(MapiMessage message)](#markAsCompleted-com.aspose.email.MapiMessage-) | 将已标记的消息标记为已完成。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCategory(MapiMessage message, String categoryName)](#removeCategory-com.aspose.email.MapiMessage-java.lang.String-) | 移除类别。 |
| [removeVotingButton(MapiMessage message, String displayName)](#removeVotingButton-com.aspose.email.MapiMessage-java.lang.String-) | 移除投票按钮。 |
| [setFlag(MapiMessage message, String flagRequest)](#setFlag-com.aspose.email.MapiMessage-java.lang.String-) | 为消息设置跟进标记。 |
| [setFlag(MapiMessage message, String flagRequest, Date startDate, Date dueDate)](#setFlag-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-java.util.Date-) | 为消息设置跟进标记。 |
| [setFlagForRecipients(MapiMessage message, String flagRequest)](#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-) | 为草稿消息设置标记，以提醒收件人进行跟进。 |
| [setFlagForRecipients(MapiMessage message, String flagRequest, Date reminderTime)](#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-) | 为草稿消息设置标记，以提醒收件人进行跟进。 |
| [setOptions(MapiMessage message, FollowUpOptions options)](#setOptions-com.aspose.email.MapiMessage-com.aspose.email.FollowUpOptions-) | 为消息设置附加的跟进选项。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FollowUpManager() {#FollowUpManager--}
```
public FollowUpManager()
```


### addCategory(MapiMessage message, String categoryName) {#addCategory-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void addCategory(MapiMessage message, String categoryName)
```


为消息添加类别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 将在其添加类别的 [MapiMessage](../../com.aspose.email/mapimessage)。 |
| categoryName | java.lang.String | 类别名称。 |

### addVotingButton(MapiMessage message, String displayName) {#addVotingButton-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void addVotingButton(MapiMessage message, String displayName)
```


添加投票按钮。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 将在其添加投票按钮的 [MapiMessage](../../com.aspose.email/mapimessage)。 |
| displayName | java.lang.String | 按钮的显示名称。 |

### clearCategories(MapiMessage message) {#clearCategories-com.aspose.email.MapiMessage-}
```
public static void clearCategories(MapiMessage message)
```


清除类别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 将在其中清除类别的 [MapiMessage](../../com.aspose.email/mapimessage). |

### clearFlag(MapiMessage message) {#clearFlag-com.aspose.email.MapiMessage-}
```
public static void clearFlag(MapiMessage message)
```


清除跟进标记和提醒。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 在其中设置标志的 [MapiMessage](../../com.aspose.email/mapimessage). |

### clearVotingButtons(MapiMessage message) {#clearVotingButtons-com.aspose.email.MapiMessage-}
```
public static void clearVotingButtons(MapiMessage message)
```


删除投票按钮。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 将在其中清除类别的 [MapiMessage](../../com.aspose.email/mapimessage). |

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
### getCategories(MapiMessage message) {#getCategories-com.aspose.email.MapiMessage-}
```
public static System.Collections.IList getCategories(MapiMessage message)
```


获取可用的消息类别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 在其中添加类别的 [MapiMessage](../../com.aspose.email/mapimessage). |

**Returns:**
com.aspose.ms.System.Collections.IList - 已添加类别的列表
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOptions(MapiMessage message) {#getOptions-com.aspose.email.MapiMessage-}
```
public static FollowUpOptions getOptions(MapiMessage message)
```


获取消息的跟进选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 在其中设置选项的 [MapiMessage](../../com.aspose.email/mapimessage). |

**Returns:**
[FollowUpOptions](../../com.aspose.email/followupoptions) - The [FollowUpOptions](../../com.aspose.email/followupoptions) that represents options for using follow-up flags, reminders, category and voting buttons.
### getVotingButtons(MapiMessage message) {#getVotingButtons-com.aspose.email.MapiMessage-}
```
public static System.Collections.IList getVotingButtons(MapiMessage message)
```


获取可用的消息投票按钮。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 在其中添加按钮的 [MapiMessage](../../com.aspose.email/mapimessage). |

**Returns:**
com.aspose.ms.System.Collections.IList - 已添加投票按钮的列表
### getVotingButtonsArray(MapiMessage message) {#getVotingButtonsArray-com.aspose.email.MapiMessage-}
```
public static String[] getVotingButtonsArray(MapiMessage message)
```


获取可用的消息投票按钮。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 在其中添加按钮的  MapiMessage  . |

**Returns:**
java.lang.String[] - 已添加投票按钮的列表
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### markAsCompleted(MapiMessage message) {#markAsCompleted-com.aspose.email.MapiMessage-}
```
public static void markAsCompleted(MapiMessage message)
```


将已标记的消息标记为已完成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 在其中设置标志的 [MapiMessage](../../com.aspose.email/mapimessage). |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeCategory(MapiMessage message, String categoryName) {#removeCategory-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void removeCategory(MapiMessage message, String categoryName)
```


移除类别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 消息。 |
| categoryName | java.lang.String | 类别的名称。 |

### removeVotingButton(MapiMessage message, String displayName) {#removeVotingButton-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void removeVotingButton(MapiMessage message, String displayName)
```


移除投票按钮。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 在其中移除投票按钮的 [MapiMessage](../../com.aspose.email/mapimessage). |
| displayName | java.lang.String | 按钮的显示名称。 |

### setFlag(MapiMessage message, String flagRequest) {#setFlag-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void setFlag(MapiMessage message, String flagRequest)
```


为消息设置跟进标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 将在其中设置标志的 [MapiMessage](../../com.aspose.email/mapimessage). |
| flagRequest | java.lang.String | 指示电子邮件消息请求操作的字符串。 |

### setFlag(MapiMessage message, String flagRequest, Date startDate, Date dueDate) {#setFlag-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-java.util.Date-}
```
public static void setFlag(MapiMessage message, String flagRequest, Date startDate, Date dueDate)
```


为消息设置跟进标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 将在其中设置标志的 [MapiMessage](../../com.aspose.email/mapimessage). |
| flagRequest | java.lang.String | 指示电子邮件消息请求操作的字符串。 |
| startDate | java.util.Date | 开始日期。 |
| dueDate | java.util.Date | 截止日期。 |

### setFlagForRecipients(MapiMessage message, String flagRequest) {#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void setFlagForRecipients(MapiMessage message, String flagRequest)
```


为草稿消息设置标记，以提醒收件人进行跟进。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 将在其中设置标志的 [MapiMessage](../../com.aspose.email/mapimessage). |
| flagRequest | java.lang.String | 指示电子邮件消息收件人请求操作的字符串。 |

### setFlagForRecipients(MapiMessage message, String flagRequest, Date reminderTime) {#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-}
```
public static void setFlagForRecipients(MapiMessage message, String flagRequest, Date reminderTime)
```


为草稿消息设置标记，以提醒收件人进行跟进。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 将在其中设置标志的 [MapiMessage](../../com.aspose.email/mapimessage). |
| flagRequest | java.lang.String | 指示电子邮件消息收件人请求操作的字符串。 |
| reminderTime | java.util.Date | 指示提醒应发生的日期和时间的日期。 |

### setOptions(MapiMessage message, FollowUpOptions options) {#setOptions-com.aspose.email.MapiMessage-com.aspose.email.FollowUpOptions-}
```
public static void setOptions(MapiMessage message, FollowUpOptions options)
```


为消息设置附加的跟进选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 将在其中设置标志的 [MapiMessage](../../com.aspose.email/mapimessage). |
| options | [FollowUpOptions](../../com.aspose.email/followupoptions) | 表示使用后续标志和提醒选项的 [FollowUpOptions](../../com.aspose.email/followupoptions). |

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

