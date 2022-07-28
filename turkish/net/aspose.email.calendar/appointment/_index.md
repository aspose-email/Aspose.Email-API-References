---
title: Appointment
second_title: Aspose.Email for .NET API Referansı
description: Bir e-postaya gönderilen takvimi temsil eder.
type: docs
weight: 430
url: /tr/net/aspose.email.calendar/appointment/
---
## Appointment class

Bir e-postaya gönderilen takvimi temsil eder.

```csharp
public class Appointment
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Appointment](appointment#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | Yeni bir örneğini başlat[`Appointment`](../appointment) sınıf. |
| [Appointment](appointment#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | Yeni bir örneğini başlat[`Appointment`](../appointment) sınıf. |
| [Appointment](appointment#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | Yeni bir örneğini başlat[`Appointment`](../appointment) sınıf. |
| [Appointment](appointment#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | Yeni bir örneğini başlat[`Appointment`](../appointment) sınıf. |
| [Appointment](appointment#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | Yeni bir örneğini başlat[`Appointment`](../appointment) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments) { get; } | Randevu eklerinin koleksiyonunu alır. |
| [Attendees](../../aspose.email.calendar/appointment/attendees) { get; set; } | Katılımcıları alır veya ayarlar. |
| [Class](../../aspose.email.calendar/appointment/class) { get; set; } | Randevu için erişim sınıflandırmasını belirtir. |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate) { get; set; } | Takvim bilgilerinin oluşturulduğu tarih ve saati alır veya ayarlar. |
| [DateTimeStamp](../../aspose.email.calendar/appointment/datetimestamp) { get; set; } | iCalendar nesnesinin örneğinin oluşturulduğu tarihi/saati alır veya ayarlar.. |
| [Description](../../aspose.email.calendar/appointment/description) { get; set; } | Açıklamayı alır veya ayarlar. |
| [EndDate](../../aspose.email.calendar/appointment/enddate) { get; set; } | Bitiş tarihini alır veya ayarlar. |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone) { get; set; } | Bitiş saat dilimi |
| [Flags](../../aspose.email.calendar/appointment/flags) { get; set; } | Randevu bayraklarını alır veya ayarlar. |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription) { get; set; } | Açıklamanın html temsilini alır veya ayarlar. |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate) { get; set; } | Takvim bilgilerinin en son revize edildiği tarih ve saati alır veya ayarlar. |
| [Location](../../aspose.email.calendar/appointment/location) { get; set; } | Konumu alır veya ayarlar. |
| [MethodType](../../aspose.email.calendar/appointment/methodtype) { get; set; } | Takvim nesnesiyle ilişkili iCalendar nesne yöntemi türünü alır veya ayarlar. |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus) { get; set; } | Bir randevunun MEŞGUL durumunu belirtir. |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance) { get; set; } | Randevunun önemini belirtir. |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus) { get; set; } | Bir randevunun AMACI durumunu belirtir. |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees) { get; } | İsteğe bağlı katılımcıları alır. |
| [Organizer](../../aspose.email.calendar/appointment/organizer) { get; set; } | Düzenleyiciyi alır veya ayarlar. |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence) { get; set; } | Yineleme modelini alır veya ayarlar. |
| [Reminders](../../aspose.email.calendar/appointment/reminders) { get; } | Randevu Hatırlatıcı koleksiyonunu içerir[`AppointmentReminder`](../appointmentreminder) nesneler. |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid) { get; } | Dizi kimliğini alır. |
| [StartDate](../../aspose.email.calendar/appointment/startdate) { get; set; } | Başlangıç tarihini alır veya ayarlar. |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone) { get; set; } | Başlangıç saat dilimi |
| [Status](../../aspose.email.calendar/appointment/status) { get; set; } | Nesnenin genel durumunu veya onayını alır veya ayarlar. |
| [Summary](../../aspose.email.calendar/appointment/summary) { get; set; } | Özeti alır veya ayarlar. |
| [Transparency](../../aspose.email.calendar/appointment/transparency) { get; set; } | Bu randevunun uygunluk aramalarında görünmesinin amaçlanıp tasarlanmadığını belirtir. |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid) { get; set; } | Takvim öğesi için GUID içeren bir dize değeri alır veya ayarlar. MS Exchange'de bu, PidLidGlobalObjectId mapi özelliğidir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load#load)(Stream) | Yükler[`Appointment`](../appointment) akışından |
| static [Load](../../aspose.email.calendar/appointment/load#load_3)(string) | Yükler[`Appointment`](../appointment) dosyadan. Desteklenen dosya biçimleri: iCalendar |
| static [Load](../../aspose.email.calendar/appointment/load#load_1)(Stream, AppointmentLoadOptions) | Yükler[`Appointment`](../appointment) akışından |
| static [Load](../../aspose.email.calendar/appointment/load#load_2)(Stream, bool) | Yükler[`Appointment`](../appointment) akışından |
| static [Load](../../aspose.email.calendar/appointment/load#load_4)(string, AppointmentLoadOptions) | Yükler[`Appointment`](../appointment) dosyadan. Desteklenen dosya biçimleri: iCalendar Bir dosya yolu.Randevu yükleme seçeneklerini temsil eder[`AppointmentLoadOptions`](../appointmentloadoptions). bir okuma[`Appointment`](../appointment). |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment)() | Randevuyu iptal eder. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment_1)(int) | Randevuyu iptal eder. |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml)() | Takvim HTML'sini alır. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext)() | Takvim metnini alır. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext_1)(AppointmentFormattingOptions) | Takvim metnini alır. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment)() | Randevu ister. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment_1)(int) | Randevu ister. |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone)() | Yerel saat dilimini ayarla |
| [Save](../../aspose.email.calendar/appointment/save#save)(Stream) | Varsayılan kaydetme seçeneklerini kullanarak randevuyu iCalendar biçiminde dosyaya kaydeder |
| [Save](../../aspose.email.calendar/appointment/save#save_3)(string) | Varsayılan kaydetme seçeneklerini kullanarak randevuyu iCalendar biçiminde dosyaya kaydeder |
| [Save](../../aspose.email.calendar/appointment/save#save_1)(Stream, AppointmentSaveFormat) | Randevuyu varsayılan kaydetme seçeneklerini kullanarak belirtilen biçimde akışa kaydeder |
| [Save](../../aspose.email.calendar/appointment/save#save_2)(Stream, AppointmentSaveOptions) | Randevuyu belirtilen kaydetme seçenekleriyle akışa kaydeder |
| [Save](../../aspose.email.calendar/appointment/save#save_4)(string, AppointmentSaveFormat) | Varsayılan kaydetme seçeneklerini kullanarak randevuyu belirtilen biçimde dosyaya kaydeder |
| [Save](../../aspose.email.calendar/appointment/save#save_5)(string, AppointmentSaveOptions) | Randevuyu belirtilen kaydetme seçenekleriyle dosyaya kaydeder |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone)(string) | Saat dilimini ayarla |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment)() | Randevuyu günceller. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment_1)(int) | Randevuyu günceller. |

### Örnekler

Bu örnek, bir E-Posta mesajına nasıl takvim ekleneceğini gösterir.

[C#]

[Visual Basic]

```csharp
MailMessage msg = new MailMessage();

