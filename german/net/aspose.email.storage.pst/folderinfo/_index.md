---
title: FolderInfo
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt Informationen über persönliche Ordner in PST dar.
type: docs
weight: 20160
url: /de/net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

Stellt Informationen über persönliche Ordner in PST dar.

```csharp
public sealed class FolderInfo
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [FolderInfo](folderinfo)() | Initialisiert eine neue Instanz von[`FolderInfo`](../folderinfo) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass) { get; } | Ruft die Containerklasse des Ordnerobjekts ab. |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount) { get; } | Ruft die Gesamtzahl der Elemente im Ordner ab. |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount) { get; } | Ruft die Anzahl der ungelesenen Elemente im Ordner ab. |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname) { get; } | Ruft den Anzeigenamen des Ordners ab. |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid) { get; } | Ruft die Eintrags-ID ab. |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring) { get; } | Ruft die Zeichenfolgendarstellung der Eintrags-ID ab. |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders) { get; } | Ruft einen Wert ab, der angibt, ob das Ordnerobjekt Unterordner hat. |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime) { get; } | Ruft die letzte Änderungszeit ab. |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties) { get; } | Ruft die Ordnereigenschaften ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile)(string, string) | Fügt eine Datei in den PST-Ordner hinzu. |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem)(IMapiMessageItem) | Fügt das IMapiMessageItem-Objekt dem Ordner hinzu. |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage)(MapiMessage) | Fügt dem Ordner eine neue Nachricht hinzu. |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages)(IEnumerable&lt;MapiMessage&gt;) | Ermöglicht das Hinzufügen von Nachrichten in einem Massenmodus. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder)(string) | Fügt den neuen Unterordner hinzu. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_1)(string, bool) | Fügt den neuen Unterordner hinzu. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_2)(string, string) | Fügt den neuen Unterordner hinzu. |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass)(string) | Ändert die Containerklasse. |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname)(string) | Ändert den Anzeigenamen. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages)(MapiPropertyCollection) | Ändert alle Nachrichten im Ordner. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | Ändert die Nachrichten im Ordner. |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem)(byte[]) | Löscht das Element (Ordner oder Nachricht) anhand seiner Eintrags-ID. |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems)(IEnumerable&lt;string&gt;) | Löscht die untergeordneten Nachrichten. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders)() | Macht den Enumerator verfügbar, der eine Iteration von Unterordnern im Ordner unterstützt. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders_1)(FolderKind) | Macht den Enumerator verfügbar, der eine Iteration von Unterordnern im Ordner unterstützt. |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages)() | Macht den Enumerator verfügbar, der eine Iteration von Nachrichten im Ordner unterstützt. |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects)() | Macht den Enumerator verfügbar, der eine Iteration von Nachrichten im Ordner unterstützt. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages)() | Macht den Enumerator verfügbar, der eine Iteration von Nachrichten im Ordner unterstützt. |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid)() | Listet die Eintrags-ID von Nachrichten auf. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents)() | Nachrichtensammlung abrufen. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_3)(bool) | Nachrichtensammlung abrufen. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_2)(MailQuery) | Nachrichtensammlung abrufen. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_1)(MessageKind) | Nachrichtensammlung abrufen. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_4)(int, int) | Ruft die Sammlung von Nachrichten ab. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder)(string) | Unterordner abrufen. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder_1)(string, bool) | Ruft den Unterordner ab. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders)() | Ruft eine Sammlung von Unterordnern ab. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_1)(FolderKind) | Ruft eine Sammlung von Unterordnern ab. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_2)(MailQuery) | Ruft eine Sammlung von Unterordnern ab. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith)(FolderInfo) | Führt den Ordner mit dem Ordner einer anderen pst zusammen. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith_1)(FolderInfo, bool) | Führt den Ordner mit dem Ordner einer anderen PST zusammen. Das OnItemMoved-Ereignis wird sowohl für Nachrichten als auch für Verzeichnisse aufgerufen. |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents)(FolderInfo) | Verschiebt den Inhalt in einen neuen Ordner. |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders)(FolderInfo) | Verschiebt die Unterordner in einen neuen übergeordneten Ordner. |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath)() | Ruft den vollständigen Pfad des Ordners in der PST-Datei ab. |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage)(string, MapiMessageItemBase) | Aktualisiert die Nachricht im Ordner. |

### Siehe auch

* namensraum [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
