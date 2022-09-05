---
title: DomainValidatingEventHandler
second_title: Aspose.Email for Android via Java API Reference
description:  Represents the event handler for DomainValidatingEvent.
type: docs
weight: 113
url: /java/com.aspose.email/domainvalidatingeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class DomainValidatingEventHandler extends System.MulticastDelegate
```

Represents the event handler for DomainValidatingEvent.
## Constructors

| Constructor | Description |
| --- | --- |
| [DomainValidatingEventHandler()](#DomainValidatingEventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Object sender, DomainValidatingEventArgs e)](#invoke-java.lang.Object-com.aspose.email.DomainValidatingEventArgs-) | invoke. |
| [beginInvoke(Object sender, DomainValidatingEventArgs e, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.aspose.email.DomainValidatingEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | beginInvoke. |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | endInvoke. |
### DomainValidatingEventHandler() {#DomainValidatingEventHandler--}
```
public DomainValidatingEventHandler()
```


### invoke(Object sender, DomainValidatingEventArgs e) {#invoke-java.lang.Object-com.aspose.email.DomainValidatingEventArgs-}
```
public abstract void invoke(Object sender, DomainValidatingEventArgs e)
```


invoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | a java.lang.Object object. |
| e | [DomainValidatingEventArgs](../../com.aspose.email/domainvalidatingeventargs) | a com.aspose.email.DomainValidatingEventArgs object. |

### beginInvoke(Object sender, DomainValidatingEventArgs e, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.aspose.email.DomainValidatingEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object sender, DomainValidatingEventArgs e, System.AsyncCallback callback, Object state)
```


beginInvoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | a java.lang.Object object. |
| e | [DomainValidatingEventArgs](../../com.aspose.email/domainvalidatingeventargs) | a com.aspose.email.DomainValidatingEventArgs object. |
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

