---
title: FolderInfo
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل information حول المجلد الشخصي في PST .
type: docs
weight: 20160
url: /ar/net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

يمثل information حول المجلد الشخصي في PST .

```csharp
public sealed class FolderInfo
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [FolderInfo](folderinfo)() | يقوم بتهيئة مثيل جديد لملف[`FolderInfo`](../folderinfo) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass) { get; } | يحصل على فئة الحاوية لكائن المجلد. |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount) { get; } | الحصول على العدد الإجمالي للعناصر في المجلد. |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount) { get; } | يحصل على عدد العناصر غير المقروءة في المجلد. |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname) { get; } | الحصول على اسم عرض المجلد. |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid) { get; } | يحصل على معرف الإدخال . |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring) { get; } | يحصل على تمثيل سلسلة لمعرف الإدخال. |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders) { get; } | يحصل على قيمة تشير إلى ما إذا كان كائن المجلد يحتوي على أي مجلدات فرعية. |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime) { get; } | يحصل على وقت التعديل الأخير. |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties) { get; } | يحصل على خصائص المجلد. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile)(string, string) | إضافة ملف إلى مجلد pst . |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem)(IMapiMessageItem) | يضيف كائن IMapiMessageItem إلى المجلد. |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage)(MapiMessage) | إضافة رسالة جديدة إلى المجلد . |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages)(IEnumerable&lt;MapiMessage&gt;) | يوفر إضافة الرسائل في وضع مجمّع . |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder)(string) | إضافة مجلد فرعي جديد . |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_1)(string, bool) | إضافة مجلد فرعي جديد . |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_2)(string, string) | إضافة مجلد فرعي جديد. |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass)(string) | يغير فئة الحاوية . |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname)(string) | يغير اسم العرض . |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages)(MapiPropertyCollection) | يغير كل الرسائل في المجلد . |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | يغير الرسائل الموجودة في المجلد . |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem)(byte[]) | حذف العنصر (المجلد أو الرسالة) بإدخاله ID . |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems)(IEnumerable&lt;string&gt;) | حذف الرسائل الفرعية . |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders)() | يعرض العداد الذي يدعم تكرار المجلدات الفرعية في المجلد. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders_1)(FolderKind) | يعرض العداد الذي يدعم تكرار المجلدات الفرعية في المجلد. |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages)() | يعرض العداد الذي يدعم تكرار الرسائل في المجلد. |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects)() | يعرض العداد الذي يدعم تكرار الرسائل في المجلد. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages)() | يعرض العداد الذي يدعم تكرار الرسائل في المجلد. |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid)() | يعدّد إدخال معرّف الرسائل . |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents)() | احصل على مجموعة من الرسائل . |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_3)(bool) | احصل على مجموعة من الرسائل . |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_2)(MailQuery) | احصل على مجموعة من الرسائل . |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_1)(MessageKind) | احصل على مجموعة من الرسائل . |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_4)(int, int) | الحصول على مجموعة الرسائل . |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder)(string) | الحصول على مجلد فرعي . |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder_1)(string, bool) | يحصل على المجلد الفرعي . |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders)() | الحصول على مجموعة من المجلدات الفرعية. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_1)(FolderKind) | الحصول على مجموعة من المجلدات الفرعية. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_2)(MailQuery) | الحصول على مجموعة من المجلدات الفرعية. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith)(FolderInfo) | يدمج المجلد مع المجلد من pst آخر . |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith_1)(FolderInfo, bool) | يدمج المجلد مع المجلد من pst آخر. يتم استدعاء حدث OnItemMoved في كل من الرسائل والأدلة. |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents)(FolderInfo) | نقل المحتويات إلى مجلد جديد. |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders)(FolderInfo) | نقل المجلدات الفرعية إلى مجلد أصل جديد. |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath)() | استرداد المسار الكامل للمجلد داخل ملف PST. |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage)(string, MapiMessageItemBase) | يقوم بتحديث الرسالة في المجلد . |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
