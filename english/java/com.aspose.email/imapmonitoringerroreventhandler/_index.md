---
title: ImapMonitoringErrorEventHandler
second_title: Aspose.Email for Java API Reference
description: Represents the method that will handle an imap monitoring error event
type: docs
weight: 319
url: /java/com.aspose.email/imapmonitoringerroreventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ImapMonitoringErrorEventHandler extends System.MulticastDelegate
```

Represents the method that will handle an imap monitoring error event
## Constructors

| Constructor | Description |
| --- | --- |
| [ImapMonitoringErrorEventHandler()](#ImapMonitoringErrorEventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Object sender, ImapMonitoringErrorEventArgs e)](#invoke-java.lang.Object-com.aspose.email.ImapMonitoringErrorEventArgs-) | invoke. |
| [beginInvoke(Object sender, ImapMonitoringErrorEventArgs e, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.aspose.email.ImapMonitoringErrorEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | beginInvoke. |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | endInvoke. |
### ImapMonitoringErrorEventHandler() {#ImapMonitoringErrorEventHandler--}
```
public ImapMonitoringErrorEventHandler()
```


### invoke(Object sender, ImapMonitoringErrorEventArgs e) {#invoke-java.lang.Object-com.aspose.email.ImapMonitoringErrorEventArgs-}
```
public abstract void invoke(Object sender, ImapMonitoringErrorEventArgs e)
```


invoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | a java.lang.Object object. |
| e | [ImapMonitoringErrorEventArgs](../../com.aspose.email/imapmonitoringerroreventargs) | a [ImapMonitoringErrorEventArgs](../../com.aspose.email/imapmonitoringerroreventargs) object. |

### beginInvoke(Object sender, ImapMonitoringErrorEventArgs e, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.aspose.email.ImapMonitoringErrorEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object sender, ImapMonitoringErrorEventArgs e, System.AsyncCallback callback, Object state)
```


beginInvoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | a java.lang.Object object. |
| e | [ImapMonitoringErrorEventArgs](../../com.aspose.email/imapmonitoringerroreventargs) | a [ImapMonitoringErrorEventArgs](../../com.aspose.email/imapmonitoringerroreventargs) object. |
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

