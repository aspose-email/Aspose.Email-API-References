---
title: ItemMovedEventHandler
second_title: Aspose.Email for Java API Reference
description: Represents the method that will handle an  event.
type: docs
weight: 342
url: /java/com.aspose.email/itemmovedeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ItemMovedEventHandler extends System.MulticastDelegate
```

Represents the method that will handle an [FolderInfo.ItemMovedDelegate](../../com.aspose.email/folderinfo\#ItemMovedDelegate) event.
## Constructors

| Constructor | Description |
| --- | --- |
| [ItemMovedEventHandler()](#ItemMovedEventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Object sender, ItemMovedEventArgs e)](#invoke-java.lang.Object-com.aspose.email.ItemMovedEventArgs-) | invoke. |
| [beginInvoke(Object sender, ItemMovedEventArgs e, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.aspose.email.ItemMovedEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | beginInvoke. |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | endInvoke. |
### ItemMovedEventHandler() {#ItemMovedEventHandler--}
```
public ItemMovedEventHandler()
```


### invoke(Object sender, ItemMovedEventArgs e) {#invoke-java.lang.Object-com.aspose.email.ItemMovedEventArgs-}
```
public abstract void invoke(Object sender, ItemMovedEventArgs e)
```


invoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | a java.lang.Object object. |
| e | [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) | a [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) object. |

### beginInvoke(Object sender, ItemMovedEventArgs e, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.aspose.email.ItemMovedEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object sender, ItemMovedEventArgs e, System.AsyncCallback callback, Object state)
```


beginInvoke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | a java.lang.Object object. |
| e | [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) | a [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) object. |
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

