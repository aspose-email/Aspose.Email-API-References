---
title: TraversalExceptionsCallback
second_title: Aspose.Email for Java API Reference
description:  Represents the callback method that handles the exceptions during storage traversal.
type: docs
weight: 677
url: /java/com.aspose.email/traversalexceptionscallback/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class TraversalExceptionsCallback extends System.MulticastDelegate
```

Represents the callback method that handles the exceptions during storage traversal.
## Constructors

| Constructor | Description |
| --- | --- |
| [TraversalExceptionsCallback()](#TraversalExceptionsCallback--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(TraversalAsposeException exception, String itemId)](#invoke-com.aspose.email.TraversalAsposeException-java.lang.String-) |  |
| [beginInvoke(TraversalAsposeException exception, String itemId, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.email.TraversalAsposeException-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### TraversalExceptionsCallback() {#TraversalExceptionsCallback--}
```
public TraversalExceptionsCallback()
```


### invoke(TraversalAsposeException exception, String itemId) {#invoke-com.aspose.email.TraversalAsposeException-java.lang.String-}
```
public abstract void invoke(TraversalAsposeException exception, String itemId)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exception | [TraversalAsposeException](../../com.aspose.email/traversalasposeexception) |  |
| itemId | java.lang.String |  |

### beginInvoke(TraversalAsposeException exception, String itemId, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.email.TraversalAsposeException-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(TraversalAsposeException exception, String itemId, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exception | [TraversalAsposeException](../../com.aspose.email/traversalasposeexception) |  |
| itemId | java.lang.String |  |
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

