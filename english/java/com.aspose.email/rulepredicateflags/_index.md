---
title: RulePredicateFlags
second_title: Aspose.Email for Java API Reference
description:  Represents the RulePredicate flags
type: docs
weight: 608
url: /java/com.aspose.email/rulepredicateflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RulePredicateFlags extends System.Enum
```

Represents the RulePredicate flags
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | No flags are specified |
| [ApprovalRequest](#ApprovalRequest) | Incoming messages must be approval requests in order for the condition or exception to apply. |
| [NotApprovalRequest](#NotApprovalRequest) | Incoming messages must NOT be approval requests in order for the condition or exception to apply. |
| [AutomaticForward](#AutomaticForward) | Incoming messages must be automatic forwards in order for the condition or exception to apply. |
| [NotAutomaticForward](#NotAutomaticForward) | Incoming messages must NOT be automatic forwards in order for the condition or exception to apply. |
| [AutomaticReply](#AutomaticReply) | Incoming messages must be automatic replies in order for the condition or exception to apply. |
| [NotAutomaticReply](#NotAutomaticReply) | Incoming messages must NOT be automatic replies in order for the condition or exception to apply. |
| [Encrypted](#Encrypted) | Incoming messages must be S/MIME encrypted in order for the condition or exception to apply. |
| [NotEncrypted](#NotEncrypted) | Incoming messages must not be S/MIME encrypted in order for the condition or exception to apply. |
| [MeetingRequest](#MeetingRequest) | Incoming messages must be meeting requests in order for the condition or exception to apply. |
| [NotMeetingRequest](#NotMeetingRequest) | Incoming messages must NOT be meeting requests in order for the condition or exception to apply. |
| [MeetingResponse](#MeetingResponse) | Incoming messages must be meeting responses in order for the condition or exception to apply. |
| [NotMeetingResponse](#NotMeetingResponse) | Incoming messages must NOT be meeting responses in order for the condition or exception to apply. |
| [Ndr](#Ndr) | Incoming messages must be non-delivery reports (NDRs) in order for the condition or exception to apply. |
| [NotNdr](#NotNdr) | Incoming messages must NOT be non-delivery reports (NDRs) in order for the condition or exception to apply. |
| [PermissionControlled](#PermissionControlled) | Incoming messages must be permission controlled (RMS protected) in order for the condition or exception to apply. |
| [NotPermissionControlled](#NotPermissionControlled) | Incoming messages must NOT be permission controlled (RMS protected) in order for the condition or exception to apply. |
| [HasAttachment](#HasAttachment) | An incoming messages have to have attachments in order for the condition or exception to apply |
| [HasNotAttachment](#HasNotAttachment) | An incoming messages have to have NOT attachments in order for the condition or exception to apply |
| [ReadReceipt](#ReadReceipt) | Incoming messages must be read receipts in order for the condition or exception to apply |
| [NotReadReceipt](#NotReadReceipt) | Incoming messages must NOT be read receipts in order for the condition or exception to apply |
| [Signed](#Signed) | Incoming messages must be S/MIME signed in order for the condition or exception to apply. |
| [NotSigned](#NotSigned) | Incoming messages must NOT be S/MIME signed in order for the condition or exception to apply. |
| [Voicemail](#Voicemail) | Incoming messages must be voice mails in order for the condition or exception to apply. |
| [NotVoicemail](#NotVoicemail) | Incoming messages cant NOT be voice mails in order for the condition or exception to apply. |
| [SentToMe](#SentToMe) | The owner of the mailbox has to be in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| [NotSentToMe](#NotSentToMe) | The owner of the mailbox cannot be in the ToRecipients property of the incoming messages in order for the condition or exception to apply. |
| [SentCcMe](#SentCcMe) | The owner of the mailbox has to be in the CcRecipients property of incoming messages in order for the condition or exception to apply. |
| [NotSentCcMe](#NotSentCcMe) | The owner of the mailbox cannot be in the CcRecipients property of incoming messages in order for the condition or exception to apply. |
| [SentOnlyToMe](#SentOnlyToMe) | The owner of the mailbox has to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| [NotSentOnlyToMe](#NotSentOnlyToMe) | The owner of the mailbox cannot to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| [SentToOrCcMe](#SentToOrCcMe) | The owner of the mailbox has to be in either a ToRecipients or CcRecipients property of incoming messages in order for the condition or exception to apply |
### None {#None}
```
public static final int None
```


No flags are specified

### ApprovalRequest {#ApprovalRequest}
```
public static final int ApprovalRequest
```


Incoming messages must be approval requests in order for the condition or exception to apply.

### NotApprovalRequest {#NotApprovalRequest}
```
public static final int NotApprovalRequest
```


Incoming messages must NOT be approval requests in order for the condition or exception to apply.

### AutomaticForward {#AutomaticForward}
```
public static final int AutomaticForward
```


Incoming messages must be automatic forwards in order for the condition or exception to apply.

### NotAutomaticForward {#NotAutomaticForward}
```
public static final int NotAutomaticForward
```


Incoming messages must NOT be automatic forwards in order for the condition or exception to apply.

### AutomaticReply {#AutomaticReply}
```
public static final int AutomaticReply
```


Incoming messages must be automatic replies in order for the condition or exception to apply.

### NotAutomaticReply {#NotAutomaticReply}
```
public static final int NotAutomaticReply
```


Incoming messages must NOT be automatic replies in order for the condition or exception to apply.

### Encrypted {#Encrypted}
```
public static final int Encrypted
```


Incoming messages must be S/MIME encrypted in order for the condition or exception to apply.

### NotEncrypted {#NotEncrypted}
```
public static final int NotEncrypted
```


Incoming messages must not be S/MIME encrypted in order for the condition or exception to apply.

### MeetingRequest {#MeetingRequest}
```
public static final int MeetingRequest
```


Incoming messages must be meeting requests in order for the condition or exception to apply.

### NotMeetingRequest {#NotMeetingRequest}
```
public static final int NotMeetingRequest
```


Incoming messages must NOT be meeting requests in order for the condition or exception to apply.

### MeetingResponse {#MeetingResponse}
```
public static final int MeetingResponse
```


Incoming messages must be meeting responses in order for the condition or exception to apply.

### NotMeetingResponse {#NotMeetingResponse}
```
public static final int NotMeetingResponse
```


Incoming messages must NOT be meeting responses in order for the condition or exception to apply.

### Ndr {#Ndr}
```
public static final int Ndr
```


Incoming messages must be non-delivery reports (NDRs) in order for the condition or exception to apply.

### NotNdr {#NotNdr}
```
public static final int NotNdr
```


Incoming messages must NOT be non-delivery reports (NDRs) in order for the condition or exception to apply.

### PermissionControlled {#PermissionControlled}
```
public static final int PermissionControlled
```


Incoming messages must be permission controlled (RMS protected) in order for the condition or exception to apply.

### NotPermissionControlled {#NotPermissionControlled}
```
public static final int NotPermissionControlled
```


Incoming messages must NOT be permission controlled (RMS protected) in order for the condition or exception to apply.

### HasAttachment {#HasAttachment}
```
public static final int HasAttachment
```


An incoming messages have to have attachments in order for the condition or exception to apply

### HasNotAttachment {#HasNotAttachment}
```
public static final int HasNotAttachment
```


An incoming messages have to have NOT attachments in order for the condition or exception to apply

### ReadReceipt {#ReadReceipt}
```
public static final int ReadReceipt
```


Incoming messages must be read receipts in order for the condition or exception to apply

### NotReadReceipt {#NotReadReceipt}
```
public static final int NotReadReceipt
```


Incoming messages must NOT be read receipts in order for the condition or exception to apply

### Signed {#Signed}
```
public static final int Signed
```


Incoming messages must be S/MIME signed in order for the condition or exception to apply.

### NotSigned {#NotSigned}
```
public static final int NotSigned
```


Incoming messages must NOT be S/MIME signed in order for the condition or exception to apply.

### Voicemail {#Voicemail}
```
public static final int Voicemail
```


Incoming messages must be voice mails in order for the condition or exception to apply.

### NotVoicemail {#NotVoicemail}
```
public static final int NotVoicemail
```


Incoming messages cant NOT be voice mails in order for the condition or exception to apply.

### SentToMe {#SentToMe}
```
public static final int SentToMe
```


The owner of the mailbox has to be in the ToRecipients property of incoming messages in order for the condition or exception to apply.

### NotSentToMe {#NotSentToMe}
```
public static final int NotSentToMe
```


The owner of the mailbox cannot be in the ToRecipients property of the incoming messages in order for the condition or exception to apply.

### SentCcMe {#SentCcMe}
```
public static final int SentCcMe
```


The owner of the mailbox has to be in the CcRecipients property of incoming messages in order for the condition or exception to apply.

### NotSentCcMe {#NotSentCcMe}
```
public static final int NotSentCcMe
```


The owner of the mailbox cannot be in the CcRecipients property of incoming messages in order for the condition or exception to apply.

### SentOnlyToMe {#SentOnlyToMe}
```
public static final int SentOnlyToMe
```


The owner of the mailbox has to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply.

### NotSentOnlyToMe {#NotSentOnlyToMe}
```
public static final int NotSentOnlyToMe
```


The owner of the mailbox cannot to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply.

### SentToOrCcMe {#SentToOrCcMe}
```
public static final int SentToOrCcMe
```


The owner of the mailbox has to be in either a ToRecipients or CcRecipients property of incoming messages in order for the condition or exception to apply

