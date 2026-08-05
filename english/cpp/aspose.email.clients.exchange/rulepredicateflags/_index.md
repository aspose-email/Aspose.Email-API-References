---
title: "RulePredicateFlags Enum"
linktitle: "RulePredicateFlags"
articleTitle: "RulePredicateFlags"
second_title: "Aspose.Email for C++"
description: "Represents the RulePredicate flags"
type: docs
weight: 10
url: /cpp/aspose.email.clients.exchange/rulepredicateflags/
---

## RulePredicateFlags enumeration (32 values)

Represents the RulePredicate flags

| Value | Description |
| --- | --- |
| None | No flags are specified |
| ApprovalRequest | Incoming messages must be approval requests in order for the condition or exception to apply. |
| NotApprovalRequest | Incoming messages must NOT be approval requests in order for the condition or exception to apply. |
| AutomaticForward | Incoming messages must be automatic forwards in order for the condition or exception to apply. |
| NotAutomaticForward | Incoming messages must NOT be automatic forwards in order for the condition or exception to apply. |
| AutomaticReply | Incoming messages must be automatic replies in order for the condition or exception to apply. |
| NotAutomaticReply | Incoming messages must NOT be automatic replies in order for the condition or exception to apply. |
| Encrypted | Incoming messages must be S/MIME encrypted in order for the condition or exception to apply. |
| NotEncrypted | Incoming messages must not be S/MIME encrypted in order for the condition or exception to apply. |
| MeetingRequest | Incoming messages must be meeting requests in order for the condition or exception to apply. |
| NotMeetingRequest | Incoming messages must NOT be meeting requests in order for the condition or exception to apply. |
| MeetingResponse | Incoming messages must be meeting responses in order for the condition or exception to apply. |
| NotMeetingResponse | Incoming messages must NOT be meeting responses in order for the condition or exception to apply. |
| Ndr | Incoming messages must be non-delivery reports (NDRs) in order for the condition or exception to apply. |
| NotNdr | Incoming messages must NOT be non-delivery reports (NDRs) in order for the condition or exception to apply. |
| PermissionControlled | Incoming messages must be permission controlled (RMS protected) in order for the condition or exception to apply. |
| NotPermissionControlled | Incoming messages must NOT be permission controlled (RMS protected) in order for the condition or exception to apply. |
| HasAttachment | An incoming messages have to have attachments in order for the condition or exception to apply |
| HasNotAttachment | An incoming messages have to have NOT attachments in order for the condition or exception to apply |
| ReadReceipt | Incoming messages must be read receipts in order for the condition or exception to apply |
| NotReadReceipt | Incoming messages must NOT be read receipts in order for the condition or exception to apply |
| Signed | Incoming messages must be S/MIME signed in order for the condition or exception to apply. |
| NotSigned | Incoming messages must NOT be S/MIME signed in order for the condition or exception to apply. |
| Voicemail | Incoming messages must be voice mails in order for the condition or exception to apply. |
| NotVoicemail | Incoming messages cant NOT be voice mails in order for the condition or exception to apply. |
| SentToMe | The owner of the mailbox has to be in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| NotSentToMe | The owner of the mailbox cannot be in the ToRecipients property of the incoming messages in order for the condition or exception to apply. |
| SentCcMe | The owner of the mailbox has to be in the CcRecipients property of incoming messages in order for the condition or exception to apply. |
| NotSentCcMe | The owner of the mailbox cannot be in the CcRecipients property of incoming messages in order for the condition or exception to apply. |
| SentOnlyToMe | The owner of the mailbox has to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| NotSentOnlyToMe | The owner of the mailbox cannot to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| SentToOrCcMe | The owner of the mailbox has to be in either a ToRecipients or CcRecipients property of incoming messages in order for the condition or exception to apply |

