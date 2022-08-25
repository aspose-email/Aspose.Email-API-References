---
title: BeforeItemCallback
second_title: Aspose.Email for Java API Reference
description:  BeforeItemCallback is called before the next item is processed the type of which depends on the task being performed.
type: docs
weight: 80
url: /java/com.aspose.email/beforeitemcallback/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class BeforeItemCallback extends System.MulticastDelegate
```

BeforeItemCallback is called before the next item is processed, the type of which depends on the task being performed.
## Constructors

| Constructor | Description |
| --- | --- |
| [BeforeItemCallback()](#BeforeItemCallback--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(ItemCallbackArgs item)](#invoke-com.aspose.email.ItemCallbackArgs-) |  |
| [beginInvoke(ItemCallbackArgs item, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.email.ItemCallbackArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### BeforeItemCallback() {#BeforeItemCallback--}
```
public BeforeItemCallback()
```


### invoke(ItemCallbackArgs item) {#invoke-com.aspose.email.ItemCallbackArgs-}
```
public abstract void invoke(ItemCallbackArgs item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ItemCallbackArgs](../../com.aspose.email/itemcallbackargs) |  |

### beginInvoke(ItemCallbackArgs item, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.email.ItemCallbackArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(ItemCallbackArgs item, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ItemCallbackArgs](../../com.aspose.email/itemcallbackargs) |  |
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

