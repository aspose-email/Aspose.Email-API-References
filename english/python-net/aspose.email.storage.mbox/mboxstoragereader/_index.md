---
title: MboxStorageReader
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 40
url: /python-net/aspose.email.storage.mbox/mboxstoragereader/
---

## MboxStorageReader class

Represents an MBOX file and provides methods for reading and extracting messages.<br/>            The MBOX file format is used for storing a collection of email messages.

The MboxStorageReader type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|base_stream|Gets the base stream.|
|current_data_size|Gets the number of bytes that is read by ReadNextMessage method.|
## Methods
| Name | Description |
| :- | :- |
|create_reader(stream, options)|  |
|create_reader(file_name, options)|  |
|enumerate_messages()|  |
|enumerate_messages(query)|  |
|enumerate_messages(start_index, count)|  |
|enumerate_messages(options)|  |
|enumerate_messages(options, query)|  |
|enumerate_messages(options, start_index, count)|  |
|enumerate_message_info()|  |
|enumerate_message_info(query)|  |
|enumerate_message_info(start_index, count)|  |
|split_into(chunk_size, output_path)|  |
|split_into(chunk_size, output_path, part_file_name_prefix)|  |
|read_next_message()|  |
|read_next_message(from_marker)|  |
|read_next_message(options)|  |
|read_next_message(from_marker, options)|  |
|extract_message(id, options)|  |
|next_message()|  |
|get_total_items_count()|  |

### See Also

* namespace [aspose.email.storage.mbox](/email/python-net/aspose.email.storage.mbox/)
* assembly [Aspose.Email](/email/python-net/)

