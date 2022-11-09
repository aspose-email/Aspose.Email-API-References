---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 100
url: /python-net/aspose.email.storage.pst/personalstoragequerybuilder/
---

## PersonalStorageQueryBuilder class

Represents the builder of search expression<br/>            that used by pst.

The PersonalStorageQueryBuilder type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PersonalStorageQueryBuilder()|Initializes a new instance of the [PersonalStorageQueryBuilder](/python-net/aspose.email.storage.pst/personalstoragequerybuilder/) class.|
## Properties
| Name | Description |
| :- | :- |
|to|Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field.|
|text|Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message.|
|bcc|Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field.|
|body|Gets the field that allows to find messages that contain the specified string in the body of the message.|
|cc|Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field.|
|from_address|Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field.|
|subject|Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field.|
|default_encoding|Gets default encoding (charset) for query builder|
|internal_date|Gets the field that allows to find messages by internal date.|
|sent_date|Gets the field that allows to find messages by sent date.|
|only_folders_created_by_user|Gets folders that created by user, i.e. excludes all standard IPM folders.|
|message_id|Gets the field that allows to find messages that contain the specified string in the envelope structure's MessageId field.|
|message_class|Gets messages with an specified message class.|
|message_size|Search messages with an specified size.|
|importance|Search messages with an specified importance.|
|container_class|Gets folders with an specified message class.|
|folder_name|Search folders with an specified display name.|
|contents_count|Search folders with an specified contents count.|
|unread_contents_count|Search folders with an specified unread contents count.|
## Methods
| Name | Description |
| :- | :- |
|either(query1, query2)|  |
|get_query()|  |
|find_conversation_thread(related_message)|  |
|has_flags(flags)|  |
|has_no_flags(flags)|  |
|has_subfolders()|  |
|has_no_subfolders()|  |

### See Also

* namespace [aspose.email.storage.pst](/python-net/aspose.email.storage.pst/)
* assembly [Aspose.Email](/python-net/)

