---
title: RightsManagementLicense
second_title: Aspose.Email for .NET API Reference
description: Contains the rights policy template settings for the template applied to the email message being synchronized.
type: docs
weight: 1900
url: /net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/
---
## RightsManagementLicense class

Contains the rights policy template settings for the template applied to the e-mail message being synchronized.

```csharp
public class RightsManagementLicense
```

## Constructors

| Name | Description |
| --- | --- |
| [RightsManagementLicense](rightsmanagementlicense)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ContentExpiryDate](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentexpirydate) { get; set; } | Specifies the expiration date for the license. The ContentExpiryDate element is set to "9999-12-30T23:59:59.999Z" if the rights management license has no expiration date set. |
| [ContentOwner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentowner) { get; set; } | Specifies whether the content of the original email can be modified by the user when the user forwards, replies, or replies all to the email message. The value is TRUE if the e-mail can be modified by the user; otherwise, FALSE. A value of FALSE requires that the client MUST exclude the original rights-managed email message from the SmartForward or SmartReply request. Consequently, inline replies are not allowed if the EditAllowed element is set to FALSE. When EditAllowed is set to FALSE and ReplaceMime is not present in a SmartForward or SmartReply request, the server will add the original rights-managed email message as an attachment to the new message. Conversely, if ReplaceMime is present, the server will not attach the original rights-managed email message as an attachment. |
| [EditAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/editallowed) { get; set; } | Specifies whether the content of the original email can be modified by the user when the user forwards, replies, or replies all to the email message. The value is TRUE if the e-mail can be modified by the user; otherwise, FALSE. A value of FALSE requires that the client MUST exclude the original rights-managed email message from the SmartForward or SmartReply request. Consequently, inline replies are not allowed if the EditAllowed element is set to FALSE. When EditAllowed is set to FALSE and ReplaceMime is not present in a SmartForward or SmartReply request, the server will add the original rights-managed email message as an attachment to the new message. Conversely, if composemail:ReplaceMime is present, the server will not attach the original rights-managed email message as an attachment. |
| [ExportAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/exportallowed) { get; set; } | Specifies whether the IRM protection on the e-mail message can be removed by the user. The value is TRUE if the user can remove the IRM protection when the user forwards, replies, or replies all to the e-mail message; otherwise, FALSE. If a rights-managed email message is forwarded or replied to using the SmartForward or SmartReply command, the following conditions are evaluated: - The original rights policy template has the ExportAllowed element set to TRUE - The TemplateID on the new message is set to the "No Restriction" template (TemplateID value "00000000-0000-0000-0000-000000000000") If both of the conditions are true, the IRM protection is removed from the outgoing message. The original message retains its IRM protection. |
| [ExtractAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/extractallowed) { get; set; } | Specifies whether the user can copy content out of the e-mail message. The value is TRUE if the content of the e-mail message can be cut, copied, or a screen capture can be taken of the content; otherwise, FALSE. |
| [ForwardAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/forwardallowed) { get; set; } | Specifies whether the user can forward the e-mail message. The value is TRUE if the user can forward the e-mail message; otherwise, FALSE. |
| [ModifyRecipientsAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/modifyrecipientsallowed) { get; set; } | Specifies whether the user can modify the recipient list when the user forwards, or replies to the e-mail message. The value is TRUE if the user can modify the recipient (1) list; otherwise, FALSE. |
| [Owner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/owner) { get; set; } | Specifies whether the user is the owner of the e-mail message. The value is TRUE if the user is the owner of the e-mail message; otherwise, FALSE. A value of TRUE indicates that the authenticated user has owner rights on this message. This element is used for information presentation purposes only. The Allowed elements (EditAllowed, ReplyAllowed, etc.) are used to evaluate whether a particular action is permitted or restricted. |
| [PrintAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/printallowed) { get; set; } | Specifies whether the e-mail can be printed by the user. This element does not indicate client support for printing an e-mail message; it only specifies whether the e-mail message can be printed if the client supports printing. The value is TRUE if the e-mail can be printed by the user; otherwise, FALSE. |
| [ProgrammaticAccessAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/programmaticaccessallowed) { get; set; } | Specifies whether the contents of the e-mail message can be accessed programmatically by third party applications. The value is TRUE if third party applications can access the content of the e-mail message programmatically; otherwise, FALSE. A value of TRUE indicates whether the protected content is accessible by other applications. Protected content consists of the message body and attachments. |
| [ReplyAllAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallallowed) { get; set; } | Specifies whether the user can reply to all of the recipients (1) of the original e-mail message. The value is TRUE if the user can reply to all of the recipients of the e-mail message; otherwise, FALSE. |
| [ReplyAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallowed) { get; set; } | Specifies whether the user is allowed to reply to the e-mail message. The value is TRUE if the user can reply to the e-mail message; otherwise, FALSE. |
| [TemplateDescription](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatedescription) { get; set; } | Contains a description of the rights policy template represented by the parent RightsManagementLicense element. This element is used for informational presentation purposes only. The maximum length of the TemplateDescription element is 10240 characters. |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templateid) { get; set; } | Contains a string that identifies the rights policy template represented by the parent RightsManagementLicense element. |
| [TemplateName](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatename) { get; set; } | Specifies the name of the rights policy template represented by the parent RightsManagementLicense element. This element is used for informational presentation purposes only. The maximum length of the TemplateName element is 256 characters. |

### See Also

* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
