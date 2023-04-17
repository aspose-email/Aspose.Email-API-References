---
title: MhtSaveOptions
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 530
url: /python-net/aspose.email/mhtsaveoptions/
---

## MhtSaveOptions class

Allows to specify additional options when saving MailMessage to Mhtml format.

The MhtSaveOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MhtSaveOptions()|Initializes a new instance of this class that can be used to save a MailMessage in the Mhtml format.|
## Properties
| Name | Description |
| :- | :- |
|mail_message_save_type|  |
|default_eml|  |
|default_msg|  |
|default_msg_unicode|  |
|default_mhtml|  |
|default_html|  |
|rendered_contact_fields|Defines groups of Contact fields which will be included in output mhtml.<br/>            Default value is ContactFieldsSet.AllExisting.|
|css_styles|Gets or sets the additional css styles for the formatter.|
|default_page_header_format|Default page header format.|
|default_header_format|Default header line format.|
|before_headers_format|Before headers format.|
|after_headers_format|After headers format.|
|rendering_headers|Gets list of headers for rendering.|
|timeout|Limits the time in milliseconds of formatting message while saving in Mht.<br/>            Default value 3 sek.|
|mht_format_options|Defines additional options when saving in MHTML format.<br/>            Default value is MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments.|
|preserve_original_boundaries|Defines whether need keep original boundaries in mail message when saving or not.|
|check_body_content_encoding|Defines whether need check message body content encoding when saving. By default the value is false.|
|save_attachments|Gets or sets a value indicating whether to save attachments.|
|preserve_original_date|Defines whether need keep original date in mail message when saving or not.<br/>            Default value is true.|
|skip_inline_images|Defines whether skip references on images at saving in mhtml or not.<br/>            Default value is false.|
|saved_headers|Gets list of headers which will be present in saved mhtml content.<br/>            Default value is empty list.|
## Methods
| Name | Description |
| :- | :- |
|create_save_options(save_type)|  |

### See Also

* namespace [aspose.email](/email/python-net/aspose.email/)
* assembly [Aspose.Email](/email/python-net/)

