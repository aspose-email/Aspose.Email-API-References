---
title: Appointment
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل التقويم إلى بريد إلكتروني.
type: docs
weight: 430
url: /ar/net/aspose.email.calendar/appointment/
---
## Appointment class

يمثل التقويم إلى بريد إلكتروني.

```csharp
public class Appointment
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Appointment](appointment#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | قم بتهيئة مثيل جديد لملف[`Appointment`](../appointment) فئة . |
| [Appointment](appointment#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | قم بتهيئة مثيل جديد لملف[`Appointment`](../appointment) فئة . |
| [Appointment](appointment#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | قم بتهيئة مثيل جديد لملف[`Appointment`](../appointment) فئة . |
| [Appointment](appointment#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | قم بتهيئة مثيل جديد لملف[`Appointment`](../appointment) فئة . |
| [Appointment](appointment#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | قم بتهيئة مثيل جديد لملف[`Appointment`](../appointment) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments) { get; } | الحصول على مجموعة مرفقات الموعد. |
| [Attendees](../../aspose.email.calendar/appointment/attendees) { get; set; } | الحصول على أو تعيين الحاضرين . |
| [Class](../../aspose.email.calendar/appointment/class) { get; set; } | يحدد تصنيف الوصول للموعد. |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate) { get; set; } | الحصول على أو تحديد تاريخ ووقت إنشاء معلومات التقويم. |
| [DateTimeStamp](../../aspose.email.calendar/appointment/datetimestamp) { get; set; } | الحصول على أو تعيين التاريخ / الوقت الذي تم فيه إنشاء مثيل كائن iCalendar .. |
| [Description](../../aspose.email.calendar/appointment/description) { get; set; } | الحصول على الوصف أو تعيينه . |
| [EndDate](../../aspose.email.calendar/appointment/enddate) { get; set; } | الحصول على تاريخ الانتهاء أو تحديده . |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone) { get; set; } | المنطقة الزمنية للانتهاء |
| [Flags](../../aspose.email.calendar/appointment/flags) { get; set; } | الحصول على إشارات المواعيد أو تعيينها . |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription) { get; set; } | الحصول على تمثيل html للوصف أو تعيينه. |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate) { get; set; } | الحصول على أو تحديد تاريخ ووقت آخر مراجعة لمعلومات التقويم. |
| [Location](../../aspose.email.calendar/appointment/location) { get; set; } | الحصول على الموقع أو تحديده. |
| [MethodType](../../aspose.email.calendar/appointment/methodtype) { get; set; } | الحصول على أو تعيين نوع أسلوب كائن iCalendar المرتبط بكائن التقويم. |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus) { get; set; } | يحدد الحالة المشغولة للموعد. |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance) { get; set; } | يحدد أهمية الموعد. |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus) { get; set; } | تحديد الحالة المنتظرة للموعد. |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees) { get; } | الحصول على الحاضرين الاختياريين . |
| [Organizer](../../aspose.email.calendar/appointment/organizer) { get; set; } | الحصول على المنظم أو تعيينه . |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence) { get; set; } | الحصول على أو تحديد نمط التكرار. |
| [Reminders](../../aspose.email.calendar/appointment/reminders) { get; } | يحتوي على مجموعة من تذكيرات المواعيد[`AppointmentReminder`](../appointmentreminder) الكائنات . |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid) { get; } | يحصل على معرف التسلسل . |
| [StartDate](../../aspose.email.calendar/appointment/startdate) { get; set; } | الحصول على تاريخ البدء أو تحديده . |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone) { get; set; } | المنطقة الزمنية للبدء |
| [Status](../../aspose.email.calendar/appointment/status) { get; set; } | الحصول على أو تحديد الحالة العامة أو التأكيد للكائن . |
| [Summary](../../aspose.email.calendar/appointment/summary) { get; set; } | الحصول على الملخص أو تعيينه. |
| [Transparency](../../aspose.email.calendar/appointment/transparency) { get; set; } | تحديد ما إذا كان هذا الموعد يهدف إلى الظهور في عمليات البحث عن التوفر أم لا. |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid) { get; set; } | الحصول على أو تعيين قيمة سلسلة تحتوي على GUID لعنصر التقويم . في MS Exchange ، هذه هي خاصية مخطط PidLidGlobalObjectId. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load#load)(Stream) | الأحمال[`Appointment`](../appointment) من تيار |
| static [Load](../../aspose.email.calendar/appointment/load#load_3)(string) | الأحمال[`Appointment`](../appointment) من الملف. تنسيقات الملفات المدعومة: iCalendar |
| static [Load](../../aspose.email.calendar/appointment/load#load_1)(Stream, AppointmentLoadOptions) | الأحمال[`Appointment`](../appointment) من تيار |
| static [Load](../../aspose.email.calendar/appointment/load#load_2)(Stream, bool) | الأحمال[`Appointment`](../appointment) من تيار |
| static [Load](../../aspose.email.calendar/appointment/load#load_4)(string, AppointmentLoadOptions) | الأحمال[`Appointment`](../appointment) من الملف. تنسيقات الملفات المدعومة: iCalendar مسار ملف.يمثل خيارات تحميل المواعيد[`AppointmentLoadOptions`](../appointmentloadoptions). قراءة[`Appointment`](../appointment). |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment)() | إلغاء الموعد . |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment_1)(int) | إلغاء الموعد . |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml)() | يحصل على التقويم HTML. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext)() | يحصل على نص التقويم . |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext_1)(AppointmentFormattingOptions) | يحصل على نص التقويم . |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment)() | طلب موعد. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment_1)(int) | طلب موعد. |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone)() | تعيين المنطقة الزمنية المحلية |
| [Save](../../aspose.email.calendar/appointment/save#save)(Stream) | يحفظ الموعد في الملف بتنسيق iCalendar باستخدام خيارات الحفظ الافتراضية |
| [Save](../../aspose.email.calendar/appointment/save#save_3)(string) | يحفظ الموعد في الملف بتنسيق iCalendar باستخدام خيارات الحفظ الافتراضية |
| [Save](../../aspose.email.calendar/appointment/save#save_1)(Stream, AppointmentSaveFormat) | يحفظ الموعد في التدفق بالتنسيق المحدد باستخدام خيارات الحفظ الافتراضية |
| [Save](../../aspose.email.calendar/appointment/save#save_2)(Stream, AppointmentSaveOptions) | يحفظ الموعد في الدفق بخيارات الحفظ المحددة |
| [Save](../../aspose.email.calendar/appointment/save#save_4)(string, AppointmentSaveFormat) | حفظ الموعد في الملف بالتنسيق المحدد باستخدام خيارات الحفظ الافتراضية |
| [Save](../../aspose.email.calendar/appointment/save#save_5)(string, AppointmentSaveOptions) | يحفظ الموعد في الملف بخيارات الحفظ المحددة |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone)(string) | تعيين المنطقة الزمنية |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment)() | يتم تحديث الموعد . |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment_1)(int) | يتم تحديث الموعد . |

### أمثلة

يوضح هذا المثال كيفية إضافة تقويم إلى رسالة بريد إلكتروني.

[C #]

[البصرية الأساسية]

```csharp
MailMessage msg = new MailMessage();

