---
title: StorageProcessedEventHandler
second_title: Aspose.Email for Android via Java API Reference
description:  Represents the method that will handle an  event.
type: docs
weight: 388
url: /java/com.aspose.email/storageprocessedeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class StorageProcessedEventHandler extends System.MulticastDelegate
```

Represents the method that will handle an [PersonalStorage\#StorageProcessedDelegate](../../com.aspose.email/personalstorage\#StorageProcessedDelegate) event.
## Constructors

| Constructor | Description |
| --- | --- |
| [StorageProcessedEventHandler()](#StorageProcessedEventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Object sender, StorageProcessedEventArgs e)](#invoke-java.lang.Object-com.aspose.email.StorageProcessedEventArgs-) |  |
| [beginInvoke(Object sender, StorageProcessedEventArgs e, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.aspose.email.StorageProcessedEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### StorageProcessedEventHandler() {#StorageProcessedEventHandler--}
```
public StorageProcessedEventHandler()
```


### invoke(Object sender, StorageProcessedEventArgs e) {#invoke-java.lang.Object-com.aspose.email.StorageProcessedEventArgs-}
```
public abstract void invoke(Object sender, StorageProcessedEventArgs e)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object |  |
| e | [StorageProcessedEventArgs](../../com.aspose.email/storageprocessedeventargs) |  |

### beginInvoke(Object sender, StorageProcessedEventArgs e, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.aspose.email.StorageProcessedEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object sender, StorageProcessedEventArgs e, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object |  |
| e | [StorageProcessedEventArgs](../../com.aspose.email/storageprocessedeventargs) |  |
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

