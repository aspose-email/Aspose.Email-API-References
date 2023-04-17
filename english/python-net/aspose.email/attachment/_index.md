---
title: Attachment
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 130
url: /python-net/aspose.email/attachment/
---

## Attachment class

Represents an e-mail attachment.

The Attachment type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Attachment(file_name)|Initializes a new instance of the Attachment class|
|Attachment(file_name, media_type)|Initializes a new instance of the Attachment class|
|Attachment(file_name, content_type)|Initializes a new instance of the Attachment class|
|Attachment(content_stream, name)|Initializes a new instance of the Attachment class|
|Attachment(content_stream, name, media_type)|Initializes a new instance of the Attachment class|
|Attachment(content_stream, content_type)|Initializes a new instance of the Attachment class|
## Properties
| Name | Description |
| :- | :- |
|content_stream|Gets or sets the content stream.|
|content_id|Gets or sets the content id.|
|headers|Gets headers collection of attachment.|
|content_type|Gets or sets the type of the content.|
|transfer_encoding|Gets or sets the transfer encoding.|
|is_tnef|Gets a value indicating whether the attachment is TNEF formatted message.|
|is_embedded_message|Gets a value indicating whether the attachment is an embedded message.|
|name|Gets or sets an attachment name|
|name_encoding|Gets or sets an encoding of attachment name|
|content_disposition|Gets Content-Disposition header|
|is_uri|Gets a value indicating whether attachment is URI-attachment.|
|preferred_text_encoding|Gets or sets a preferred text encoding|
## Methods
| Name | Description |
| :- | :- |
|save(stream)|  |
|save(file_name)|  |
|create_attachment_from_string(content, name)|  |
|create_attachment_from_string(content, name, content_encoding, media_type)|  |
|create_attachment_from_string(content, content_type)|  |

### See Also

* namespace [aspose.email](/email/python-net/aspose.email/)
* assembly [Aspose.Email](/email/python-net/)

