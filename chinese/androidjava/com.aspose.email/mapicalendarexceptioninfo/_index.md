---
title: MapiCalendarExceptionInfo
second_title: Aspose.Email for Android via Java API 参考
description: 异常指定对重复系列实例的更改。
type: docs
weight: 212
url: /zh/androidjava/com.aspose.email/mapicalendarexceptioninfo/
---

**Inheritance:**
java.lang.Object
```
public final class MapiCalendarExceptionInfo
```

异常指定对重复系列实例的更改。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiCalendarExceptionInfo()](#MapiCalendarExceptionInfo--) | 初始化一个新的 [MapiCalendarExceptionInfo](../../com.aspose.email/mapicalendarexceptioninfo) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | 获取或设置重复异常中的附件。 |
| [getBody()](#getBody--) | 获取或设置正文。 |
| [getBusyStatus()](#getBusyStatus--) | 获取或设置忙碌状态。 |
| [getClass()](#getClass--) |  |
| [getEndDateTime()](#getEndDateTime--) | 获取或设置结束日期。 |
| [getLocation()](#getLocation--) | 获取或设置位置。 |
| [getMeetingType()](#getMeetingType--) | 获取或设置会议类型。 |
| [getOriginalStartDate()](#getOriginalStartDate--) | 获取或设置原始开始日期。 |
| [getOverrideFlags()](#getOverrideFlags--) | 获取覆盖标志。 |
| [getReminderDelta()](#getReminderDelta--) | 获取或设置提醒间隔。 |
| [getReminderSet()](#getReminderSet--) | 获取或设置 PidLidReminderSet 属性的值。 |
| [getStartDateTime()](#getStartDateTime--) | 获取或设置开始日期。 |
| [getSubType()](#getSubType--) | 获取或设置子类型。 |
| [getSubject()](#getSubject--) | 获取或设置主题。 |
| [hasAttachment()](#hasAttachment--) | 获取此字段的值，指定异常嵌入消息对象是否包含附件。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttachments(MapiAttachmentCollection value)](#setAttachments-com.aspose.email.MapiAttachmentCollection-) | 获取或设置重复异常中的附件。 |
| [setBody(String value)](#setBody-java.lang.String-) | 获取或设置正文。 |
| [setBusyStatus(int value)](#setBusyStatus-int-) | 获取或设置忙碌状态。 |
| [setEndDateTime(Date value)](#setEndDateTime-java.util.Date-) | 获取或设置结束日期。 |
| [setLocation(String value)](#setLocation-java.lang.String-) | 获取或设置位置。 |
| [setMeetingType(int value)](#setMeetingType-int-) | 获取或设置会议类型。 |
| [setOriginalStartDate(Date value)](#setOriginalStartDate-java.util.Date-) | 获取或设置原始开始日期。 |
| [setReminderDelta(int value)](#setReminderDelta-int-) | 获取或设置提醒间隔。 |
| [setReminderSet(boolean value)](#setReminderSet-boolean-) | 获取或设置 PidLidReminderSet 属性的值。 |
| [setStartDateTime(Date value)](#setStartDateTime-java.util.Date-) | 获取或设置开始日期。 |
| [setSubType(int value)](#setSubType-int-) | 获取或设置子类型。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 获取或设置主题。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarExceptionInfo() {#MapiCalendarExceptionInfo--}
```
public MapiCalendarExceptionInfo()
```


初始化一个新的 [MapiCalendarExceptionInfo](../../com.aspose.email/mapicalendarexceptioninfo) 类的实例。

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
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


获取或设置重复异常中的附件。

值：附件。

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection)
### getBody() {#getBody--}
```
public final String getBody()
```


获取或设置正文。

值：正文。

**Returns:**
java.lang.String
### getBusyStatus() {#getBusyStatus--}
```
public final int getBusyStatus()
```


获取或设置忙碌状态。

值：忙碌状态。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEndDateTime() {#getEndDateTime--}
```
public final Date getEndDateTime()
```


获取或设置结束日期。

值：结束日期时间。

**Returns:**
java.util.Date
### getLocation() {#getLocation--}
```
public final String getLocation()
```


获取或设置位置。

值：位置。

**Returns:**
java.lang.String
### getMeetingType() {#getMeetingType--}
```
public final int getMeetingType()
```


获取或设置会议类型。

值：会议类型。

**Returns:**
int
### getOriginalStartDate() {#getOriginalStartDate--}
```
public final Date getOriginalStartDate()
```


获取或设置原始开始日期。

值：原始开始日期。

**Returns:**
java.util.Date
### getOverrideFlags() {#getOverrideFlags--}
```
public final int getOverrideFlags()
```


获取覆盖标志。

值：覆盖标志。

**Returns:**
int
### getReminderDelta() {#getReminderDelta--}
```
public final int getReminderDelta()
```


获取或设置提醒间隔。

值：提醒增量。

**Returns:**
int
### getReminderSet() {#getReminderSet--}
```
public final boolean getReminderSet()
```


获取或设置 PidLidReminderSet 属性的值。

值：如果 [reminder set] 为 true；否则为 false。

**Returns:**
boolean
### getStartDateTime() {#getStartDateTime--}
```
public final Date getStartDateTime()
```


获取或设置开始日期。

值：开始日期时间。

**Returns:**
java.util.Date
### getSubType() {#getSubType--}
```
public final int getSubType()
```


获取或设置子类型。

值：子类型。

**Returns:**
int
### getSubject() {#getSubject--}
```
public final String getSubject()
```


获取或设置主题。

值：主题。

**Returns:**
java.lang.String
### hasAttachment() {#hasAttachment--}
```
public final boolean hasAttachment()
```


获取此字段的值，指定异常嵌入消息对象是否包含附件。

值：如果 Exception Embedded Message 对象有附件则为 true；否则为 false。

**Returns:**
boolean
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




### setAttachments(MapiAttachmentCollection value) {#setAttachments-com.aspose.email.MapiAttachmentCollection-}
```
public final void setAttachments(MapiAttachmentCollection value)
```


获取或设置重复异常中的附件。

值：附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


获取或设置正文。

值：正文。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBusyStatus(int value) {#setBusyStatus-int-}
```
public final void setBusyStatus(int value)
```


获取或设置忙碌状态。

值：忙碌状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setEndDateTime(Date value) {#setEndDateTime-java.util.Date-}
```
public final void setEndDateTime(Date value)
```


获取或设置结束日期。

值：结束日期时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


获取或设置位置。

值：位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMeetingType(int value) {#setMeetingType-int-}
```
public final void setMeetingType(int value)
```


获取或设置会议类型。

值：会议类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setOriginalStartDate(Date value) {#setOriginalStartDate-java.util.Date-}
```
public final void setOriginalStartDate(Date value)
```


获取或设置原始开始日期。

值：原始开始日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setReminderDelta(int value) {#setReminderDelta-int-}
```
public final void setReminderDelta(int value)
```


获取或设置提醒间隔。

值：提醒增量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setReminderSet(boolean value) {#setReminderSet-boolean-}
```
public final void setReminderSet(boolean value)
```


获取或设置 PidLidReminderSet 属性的值。

值：如果 [reminder set] 为 true；否则为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setStartDateTime(Date value) {#setStartDateTime-java.util.Date-}
```
public final void setStartDateTime(Date value)
```


获取或设置开始日期。

值：开始日期时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setSubType(int value) {#setSubType-int-}
```
public final void setSubType(int value)
```


获取或设置子类型。

值：子类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


获取或设置主题。

值：主题。

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