// الحاضرين للحدث
MailAddressCollection attendees = new MailAddressCollection();
attendees.Add(new MailAddress("person1@domain.com"));
attendees.Add(new MailAddress("person2@domain.com"));
attendees.Add(new MailAddress("person3@domain.com"));

// إنشاء موعد
Appointment app = new Appointment("Room 112",new DateTime(2006,7,17,13,0,0),new DateTime(2006,7,17,14,0,0),new MailAddress("somebody@domain.com"), attendees );
cal.Summary = "Release Meetting";
cal.Description = "Discuss for the next release";

// أضف التقويم إلى الرسالة
msg.AddAlternateView(app.RequestApointment());

// أرسل رسالة البريد الإلكتروني
SmtpClient smtp= new SmtpClient("smtp.server.com", 25, "user", "password");
smtp.Send(msg);
```

```csharp
Dim msg As MailMessage =  New MailMessage() 

'الحاضرين لهذا الحدث
Dim attendees As MailAddressCollection =  New MailAddressCollection() 
attendees.Add(New MailAddress("person1@domain.com"))
attendees.Add(New MailAddress("person2@domain.com"))
attendees.Add(New MailAddress("person3@domain.com"))

'إنشاء التقويم
Dim cal As Appointment =  New Appointment("Room 112",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com"),attendees) 
cal.Summary = "Release Meetting"
cal.Description = "Discuss for the next release"

'أضف التقويم إلى الرسالة
msg.AddAlternateView(app.RequestApointment())
```

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Calendar](../../aspose.email.calendar)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
