---
title: Load
second_title: Aspose.Email for .NET API Referansı
description: Dosyadan mesaj yükler.
type: docs
weight: 40
url: /tr/net/aspose.email.mapi/mapimessage/load/
---
## Load(string) {#load_2}

Dosyadan mesaj yükler.

```csharp
public static MapiMessage Load(string fileName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fileName | String | Kaynak dosya yoluString. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Dosya adı boş veya boş olmamalıdır. |
| NotSupportedException | Akış okumayı desteklemiyor. |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception) | Başarılı mesaj formatı desteklenmiyor. |

### Ayrıca bakınız

* class [MapiMessage](../../mapimessage)
* ad alanı [Aspose.Email.Mapi](../../mapimessage)
* toplantı [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Akıştan mesaj yükler.

```csharp
public static MapiMessage Load(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Kaynak akışıStream. |

### istisnalar

| istisna | şart |
| --- | --- |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception) | Başarılı mesaj formatı desteklenmiyor. |
| ArgumentNullException | Akış boş veya boş olmamalıdır. |
| NotSupportedException | Akış okumayı desteklemiyor. |

### Ayrıca bakınız

* class [MapiMessage](../../mapimessage)
* ad alanı [Aspose.Email.Mapi](../../mapimessage)
* toplantı [Aspose.Email](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

İletiyi akıştan ek seçeneklerle yükler.

```csharp
public static MapiMessage Load(Stream stream, LoadOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Kaynak akışıStream. |
| options | LoadOptions | Ekstra seçenekler[`LoadOptions`](../../../aspose.email/loadoptions). |

### istisnalar

| istisna | şart |
| --- | --- |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception) | Başarılı mesaj formatı desteklenmiyor. |
| ArgumentNullException | Akış boş veya boş olmamalıdır. |
| NotSupportedException | Akış okumayı desteklemiyor. |

### Ayrıca bakınız

* class [LoadOptions](../../../aspose.email/loadoptions)
* class [MapiMessage](../../mapimessage)
* ad alanı [Aspose.Email.Mapi](../../mapimessage)
* toplantı [Aspose.Email](../../../)

---

## Load(string, LoadOptions) {#load_3}

Dosyadan ek seçeneklerle mesaj yükler.

```csharp
public static MapiMessage Load(string fileName, LoadOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fileName | String | Kaynak dosya yoluString. |
| options | LoadOptions | Ekstra seçenekler[`LoadOptions`](../../../aspose.email/loadoptions). |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Dosya adı boş veya boş olmamalıdır. |
| NotSupportedException | Akış okumayı desteklemiyor. |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception) | Başarılı mesaj formatı desteklenmiyor. |

### Ayrıca bakınız

* class [LoadOptions](../../../aspose.email/loadoptions)
* class [MapiMessage](../../mapimessage)
* ad alanı [Aspose.Email.Mapi](../../mapimessage)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->