---
title: SyntaxValidatingEventHandler
second_title: Aspose.Email for Android via Java API Reference
description:  Represents the event handler for SyntaxValidatingEvent.
type: docs
weight: 391
url: /java/com.aspose.email/syntaxvalidatingeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class SyntaxValidatingEventHandler extends System.MulticastDelegate
```

Represents the event handler for SyntaxValidatingEvent.
## Constructors

| Constructor | Description |
| --- | --- |
| [SyntaxValidatingEventHandler()](#SyntaxValidatingEventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Object sender, SyntaxValidatingEventArgs e)](#invoke-java.lang.Object-com.aspose.email.SyntaxValidatingEventArgs-) |  |
| [beginInvoke(Object sender, SyntaxValidatingEventArgs e, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.aspose.email.SyntaxValidatingEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### SyntaxValidatingEventHandler() {#SyntaxValidatingEventHandler--}
```
public SyntaxValidatingEventHandler()
```


### invoke(Object sender, SyntaxValidatingEventArgs e) {#invoke-java.lang.Object-com.aspose.email.SyntaxValidatingEventArgs-}
```
public abstract void invoke(Object sender, SyntaxValidatingEventArgs e)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object |  |
| e | [SyntaxValidatingEventArgs](../../com.aspose.email/syntaxvalidatingeventargs) |  |

### beginInvoke(Object sender, SyntaxValidatingEventArgs e, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.aspose.email.SyntaxValidatingEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object sender, SyntaxValidatingEventArgs e, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object |  |
| e | [SyntaxValidatingEventArgs](../../com.aspose.email/syntaxvalidatingeventargs) |  |
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

