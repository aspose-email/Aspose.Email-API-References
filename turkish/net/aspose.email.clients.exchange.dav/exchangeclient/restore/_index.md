---
title: Restore
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen kişisel depolama dosyasından değişim klasörlerini geri yükler.
type: docs
weight: 350
url: /tr/net/aspose.email.clients.exchange.dav/exchangeclient/restore/
---
## Restore(string, RestoreOptions) {#restore_5}

Belirtilen kişisel depolama dosyasından değişim klasörlerini geri yükler.

```csharp
public void Restore(string fileName, RestoreOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fileName | String | Kişisel depolama dosyasına giden yol. |
| options | RestoreOptions | Seçenekleri geri yükleyin. |

### istisnalar

| istisna | şart |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* belirtilmemiş. |

### Ayrıca bakınız

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## Restore(Stream, RestoreOptions) {#restore_3}

Verilen kişisel depolama alanından değişim klasörlerini geri yükler.

```csharp
public void Restore(Stream stream, RestoreOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Kişisel depolama içeren bir akış. |
| options | RestoreOptions | Seçenekleri geri yükleyin. |

### istisnalar

| istisna | şart |
| --- | --- |
| NotSupportedException | bu*stream* okumayı desteklemez. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream* dır-dir`hükümsüz`. |

### Ayrıca bakınız

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## Restore(PersonalStorage, RestoreOptions) {#restore_1}

Verilen kişisel depolama alanından değişim klasörlerini geri yükler.

```csharp
public void Restore(PersonalStorage pst, RestoreOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pst | PersonalStorage | Yedeklenen imap klasörlerini içeren kişisel bir depolama. |
| options | RestoreOptions | Seçenekleri geri yükleyin. |

### istisnalar

| istisna | şart |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst* dır-dir`hükümsüz`. |

### Ayrıca bakınız

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## Restore(string, ExchangeFolderInfoCollection, RestoreOptions) {#restore_4}

Belirtilen kişisel depolama dosyasından belirtilen değişim klasörlerini geri yükler.

```csharp
public void Restore(string fileName, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fileName | String | Kişisel depolama dosyasına giden yol. |
| folders | ExchangeFolderInfoCollection | Geri yüklenecek bir klasör. |
| options | RestoreOptions | Seçenekleri geri yükleyin. |

### istisnalar

| istisna | şart |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* belirtilmemiş. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* dır-dir`hükümsüz`. |

### Ayrıca bakınız

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## Restore(Stream, ExchangeFolderInfoCollection, RestoreOptions) {#restore_2}

Belirtilen değişim klasörlerini verilen kişisel depolama alanından geri yükler.

```csharp
public void Restore(Stream stream, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Kişisel depolama içeren bir akış. |
| folders | ExchangeFolderInfoCollection | Geri yüklenecek bir klasör. |
| options | RestoreOptions | Seçenekleri geri yükleyin. |

### istisnalar

| istisna | şart |
| --- | --- |
| NotSupportedException | bu*stream* okumayı desteklemez. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream*veya*folders* dır-dir`hükümsüz`. |

### Ayrıca bakınız

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## Restore(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) {#restore}

Belirtilen değişim klasörlerini verilen kişisel depolama alanından geri yükler.

```csharp
public void Restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, 
    RestoreOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pst | PersonalStorage | Yedeklenmiş değişim klasörlerini içeren kişisel bir depolama. |
| folders | ExchangeFolderInfoCollection | Geri yüklenecek bir klasör. |
| options | RestoreOptions | Seçenekleri geri yükleyin. |

### istisnalar

| istisna | şart |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst*veya*folders* dır-dir`hükümsüz`. |

### Ayrıca bakınız

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
