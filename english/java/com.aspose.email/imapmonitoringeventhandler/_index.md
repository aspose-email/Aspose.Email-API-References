---
title: ImapMonitoringEventHandler
second_title: Aspose.Email for Java API Reference
description:  Represents the method that will handle an imap monitoring event
type: docs
weight: 321
url: /java/com.aspose.email/imapmonitoringeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ImapMonitoringEventHandler extends System.MulticastDelegate
```

Represents the method that will handle an imap monitoring event
## Constructors

| Constructor | Description |
| --- | --- |
| [ImapMonitoringEventHandler()](#ImapMonitoringEventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Object sender, ImapMonitoringEventArgs e)](#invoke-java.lang.Object-com.aspose.email.ImapMonitoringEventArgs-) | invoke. |
| [beginInvoke(Object sender, ImapMonitoringEventArgs e, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.aspose.email.ImapMonitoringEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | beginInvoke. |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | endInvoke. |
### ImapMonitoringEventHandler() {#ImapMonitoringEventHandler--}
```
public ImapMonitoringEventHandler()
```


### invoke(Object sender, ImapMonitoringEventArgs e) {#invoke-java.lang.Object-com.aspose.email.ImapMonitoringEventArgs-}
```
public abstract void invoke(Object sender, ImapMonitoringEventArgs e)
```


invoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | a java.lang.Object object. |
| e | [ImapMonitoringEventArgs](../../com.aspose.email/imapmonitoringeventargs) | a com.aspose.email.ImapMonitoringEventArgs object. |

### beginInvoke(Object sender, ImapMonitoringEventArgs e, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.aspose.email.ImapMonitoringEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object sender, ImapMonitoringEventArgs e, System.AsyncCallback callback, Object state)
```


beginInvoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | a java.lang.Object object. |
| e | [ImapMonitoringEventArgs](../../com.aspose.email/imapmonitoringeventargs) | a com.aspose.email.ImapMonitoringEventArgs object. |
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

