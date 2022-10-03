---
title: MailTips
second_title: Aspose.Email for Java API Reference
description: Represents values for the Mail Tips
type: docs
weight: 377
url: /java/com.aspose.email/mailtips/
---
**Inheritance:**
java.lang.Object
```
public final class MailTips
```

Represents values for the Mail Tips
## Methods

| Method | Description |
| --- | --- |
| [getRecipientAddress()](#getRecipientAddress--) | Gets the mailbox of the recipient. |
| [getPendingMailTips()](#getPendingMailTips--) | Gets a value indicating whether the mail tips in this element could not be evaluated before the server's processing timeout expired. |
| [getOutOfOffice()](#getOutOfOffice--) | Gets the response message for OOF and the duration for sending this message. |
| [getMailboxFull()](#getMailboxFull--) | Gets a value indicating whether the mailbox for the recipient is full. |
| [isMailboxFullSpecified()](#isMailboxFullSpecified--) | Gets a value indicating whether the  MailboxFull (\#getMailboxFull.getMailboxFull/\#setMailboxFull(boolean).setMailboxFull(boolean)) is specified |
| [getCustomMailTip()](#getCustomMailTip--) | Gets a custom mail tip. |
| [getTotalMemberCnt()](#getTotalMemberCnt--) | Gets the total number of members in a group. |
| [getExternalMemberCnt()](#getExternalMemberCnt--) | Gets the number of external members in a group. |
| [getMaxMsgSize()](#getMaxMsgSize--) | Gets the maximum message size the recipient can accept |
| [getDeliveryRestricted()](#getDeliveryRestricted--) | Gets a value indicating whether delivery restrictions will prevent the sender's message from reaching the recipient. |
| [isDeliveryRestrictedSpecified()](#isDeliveryRestrictedSpecified--) | Gets a value indicating whether  DeliveryRestricted (\#getDeliveryRestricted.getDeliveryRestricted/\#setDeliveryRestricted(boolean).setDeliveryRestricted(boolean)) is specified |
| [isModerated()](#isModerated--) | Gets a value indicating whether the recipient's mailbox is being moderated. |
| [isModeratedSpecified()](#isModeratedSpecified--) | Gets a value indicating whether the  IsModerated (\#isModerated.isModerated/\#setModerated(boolean).setModerated(boolean)) is specified |
| [getInvalidRecipient()](#getInvalidRecipient--) | Gets a value indicating whether the recipient is invalid. |
| [isInvalidRecipientSpecified()](#isInvalidRecipientSpecified--) | Gets a value indicating whether  InvalidRecipient (\#getInvalidRecipient.getInvalidRecipient/\#setInvalidRecipient(boolean).setInvalidRecipient(boolean)) is specified |
### getRecipientAddress() {#getRecipientAddress--}
```
public final MailAddress getRecipientAddress()
```


Gets the mailbox of the recipient.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getPendingMailTips() {#getPendingMailTips--}
```
public final int getPendingMailTips()
```


Gets a value indicating whether the mail tips in this element could not be evaluated before the server's processing timeout expired.

**Returns:**
int
### getOutOfOffice() {#getOutOfOffice--}
```
public final OutOfOfficeMailTip getOutOfOffice()
```


Gets the response message for OOF and the duration for sending this message.

**Returns:**
[OutOfOfficeMailTip](../../com.aspose.email/outofofficemailtip)
### getMailboxFull() {#getMailboxFull--}
```
public final boolean getMailboxFull()
```


Gets a value indicating whether the mailbox for the recipient is full.

**Returns:**
boolean
### isMailboxFullSpecified() {#isMailboxFullSpecified--}
```
public final boolean isMailboxFullSpecified()
```


Gets a value indicating whether the  MailboxFull (\#getMailboxFull.getMailboxFull/\#setMailboxFull(boolean).setMailboxFull(boolean)) is specified

**Returns:**
boolean
### getCustomMailTip() {#getCustomMailTip--}
```
public final String getCustomMailTip()
```


Gets a custom mail tip.

**Returns:**
java.lang.String
### getTotalMemberCnt() {#getTotalMemberCnt--}
```
public final int getTotalMemberCnt()
```


Gets the total number of members in a group.

**Returns:**
int
### getExternalMemberCnt() {#getExternalMemberCnt--}
```
public final int getExternalMemberCnt()
```


Gets the number of external members in a group.

**Returns:**
int
### getMaxMsgSize() {#getMaxMsgSize--}
```
public final int getMaxMsgSize()
```


Gets the maximum message size the recipient can accept

**Returns:**
int
### getDeliveryRestricted() {#getDeliveryRestricted--}
```
public final boolean getDeliveryRestricted()
```


Gets a value indicating whether delivery restrictions will prevent the sender's message from reaching the recipient.

**Returns:**
boolean
### isDeliveryRestrictedSpecified() {#isDeliveryRestrictedSpecified--}
```
public final boolean isDeliveryRestrictedSpecified()
```


Gets a value indicating whether  DeliveryRestricted (\#getDeliveryRestricted.getDeliveryRestricted/\#setDeliveryRestricted(boolean).setDeliveryRestricted(boolean)) is specified

**Returns:**
boolean
### isModerated() {#isModerated--}
```
public final boolean isModerated()
```


Gets a value indicating whether the recipient's mailbox is being moderated.

**Returns:**
boolean
### isModeratedSpecified() {#isModeratedSpecified--}
```
public final boolean isModeratedSpecified()
```


Gets a value indicating whether the  IsModerated (\#isModerated.isModerated/\#setModerated(boolean).setModerated(boolean)) is specified

**Returns:**
boolean
### getInvalidRecipient() {#getInvalidRecipient--}
```
public final boolean getInvalidRecipient()
```


Gets a value indicating whether the recipient is invalid.

**Returns:**
boolean
### isInvalidRecipientSpecified() {#isInvalidRecipientSpecified--}
```
public final boolean isInvalidRecipientSpecified()
```


Gets a value indicating whether  InvalidRecipient (\#getInvalidRecipient.getInvalidRecipient/\#setInvalidRecipient(boolean).setInvalidRecipient(boolean)) is specified

**Returns:**
boolean
