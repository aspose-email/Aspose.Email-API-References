---
title: FolderInfo
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta informazioni sulla cartella personale in PST.
type: docs
weight: 20160
url: /it/net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

Rappresenta informazioni sulla cartella personale in PST.

```csharp
public sealed class FolderInfo
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FolderInfo](folderinfo)() | Inizializza una nuova istanza di[`FolderInfo`](../folderinfo) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass) { get; } | Ottiene la classe contenitore dell'oggetto cartella. |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount) { get; } | Ottiene il numero totale di elementi nella cartella. |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount) { get; } | Ottiene il numero di elementi non letti nella cartella. |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname) { get; } | Ottiene il nome visualizzato della cartella. |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid) { get; } | Ottiene l'ID voce. |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring) { get; } | Ottiene la rappresentazione di stringa dell'ID voce. |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders) { get; } | Ottiene un valore che indica se l'oggetto Folder ha delle sottocartelle. |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime) { get; } | Ottiene l'ora dell'ultima modifica. |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties) { get; } | Ottiene le proprietà della cartella. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile)(string, string) | Aggiunge un file nella cartella pst. |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem)(IMapiMessageItem) | Aggiunge l'oggetto IMapiMessageItem nella cartella. |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage)(MapiMessage) | Aggiunge un nuovo messaggio nella cartella. |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages)(IEnumerable&lt;MapiMessage&gt;) | Fornisce l'aggiunta di messaggi in modalità in blocco. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder)(string) | Aggiunge la nuova sottocartella. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_1)(string, bool) | Aggiunge la nuova sottocartella. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_2)(string, string) | Aggiunge la nuova sottocartella. |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass)(string) | Modifica la classe del contenitore. |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname)(string) | Modifica il nome visualizzato. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages)(MapiPropertyCollection) | Modifica tutti i messaggi nella cartella. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | Modifica i messaggi nella cartella. |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem)(byte[]) | Elimina l'elemento (cartella o messaggio) in base al suo entryId. |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems)(IEnumerable&lt;string&gt;) | Elimina i messaggi figlio. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders)() | Espone l'enumeratore, che supporta un'iterazione delle sottocartelle nella cartella. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders_1)(FolderKind) | Espone l'enumeratore, che supporta un'iterazione delle sottocartelle nella cartella. |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages)() | Espone l'enumeratore, che supporta un'iterazione dei messaggi nella cartella. |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects)() | Espone l'enumeratore, che supporta un'iterazione dei messaggi nella cartella. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages)() | Espone l'enumeratore, che supporta un'iterazione dei messaggi nella cartella. |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid)() | Enumera l'ID voce dei messaggi. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents)() | Ottieni raccolta di messaggi. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_3)(bool) | Ottieni raccolta di messaggi. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_2)(MailQuery) | Ottieni raccolta di messaggi. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_1)(MessageKind) | Ottieni raccolta di messaggi. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_4)(int, int) | Ottiene la raccolta di messaggi. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder)(string) | Ottieni sottocartella. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder_1)(string, bool) | Ottiene la sottocartella. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders)() | Ottiene la raccolta di sottocartelle. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_1)(FolderKind) | Ottiene la raccolta di sottocartelle. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_2)(MailQuery) | Ottiene la raccolta di sottocartelle. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith)(FolderInfo) | Unisce la cartella con la cartella di un altro pst. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith_1)(FolderInfo, bool) | Unisce la cartella con la cartella da un altro pst. L'evento OnItemMoved viene chiamato sia sui messaggi che sulle directory. |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents)(FolderInfo) | Sposta il contenuto in una nuova cartella. |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders)(FolderInfo) | Sposta le sottocartelle in una nuova cartella principale. |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath)() | Recupera il percorso completo della cartella all'interno del file PST. |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage)(string, MapiMessageItemBase) | Aggiorna il messaggio nella cartella. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
