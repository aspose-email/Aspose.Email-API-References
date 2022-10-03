---
title: MailStorageConverter.MailHandler
second_title: Aspose.Email for Java API Reference
description:  Represents the method that will handle an event that occurs after
 successfully reading a message from the Mbox and before adding it to Pst.
type: docs
weight: 10
url: /java/com.aspose.email/mailstorageconverter.mailhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class MailStorageConverter.MailHandler extends System.MulticastDelegate
```

Represents the method that will handle an event that occurs after successfully reading a message from the Mbox and before adding it to Pst.

--------------------

The handler can be used to any additional message changes before adding to the PST.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailHandler()](#MailHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(MailMessage message)](#invoke-com.aspose.email.MailMessage-) |  |
| [beginInvoke(MailMessage message, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### MailHandler() {#MailHandler--}
```
public MailHandler()
```


### invoke(MailMessage message) {#invoke-com.aspose.email.MailMessage-}
```
public abstract void invoke(MailMessage message)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) |  |

### beginInvoke(MailMessage message, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.email.MailMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(MailMessage message, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

