---
title: FolderInfo
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente des informations sur le dossier personnel dans PST.
type: docs
weight: 20160
url: /fr/net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

Représente des informations sur le dossier personnel dans PST.

```csharp
public sealed class FolderInfo
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [FolderInfo](folderinfo)() | Initialise une nouvelle instance du[`FolderInfo`](../folderinfo) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass) { get; } | Obtient la classe de conteneur de l'objet dossier. |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount) { get; } | Obtient le nombre total d'éléments dans le dossier. |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount) { get; } | Obtient le nombre d'éléments non lus dans le dossier. |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname) { get; } | Obtient le nom d'affichage du dossier. |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid) { get; } | Obtient l'ID d'entrée. |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring) { get; } | Obtient la représentation sous forme de chaîne de l'ID d'entrée. |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders) { get; } | Obtient une valeur indiquant si l'objet Dossier contient des sous-dossiers. |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime) { get; } | Obtient l'heure de la dernière modification. |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties) { get; } | Obtient les propriétés du dossier. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile)(string, string) | Ajoute un fichier dans le dossier pst. |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem)(IMapiMessageItem) | Ajoute l'objet IMapiMessageItem dans le dossier. |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage)(MapiMessage) | Ajoute un nouveau message dans le dossier. |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages)(IEnumerable&lt;MapiMessage&gt;) | Fournit l'ajout de messages en mode groupé. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder)(string) | Ajoute le nouveau sous-dossier. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_1)(string, bool) | Ajoute le nouveau sous-dossier. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_2)(string, string) | Ajoute le nouveau sous-dossier. |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass)(string) | Modifie la classe du conteneur. |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname)(string) | Modifie le nom d'affichage. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages)(MapiPropertyCollection) | Modifie tous les messages du dossier. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | Modifie les messages dans le dossier. |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem)(byte[]) | Supprime l'élément (dossier ou message) par son entryId. |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems)(IEnumerable&lt;string&gt;) | Supprime les messages enfants. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders)() | Expose l'énumérateur, qui prend en charge une itération de sous-dossiers dans le dossier. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders_1)(FolderKind) | Expose l'énumérateur, qui prend en charge une itération de sous-dossiers dans le dossier. |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages)() | Expose l'énumérateur, qui prend en charge une itération de messages dans le dossier. |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects)() | Expose l'énumérateur, qui prend en charge une itération de messages dans le dossier. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages)() | Expose l'énumérateur, qui prend en charge une itération de messages dans le dossier. |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid)() | Enumère l'entryID des messages. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents)() | Obtenir une collection de messages. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_3)(bool) | Obtenir une collection de messages. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_2)(MailQuery) | Obtenir une collection de messages. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_1)(MessageKind) | Obtenir une collection de messages. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_4)(int, int) | Obtient la collection de messages. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder)(string) | Obtenir le sous-dossier. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder_1)(string, bool) | Obtient le sous-dossier. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders)() | Obtient une collection de sous-dossiers. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_1)(FolderKind) | Obtient une collection de sous-dossiers. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_2)(MailQuery) | Obtient une collection de sous-dossiers. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith)(FolderInfo) | Fusionne le dossier avec le dossier d'un autre pst. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith_1)(FolderInfo, bool) | Fusionne le dossier avec le dossier d'un autre pst. L'événement OnItemMoved est appelé à la fois sur les messages et sur les répertoires. |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents)(FolderInfo) | Déplace le contenu vers un nouveau dossier. |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders)(FolderInfo) | Déplace les sous-dossiers vers un nouveau dossier parent. |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath)() | Récupère le chemin complet du dossier dans le fichier PST. |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage)(string, MapiMessageItemBase) | Met à jour le message dans le dossier. |

### Voir également

* espace de noms [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
