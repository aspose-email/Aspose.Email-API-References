---
title: EmlSaveOptions
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 190
url: /email/python-net/aspose.email/emlsaveoptions/
---

## EmlSaveOptions class

Allows to specify additional options when saving MailMessage to Eml and Emlx format.

The EmlSaveOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|EmlSaveOptions(save_type)|Initializes a new instance of the EmlSaveOptions class|
## Properties
| Name | Description |
| :- | :- |
|mail_message_save_type|Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format.<br/>            The default value is Eml.|
|default_eml|Gets options with default values for saving message to Eml format.|
|default_msg|Gets options with default values for saving message to Msg(ASCII) format.|
|default_msg_unicode|Gets options with default values for saving message to Msg(Unicode) format.|
|default_mhtml|Gets options with default values for saving message to Mhtml format.|
|default_html|Gets options with default values for saving message to Html format.|
|file_compatibility_mode|Defines inner conversions,that are necessarily to be done when saving a message.<br/>            The default value is FileCompatibilityMode.None.|
|preserve_signed_content|Gets or sets a value indicating whether it is necessary to save signed message<br/>            without changes of content to provide correctly structure of digital sign.<br/>            By default the value is false.|
|check_body_content_encoding|Defines whether need check message body content encoding when saving. By default the value is false.|
|preserve_embedded_message_format|Gets or sets a value indicating whether it is necessary to preserve MSG format of <br/>            embedded message at converting to MailMessage. By default the value is false.|
## Methods
| Name | Description |
| :- | :- |
|create_save_options(save_type)|  |

### See Also

* namespace [aspose.email](/email/python-net/aspose.email/)
* assembly [Aspose.Email](/slides/python-net/)

