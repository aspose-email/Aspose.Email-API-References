---
title: IGraphClient
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 90
url: /python-net/aspose.email.clients.graph/igraphclient/
---

## IGraphClient class

Represents the interface for Exchange REST client.

The IGraphClient type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|multiple_services_token_provider|Gets or sets an object allows to retrieve OAuth access token.|
|token_provider|Gets or sets an object allows to retrieve OAuth access token.|
|timeout|Gets or sets the number of milliseconds to wait before the operation times out.<br/>            The default value is 100,000 milliseconds (100 seconds).|
|tenant_id|Gets or sets tenant identifier|
|resource_id|Gets or sets resource id.<br/>            For instance for users it may be user principal name (UPN) or user id|
|resource|Gets or sets resource type.|
## Methods
| Name | Description |
| :- | :- |
|list_folders()|  |
|list_folders(id)|  |
|create_folder(folder_name)|  |
|create_folder(parent_folder_id, folder_name)|  |
|list_messages(id)|  |
|list_messages(id, page, query)|  |
|update_message(message)|  |
|update_message(message, update_settings)|  |
|send(item_id)|  |
|send(message)|  |
|send(message, save_to_sent_items)|  |
|create_or_update_override(sender, classify_as)|  |
|create_or_update_override(classification_override)|  |
|delete(id)|  |
|get_folder(id)|  |
|update_folder(folder_info)|  |
|copy_folder(new_parent_id, item_id)|  |
|move_folder(new_parent_id, item_id)|  |
|create_attachment(parent_id, attachment)|  |
|fetch_attachment(id)|  |
|delete_attachment(id)|  |
|list_attachments(id)|  |
|fetch_message(id)|  |
|create_message(folder_id, message)|  |
|copy_message(new_parent_id, item_id)|  |
|move_message(new_parent_id, item_id)|  |
|set_read(item_id)|  |
|list_categories()|  |
|create_category(display_name, preset)|  |
|update_category(category)|  |
|fetch_category(item_id)|  |
|update_override(classification_override)|  |
|list_overrides()|  |
|fetch_notebook(item_id)|  |
|create_notebook(notebook)|  |
|list_notebooks()|  |
|copy_notebook(item_id, group_id, rename_as)|  |
|get_one_note_operation_status(operation_id)|  |

### See Also

* namespace [aspose.email.clients.graph](/python-net/aspose.email.clients.graph/)
* assembly [Aspose.Email](/python-net/)

