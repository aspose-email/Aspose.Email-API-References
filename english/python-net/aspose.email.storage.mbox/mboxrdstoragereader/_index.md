---
title: MboxrdStorageReader
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 70
url: /python-net/aspose.email.storage.mbox/mboxrdstoragereader/
---

## MboxrdStorageReader class

Represents mboxrd format storage reader, this format is being used by Thunderbird and other mail clients.

The MboxrdStorageReader type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MboxrdStorageReader(stream, options)|Initializes a new instance of the MboxrdStorageReader class|
|MboxrdStorageReader(file_name, options)|Initializes a new instance of the MboxrdStorageReader class|
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
|read_next_message(from_marker)|  |
|read_next_message(options)|  |
|read_next_message(from_marker, options)|  |
|read_next_message()|  |
|extract_message(id, options)|  |
|next_message()|  |
|get_total_items_count()|  |

### See Also

* namespace [aspose.email.storage.mbox](/email/python-net/aspose.email.storage.mbox/)
* assembly [Aspose.Email](/email/python-net/)

