---
title: CreateFolder
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen üst klasörde belirtilen ada sahip yeni klasörü oluşturur.
type: docs
weight: 500
url: /tr/net/aspose.email.clients.exchange.webservice/iewsclient/createfolder/
---
## CreateFolder(string, string) {#createfolder_2}

Belirtilen üst klasörde belirtilen ada sahip yeni klasörü oluşturur.

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| parentFolderUri | String | Üst klasörün bir uri'si. |
| name | String | Oluşturulacak klasörün adı. |

### istisnalar

| istisna | şart |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*veya*name* dır-dir`hükümsüz`veya`boş`. |

### Ayrıca bakınız

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection) {#createfolder_3}

Yeni klasörü oluşturur

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| parentFolderUri | String | Üst klasörün URI'si |
| name | String | Yeni klasörün adı |
| permissions | ExchangeFolderPermissionCollection | Yeni klasörde izin |

### Geri dönüş değeri

Klasör bilgilerini döndürür

### Ayrıca bakınız

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection, string) {#createfolder_4}

Yeni klasörü oluşturur

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions, string folderClass)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| parentFolderUri | String | Üst klasörün URI'si |
| name | String | Yeni klasörün adı |
| permissions | ExchangeFolderPermissionCollection | Yeni klasörde izin |
| folderClass | String | Yeni klasör sınıfı |

### Geri dönüş değeri

Klasör bilgilerini döndürür

### Ayrıca bakınız

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## CreateFolder(string, ExchangeFolderType) {#createfolder_1}

Kök klasörde yeni klasör oluşturur.

```csharp
public ExchangeFolderInfo CreateFolder(string name, ExchangeFolderType folderType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| name | String | Yeni klasörün adı |
| folderType | ExchangeFolderType | Klasör türü |

### Geri dönüş değeri

Klasör bilgilerini döndürür

### Ayrıca bakınız

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderType) {#createfolder_5}

Yeni klasörü oluşturur

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderType folderType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| parentFolderUri | String | Üst klasörün URI'si |
| name | String | Yeni klasörün adı |
| folderType | ExchangeFolderType | Klasör türü |

### Geri dönüş değeri

Klasör bilgilerini döndürür

### Ayrıca bakınız

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## CreateFolder(string) {#createfolder}

Kök klasörde yeni klasör oluşturur.

```csharp
public ExchangeFolderInfo CreateFolder(string name)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| name | String | Yeni klasörün adı |

### Geri dönüş değeri

Klasör bilgilerini döndürür

### Ayrıca bakınız

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
