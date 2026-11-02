---
title: Aspose.Email
second_title: Aspose.Email for .NET API Reference
description: Core API for creating loading converting and saving email messages in EML MSG MHTML and HTML formats. Start here
type: docs
weight: 10
url: /net/aspose.email/
---
Core API for creating, loading, converting and saving email messages in EML, MSG, MHTML and HTML formats. Start here.

## Classes

| Class | Description |
| --- | --- |
| [AlternateView](./alternateview/) | One representation of the body of a message, such as plain text or HTML. A message can carry several, and the mail client shows the best one it supports. |
| [AlternateViewCollection](./alternateviewcollection/) | The alternate views of a message. |
| [AlternateViewRemovedEventArgs](./alternateviewremovedeventargs/) | Provides data for the event raised when an alternate view is removed from a message. |
| [AsposeArgumentException](./asposeargumentexception/) | The exception that is thrown when an argument passed to a method is not valid. |
| [AsposeArgumentNullException](./asposeargumentnullexception/) | The exception that is thrown when `null` is passed to a method that does not accept it. |
| [AsposeArgumentOutOfRangeException](./asposeargumentoutofrangeexception/) | The exception that is thrown when an argument is outside the range of allowed values. |
| [AsposeBadServerResponceException](./asposebadserverresponceexception/) | The exception that is thrown when a server returns a response the client cannot process. |
| [AsposeException](./asposeexception/) | The base class of the exceptions thrown by Aspose.Email. |
| [AsposeInvalidDataException](./asposeinvaliddataexception/) | The exception that is thrown when data is in an invalid format. |
| [AsposeInvalidEnumArgumentException](./asposeinvalidenumargumentexception/) | The exception that is thrown when an argument is not a valid value of its enumeration. |
| [AsposeInvalidOperationException](./asposeinvalidoperationexception/) | The exception that is thrown when a method call is not valid for the current state of the object. |
| [AsposeNotSupportedException](./asposenotsupportedexception/) | The exception that is thrown when a method or a parameter value is not supported, or a stream does not support the requested reading, seeking or writing. |
| [Attachment](./attachment/) | Represents an email attachment that can be added to a [`MailMessage`](../aspose.email/mailmessage/). This class provides functionality for managing attachment content, name, content type, encoding, and content disposition. It supports various attachment types including regular files, embedded messages (message/rfc822), and TNEF formatted messages. |
| [AttachmentBase](./attachmentbase/) | The base class of attachments, alternate views and linked resources: a MIME part with its content and headers. |
| [AttachmentCollection](./attachmentcollection/) | The attachments of a message. |
| [BuildVersionInfo](./buildversioninfo/) | Provides the name and version of the product. |
| [ConversionProgressEventHandler](./conversionprogresseventhandler/) | Represents the method that handles the progress events of a conversion. |
| [ElementProcessingException](./elementprocessingexception/) | The exception recorded when one element of a batch operation fails, such as one message of a set being fetched; the other elements are still processed. |
| [EmlLoadOptions](./emlloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from EML format. This class allows you to customize the loading behavior for specific EML features such as TNEF attachment handling and embedded message preservation. |
| [EmlSaveOptions](./emlsaveoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are saved to EML and EMLX format. This class allows you to customize the saving behavior for features such as embedded message format preservation, TNEF handling, signed message integrity, and boundary template configuration. |
| [EmlValidationError](./emlvalidationerror/) | An error found in the MIME structure of a message. |
| [EmlValidationErrorCollection](./emlvalidationerrorcollection/) | A collection of [`EmlValidationError`](../aspose.email/emlvalidationerror/) objects. |
| [EmlxLoadOptions](./emlxloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from EMLX format. This class inherits from [`LoadOptions`](../aspose.email/loadoptions/) and is specifically designed for Apple Mail EMLX file format. |
| [ExchangeException](./exchangeexception/) | The exception that is thrown when communication with Microsoft Exchange Server fails. |
| [FileCorruptedException](./filecorruptedexception/) | The exception that is thrown when a file is corrupted and cannot be read. |
| [FileFormatInfo](./fileformatinfo/) | Information about the format of a file, as detected by `FileFormatUtil.DetectFileFormat`. |
| [FormatNotSupportedException](./formatnotsupportedexception/) | The exception that is thrown when the format of a document is not recognized or not supported. |
| [GlobalFormattingOptions](./globalformattingoptions/) | The default header formats for every new [`HtmlSaveOptions`](../aspose.email/htmlsaveoptions/) and [`MhtSaveOptions`](../aspose.email/mhtsaveoptions/) object. |
| [GoogleClientException](./googleclientexception/) | The exception that is thrown when a request to a Google service fails. |
| [HeadersFormattingOptions](./headersformattingoptions/) | The base class of the options for saving a message to HTML or MHTML: how the headers are formatted, which are shown, and how embedded resources are rendered. |
| [HeaderType](./headertype/) | Identifies a standard header of an Internet message, such as `From`, `Subject` or `Content-Type`. |
| [HtmlLoadOptions](./htmlloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from HTML format. This class allows you to specify resource paths and control the generation of plain text views when converting HTML messages to MailMessage objects. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are saved to HTML format. This class allows you to customize HTML output formatting, resource rendering modes, and encoding behavior when converting email messages to HTML files. |
| [HyperlinkRenderingCallback](./hyperlinkrenderingcallback/) | Represents a method that renders a hyperlink of the HTML body as text, for [`GetHtmlBodyText`](../aspose.email/mailmessage/gethtmlbodytext/). |
| [ImapException](./imapexception/) | The exception that is thrown when an IMAP client cannot complete an operation. |
| [License](./license/) | Provides methods to license the component. |
| [LinkedResource](./linkedresource/) | Represents an embedded resource (such as an image or file) that can be referenced by an [`AlternateView`](../aspose.email/alternateview/) in an email message. Linked resources are typically used to embed images, fonts, or other assets directly into HTML email content using Content-ID references. |
| [LinkedResourceCollection](./linkedresourcecollection/) | The resources embedded in an alternate view or a message. |
| [LinkedResourceRemovedEventArgs](./linkedresourceremovedeventargs/) | Provides data for the event that is raised when a linked resource is removed from a message. |
| [LoadOptions](./loadoptions/) | Serves as the abstract base class for format-specific options when loading [`MailMessage`](../aspose.email/mailmessage/) from various email formats (EML, EMLX, HTML, MHTML, etc.). This class provides common configuration properties such as text encoding, embedded message format preservation, and signature handling. |
| [MailAddress](./mailaddress/) | Represents an email address with support for display names, encoding, and address parsing. This class provides functionality for working with email addresses in email messages, including properties for the display name, user name, host, and raw address. It supports proper encoding of international characters in display names and validates email addresses against SMTP standards. |
| [MailAddressCollection](./mailaddresscollection/) | A list of e-mail addresses, such as the recipients of a message. |
| [MailboxInfo](./mailboxinfo/) | Identifies a message in a mailbox on a server. |
| [MailException](./mailexception/) | The exception that is thrown when a mail message cannot be processed. |
| [MailMessage](./mailmessage/) | Represents an e-mail message: its headers, body, attachments and recipients. Load it from or save it to EML, MSG, MHTML, HTML and other formats, and send it with the mail clients. |
| [MailMessageCollection](./mailmessagecollection/) | A collection of [`MailMessage`](../aspose.email/mailmessage/) objects. |
| [MailMessageSaveType](./mailmessagesavetype/) | Defines the formats a message can be saved to. Pass one to [`CreateSaveOptions`](../aspose.email/saveoptions/createsaveoptions/) to get options for that format. |
| [MessageAcceptanceCallback](./messageacceptancecallback/) | Represents a method that decides whether a message is included in a conversion. |
| [MessageFormat](./messageformat/) | Defines the formats a message can be loaded from. |
| [Metered](./metered/) | Licenses the product with a metered (pay-per-use) key and reports the consumption. |
| [MhtmlLoadOptions](./mhtmlloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from MHTML format. This class allows you to customize the loading behavior for MHTML (MIME HTML) files, particularly for handling TNEF attachments that may be embedded in the message. |
| [MhtSaveOptions](./mhtsaveoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are saved to MHTML format. This class allows you to customize MHTML output formatting, attachment handling, header preservation, and resource rendering behavior when converting email messages to MHTML (MIME HTML) files. |
| [MhtTemplateName](./mhttemplatename/) | The names of the headers that can be rendered when a message is saved to HTML or MHTML. |
| [MsgLoadOptions](./msgloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from MSG format. This class allows you to customize the loading behavior for Outlook MSG files, including TNEF attachment handling, RTF body preservation, email address preservation, and timeout configuration. |
| [MsgSaveOptions](./msgsaveoptions/) | Options for saving a [`MailMessage`](../aspose.email/mailmessage/) to Outlook MSG format, with ANSI or Unicode strings, or to an Outlook template (OFT). |
| [ObjectIdentifier](./objectidentifier/) | The identifiers of an object on the servers it came from. |
| [Pop3Exception](./pop3exception/) | The exception that is thrown when a POP3 client cannot complete an operation. |
| [ProgressEventHandlerInfo](./progresseventhandlerinfo/) | Information about the progress of a conversion, passed to a [`ConversionProgressEventHandler`](../aspose.email/conversionprogresseventhandler/). |
| [ReferenceAttachment](./referenceattachment/) | An attachment that is a link to a file in a cloud storage, such as OneDrive, instead of the file itself. |
| [ResourceHtmlRenderingEventArgs](./resourcehtmlrenderingeventargs/) | Provides data for the [`ResourceHtmlRendering`](../aspose.email/headersformattingoptions/resourcehtmlrendering/) event: what to render for an attachment in the HTML. |
| [SaveOptions](./saveoptions/) | Serves as the abstract base class for format-specific options when saving [`MailMessage`](../aspose.email/mailmessage/) to various email formats (EML, EMLX, MSG, MHTML, HTML, etc.). This class provides common configuration properties such as custom progress handlers and save type configuration. |
| [SecureEmailManager](./secureemailmanager/) | Provides methods for working with secure emails, including S/MIME signing and encryption operations. This class enables digital signature verification, message decryption, and signing of email messages using X.509 certificates and PKCS#7/CMS standards. |
| [SignatureOptions](./signatureoptions/) | Options for signing a message. |
| [SmimeResult](./smimeresult/) | The result of verifying the signature of a message. |
| [SmtpException](./smtpexception/) | The exception that is thrown when an SMTP client cannot complete an operation. |
| [SSPIException](./sspiexception/) | The exception that is thrown when Windows integrated authentication (SSPI) fails. |
| [TimeoutException](./timeoutexception/) | The exception that is thrown when an operation does not complete in the allotted time. |
| [TnefLoadOptions](./tnefloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from TNEF (Transport Neutral Encapsulation Format) format. This class is used primarily for handling Microsoft Outlook TNEF attachments (winmail.dat) that may contain rich text formatting and embedded objects. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IAttachment](./iattachment/) | The common interface of attachments. |
| [IMailAddress](./imailaddress/) | The common interface of e-mail addresses. |
| [IMessage](./imessage/) | The common interface of messages. |
| [IMessageFormatter](./imessageformatter/) | Formats a message, for example by writing its headers into the body before it is saved. |
| [IPreferredTextEncodingProvider](./ipreferredtextencodingprovider/) | An object with a preferred text encoding, used for its text when no other encoding is specified. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [AttachmentPermissionType](./attachmentpermissiontype/) | Defines who can view or edit the file of a cloud (reference) attachment. |
| [AttachmentProviderType](./attachmentprovidertype/) | Defines the cloud storage service that holds the file of a reference attachment. |
| [ContactFieldsSet](./contactfieldsset/) | Defines the groups of contact fields written when a contact is saved to MHTML. The values can be combined. |
| [DeliveryNotificationOptions](./deliverynotificationoptions/) | Defines when the SMTP server sends a delivery status notification to the sender. The values can be combined. |
| [EmlValidationErrorType](./emlvalidationerrortype/) | Defines the types of errors in the MIME structure of a message. |
| [FileCompatibilityMode](./filecompatibilitymode/) | Defines conversions applied while a message is loaded or saved. The values can be combined. |
| [FileFormatType](./fileformattype/) | Defines the file formats that can be detected. |
| [HtmlFormatOptions](./htmlformatoptions/) | Defines options for saving a message to HTML. The values can be combined. |
| [MailPriority](./mailpriority/) | Defines the priorities of a message. |
| [MailSensitivity](./mailsensitivity/) | Defines the sensitivity of a message. |
| [MhtFormatOptions](./mhtformatoptions/) | Defines options for saving a message to MHTML. The values can be combined. |
| [ParticipationStatus](./participationstatus/) | Defines the responses of an attendee to a meeting request. |
| [ProgressEventType](./progresseventtype/) | Defines the stages of a conversion reported to a progress handler. |
| [ResourceRenderingMode](./resourcerenderingmode/) | Defines how attachments and other resources are rendered into HTML. |


