---
title: FolderInfo
second_title: Aspose.Email för .NET API-referens
description: Representerar information om personlig mapp i PST.
type: docs
weight: 20160
url: /sv/net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

Representerar information om personlig mapp i PST.

```csharp
public sealed class FolderInfo
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [FolderInfo](folderinfo)() | Initierar en ny instans av[`FolderInfo`](../folderinfo) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass) { get; } | Hämtar containerklass för mappobjektet. |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount) { get; } | Hämtar det totala antalet objekt i mappen. |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount) { get; } | Hämtar antalet olästa objekt i mappen. |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname) { get; } | Hämtar visningsnamnet på mappen. |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid) { get; } | Hämtar postens ID. |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring) { get; } | Hämtar strängrepresentation av post-ID. |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders) { get; } | Får ett värde som indikerar om Folder-objektet har några undermappar. |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime) { get; } | Hämtar den senaste ändringstiden. |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties) { get; } | Hämtar mappegenskaperna. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile)(string, string) | Lägger till en fil i pst-mappen. |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem)(IMapiMessageItem) | Lägger till IMapiMessageItem-objektet i mappen. |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage)(MapiMessage) | Lägger till ett nytt meddelande i mappen. |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages)(IEnumerable&lt;MapiMessage&gt;) | Ger meddelandetillägg i ett bulkläge. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder)(string) | Lägger till den nya undermappen. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_1)(string, bool) | Lägger till den nya undermappen. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_2)(string, string) | Lägger till den nya undermappen. |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass)(string) | Ändrar behållarklassen. |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname)(string) | Ändrar visningsnamnet. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages)(MapiPropertyCollection) | Ändrar alla meddelanden i mappen. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | Ändrar meddelanden i mappen. |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem)(byte[]) | Tar bort objektet (mapp eller meddelande) med dess entryId. |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems)(IEnumerable&lt;string&gt;) | Tar bort underordnade meddelanden. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders)() | Visar enumeratorn, som stöder en iteration av undermappar i mappen. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders_1)(FolderKind) | Visar enumeratorn, som stöder en iteration av undermappar i mappen. |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages)() | Visar enumeratorn, som stöder en iteration av meddelanden i mappen. |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects)() | Visar enumeratorn, som stöder en iteration av meddelanden i mappen. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages)() | Visar enumeratorn, som stöder en iteration av meddelanden i mappen. |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid)() | Räknar upp post-ID för meddelanden. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents)() | Få samling av meddelanden. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_3)(bool) | Få samling av meddelanden. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_2)(MailQuery) | Få samling av meddelanden. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_1)(MessageKind) | Få samling av meddelanden. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_4)(int, int) | Hämtar samlingen av meddelanden. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder)(string) | Hämta undermapp. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder_1)(string, bool) | Hämtar undermappen. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders)() | Får samling av undermappar. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_1)(FolderKind) | Får samling av undermappar. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_2)(MailQuery) | Får samling av undermappar. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith)(FolderInfo) | Slår ihop mappen med mappen från en annan pst. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith_1)(FolderInfo, bool) | Slår ihop mappen med mappen från en annan pst. OnItemMoved-händelsen anropas på både meddelanden och kataloger. |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents)(FolderInfo) | Flyttar innehållet till en ny mapp. |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders)(FolderInfo) | Flyttar undermapparna till en ny överordnad mapp. |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath)() | Hämtar hela sökvägen till mappen i PST-filen. |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage)(string, MapiMessageItemBase) | Uppdaterar meddelandet i mappen. |

### Se även

* namnutrymme [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
