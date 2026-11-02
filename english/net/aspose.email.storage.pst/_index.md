---
title: Aspose.Email.Storage.Pst
second_title: Aspose.Email for .NET API Reference
description: Create read search and modify Outlook PST and OST files including their folders messages and attachments and split merge or convert them
type: docs
weight: 390
url: /net/aspose.email.storage.pst/
---
Create, read, search and modify Outlook PST and OST files, including their folders, messages and attachments, and split, merge or convert them.

## Classes

| Class | Description |
| --- | --- |
| [FolderCreationOptions](./foldercreationoptions/) | Options for creating a subfolder with `FolderInfo.AddSubFolder`: whether the name is a path, how names are compared, and the container class of the new folder. |
| [FolderInfo](./folderinfo/) | Represents a folder of a PST or OST file and gives access to its messages and subfolders. |
| [FolderInfoCollection](./folderinfocollection/) | A list of [`FolderInfo`](../aspose.email.storage.pst/folderinfo/) objects. |
| [ItemMovedEventArgs](./itemmovedeventargs/) | Provides data for the [`ItemMoved`](../aspose.email.storage.pst/folderinfo/itemmoved/) event. |
| [ItemMovedEventHandler](./itemmovedeventhandler/) | Represents the method that will handle an [`ItemMoved`](../aspose.email.storage.pst/folderinfo/itemmoved/) event. |
| [MessageAddedEventArgs](./messageaddedeventargs/) | Provides data for the [`MessageAdded`](../aspose.email.storage.pst/folderinfo/messageadded/) event. |
| [MessageAddedEventHandler](./messageaddedeventhandler/) | Represents the method that will handle a [`MessageAdded`](../aspose.email.storage.pst/folderinfo/messageadded/) event. |
| [MessageInfo](./messageinfo/) | Summary information about a message in a PST, such as its subject, recipients and message class, available without loading the whole message. |
| [MessageInfoCollection](./messageinfocollection/) | A list of [`MessageInfo`](../aspose.email.storage.pst/messageinfo/) objects. |
| [MessageStore](./messagestore/) | The message store of a PST: its top-level object, which holds the display name, password and other settings of the file. |
| [PersonalStorage](./personalstorage/) | Provides functionality to access and manipulate the PST (Personal Storage Table) files used by Microsoft Outlook. |
| [PersonalStorageLoadOptions](./personalstorageloadoptions/) | Options for opening a PST or OST file or stream. |
| [PersonalStorageQueryBuilder](./personalstoragequerybuilder/) | Builds search queries for the messages and folders of a PST. |
| [PstItemCategory](./pstitemcategory/) | A category used in a PST, with its name and color. |
| [RestoredItemEntry](./restoreditementry/) | A soft-deleted message found in a PST, with the folder it was in. |
| [SaveResult](./saveresult/) | The result of saving a message with [`TryToSaveMessage`](../aspose.email.storage.pst/personalstorage/trytosavemessage/). |
| [StorageProcessedEventArgs](./storageprocessedeventargs/) | Provides data for the [`StorageProcessed`](../aspose.email.storage.pst/personalstorage/storageprocessed/) event. |
| [StorageProcessedEventHandler](./storageprocessedeventhandler/) | Represents the method that will handle a [`StorageProcessed`](../aspose.email.storage.pst/personalstorage/storageprocessed/) event. |
| [StorageProcessingEventArgs](./storageprocessingeventargs/) | Provides data for the [`StorageProcessing`](../aspose.email.storage.pst/personalstorage/storageprocessing/) event. |
| [StorageProcessingEventHandler](./storageprocessingeventhandler/) | Represents the method that will handle a [`StorageProcessing`](../aspose.email.storage.pst/personalstorage/storageprocessing/) event. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [BackupOptions](./backupoptions/) | Options for backing up mail folders to a PST file. |
| [FileFormat](./fileformat/) | Defines the format of an Outlook data file. |
| [FileFormatVersion](./fileformatversion/) | Defines the version of a PST file: Unicode, used by Outlook 2003 and later, or ANSI, used by earlier versions. |
| [FolderKind](./folderkind/) | Defines kinds of PST folders. The values can be combined. |
| [MapiImportance](./mapiimportance/) | Defines the importance of a message. |
| [MapiSensitivity](./mapisensitivity/) | Defines the sensitivity of a message. |
| [MessageKind](./messagekind/) | Defines kinds of PST messages. The values can be combined. |
| [OutlookCategoryColor](./outlookcategorycolor/) | Represents the category colors used in Outlook. |
| [RestoreOptions](./restoreoptions/) | Options for restoring mail folders from a PST file. |
| [SaveStatus](./savestatus/) | Defines how completely a damaged message could be saved. |
| [StandardIpmFolder](./standardipmfolder/) | Defines the standard Outlook folders of a mailbox, also known as interpersonal message (IPM) folders. |


