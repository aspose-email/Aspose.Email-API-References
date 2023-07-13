---
title: MailMessage
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 470
url: /python-net/aspose.email/mailmessage/
---

## MailMessage class



The MailMessage type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MailMessage(from_address, to)|Initializes a new instance of the MailMessage class|
|MailMessage()|Initializes a new instance of the [MailMessage](/email/python-net/aspose.email/mailmessage/) class|
|MailMessage(from_address, to, subject, body)|Initializes a new instance of the MailMessage class|
|MailMessage(from_address, to)|Initializes a new instance of the MailMessage class|
## Properties
| Name | Description |
| :- | :- |
|preamble|Gets or sets a preamble text.<br/>            It is located before the first boundary<br/>            and generally includes an explanatory note to non-MIME conformant readers.|
|epilogue|Gets or sets an epilogue text.<br/>            It is located after the last boundary.|
|preferred_text_encoding|Gets or sets preferred encoding for all text properties|
|from_address|Gets or sets the from address|
|sender|Gets or sets sender address|
|reverse_path|Gets or sets ReversePath address|
|reply_to_list|Gets or sets the list of addresses <br/>            to reply to for the mail message|
|to|Gets or sets the address collection that contains <br/>            the recipients of message|
|bcc|Gets or sets the address collection <br/>            that contains the BCC recipients of message|
|cc|Gets or sets the address collection <br/>            that contains the CC recipients|
|priority|Gets or sets the priority of message|
|sensitivity|Gets or sets the sensitivity of message|
|delivery_notification_options|Gets or sets the delivery notifications|
|subject|Gets or sets the subject line|
|time_zone_offset|Gets or sets the Coordinated Universal Time (UTC) <br/>            offset for the message dates.<br/>            This property defines the time zone difference, <br/>            between the local time and UTC.|
|date|Gets or sets the date of message|
|message_id|Gets or sets the message id|
|x_mailer|Gets or sets the X-Mailer the software <br/>            that created the e-mail message|
|subject_encoding|Gets or sets the encoding of subject|
|headers|Gets headers collection of message|
|html_body|Gets or sets html body|
|body|Gets or sets the plain text representation of message's body.<br/>            If the text/plain part is present in a message, the propery returns its text data.<br/>            Otherwise, property returns the text content of the HtmlBody property without html markup.|
|html_body_text|Gets the message htmlbody as plain text.|
|body_encoding|Gets or sets encoding of body|
|is_body_html|Gets or sets a value indicating <br/>            whether the message body is in Html|
|is_signed|Gets a value indicating whether the message is signed.|
|is_encrypted|Gets a value indicating whether the message is encrypted.|
|is_read_only|Gets a value indicating <br/>            whether the message is read only|
|item_id|Represents identification information about message in a mailbox.|
|is_draft|Gets or sets value that indicates whether or not a message has been sent.|
|attachments|Gets the collection of attachments of message|
|linked_resources|Gets the collection of linked resources of message|
|alternate_views|Gets the collection of alternate views of message|
|body_type|Gets the type of the body.|
|original_is_tnef|Gets a value indicating <br/>            whether original EML message is in TNEF format.|
|read_receipt_to|Gets or sets the read receipt address.|
## Methods
| Name | Description |
| :- | :- |
|load(file_name)|  |
|load(stream)|  |
|load(file_name, options)|  |
|load(stream, options)|  |
|validate_message(file_name)|  |
|validate_message(stream)|  |
|save(file_name)|  |
|save(file_name, options)|  |
|save(stream, options)|  |
|save(stream)|  |
|attach_signature(certificate, detached)|  |
|attach_signature(certificate)|  |
|check_signature(file_name)|  |
|check_signature(stream)|  |
|check_signature()|  |
|decrypt()|  |
|decrypt(certificate)|  |
|encrypt(certificate)|  |
|encrypt(certificates)|  |
|import_from_stream(stream)|  |
|clone()|  |
|recompose_tnef_content()|  |
|set_html_body(value, detect_encoding)|  |
|get_html_body_text(show_url)|  |
|create_read_receipt(from_address, body_text)|  |
|add_alternate_view(view)|  |
|add_attachment(attachment)|  |
|remove_signature()|  |
|check_bounced()|  |

### See Also

* namespace [aspose.email](/email/python-net/aspose.email/)
* assembly [Aspose.Email](/email/python-net/)

