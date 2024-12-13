---
title: Enum RulePredicateFlags
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.RulePredicateFlags enum. Represents the RulePredicate flags
type: docs
weight: 3550
url: /net/aspose.email.clients.exchange/rulepredicateflags/
---
## RulePredicateFlags enumeration

Represents the RulePredicate flags

```csharp
[Flags]
public enum RulePredicateFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No flags are specified |
| ApprovalRequest | `1` | Incoming messages must be approval requests in order for the condition or exception to apply. |
| NotApprovalRequest | `2` | Incoming messages must NOT be approval requests in order for the condition or exception to apply. |
| AutomaticForward | `4` | Incoming messages must be automatic forwards in order for the condition or exception to apply. |
| NotAutomaticForward | `8` | Incoming messages must NOT be automatic forwards in order for the condition or exception to apply. |
| AutomaticReply | `10` | Incoming messages must be automatic replies in order for the condition or exception to apply. |
| NotAutomaticReply | `20` | Incoming messages must NOT be automatic replies in order for the condition or exception to apply. |
| Encrypted | `40` | Incoming messages must be S/MIME encrypted in order for the condition or exception to apply. |
| NotEncrypted | `80` | Incoming messages must not be S/MIME encrypted in order for the condition or exception to apply. |
| MeetingRequest | `100` | Incoming messages must be meeting requests in order for the condition or exception to apply. |
| NotMeetingRequest | `200` | Incoming messages must NOT be meeting requests in order for the condition or exception to apply. |
| MeetingResponse | `400` | Incoming messages must be meeting responses in order for the condition or exception to apply. |
| NotMeetingResponse | `800` | Incoming messages must NOT be meeting responses in order for the condition or exception to apply. |
| Ndr | `1000` | Incoming messages must be non-delivery reports (NDRs) in order for the condition or exception to apply. |
| NotNdr | `2000` | Incoming messages must NOT be non-delivery reports (NDRs) in order for the condition or exception to apply. |
| PermissionControlled | `4000` | Incoming messages must be permission controlled (RMS protected) in order for the condition or exception to apply. |
| NotPermissionControlled | `8000` | Incoming messages must NOT be permission controlled (RMS protected) in order for the condition or exception to apply. |
| HasAttachment | `10000` | An incoming messages have to have attachments in order for the condition or exception to apply |
| HasNotAttachment | `20000` | An incoming messages have to have NOT attachments in order for the condition or exception to apply |
| ReadReceipt | `40000` | Incoming messages must be read receipts in order for the condition or exception to apply |
| NotReadReceipt | `80000` | Incoming messages must NOT be read receipts in order for the condition or exception to apply |
| Signed | `100000` | Incoming messages must be S/MIME signed in order for the condition or exception to apply. |
| NotSigned | `200000` | Incoming messages must NOT be S/MIME signed in order for the condition or exception to apply. |
| Voicemail | `400000` | Incoming messages must be voice mails in order for the condition or exception to apply. |
| NotVoicemail | `800000` | Incoming messages cant NOT be voice mails in order for the condition or exception to apply. |
| SentToMe | `1000000` | The owner of the mailbox has to be in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| NotSentToMe | `2000000` | The owner of the mailbox cannot be in the ToRecipients property of the incoming messages in order for the condition or exception to apply. |
| SentCcMe | `4000000` | The owner of the mailbox has to be in the CcRecipients property of incoming messages in order for the condition or exception to apply. |
| NotSentCcMe | `8000000` | The owner of the mailbox cannot be in the CcRecipients property of incoming messages in order for the condition or exception to apply. |
| SentOnlyToMe | `10000000` | The owner of the mailbox has to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| NotSentOnlyToMe | `20000000` | The owner of the mailbox cannot to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| SentToOrCcMe | `40000000` | The owner of the mailbox has to be in either a ToRecipients or CcRecipients property of incoming messages in order for the condition or exception to apply |

### See Also

* namespace [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange/)
* assembly [Aspose.Email](../../)


