---
title: FolderInfo
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa información sobre la carpeta personal en PST.
type: docs
weight: 20160
url: /es/net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

Representa información sobre la carpeta personal en PST.

```csharp
public sealed class FolderInfo
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FolderInfo](folderinfo)() | Inicializa una nueva instancia del[`FolderInfo`](../folderinfo) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass) { get; } | Obtiene la clase contenedora del objeto de carpeta. |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount) { get; } | Obtiene el número total de elementos en la carpeta. |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount) { get; } | Obtiene el número de elementos no leídos en la carpeta. |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname) { get; } | Obtiene el nombre para mostrar de la carpeta. |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid) { get; } | Obtiene el ID de entrada. |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring) { get; } | Obtiene la representación de cadena de la entrada ID. |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders) { get; } | Obtiene un valor que indica si el objeto Carpeta tiene subcarpetas. |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime) { get; } | Obtiene la hora de la última modificación. |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties) { get; } | Obtiene las propiedades de la carpeta. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile)(string, string) | Agrega un archivo a la carpeta pst. |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem)(IMapiMessageItem) | Agrega el objeto IMapiMessageItem a la carpeta. |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage)(MapiMessage) | Agrega un nuevo mensaje a la carpeta. |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages)(IEnumerable&lt;MapiMessage&gt;) | Proporciona la adición de mensajes en modo masivo. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder)(string) | Agrega la nueva subcarpeta. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_1)(string, bool) | Agrega la nueva subcarpeta. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_2)(string, string) | Agrega la nueva subcarpeta. |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass)(string) | Cambia la clase del contenedor. |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname)(string) | Cambia el nombre para mostrar. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages)(MapiPropertyCollection) | Cambia todos los mensajes en la carpeta. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | Cambia los mensajes en la carpeta. |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem)(byte[]) | Elimina el elemento (carpeta o mensaje) por su Id. de entrada. |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems)(IEnumerable&lt;string&gt;) | Elimina los mensajes secundarios. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders)() | Expone el enumerador, que admite una iteración de subcarpetas en la carpeta. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders_1)(FolderKind) | Expone el enumerador, que admite una iteración de subcarpetas en la carpeta. |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages)() | Expone el enumerador, que admite una iteración de mensajes en la carpeta. |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects)() | Expone el enumerador, que admite una iteración de mensajes en la carpeta. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages)() | Expone el enumerador, que admite una iteración de mensajes en la carpeta. |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid)() | Enumera el ID de entrada de los mensajes. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents)() | Obtener colección de mensajes. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_3)(bool) | Obtener colección de mensajes. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_2)(MailQuery) | Obtener colección de mensajes. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_1)(MessageKind) | Obtener colección de mensajes. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_4)(int, int) | Obtiene la colección de mensajes. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder)(string) | Obtener subcarpeta. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder_1)(string, bool) | Obtiene la subcarpeta. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders)() | Obtiene la colección de subcarpetas. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_1)(FolderKind) | Obtiene la colección de subcarpetas. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_2)(MailQuery) | Obtiene la colección de subcarpetas. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith)(FolderInfo) | Fusiona la carpeta con la carpeta de otro pst. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith_1)(FolderInfo, bool) | Fusiona la carpeta con la carpeta de otro pst. El evento OnItemMoved se llama tanto en mensajes como en directorios. |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents)(FolderInfo) | Mueve el contenido a una nueva carpeta. |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders)(FolderInfo) | Mueve las subcarpetas a una nueva carpeta principal. |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath)() | Recupera la ruta completa de la carpeta dentro del archivo PST. |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage)(string, MapiMessageItemBase) | Actualiza el mensaje en la carpeta. |

### Ver también

* espacio de nombres [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
