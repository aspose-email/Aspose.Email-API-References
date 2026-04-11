---
title: Appointment
second_title: Aspose.Email for Android via Java API 参考
description: 表示电子邮件的日历。
type: docs
weight: 26
url: /zh/androidjava/com.aspose.email/appointment/
---

**Inheritance:**
java.lang.Object
```
public class Appointment
```

表示电子邮件的日历。

--------------------

> This example demonstrates how to add a calendar to an E-Mail message.
> 
> [Java]
> 
> ```
> MailMessage msg = new MailMessage();
> 
>      //attendees for the event
>      MailAddressCollection attendees = new MailAddressCollection();
>      attendees.add(new MailAddress("person1@domain.com"));
>      attendees.add(new MailAddress("person2@domain.com"));
>      attendees.add(new MailAddress("person3@domain.com"));
> 
>      //create appointment
>      Appointment app = new Appointment("Room 112",
>           new Date(2006,7,17,13,0,0), new Date(2006,7,17,14,0,0),
>           new MailAddress("somebody@domain.com"),
>           attendees );
>      app.setSummary("Release Meetting");
>      app.setDescription("Discuss for the next release");
> 
>      //add calendar to the message
>      msg.addAlternateView(app.requestApointment());
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)](#Appointment-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-) | 初始化 [Appointment](../../com.aspose.email/appointment) 类的新实例。 |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-) | 初始化 [Appointment](../../com.aspose.email/appointment) 类的新实例。 |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-) | 初始化 [Appointment](../../com.aspose.email/appointment) 类的新实例。 |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-com.aspose.email.RecurrencePattern-) | 初始化 [Appointment](../../com.aspose.email/appointment) 类的新实例。 |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-com.aspose.email.RecurrencePattern-) | 初始化 [Appointment](../../com.aspose.email/appointment) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [cancelAppointment()](#cancelAppointment--) | 取消该预约。 |
| [cancelAppointment(int seqId)](#cancelAppointment-int-) | 取消该预约。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppointmentClass()](#getAppointmentClass--) | 指定该预约的访问分类。 |
| [getAppointmentHtml()](#getAppointmentHtml--) | 获取日历 HTML。 |
| [getAppointmentText()](#getAppointmentText--) | 获取日历文本。 |
| [getAppointmentText(AppointmentFormattingOptions formattingOptions)](#getAppointmentText-com.aspose.email.AppointmentFormattingOptions-) | 获取日历文本。 |
| [getAttachments()](#getAttachments--) | 获取预约的附件集合。 |
| [getAttendees()](#getAttendees--) | 获取或设置与会者。 |
| [getClass()](#getClass--) |  |
| [getCreatedDate()](#getCreatedDate--) | 获取或设置日历信息创建的日期和时间。 |
| [getDateTimeStamp()](#getDateTimeStamp--) | 获取或设置 iCalendar 对象实例创建的日期/时间.. |
| [getDescription()](#getDescription--) | 获取或设置描述。 |
| [getEndDate()](#getEndDate--) | 获取或设置结束日期。 |
| [getEndTimeZone()](#getEndTimeZone--) | 结束时区 |
| [getFlags()](#getFlags--) | 获取或设置约会标志。 |
| [getHtmlDescription()](#getHtmlDescription--) | 获取或设置描述的 HTML 表示形式。 |
| [getLastModifiedDate()](#getLastModifiedDate--) | 获取或设置日历信息上次修订的日期和时间。 |
| [getLocation()](#getLocation--) | 获取或设置位置。 |
| [getMethodType()](#getMethodType--) | 获取或设置与日历对象关联的 iCalendar 对象方法类型。 |
| [getMicrosoftBusyStatus()](#getMicrosoftBusyStatus--) | 指定约会的 BUSY 状态。 |
| [getMicrosoftImportance()](#getMicrosoftImportance--) | 指定约会的重要性。 |
| [getMicrosoftIntendedStatus()](#getMicrosoftIntendedStatus--) | 指定约会的 INTENDED 状态。 |
| [getOptionalAttendees()](#getOptionalAttendees--) | 获取可选与会者。 |
| [getOrganizer()](#getOrganizer--) | 获取或设置组织者。 |
| [getRecurrence()](#getRecurrence--) | 获取或设置重复模式。 |
| [getReminders()](#getReminders--) | 包含 AppointmentReminder [AppointmentReminder](../../com.aspose.email/appointmentreminder) 对象的集合。 |
| [getSequenceId()](#getSequenceId--) | 获取序列 ID。 |
| [getStartDate()](#getStartDate--) | 获取或设置开始日期。 |
| [getStartTimeZone()](#getStartTimeZone--) | 开始时区 |
| [getStatus()](#getStatus--) | 获取或设置对象的整体状态或确认。 |
| [getSummary()](#getSummary--) | 获取或设置摘要。 |
| [getTransparency()](#getTransparency--) | 指定此约会是否应在可用性搜索中可见。 |
| [getUniqueId()](#getUniqueId--) | 获取或设置包含日历项 GUID 的字符串值。 |
| [hashCode()](#hashCode--) |  |
| [isDescriptionHtml()](#isDescriptionHtml--) | 获取或设置指示描述是否为 HTML 格式的值 |
| [load(InputStream stream)](#load-java.io.InputStream-) | 从流加载 [Appointment](../../com.aspose.email/appointment) |
| [load(InputStream stream, boolean applyLocalTimeZone)](#load-java.io.InputStream-boolean-) | 从流加载 [Appointment](../../com.aspose.email/appointment) |
| [load(InputStream stream, AppointmentLoadOptions options)](#load-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-) | 从流加载 [Appointment](../../com.aspose.email/appointment) |
| [load(String filePath)](#load-java.lang.String-) | 从文件加载 [Appointment](../../com.aspose.email/appointment)。 |
| [load(String filePath, AppointmentLoadOptions options)](#load-java.lang.String-com.aspose.email.AppointmentLoadOptions-) | 从文件加载 [Appointment](../../com.aspose.email/appointment)。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [requestApointment()](#requestApointment--) | 请求约会。 |
| [requestApointment(int seqId)](#requestApointment-int-) | 请求约会。 |
| [resetTimeZone()](#resetTimeZone--) | 设置本地时区 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 使用默认保存选项将约会以 iCalendar 格式保存到文件。 |
| [save(OutputStream stream, AppointmentSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.AppointmentSaveOptions-) | 使用指定的保存选项将约会保存到流中 |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | 使用默认保存选项将约会以指定格式保存到流中 |
| [save(String filePath)](#save-java.lang.String-) | 使用默认保存选项将约会以 iCalendar 格式保存到文件。 |
| [save(String filePath, AppointmentSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.AppointmentSaveOptions-) | 使用指定的保存选项将约会保存到文件中 |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | 使用默认保存选项将约会以指定格式保存到文件中 |
| [setAppointmentClass(int value)](#setAppointmentClass-int-) | 指定该预约的访问分类。 |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | 获取或设置与会者。 |
| [setCreatedDate(Date value)](#setCreatedDate-java.util.Date-) | 获取或设置日历信息创建的日期和时间。 |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | 获取或设置 iCalendar 对象实例创建的日期/时间.. |
| [setDescription(String value)](#setDescription-java.lang.String-) | 获取或设置描述。 |
| [setDescriptionHtml(boolean value)](#setDescriptionHtml-boolean-) | 获取或设置指示描述是否为 HTML 格式的值 |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | 获取或设置结束日期。 |
| [setEndTimeZone(String value)](#setEndTimeZone-java.lang.String-) | 结束时区 |
| [setFlags(int value)](#setFlags-int-) | 获取或设置约会标志。 |
| [setHtmlDescription(String value)](#setHtmlDescription-java.lang.String-) | 获取或设置描述的 HTML 表示形式。 |
| [setLastModifiedDate(Date value)](#setLastModifiedDate-java.util.Date-) | 获取或设置日历信息上次修订的日期和时间。 |
| [setLocation(String value)](#setLocation-java.lang.String-) | 获取或设置位置。 |
| [setMethodType(int value)](#setMethodType-int-) | 获取或设置与日历对象关联的 iCalendar 对象方法类型。 |
| [setMicrosoftBusyStatus(int value)](#setMicrosoftBusyStatus-int-) | 指定约会的 BUSY 状态。 |
| [setMicrosoftImportance(int value)](#setMicrosoftImportance-int-) | 指定约会的重要性。 |
| [setMicrosoftIntendedStatus(int value)](#setMicrosoftIntendedStatus-int-) | 指定约会的 INTENDED 状态。 |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | 获取或设置组织者。 |
| [setRecurrence(RecurrencePattern value)](#setRecurrence-com.aspose.email.RecurrencePattern-) | 获取或设置重复模式。 |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | 获取或设置开始日期。 |
| [setStartTimeZone(String value)](#setStartTimeZone-java.lang.String-) | 开始时区 |
| [setStatus(int value)](#setStatus-int-) | 获取或设置对象的整体状态或确认。 |
| [setSummary(String value)](#setSummary-java.lang.String-) | 获取或设置摘要。 |
| [setTimeZone(String tzName)](#setTimeZone-java.lang.String-) | 设置时区 |
| [setTransparency(int value)](#setTransparency-int-) | 指定此约会是否应在可用性搜索中可见。 |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | 获取或设置包含日历项 GUID 的字符串值。 |
| [toString()](#toString--) |  |
| [updateAppointment()](#updateAppointment--) | 更新约会。 |
| [updateAppointment(int seqId)](#updateAppointment-int-) | 更新约会。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees) {#Appointment-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-}
```
public Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)
```


初始化 [Appointment](../../com.aspose.email/appointment) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | java.lang.String | 日历事件的位置。 |
| startDate | java.util.Date | 日历事件的开始时间。 |
| endDate | java.util.Date | 日历事件的结束时间。 |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | 日历事件的组织者。 |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | 日历事件的与会者。 |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)
```


