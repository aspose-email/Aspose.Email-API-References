---
title: PersonalStorage
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 80
url: /email/python-net/aspose.email.storage.pst/personalstorage/
---

## PersonalStorage class

Represents Personal Storage Table (.pst) file.

The PersonalStorage type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|root_folder|Gets the root folder of PST.|
|store|Gets the PST message store.|
|format|Gets the file format.|
|can_write|Gets a value indicating whether <br/>            the current pst supports writing.|
|is_unicode|Gets a value indicating whether the PST file format is Unicode.<br/>            There are two versions of the PST file format: Unicode and ANSI.|
## Methods
| Name | Description |
| :- | :- |
|from_file(file_name)|  |
|from_file(file_name, writable)|  |
|from_file(file_name, load_options)|  |
|from_stream(stream, writable)|  |
|from_stream(stream, load_options)|  |
|from_stream(stream)|  |
|load(file_name)|  |
|load(stream)|  |
|create(file_name, version)|  |
|create(stream, version)|  |
|create(stream, version, leave_stream_open)|  |
|save_as(file_name, format)|  |
|save_as(stream, format)|  |
|extract_message(message_info)|  |
|extract_message(entry_id)|  |
|extract_message(entry_id)|  |
|enumerate_messages(entry_id)|  |
|enumerate_messages(entry_id, start_index, count)|  |
|extract_attachments(message_info)|  |
|extract_attachments(entry_id)|  |
|get_folder_by_id(entry_id)|  |
|get_folder_by_id(entry_id_string)|  |
|get_parent_folder(entry_id_string)|  |
|get_parent_folder(entry_id)|  |
|create_predefined_folder(name, default_folder, create_hierarchy)|  |
|create_predefined_folder(name, default_folder)|  |
|move_item(message, new_folder)|  |
|move_item(folder, new_folder)|  |
|merge_with(source_file_names)|  |
|merge_with(source_streams)|  |
|split_into(chunk_size, path)|  |
|split_into(criteria, path)|  |
|convert_to(format)|  |
|extract_property(entry_id, tag)|  |
|save_message_to_stream(entry_id, stream)|  |
|try_to_save_message(entry_id, stream)|  |
|try_to_get_folder_by_id(entry_id_string, folder)|  |
|find_subfolders(parent_entry_id)|  |
|find_messages(parent_entry_id)|  |
|get_predefined_folder(default_folder)|  |
|change_message(entry_id, updated_properties)|  |

### See Also

* namespace [aspose.email.storage.pst](/email/python-net/aspose.email.storage.pst/)
* assembly [Aspose.Email](/slides/python-net/)

