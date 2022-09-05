---
title: MailServerValidatingEventHandler
second_title: Aspose.Email for Java API Reference
description:  Represents the event handler for MailServerValidatingEvent.
type: docs
weight: 375
url: /java/com.aspose.email/mailservervalidatingeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class MailServerValidatingEventHandler extends System.MulticastDelegate
```

Represents the event handler for MailServerValidatingEvent.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailServerValidatingEventHandler()](#MailServerValidatingEventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Object sender, MailServerValidatingEventArgs e)](#invoke-java.lang.Object-com.aspose.email.MailServerValidatingEventArgs-) | invoke. |
| [beginInvoke(Object sender, MailServerValidatingEventArgs e, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.aspose.email.MailServerValidatingEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | beginInvoke. |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | endInvoke. |
### MailServerValidatingEventHandler() {#MailServerValidatingEventHandler--}
```
public MailServerValidatingEventHandler()
```


### invoke(Object sender, MailServerValidatingEventArgs e) {#invoke-java.lang.Object-com.aspose.email.MailServerValidatingEventArgs-}
```
public abstract void invoke(Object sender, MailServerValidatingEventArgs e)
```


invoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | a java.lang.Object object. |
| e | [MailServerValidatingEventArgs](../../com.aspose.email/mailservervalidatingeventargs) | a com.aspose.email.MailServerValidatingEventArgs object. |

### beginInvoke(Object sender, MailServerValidatingEventArgs e, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.aspose.email.MailServerValidatingEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object sender, MailServerValidatingEventArgs e, System.AsyncCallback callback, Object state)
```


beginInvoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | a java.lang.Object object. |
| e | [MailServerValidatingEventArgs](../../com.aspose.email/mailservervalidatingeventargs) | a com.aspose.email.MailServerValidatingEventArgs object. |
| callback | com.aspose.ms.System.AsyncCallback | a com.aspose.ms.System.AsyncCallback object. |
| state | java.lang.Object | a java.lang.Object object. |

**Returns:**
com.aspose.ms.System.IAsyncResult - a com.aspose.ms.System.IAsyncResult object.
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```


endInvoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult | a com.aspose.ms.System.IAsyncResult object. |

