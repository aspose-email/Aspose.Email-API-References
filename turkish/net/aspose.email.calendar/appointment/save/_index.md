---
title: Save
second_title: Aspose.Email for .NET API Referansı
description: Randevuyu belirtilen kaydetme seçenekleriyle akışa kaydeder
type: docs
weight: 350
url: /tr/net/aspose.email.calendar/appointment/save/
---
## Save(Stream, AppointmentSaveOptions) {#save_2}

Randevuyu belirtilen kaydetme seçenekleriyle akışa kaydeder

```csharp
public void Save(Stream stream, AppointmentSaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Kaydedilecek bir akış |
| saveOptions | AppointmentSaveOptions | Bir kaydetme seçenekleri |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *saveOptions*veya*stream* dır-dir`hükümsüz` |
| NotSupportedException | belirtilen kaydetme seçenekleri desteklenmiyor |
| NotSupportedException | akış yazmayı desteklemiyor |

### Ayrıca bakınız

* class [AppointmentSaveOptions](../../appointmentsaveoptions)
* class [Appointment](../../appointment)
* ad alanı [Aspose.Email.Calendar](../../appointment)
* toplantı [Aspose.Email](../../../)

---

## Save(string) {#save_3}

Varsayılan kaydetme seçeneklerini kullanarak randevuyu iCalendar biçiminde dosyaya kaydeder

```csharp
public void Save(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | bir dosya yolu |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *filePath* dır-dir`hükümsüz`veya`boş` |

### Ayrıca bakınız

* class [Appointment](../../appointment)
* ad alanı [Aspose.Email.Calendar](../../appointment)
* toplantı [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveFormat) {#save_4}

Varsayılan kaydetme seçeneklerini kullanarak randevuyu belirtilen biçimde dosyaya kaydeder

```csharp
public void Save(string filePath, AppointmentSaveFormat saveFormat)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | bir dosya yolu |
| saveFormat | AppointmentSaveFormat | Bir kaydetme biçimi |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *filePath* dır-dir`hükümsüz`veya`boş` |
| NotSupportedException | Belirtilen kaydetme seçenekleri desteklenmiyor |

### Ayrıca bakınız

* enum [AppointmentSaveFormat](../../appointmentsaveformat)
* class [Appointment](../../appointment)
* ad alanı [Aspose.Email.Calendar](../../appointment)
* toplantı [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveOptions) {#save_5}

Randevuyu belirtilen kaydetme seçenekleriyle dosyaya kaydeder

```csharp
public void Save(string filePath, AppointmentSaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | bir dosya yolu |
| saveOptions | AppointmentSaveOptions | Bir kaydetme seçenekleri |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *filePath* dır-dir`hükümsüz`veya`boş` |
| ArgumentNullException | *saveOptions* dır-dir`hükümsüz` |
| NotSupportedException | Belirtilen kaydetme seçenekleri desteklenmiyor |

### Ayrıca bakınız

* class [AppointmentSaveOptions](../../appointmentsaveoptions)
* class [Appointment](../../appointment)
* ad alanı [Aspose.Email.Calendar](../../appointment)
* toplantı [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Varsayılan kaydetme seçeneklerini kullanarak randevuyu iCalendar biçiminde dosyaya kaydeder

```csharp
public void Save(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Kaydedilecek bir akış |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *stream* dır-dir`hükümsüz` |
| NotSupportedException | akış yazmayı desteklemiyor |

### Ayrıca bakınız

* class [Appointment](../../appointment)
* ad alanı [Aspose.Email.Calendar](../../appointment)
* toplantı [Aspose.Email](../../../)

---

## Save(Stream, AppointmentSaveFormat) {#save_1}

Randevuyu varsayılan kaydetme seçeneklerini kullanarak belirtilen biçimde akışa kaydeder

```csharp
public void Save(Stream stream, AppointmentSaveFormat saveFormat)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Kaydedilecek bir akış |
| saveFormat | AppointmentSaveFormat | Bir kaydetme biçimi |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *stream* dır-dir`hükümsüz` |
| NotSupportedException | Belirtilen kaydetme seçenekleri desteklenmiyor |
| NotSupportedException | akış yazmayı desteklemiyor |

### Ayrıca bakınız

* enum [AppointmentSaveFormat](../../appointmentsaveformat)
* class [Appointment](../../appointment)
* ad alanı [Aspose.Email.Calendar](../../appointment)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->