---
title: AppendMessagesResult
second_title: Aspose.Email for Java API Reference
description:  Contains result of operation with messages
type: docs
weight: 28
url: /java/com.aspose.email/appendmessagesresult/
---
**Inheritance:**
java.lang.Object
```
public class AppendMessagesResult
```

Contains result of operation with messages
## Constructors

| Constructor | Description |
| --- | --- |
| [AppendMessagesResult()](#AppendMessagesResult--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSucceeded()](#getSucceeded--) | Gets mail messages that have been handled successfully |
| [getFailed()](#getFailed--) | Gets mail messages that have been handled with errors |
| [getNotHandled()](#getNotHandled--) | Gets mail messages that have not been handled |
### AppendMessagesResult() {#AppendMessagesResult--}
```
public AppendMessagesResult()
```


### getSucceeded() {#getSucceeded--}
```
public final System.Collections.Generic.Dictionary<MailMessage,String> getSucceeded()
```


Gets mail messages that have been handled successfully

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.email.MailMessage,java.lang.String>
### getFailed() {#getFailed--}
```
public final System.Collections.Generic.Dictionary<MailMessage,RuntimeException> getFailed()
```


Gets mail messages that have been handled with errors

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.email.MailMessage,java.lang.RuntimeException>
### getNotHandled() {#getNotHandled--}
```
public final List<MailMessage> getNotHandled()
```


Gets mail messages that have not been handled

**Returns:**
java.util.List<com.aspose.email.MailMessage>