初始化 [Appointment](../../com.aspose.email/appointment) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | java.lang.String | 日历事件的位置。 |
| 摘要 | java.lang.String | 日历事件的摘要。 |
| description | java.lang.String | 日历事件的描述。 |
| startDate | java.util.Date | 日历事件的开始时间。 |
| endDate | java.util.Date | 日历事件的结束时间。 |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | 日历事件的组织者。 |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | 日历事件的与会者。 |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid)
```


初始化 [Appointment](../../com.aspose.email/appointment) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | java.lang.String | 日历事件的位置。 |
| 摘要 | java.lang.String | 日历事件的摘要。 |
| description | java.lang.String | 日历事件的描述。 |
| startDate | java.util.Date | 日历事件的开始时间。 |
| endDate | java.util.Date | 日历事件的结束时间。 |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | 日历事件的组织者。 |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | 日历事件的与会者。 |
| uid | java.lang.String | 日历事件的唯一标识符。 |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-com.aspose.email.RecurrencePattern-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern)
```


初始化 [Appointment](../../com.aspose.email/appointment) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | java.lang.String | 日历事件的位置。 |
| 摘要 | java.lang.String | 日历事件的摘要。 |
| description | java.lang.String | 日历事件的描述。 |
| startDate | java.util.Date | 日历事件的开始时间。 |
| endDate | java.util.Date | 日历事件的结束时间。 |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | 日历事件的组织者。 |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | 日历事件的与会者。 |
| recurrencePattern | [RecurrencePattern](../../com.aspose.email/recurrencepattern) | 重复模式。 |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-com.aspose.email.RecurrencePattern-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern)
```


初始化 [Appointment](../../com.aspose.email/appointment) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | java.lang.String | 日历事件的位置。 |
| 摘要 | java.lang.String | 日历事件的摘要。 |
| description | java.lang.String | 日历事件的描述。 |
| startDate | java.util.Date | 日历事件的开始时间。 |
| endDate | java.util.Date | 日历事件的结束时间。 |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | 日历事件的组织者。 |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | 日历事件的与会者。 |
| uid | java.lang.String | 日历事件的唯一标识符。 |
| recurrencePattern | [RecurrencePattern](../../com.aspose.email/recurrencepattern) | 重复模式。 |

### cancelAppointment() {#cancelAppointment--}
```
public final AlternateView cancelAppointment()
```


取消该预约。

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### cancelAppointment(int seqId) {#cancelAppointment-int-}
```
public final AlternateView cancelAppointment(int seqId)
```


取消该预约。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| seqId | int | 序列标识。 |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
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
### getAppointmentClass() {#getAppointmentClass--}
```
public final int getAppointmentClass()
```


指定该预约的访问分类。

**Returns:**
int
### getAppointmentHtml() {#getAppointmentHtml--}
```
public final String getAppointmentHtml()
```


获取日历 HTML。

**Returns:**
java.lang.String - 日历的 HTML 字符串值。
### getAppointmentText() {#getAppointmentText--}
```
public final String getAppointmentText()
```


获取日历文本。

**Returns:**
java.lang.String - 日历的纯文本字符串值。
### getAppointmentText(AppointmentFormattingOptions formattingOptions) {#getAppointmentText-com.aspose.email.AppointmentFormattingOptions-}
```
public final String getAppointmentText(AppointmentFormattingOptions formattingOptions)
```


获取日历文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattingOptions | [AppointmentFormattingOptions](../../com.aspose.email/appointmentformattingoptions) | [AppointmentFormattingOptions](../../com.aspose.email/appointmentformattingoptions) 表示约会的格式化选项。 |

**Returns:**
java.lang.String - 约会的文本表示。
### getAttachments() {#getAttachments--}
```
public final AttachmentCollection getAttachments()
```


获取预约的附件集合。

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getAttendees() {#getAttendees--}
```
public final MailAddressCollection getAttendees()
```


获取或设置与会者。

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreatedDate() {#getCreatedDate--}
```
public final Date getCreatedDate()
```


获取或设置日历信息创建的日期和时间。

值：表示创建日期和时间的 java.util.Date。

**Returns:**
java.util.Date
### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


获取或设置 iCalendar 对象实例创建的日期/时间..

**Returns:**
java.util.Date
### getDescription() {#getDescription--}
```
public final String getDescription()
```


获取或设置描述。

**Returns:**
java.lang.String
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


获取或设置结束日期。

**Returns:**
java.util.Date
### getEndTimeZone() {#getEndTimeZone--}
```
public final String getEndTimeZone()
```


结束时区

**Returns:**
java.lang.String
### getFlags() {#getFlags--}
```
public final int getFlags()
```


获取或设置约会标志。

**Returns:**
int
### getHtmlDescription() {#getHtmlDescription--}
```
public final String getHtmlDescription()
```


获取或设置描述的 HTML 表示形式。

**Returns:**
java.lang.String
### getLastModifiedDate() {#getLastModifiedDate--}
```
public final Date getLastModifiedDate()
```


获取或设置日历信息上次修订的日期和时间。

值：表示修改日期和时间的 java.util.Date。

**Returns:**
java.util.Date
### getLocation() {#getLocation--}
```
public final String getLocation()
```


获取或设置位置。

**Returns:**
java.lang.String
### getMethodType() {#getMethodType--}
```
public final int getMethodType()
```


获取或设置与日历对象关联的 iCalendar 对象方法类型。

**Returns:**
int
### getMicrosoftBusyStatus() {#getMicrosoftBusyStatus--}
```
public final int getMicrosoftBusyStatus()
```


指定约会的 BUSY 状态。

**Returns:**
int
### getMicrosoftImportance() {#getMicrosoftImportance--}
```
public final int getMicrosoftImportance()
```


指定约会的重要性。

**Returns:**
int
### getMicrosoftIntendedStatus() {#getMicrosoftIntendedStatus--}
```
public final int getMicrosoftIntendedStatus()
```


指定约会的 INTENDED 状态。

**Returns:**
int
### getOptionalAttendees() {#getOptionalAttendees--}
```
public final MailAddressCollection getOptionalAttendees()
```


获取可选与会者。

值：可选与会者的地址集合。

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getOrganizer() {#getOrganizer--}
```
public final MailAddress getOrganizer()
```


获取或设置组织者。

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getRecurrence() {#getRecurrence--}
```
public final RecurrencePattern getRecurrence()
```


获取或设置重复模式。

值：重复模式。

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern)
### getReminders() {#getReminders--}
```
public final AppointmentReminderCollection getReminders()
```


包含 AppointmentReminder [AppointmentReminder](../../com.aspose.email/appointmentreminder) 对象的集合。

**Returns:**
[AppointmentReminderCollection](../../com.aspose.email/appointmentremindercollection)
### getSequenceId() {#getSequenceId--}
```
public final String getSequenceId()
```


获取序列 ID。

值：序列 ID。

**Returns:**
java.lang.String
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


获取或设置开始日期。

**Returns:**
java.util.Date
### getStartTimeZone() {#getStartTimeZone--}
```
public final String getStartTimeZone()
```


开始时区

**Returns:**
java.lang.String
### getStatus() {#getStatus--}
```
public final int getStatus()
```


获取或设置对象的整体状态或确认。

**Returns:**
int
### getSummary() {#getSummary--}
```
public final String getSummary()
```


获取或设置摘要。

**Returns:**
java.lang.String
### getTransparency() {#getTransparency--}
```
public final int getTransparency()
```


指定此约会是否应在可用性搜索中可见。

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


获取或设置包含日历项 GUID 的字符串值。在 MS Exchange 中，这对应于 PidLidGlobalObjectId mapi 属性。

值：唯一标识符。

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDescriptionHtml() {#isDescriptionHtml--}
```
public final boolean isDescriptionHtml()
```


获取或设置指示描述是否为 HTML 格式的值

**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Appointment load(InputStream stream)
```