//etkinliğe katılanlar
MailAddressCollection attendees = new MailAddressCollection();
attendees.Add(new MailAddress("person1@domain.com"));
attendees.Add(new MailAddress("person2@domain.com"));
attendees.Add(new MailAddress("person3@domain.com"));

//randevu oluştur
Appointment app = new Appointment("Room 112",new DateTime(2006,7,17,13,0,0),new DateTime(2006,7,17,14,0,0),new MailAddress("somebody@domain.com"), attendees );
cal.Summary = "Release Meetting";
cal.Description = "Discuss for the next release";

// mesaja takvim ekle
msg.AddAlternateView(app.RequestApointment());

// e-posta mesajını gönder
SmtpClient smtp= new SmtpClient("smtp.server.com", 25, "user", "password");
smtp.Send(msg);
```

```csharp
Dim msg As MailMessage =  New MailMessage() 

'etkinliğe katılanlar
Dim attendees As MailAddressCollection =  New MailAddressCollection() 
attendees.Add(New MailAddress("person1@domain.com"))
attendees.Add(New MailAddress("person2@domain.com"))
attendees.Add(New MailAddress("person3@domain.com"))

'takvim oluştur
Dim cal As Appointment =  New Appointment("Room 112",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com"),attendees) 
cal.Summary = "Release Meetting"
cal.Description = "Discuss for the next release"

'mesaja takvim ekle
msg.AddAlternateView(app.RequestApointment())
```

### Ayrıca bakınız

* ad alanı [Aspose.Email.Calendar](../../aspose.email.calendar)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
