---
title: FolderInfo
second_title: Aspose.Email for .NET API Referansı
description: PSTdeki kişisel klasör hakkındaki bilgileri temsil eder.
type: docs
weight: 20160
url: /tr/net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

PST'deki kişisel klasör hakkındaki bilgileri temsil eder.

```csharp
public sealed class FolderInfo
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [FolderInfo](folderinfo)() | Yeni bir örneğini başlatır[`FolderInfo`](../folderinfo) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass) { get; } | Klasör nesnesinin kapsayıcı sınıfını alır. |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount) { get; } | Klasördeki toplam öğe sayısını alır. |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount) { get; } | Klasördeki okunmamış öğelerin sayısını alır. |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname) { get; } | Klasörün görünen adını alır. |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid) { get; } | Giriş kimliğini alır. |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring) { get; } | Giriş kimliğinin dize temsilini alır. |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders) { get; } | Klasör nesnesinin alt klasörleri olup olmadığını gösteren bir değer alır. |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime) { get; } | Son değişiklik zamanını alır. |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties) { get; } | Klasör özelliklerini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile)(string, string) | pst klasörüne bir dosya ekler. |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem)(IMapiMessageItem) | IMapiMessageItem nesnesini klasöre ekler. |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage)(MapiMessage) | Klasöre yeni bir mesaj ekler. |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages)(IEnumerable&lt;MapiMessage&gt;) | Toplu modda mesaj ekleme sağlar. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder)(string) | Yeni alt klasörü ekler. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_1)(string, bool) | Yeni alt klasörü ekler. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_2)(string, string) | Yeni alt klasörü ekler. |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass)(string) | Kapsayıcı sınıfını değiştirir. |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname)(string) | Görünen adı değiştirir. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages)(MapiPropertyCollection) | Klasördeki tüm mesajları değiştirir. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | Klasördeki mesajları değiştirir. |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem)(byte[]) | Öğeyi (klasör veya mesaj) giriş kimliğine göre siler. |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems)(IEnumerable&lt;string&gt;) | Alt mesajları siler. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders)() | Klasördeki alt klasörlerin yinelenmesini destekleyen numaralandırıcıyı gösterir. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders_1)(FolderKind) | Klasördeki alt klasörlerin yinelenmesini destekleyen numaralandırıcıyı gösterir. |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages)() | Klasördeki mesajların yinelenmesini destekleyen numaralandırıcıyı gösterir. |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects)() | Klasördeki mesajların yinelenmesini destekleyen numaralandırıcıyı gösterir. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages)() | Klasördeki mesajların yinelenmesini destekleyen numaralandırıcıyı gösterir. |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid)() | İletilerin giriş kimliğini numaralandırır. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents)() | İleti koleksiyonunu alın. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_3)(bool) | İleti koleksiyonunu alın. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_2)(MailQuery) | İleti koleksiyonunu alın. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_1)(MessageKind) | İleti koleksiyonunu alın. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_4)(int, int) | İleti koleksiyonunu alır. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder)(string) | Alt klasörü alın. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder_1)(string, bool) | Alt klasörü alır. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders)() | Alt klasörlerin koleksiyonunu alır. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_1)(FolderKind) | Alt klasörlerin koleksiyonunu alır. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_2)(MailQuery) | Alt klasörlerin koleksiyonunu alır. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith)(FolderInfo) | Klasörü başka bir pst. klasörüyle birleştirir |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith_1)(FolderInfo, bool) | Klasörü başka bir pst'den gelen klasörle birleştirir. OnItemMoved olayı hem iletilerde hem de dizinlerde çağrılır. |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents)(FolderInfo) | İçeriği yeni bir klasöre taşır. |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders)(FolderInfo) | Alt klasörleri yeni bir üst klasöre taşır. |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath)() | PST dosyası içindeki klasörün tam yolunu alır. |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage)(string, MapiMessageItemBase) | Klasördeki mesajı günceller. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
