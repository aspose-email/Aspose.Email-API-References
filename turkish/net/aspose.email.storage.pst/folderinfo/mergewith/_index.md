---
title: MergeWith
second_title: Aspose.Email for .NET API Referansı
description: Klasörü başka bir pst. klasörüyle birleştirir
type: docs
weight: 310
url: /tr/net/aspose.email.storage.pst/folderinfo/mergewith/
---
## MergeWith(FolderInfo) {#mergewith}

Klasörü başka bir pst. klasörüyle birleştirir

```csharp
public void MergeWith(FolderInfo sourceFolder)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sourceFolder | FolderInfo | Kaynak klasör. |

### istisnalar

| istisna | şart |
| --- | --- |
| InvalidOperationException | Kaynak klasör aynı pst içinde bulunduğunda atar. |

### Ayrıca bakınız

* class [FolderInfo](../../folderinfo)
* ad alanı [Aspose.Email.Storage.Pst](../../folderinfo)
* toplantı [Aspose.Email](../../../)

---

## MergeWith(FolderInfo, bool) {#mergewith_1}

Klasörü başka bir pst'den gelen klasörle birleştirir. OnItemMoved olayı hem iletilerde hem de dizinlerde çağrılır.

```csharp
public void MergeWith(FolderInfo sourceFolder, bool recursiveHandler)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sourceFolder | FolderInfo | Kaynak klasör. |
| recursiveHandler | Boolean | Doğruysa, alt dizinlerdeki mesajlar dahil tüm mesajlarda OnItemMoved çağrılır, aksi takdirde OnItemMoved yalnızca geçerli dizindeki mesajlar için çağrılır. |

### istisnalar

| istisna | şart |
| --- | --- |
| InvalidOperationException | Kaynak klasör aynı pst içinde bulunduğunda atar. |

### Ayrıca bakınız

* class [FolderInfo](../../folderinfo)
* ad alanı [Aspose.Email.Storage.Pst](../../folderinfo)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->