从流加载 [Appointment](../../com.aspose.email/appointment)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于加载的流 |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(InputStream stream, boolean applyLocalTimeZone) {#load-java.io.InputStream-boolean-}
```
public static Appointment load(InputStream stream, boolean applyLocalTimeZone)
```


从流加载 [Appointment](../../com.aspose.email/appointment)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于加载的流 |
| applyLocalTimeZone | boolean | 将时间转换为本地时区 |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(InputStream stream, AppointmentLoadOptions options) {#load-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-}
```
public static Appointment load(InputStream stream, AppointmentLoadOptions options)
```


从流加载 [Appointment](../../com.aspose.email/appointment)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于加载的流 |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | 表示约会加载选项 |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(String filePath) {#load-java.lang.String-}
```
public static Appointment load(String filePath)
```


从文件加载 [Appointment](../../com.aspose.email/appointment)。支持的文件格式：iCalendar

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径 |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(String filePath, AppointmentLoadOptions options) {#load-java.lang.String-com.aspose.email.AppointmentLoadOptions-}
```
public static Appointment load(String filePath, AppointmentLoadOptions options)
```


从文件加载 [Appointment](../../com.aspose.email/appointment)。支持的文件格式：iCalendar

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径。 |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | 表示约会加载选项[AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions)。 |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment).
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### requestApointment() {#requestApointment--}
```
public final AlternateView requestApointment()
```


请求约会。

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### requestApointment(int seqId) {#requestApointment-int-}
```
public final AlternateView requestApointment(int seqId)
```


请求约会。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| seqId | int | 序列标识。 |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### resetTimeZone() {#resetTimeZone--}
```
public final void resetTimeZone()
```


设置本地时区

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


使用默认保存选项将约会以 iCalendar 格式保存到文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存的流 |

### save(OutputStream stream, AppointmentSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.AppointmentSaveOptions-}
```
public final void save(OutputStream stream, AppointmentSaveOptions saveOptions)
```


使用指定的保存选项将约会保存到流中

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存的流 |
| saveOptions | [AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions) | 保存选项 |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


使用默认保存选项将约会以指定格式保存到流中

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存的流 |
| saveFormat | int | 保存格式 |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


使用默认保存选项将约会以 iCalendar 格式保存到文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径 |

### save(String filePath, AppointmentSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.AppointmentSaveOptions-}
```
public final void save(String filePath, AppointmentSaveOptions saveOptions)
```


使用指定的保存选项将约会保存到文件中

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径 |
| saveOptions | [AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions) | 保存选项 |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


使用默认保存选项将约会以指定格式保存到文件中

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径 |
| saveFormat | int | 保存格式 |

### setAppointmentClass(int value) {#setAppointmentClass-int-}
```
public final void setAppointmentClass(int value)
```


指定该预约的访问分类。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setAttendees(MailAddressCollection value) {#setAttendees-com.aspose.email.MailAddressCollection-}
```
public final void setAttendees(MailAddressCollection value)
```


获取或设置与会者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setCreatedDate(Date value) {#setCreatedDate-java.util.Date-}
```
public final void setCreatedDate(Date value)
```


获取或设置日历信息创建的日期和时间。

值：表示创建日期和时间的 java.util.Date。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


获取或设置 iCalendar 对象实例创建的日期/时间..

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


获取或设置描述。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setDescriptionHtml(boolean value) {#setDescriptionHtml-boolean-}
```
public final void setDescriptionHtml(boolean value)
```


获取或设置指示描述是否为 HTML 格式的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


获取或设置结束日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setEndTimeZone(String value) {#setEndTimeZone-java.lang.String-}
```
public final void setEndTimeZone(String value)
```


结束时区

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFlags(int value) {#setFlags-int-}
```
public final void setFlags(int value)
```


获取或设置约会标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setHtmlDescription(String value) {#setHtmlDescription-java.lang.String-}
```
public final void setHtmlDescription(String value)
```


获取或设置描述的 HTML 表示形式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setLastModifiedDate(Date value) {#setLastModifiedDate-java.util.Date-}
```
public final void setLastModifiedDate(Date value)
```


获取或设置日历信息上次修订的日期和时间。

值：表示修改日期和时间的 java.util.Date。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


获取或设置位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMethodType(int value) {#setMethodType-int-}
```
public final void setMethodType(int value)
```


获取或设置与日历对象关联的 iCalendar 对象方法类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setMicrosoftBusyStatus(int value) {#setMicrosoftBusyStatus-int-}
```
public final void setMicrosoftBusyStatus(int value)
```


指定约会的 BUSY 状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setMicrosoftImportance(int value) {#setMicrosoftImportance-int-}
```
public final void setMicrosoftImportance(int value)
```


指定约会的重要性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setMicrosoftIntendedStatus(int value) {#setMicrosoftIntendedStatus-int-}
```
public final void setMicrosoftIntendedStatus(int value)
```


指定约会的 INTENDED 状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setOrganizer(MailAddress value) {#setOrganizer-com.aspose.email.MailAddress-}
```
public final void setOrganizer(MailAddress value)
```


获取或设置组织者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setRecurrence(RecurrencePattern value) {#setRecurrence-com.aspose.email.RecurrencePattern-}
```
public final void setRecurrence(RecurrencePattern value)
```


获取或设置重复模式。

值：重复模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RecurrencePattern](../../com.aspose.email/recurrencepattern) |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


获取或设置开始日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartTimeZone(String value) {#setStartTimeZone-java.lang.String-}
```
public final void setStartTimeZone(String value)
```


开始时区

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


获取或设置对象的整体状态或确认。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setSummary(String value) {#setSummary-java.lang.String-}
```
public final void setSummary(String value)
```


获取或设置摘要。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setTimeZone(String tzName) {#setTimeZone-java.lang.String-}
```
public final void setTimeZone(String tzName)
```


设置时区

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tzName | java.lang.String | 时区名称，例如 "America/New\_York" |

### setTransparency(int value) {#setTransparency-int-}
```
public final void setTransparency(int value)
```


指定此约会是否应在可用性搜索中可见。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


获取或设置包含日历项 GUID 的字符串值。在 MS Exchange 中，这对应于 PidLidGlobalObjectId mapi 属性。

值：唯一标识符。

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
### updateAppointment() {#updateAppointment--}
```
public final AlternateView updateAppointment()
```


更新约会。

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### updateAppointment(int seqId) {#updateAppointment-int-}
```
public final AlternateView updateAppointment(int seqId)
```


更新约会。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| seqId | int | 序列标识。 |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
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

