---
title: Aspose.Email
second_title: Aspose.Email for .NET API Reference
description: The Aspose.Email namespace contains common classes of Aspose.Email
type: docs
weight: 10
url: /net/aspose.email/
---
The **Aspose.Email** namespace contains common classes of Aspose.Email.

## Classes

| Class | Description |
| --- | --- |
| [AlternateView](./alternateview/) | Represents an alternative format view of an email message, such as plain text or HTML versions. This class allows you to provide multiple content representations for email clients with different capabilities. Alternate views can include linked resources (embedded images, files) and support content encoding and transfer encoding configuration. |
| [AlternateViewCollection](./alternateviewcollection/) | Represents a collection of AlternateView objects. |
| [AlternateViewRemovedEventArgs](./alternateviewremovedeventargs/) | Provides data for the AlternateViewRemoved event. |
| [AsposeArgumentException](./asposeargumentexception/) | The exception that is thrown when one of the arguments provided to a method is not valid. |
| [AsposeArgumentNullException](./asposeargumentnullexception/) | The ArgumentException is thrown when an argument is null when it shouldn't be. |
| [AsposeArgumentOutOfRangeException](./asposeargumentoutofrangeexception/) | The exception that is thrown when one of the arguments provided to a method is out of range. |
| [AsposeBadServerResponceException](./asposebadserverresponceexception/) | Represents errors that occur during server operation execution. |
| [AsposeException](./asposeexception/) | Base exception type for Aspose.Email Represents errors that occur during application execution. |
| [AsposeInvalidDataException](./asposeinvaliddataexception/) | The exception that is thrown when one of the arguments provided to a method is not valid. |
| [AsposeInvalidEnumArgumentException](./asposeinvalidenumargumentexception/) | Base exceptioon type for Aspose.Email Represents errors that occur during application execution. |
| [AsposeInvalidOperationException](./asposeinvalidoperationexception/) | Exception class for denoting an object was in a state that made calling a method illegal. |
| [AsposeNotSupportedException](./asposenotsupportedexception/) | The exception that is thrown when an invoked method or parameter is not supported, or when there is an attempt to read, seek, or write to a stream that does not support the invoked functionality. |
| [Attachment](./attachment/) | Represents an email attachment that can be added to a [`MailMessage`](../aspose.email/mailmessage/). This class provides functionality for managing attachment content, name, content type, encoding, and content disposition. It supports various attachment types including regular files, embedded messages (message/rfc822), and TNEF formatted messages. |
| [AttachmentBase](./attachmentbase/) | Provides the base class for mail attachments and inline views. This abstract class supplies core functionality for managing attachment content, MIME parts, content identifiers, and resource disposal. |
| [AttachmentCollection](./attachmentcollection/) | Represents a collection of e-mail message attachments. |
| [BuildVersionInfo](./buildversioninfo/) | Provides information about the current product name and version. |
| [ConversionProgressEventHandler](./conversionprogresseventhandler/) | Represents signature for method that usually supplied by calling side and handles progress events. |
| [ElementProcessingException](./elementprocessingexception/) | The exception that is thrown when one of many elements failed with exception. |
| [EmlLoadOptions](./emlloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from EML format. This class allows you to customize the loading behavior for specific EML features such as TNEF attachment handling and embedded message preservation. |
| [EmlSaveOptions](./emlsaveoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are saved to EML and EMLX format. This class allows you to customize the saving behavior for features such as embedded message format preservation, TNEF handling, signed message integrity, and boundary template configuration. |
| [EmlValidationError](./emlvalidationerror/) | Represents the eml validation error information. |
| [EmlValidationErrorCollection](./emlvalidationerrorcollection/) | Represents the collection of [`EmlValidationError`](../aspose.email/emlvalidationerror/) |
| [EmlxLoadOptions](./emlxloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from EMLX format. This class inherits from [`LoadOptions`](../aspose.email/loadoptions/) and is specifically designed for Apple Mail EMLX file format. |
| [ExchangeException](./exchangeexception/) | Thrown if there is a MS Exchange communication failure. |
| [FileCorruptedException](./filecorruptedexception/) | Exception that is thrown during file reading, when the file appears to be corrupted and impossible to read. |
| [FileFormatInfo](./fileformatinfo/) |  |
| [FormatNotSupportedException](./formatnotsupportedexception/) | Exception that is thrown during document load, when the document format is not recognized or not supported by the component. |
| [GlobalFormattingOptions](./globalformattingoptions/) | Class that allow to set some formatting options for all newly created instances of this options. |
| [GoogleClientException](./googleclientexception/) | Represents errors that occur during ActiveSync protocol execution. |
| [HeadersFormattingOptions](./headersformattingoptions/) | Serves as the abstract base class for format-specific options when saving [`MailMessage`](../aspose.email/mailmessage/) to HTML-based formats (MHTML, HTML). This class provides configuration properties for controlling header formatting, CSS styles, timeout settings, and resource rendering behavior. |
| [HeaderType](./headertype/) | Represents the Internet standards and RFCs define header fields which may occur on Internet Mail Messages . |
| [HtmlLoadOptions](./htmlloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from HTML format. This class allows you to specify resource paths and control the generation of plain text views when converting HTML messages to MailMessage objects. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are saved to HTML format. This class allows you to customize HTML output formatting, resource rendering modes, and encoding behavior when converting email messages to HTML files. |
| [HyperlinkRenderingCallback](./hyperlinkrenderingcallback/) | Provides possibility to handle rendering of hyperlink in custom style. |
| [ImapException](./imapexception/) | Represents the exception that is thrown when the ImapClient is not able to complete an operation. |
| [License](./license/) | Provides methods to license the component. |
| [LinkedResource](./linkedresource/) | Represents an embedded resource (such as an image or file) that can be referenced by an [`AlternateView`](../aspose.email/alternateview/) in an email message. Linked resources are typically used to embed images, fonts, or other assets directly into HTML email content using Content-ID references. |
| [LinkedResourceCollection](./linkedresourcecollection/) | Represents a collection of LinkedResource objects |
| [LinkedResourceRemovedEventArgs](./linkedresourceremovedeventargs/) | Provides data for the event that is raised when a linked resource is removed from a message. |
| [LoadOptions](./loadoptions/) | Serves as the abstract base class for format-specific options when loading [`MailMessage`](../aspose.email/mailmessage/) from various email formats (EML, EMLX, HTML, MHTML, etc.). This class provides common configuration properties such as text encoding, embedded message format preservation, and signature handling. |
| [MailAddress](./mailaddress/) | Represents an email address with support for display names, encoding, and address parsing. This class provides functionality for working with email addresses in email messages, including properties for the display name, user name, host, and raw address. It supports proper encoding of international characters in display names and validates email addresses against SMTP standards. |
| [MailAddressCollection](./mailaddresscollection/) | Represents a collection of [`MailAddress`](../aspose.email/mailaddress/) objects. |
| [MailboxInfo](./mailboxinfo/) | Represents identification information about message in a mailbox. |
| [MailException](./mailexception/) | Represents the exception that is thrown when the mail message processing. |
| [MailMessage](./mailmessage/) |  |
| [MailMessageCollection](./mailmessagecollection/) | Represents a collection of [`MailMessage`](../aspose.email/mailmessage/) objects. |
| [MailMessageSaveType](./mailmessagesavetype/) | Represents the mail message format.It can be in eml,msg or mhtml format. |
| [MessageAcceptanceCallback](./messageacceptancecallback/) | Callback function which is being called during the conversion process. |
| [MessageFormat](./messageformat/) | Represents the mail message format.It can be in eml,msg or mhtml format. |
| [Metered](./metered/) | Provides methods to set metered key. |
| [MhtmlLoadOptions](./mhtmlloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from MHTML format. This class allows you to customize the loading behavior for MHTML (MIME HTML) files, particularly for handling TNEF attachments that may be embedded in the message. |
| [MhtSaveOptions](./mhtsaveoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are saved to MHTML format. This class allows you to customize MHTML output formatting, attachment handling, header preservation, and resource rendering behavior when converting email messages to MHTML (MIME HTML) files. |
| [MhtTemplateName](./mhttemplatename/) | Defines well known names of headers for Mhtml formatting. |
| [MsgLoadOptions](./msgloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from MSG format. This class allows you to customize the loading behavior for Outlook MSG files, including TNEF attachment handling, RTF body preservation, email address preservation, and timeout configuration. |
| [MsgSaveOptions](./msgsaveoptions/) | This class allows the user to specify additional settings when saving a MailMessage in the Msg(ASCII) and Msg(Unicode) format. |
| [ObjectIdentifier](./objectidentifier/) | Contains object identification information |
| [Pop3Exception](./pop3exception/) | Represents the exception that is thrown when the Pop3Client is not able to complete an operation. |
| [ProgressEventHandlerInfo](./progresseventhandlerinfo/) | This class represents information about conversion progress that can be used in external applicatuion to show conversion progress to end user. |
| [ReferenceAttachment](./referenceattachment/) | This class represents a reference attachment |
| [ResourceHtmlRenderingEventArgs](./resourcehtmlrenderingeventargs/) | Represents additional parameters for ResourceHtmlRendering event. |
| [SaveOptions](./saveoptions/) | Serves as the abstract base class for format-specific options when saving [`MailMessage`](../aspose.email/mailmessage/) to various email formats (EML, EMLX, MSG, MHTML, HTML, etc.). This class provides common configuration properties such as custom progress handlers and save type configuration. |
| [SecureEmailManager](./secureemailmanager/) | Provides methods for working with secure emails, including S/MIME signing and encryption operations. This class enables digital signature verification, message decryption, and signing of email messages using X.509 certificates and PKCS#7/CMS standards. |
| [SignatureOptions](./signatureoptions/) | This class allow the user to specify additional options when sign a message. |
| [SmimeResult](./smimeresult/) | This class containing results of checking secure emails. |
| [SmtpException](./smtpexception/) | Represents the exception that is thrown when the SmtpClient is not able to complete an operation. |
| [SSPIException](./sspiexception/) | Represents errors that occur during SSPI execution. |
| [TimeoutException](./timeoutexception/) | Represents the exception that is thrown when the time for operation has expired. |
| [TnefLoadOptions](./tnefloadoptions/) | Provides options for controlling how [`MailMessage`](../aspose.email/mailmessage/) instances are loaded from TNEF (Transport Neutral Encapsulation Format) format. This class is used primarily for handling Microsoft Outlook TNEF attachments (winmail.dat) that may contain rich text formatting and embedded objects. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IAttachment](./iattachment/) | Represents a common attachment interface |
| [IMailAddress](./imailaddress/) | Represents a common mail address interface |
| [IMessage](./imessage/) | Represents a common message interface |
| [IMessageFormatter](./imessageformatter/) | Provides a mechanism for retrieving an object to Message formatting. |
| [IPreferredTextEncodingProvider](./ipreferredtextencodingprovider/) | Defines a interface for objects that can define PreferredTextEncoding. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [AttachmentPermissionType](./attachmentpermissiontype/) | The permission type data associated with a web reference attachment. |
| [AttachmentProviderType](./attachmentprovidertype/) | The type of web service manipulating the attachment. |
| [ContactFieldsSet](./contactfieldsset/) | Enumerates the groups of Contact fields that will be included in resultant mhtml file. |
| [DeliveryNotificationOptions](./deliverynotificationoptions/) | Specifies delivery notifications. |
| [EmlValidationErrorType](./emlvalidationerrortype/) | Enumerates the types of the eml validation errors. |
| [FileCompatibilityMode](./filecompatibilitymode/) | Defines inner conversions, that are necessarily to be done when loading or saving a message. By default CR is not replaces by CRLF, Tnef-attachment is not saved. |
| [FileFormatType](./fileformattype/) | Enumerates file format types. |
| [HtmlFormatOptions](./htmlformatoptions/) | Enumerates the Html format options. |
| [MailPriority](./mailpriority/) | Represents the mail priopity |
| [MailSensitivity](./mailsensitivity/) | Specifies the sensitivity of a MailMessage. |
| [MhtFormatOptions](./mhtformatoptions/) | Enumerates the Mht format options |
| [ParticipationStatus](./participationstatus/) | Identifies the participation status for the calendar user. |
| [ProgressEventType](./progresseventtype/) | Type of progress event that occured. |
| [ResourceRenderingMode](./resourcerenderingmode/) | Provides set various modes of rendering resources in html. |


