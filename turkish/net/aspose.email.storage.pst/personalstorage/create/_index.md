---
title: Create
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen dosya adıyla yeni PST dosyasını oluşturur.
type: docs
weight: 20
url: /tr/net/aspose.email.storage.pst/personalstorage/create/
---
## Create(string, FileFormatVersion, CancellationToken) {#create_5}

Belirtilen dosya adıyla yeni PST dosyasını oluşturur.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fileName | String | Dosyanın tam adı. |
| version | FileFormatVersion | PST dosyası sürümü. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Yeni PST'yi temsil eden bir PersonalStorage nesnesi.

### istisnalar

| istisna | şart |
| --- | --- |
| NotImplementedException | ANSI dosya sürümü oluşturulursa atar |
| ArgumentNullException | dosya adı boş veya boş ise atar |

### Notlar

Şu anda yalnızca Unicode dosya sürümü oluşturmanın desteklendiğini unutmayın.

### Ayrıca bakınız

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* ad alanı [Aspose.Email.Storage.Pst](../../personalstorage)
* toplantı [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, CancellationToken) {#create_3}

Bir akışta PST oluşturur.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | PST'nin oluşturulduğu akış. |
| version | FileFormatVersion | PST dosyası sürümü. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Yeni PST'yi temsil eden bir PersonalStorage nesnesi.

### istisnalar

| istisna | şart |
| --- | --- |
| NotImplementedException | ANSI dosya sürümü oluşturulursa atar |
| ArgumentNullException | dosya adı boş veya boş ise atar |

### Notlar

Şu anda yalnızca Unicode dosya sürümü oluşturmanın desteklendiğini unutmayın.

### Ayrıca bakınız

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* ad alanı [Aspose.Email.Storage.Pst](../../personalstorage)
* toplantı [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool, CancellationToken) {#create_2}

Bir akışta PST oluşturur.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | PST'nin oluşturulduğu akış. |
| version | FileFormatVersion | PST dosyası sürümü. |
| leaveStreamOpen | Boolean | PersonalStorage atıldığında akışı açık bırakın. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Yeni PST'yi temsil eden bir PersonalStorage nesnesi.

### istisnalar

| istisna | şart |
| --- | --- |
| NotImplementedException | ANSI dosya sürümü oluşturulursa atar |
| ArgumentNullException | dosya adı boş veya boş ise atar |

### Notlar

Şu anda yalnızca Unicode dosya sürümü oluşturmanın desteklendiğini unutmayın.

### Ayrıca bakınız

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* ad alanı [Aspose.Email.Storage.Pst](../../personalstorage)
* toplantı [Aspose.Email](../../../)

---

## Create(string, FileFormatVersion) {#create_4}

Belirtilen dosya adıyla yeni PST dosyasını oluşturur.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fileName | String | Dosyanın tam adı. |
| version | FileFormatVersion | PST dosyası sürümü. |

### Geri dönüş değeri

Yeni PST'yi temsil eden bir PersonalStorage nesnesi.

### istisnalar

| istisna | şart |
| --- | --- |
| NotImplementedException | ANSI dosya sürümü oluşturulursa atar |
| ArgumentNullException | dosya adı boş veya boş ise atar |

### Notlar

Şu anda yalnızca Unicode dosya sürümü oluşturmanın desteklendiğini unutmayın.

### Ayrıca bakınız

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* ad alanı [Aspose.Email.Storage.Pst](../../personalstorage)
* toplantı [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion) {#create}

Bir akışta PST oluşturur.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | PST'nin oluşturulduğu akış. |
| version | FileFormatVersion | PST dosyası sürümü. |

### Geri dönüş değeri

Yeni PST'yi temsil eden bir PersonalStorage nesnesi.

### istisnalar

| istisna | şart |
| --- | --- |
| NotImplementedException | ANSI dosya sürümü oluşturulursa atar |
| ArgumentNullException | akış boşsa atar |

### Notlar

Şu anda yalnızca Unicode dosya sürümü oluşturmanın desteklendiğini unutmayın.

### Ayrıca bakınız

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* ad alanı [Aspose.Email.Storage.Pst](../../personalstorage)
* toplantı [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool) {#create_1}

Bir akışta PST oluşturur.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | PST'nin oluşturulduğu akış. |
| version | FileFormatVersion | PST dosyası sürümü. |
| leaveStreamOpen | Boolean | PersonalStorage atıldığında akışı açık bırakın. |

### Geri dönüş değeri

Yeni PST'yi temsil eden bir PersonalStorage nesnesi.

### istisnalar

| istisna | şart |
| --- | --- |
| NotImplementedException | ANSI dosya sürümü oluşturulursa atar |
| ArgumentNullException | akış boşsa atar |

### Notlar

Şu anda yalnızca Unicode dosya sürümü oluşturmanın desteklendiğini unutmayın.

### Ayrıca bakınız

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* ad alanı [Aspose.Email.Storage.Pst](../../personalstorage)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
