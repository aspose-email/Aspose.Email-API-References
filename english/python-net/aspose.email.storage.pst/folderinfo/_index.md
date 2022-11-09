---
title: FolderInfo
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 10
url: /python-net/aspose.email.storage.pst/folderinfo/
---

## FolderInfo class

Represents information<br/>            about personal folder in PST.

The FolderInfo type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FolderInfo()|Initializes a new instance of the [FolderInfo](/python-net/aspose.email.storage.pst/folderinfo/) class.|
## Properties
| Name | Description |
| :- | :- |
|display_name|Gets the display name of folder.|
|content_count|Gets the total number of items in the folder.|
|content_unread_count|Gets the number of unread items in the folder.|
|has_sub_folders|Gets a value indicating whether the Folder object has any subfolders.|
|container_class|Gets container class of the folder object.|
|last_modification_time|Gets the last modification time.|
|entry_id|Gets the entry ID.|
|entry_id_string|Gets string representation of entry ID.|
|properties|Gets the folder properties.|
## Methods
| Name | Description |
| :- | :- |
|get_sub_folder(name)|  |
|get_sub_folder(name, ignore_case)|  |
|get_sub_folders()|  |
|get_sub_folders(kind)|  |
|get_sub_folders(query)|  |
|get_contents(try_to_read_corrupted_contents)|  |
|get_contents()|  |
|get_contents(kind)|  |
|get_contents(query)|  |
|get_contents(start_index, count)|  |
|enumerate_folders()|  |
|enumerate_folders(kind)|  |
|add_sub_folder(name, create_hierarchy)|  |
|add_sub_folder(name)|  |
|add_sub_folder(name, container_class)|  |
|merge_with(source_folder)|  |
|merge_with(source_folder, recursive_handler)|  |
|change_messages(entry_id_collection, updated_properties)|  |
|change_messages(updated_properties)|  |
|enumerate_messages()|  |
|enumerate_message_objects()|  |
|enumerate_mapi_messages()|  |
|enumerate_messages_entry_id()|  |
|retrieve_full_path()|  |
|add_message(message)|  |
|add_file(file_name, message_class)|  |
|add_mapi_message_item(item)|  |
|add_messages(messages)|  |
|move_contents(new_folder)|  |
|move_subfolders(new_folder)|  |
|delete_child_item(entry_id)|  |
|delete_child_items(entry_id_collection)|  |
|update_message(entry_id, updated_message)|  |
|change_container_class(container_class)|  |
|change_display_name(new_name)|  |

### See Also

* namespace [aspose.email.storage.pst](/python-net/aspose.email.storage.pst/)
* assembly [Aspose.Email](/python-net/)

