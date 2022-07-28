---
title: Save
second_title: Aspose.Email for .NET API Referansı
description: Bunu kaydederMapiContactaspose.email.mapi/mapicontact varsayılan seçeneklerle vCard dosyasına. Desteklenen vCard sürümü 2.1
type: docs
weight: 140
url: /tr/net/aspose.email.mapi/mapicontact/save/
---
## Save(string) {#save_3}

Bunu kaydeder[`MapiContact`](../../mapicontact) varsayılan seçeneklerle vCard dosyasına. Desteklenen vCard sürümü 2.1

```csharp
public void Save(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Bir vCard dosya adı |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | *filePath* dır-dir`hükümsüz`veya`boş` |

### Ayrıca bakınız

* class [MapiContact](../../mapicontact)
* ad alanı [Aspose.Email.Mapi](../../mapicontact)
* toplantı [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

Bunu kaydeder[`MapiContact`](../../mapicontact)varsayılan seçenekleri kullanarak bir formatta belirtilen dosyaya. Desteklenen kaydetme formatı vCard'dır.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Bir vCard dosya adı |
| saveFormat | ContactSaveFormat | Bir kaydetme biçimi |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | *filePath* dır-dir`hükümsüz`veya`boş` |
| NotSupportedException | belirtilen biçim desteklenmiyor |

### Ayrıca bakınız

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* ad alanı [Aspose.Email.Mapi](../../mapicontact)
* toplantı [Aspose.Email](../../../)

---

## Save(string, ContactSaveOptions) {#save_5}

Bunu kaydeder[`MapiContact`](../../mapicontact) belirtilen kaydetme seçeneklerini kullanarak dosyaya. Desteklenen kaydetme seçenekleri[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Bir vCard dosya adı |
| saveOptions | ContactSaveOptions | Bir kaydetme seçenekleri |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | *filePath* dır-dir`hükümsüz`veya`boş` |
| ArgumentNullException | *saveOptions* dır-dir`hükümsüz` |
| NotSupportedException | bazı kaydetme seçenekleri desteklenmiyor |

### Ayrıca bakınız

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* ad alanı [Aspose.Email.Mapi](../../mapicontact)
* toplantı [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Bunu kaydeder[`MapiContact`](../../mapicontact) vCard biçimiyle verilen akışa. Desteklenen vCard sürümü 2.1

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
| NotSupportedException | *stream* yazmayı desteklemiyor |

### Ayrıca bakınız

* class [MapiContact](../../mapicontact)
* ad alanı [Aspose.Email.Mapi](../../mapicontact)
* toplantı [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

Bunu kaydeder[`MapiContact`](../../mapicontact) varsayılan seçenekleri kullanan bir formatla verilen akışa. Desteklenen kaydetme formatı vCard 'dir.

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Kaydedilecek bir akış |
| saveFormat | ContactSaveFormat | Bir kaydetme biçimi |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *stream* dır-dir`hükümsüz` |
| NotSupportedException | *stream* yazmayı desteklemiyor |
| NotSupportedException | Belirtilen biçim desteklenmiyor |

### Ayrıca bakınız

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* ad alanı [Aspose.Email.Mapi](../../mapicontact)
* toplantı [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

Bunu kaydeder[`MapiContact`](../../mapicontact) belirtilen kaydetme seçeneklerini kullanarak verilen akışa. Desteklenen kaydetme seçenekleri[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Kaydedilecek bir akış |
| saveOptions | ContactSaveOptions | Bir kaydetme seçenekleri |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *stream*veya*saveOptions* dır-dir`hükümsüz` |
| NotSupportedException | *stream* yazmayı desteklemiyor |
| ArgumentException | yanlış*saveOptions* |
| NotSupportedException | bazı kaydetme seçenekleri desteklenmiyor |

### Ayrıca bakınız

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* ad alanı [Aspose.Email.Mapi](../../mapicontact)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
