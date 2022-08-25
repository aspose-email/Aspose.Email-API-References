---
title: SendMessagesResult
second_title: Aspose.Email for Java API Reference
description:  Contains result of operation with messages
type: docs
weight: 623
url: /java/com.aspose.email/sendmessagesresult/
---
**Inheritance:**
java.lang.Object
```
public class SendMessagesResult
```

Contains result of operation with messages
## Constructors

| Constructor | Description |
| --- | --- |
| [SendMessagesResult()](#SendMessagesResult--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSucceeded()](#getSucceeded--) | Gets mail messages that have been handled successfully |
| [getFailed()](#getFailed--) | Gets mail messages that have been handled with errors |
| [getNotHandled()](#getNotHandled--) | Gets mail messages that have not been handled |
### SendMessagesResult() {#SendMessagesResult--}
```
public SendMessagesResult()
```


### getSucceeded() {#getSucceeded--}
```
public final List<MailMessage> getSucceeded()
```


Gets mail messages that have been handled successfully

**Returns:**
java.util.List<com.aspose.email.MailMessage>
### getFailed() {#getFailed--}
```
public final System.Collections.Generic.Dictionary<MailMessage,Throwable> getFailed()
```


Gets mail messages that have been handled with errors

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.email.MailMessage,java.lang.Throwable>
### getNotHandled() {#getNotHandled--}
```
public final List<MailMessage> getNotHandled()
```


Gets mail messages that have not been handled

**Returns:**
java.util.List<com.aspose.email.MailMessage>
