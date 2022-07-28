---
title: ExtendedCalendar
second_title: Aspose.Email for .NET API Referansı
description: Tek bir takvim için renkler gibi bir dizi genişletilmiş meta veri.
type: docs
weight: 15700
url: /tr/net/aspose.email.clients.google/extendedcalendar/
---
## ExtendedCalendar class

Tek bir takvim için renkler gibi bir dizi genişletilmiş meta veri.

```csharp
public class ExtendedCalendar : Calendar
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ExtendedCalendar](extendedcalendar#constructor)() | ExtendedCalendar sınıfının yeni bir örneğini başlatır. |
| [ExtendedCalendar](extendedcalendar#constructor_1)(string) | ExtendedCalendar sınıfının yeni bir örneğini başlatır. |
| [ExtendedCalendar](extendedcalendar#constructor_2)(string, string) | ExtendedCalendar sınıfının yeni bir örneğini başlatır. |
| [ExtendedCalendar](extendedcalendar#constructor_3)(string, string, string, string) | ExtendedCalendar sınıfının yeni bir örneğini başlatır. |
| [ExtendedCalendar](extendedcalendar#constructor_4)(string, string, string, string, string) | ExtendedCalendar sınıfının yeni bir örneğini başlatır. |
| [ExtendedCalendar](extendedcalendar#constructor_5)(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | ExtendedCalendar sınıfının yeni bir örneğini başlatır. |
| [ExtendedCalendar](extendedcalendar#constructor_6)(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | ExtendedCalendar sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [AccessRole](../../aspose.email.clients.google/extendedcalendar/accessrole) { get; } | Kimliği doğrulanmış kullanıcının takvimde sahip olduğu etkin erişim rolü. Sadece oku. Olası değerler: |
| virtual [BackgroundColor](../../aspose.email.clients.google/extendedcalendar/backgroundcolor) { get; set; } | Takvimin '#0088aa' biçimindeki ana rengi. Bu özellik, dizin tabanlı colorId özelliğinin yerini alır. |
| virtual [ColorId](../../aspose.email.clients.google/extendedcalendar/colorid) { get; set; } | Takvimin rengi. Bu, renk tanımının "takvim" bölümündeki bir girdiye atıfta bulunan bir kimliktir ("renkler" uç noktasına bakın). |
| virtual [ConferenceProperties](../../aspose.email.clients.google/calendar/conferenceproperties) { get; } | Bu takvim için konferans özelliklerini alır. |
| virtual [DefaultReminders](../../aspose.email.clients.google/extendedcalendar/defaultreminders) { get; set; } | Kimliği doğrulanmış kullanıcının bu takvim için sahip olduğu varsayılan anımsatıcılar. |
| virtual [Description](../../aspose.email.clients.google/calendar/description) { get; set; } | Takvimin açıklaması. |
| virtual [ETag](../../aspose.email.clients.google/basedataobject/etag) { get; set; } | Bir ETag veya varlık etiketi, HTTP'nin web önbelleği doğrulaması için sağladığı ve bir istemcinin koşullu isteklerde bulunmasına olanak tanıyan çeşitli mekanizmalardan biridir. Bu, önbelleklerin daha verimli olmasını sağlar ve içerik değişmediyse bir web sunucusunun tam bir yanıt göndermesi gerekmediğinden bant genişliğinden tasarruf sağlar. ETag'ler, bir kaynağın eşzamanlı güncellemelerinin birbirinin üzerine yazılmasını önlemeye yardımcı olmanın bir yolu olarak iyimser eşzamanlılık kontrolü için de kullanılabilir. |
| virtual [ForegroundColor](../../aspose.email.clients.google/extendedcalendar/foregroundcolor) { get; set; } | Takvimin '#ffffff' biçimindeki ön plan rengi. Bu özellik, dizin tabanlı colorId özelliğinin yerini alır. |
| virtual [Hidden](../../aspose.email.clients.google/extendedcalendar/hidden) { get; set; } | Takvimin listeden gizlenip gizlenmediği. Varsayılan, False'dır. |
| virtual [Id](../../aspose.email.clients.google/basedataobject/id) { get; set; } | Kaynağın tanımlayıcısı. |
| virtual [Kind](../../aspose.email.clients.google/basedataobject/kind) { get; } | Kaynağın türü |
| virtual [Location](../../aspose.email.clients.google/calendar/location) { get; set; } | Serbest biçimli metin olarak takvimin coğrafi konumu. |
| virtual [NotificationSettings](../../aspose.email.clients.google/extendedcalendar/notificationsettings) { get; set; } | Kimliği doğrulanmış kullanıcının bu takvim için aldığı bildirimler. |
| virtual [Primary](../../aspose.email.clients.google/extendedcalendar/primary) { get; set; } | Takvimin, kimliği doğrulanmış kullanıcının birincil takvimi olup olmadığı. Sadece oku. Varsayılan, False'dır. |
| virtual [Selected](../../aspose.email.clients.google/extendedcalendar/selected) { get; set; } | Takvim içeriğinin takvim kullanıcı arayüzünde gösterilip gösterilmeyeceği. Varsayılan, False'dır. |
| virtual [Summary](../../aspose.email.clients.google/calendar/summary) { get; set; } | Takvimin başlığı. |
| virtual [SummaryOverride](../../aspose.email.clients.google/extendedcalendar/summaryoverride) { get; set; } | Kimliği doğrulanmış kullanıcının bu takvim için ayarladığı özet. |
| virtual [TimeZone](../../aspose.email.clients.google/calendar/timezone) { get; set; } | Takvimin saat dilimi. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [ToString](../../aspose.email.clients.google/extendedcalendar/tostring)() | Nesne örneğini temsil eden bir dize döndürür. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [ExtendedCalendarKind](../../aspose.email.clients.google/extendedcalendar/extendedcalendarkind) | "calendar#calendarListEntry" kaynağının türü. |
| const [ListKind](../../aspose.email.clients.google/extendedcalendar/listkind) | "calendar#calendarList" kaynak listesi türü. |

### Ayrıca bakınız

* class [Calendar](../calendar)
* ad alanı [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
