---
title: MsgSaveOptions
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 590
url: /python-net/aspose.email/msgsaveoptions/
---

## MsgSaveOptions class

This class allows the user to specify additional settings when saving a MailMessage in the Msg(ASCII) and Msg(Unicode) format.

The MsgSaveOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MsgSaveOptions(save_type)|Initializes a new instance of the MsgSaveOptions class|
## Properties
| Name | Description |
| :- | :- |
|mail_message_save_type|Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format.<br/>            The default value is Eml.|
|default_eml|Gets options with default values for saving message to Eml format.|
|default_emlx|Gets options with default values for saving message to Emlx format.|
|default_msg|Gets options with default values for saving message to Msg(ASCII) format.|
|default_msg_unicode|Gets options with default values for saving message to Msg(Unicode) format.|
|default_oft|Gets options with default values for saving message to Outlook template (Oft) format.|
|default_mhtml|Gets options with default values for saving message to Mhtml format.|
|default_html|Gets options with default values for saving message to Html format.|
|preserve_original_dates|Gets or sets a value indicating whether it is necessary to generate <br/>            new saving and modification dates when saving a message.<br/>            By default the value is true, meaning the creation and modification dates will be not set to DateTime.Now.|
|preserve_signature|Set to true, if signature is to be preserved.|
|save_as_template|Set to true, if need to be saved as Outlook File Template(OFT format).|
## Methods
| Name | Description |
| :- | :- |
|create_save_options(save_type)|  |

### See Also

* namespace [aspose.email](/email/python-net/aspose.email/)
* assembly [Aspose.Email](/email/python-net/)

