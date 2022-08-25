---
title: BounceResult
second_title: Aspose.Email for Android via Java API Reference
description:  Represents result of the message examination as a bounce message.
type: docs
weight: 60
url: /java/com.aspose.email/bounceresult/
---
**Inheritance:**
java.lang.Object
```
public class BounceResult
```

Represents result of the message examination as a bounce message.
## Constructors

| Constructor | Description |
| --- | --- |
| [BounceResult()](#BounceResult--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isBounced()](#isBounced--) | True if email is a delivery failure or deliver delay report. |
| [getAction()](#getAction--) | Indicates the action performed as a result of attempt to deliver the message. |
| [getReason()](#getReason--) | For a "failed" or "delayed" recipient, contains the actual diagnostic code issued by the mail transport. |
| [getRecipient()](#getRecipient--) | Indicates the original recipient address as specified by the sender of the message for which the delivery failure report was issued. |
| [getStatus()](#getStatus--) | Contains a transport-independent status code which indicates the delivery status of the message to that recipient. |
| [getOriginalMessage()](#getOriginalMessage--) | Contains the original message. |
### BounceResult() {#BounceResult--}
```
public BounceResult()
```


### isBounced() {#isBounced--}
```
public final boolean isBounced()
```


True if email is a delivery failure or deliver delay report.

**Returns:**
boolean
### getAction() {#getAction--}
```
public final int getAction()
```


Indicates the action performed as a result of attempt to deliver the message.

**Returns:**
int
### getReason() {#getReason--}
```
public final String getReason()
```


For a "failed" or "delayed" recipient, contains the actual diagnostic code issued by the mail transport.

**Returns:**
java.lang.String
### getRecipient() {#getRecipient--}
```
public final String getRecipient()
```


Indicates the original recipient address as specified by the sender of the message for which the delivery failure report was issued.

**Returns:**
java.lang.String
### getStatus() {#getStatus--}
```
public final String getStatus()
```


Contains a transport-independent status code which indicates the delivery status of the message to that recipient.

**Returns:**
java.lang.String
### getOriginalMessage() {#getOriginalMessage--}
```
public final MailMessage getOriginalMessage()
```


Contains the original message.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
