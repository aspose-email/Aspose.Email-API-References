---
title: MsgLoadOptions
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 580
url: /python-net/aspose.email/msgloadoptions/
---

## MsgLoadOptions class

Allows to specify additional options when loading MailMessage from Msg format.

The MsgLoadOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MsgLoadOptions()|Initializes a new instance of this class that can be used to loading MailMessage from Msg format.|
## Properties
| Name | Description |
| :- | :- |
|preffered_text_encoding|Gets or sets preferred encoding for message.<br/>            Forcibly sets the preferred encoding for message subject and body.<br/>            The default value is null.|
|preferred_text_encoding|Gets or sets preferred encoding for message.<br/>            Forcibly sets the preferred encoding for message subject and body.<br/>            The default value is null.|
|message_format|Represents the mail message format.It can be in eml,msg or mhtml format.<br/>            The default value is Eml.|
|preserve_embedded_message_format|Gets or sets a value indicating whether it is necessary to preserve format of <br/>            embedded message at loading. By default the value is false.|
|preserve_tnef_attachments|Controls loading TNEF attachment behaviour. By default the value is false.|
|decode_clear_signed_content|Gets or sets a value indicating whether clear-signed message will be decoded.|
|decode_signed_content|Gets or sets a value indicating whether signed message will be decoded.|
|keep_original_email_addresses|Gets or sets a value indicating whether need keep original email address.|
|preserve_rtf_content|Gets or sets a value indicating whether need keep rtf body in MailMessage.|

### See Also

* namespace [aspose.email](/email/python-net/aspose.email/)
* assembly [Aspose.Email](/email/python-net/)

