---
title: MessageAddedEventHandler
second_title: Aspose.Email for Java API Reference
description: Represents the method that will handle an  event.
type: docs
weight: 487
url: /java/com.aspose.email/messageaddedeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class MessageAddedEventHandler extends System.MulticastDelegate
```

Represents the method that will handle an [FolderInfo.MessageAddedDelegate](../../com.aspose.email/folderinfo\#MessageAddedDelegate) event.
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageAddedEventHandler()](#MessageAddedEventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Object sender, MessageAddedEventArgs e)](#invoke-java.lang.Object-com.aspose.email.MessageAddedEventArgs-) |  |
| [beginInvoke(Object sender, MessageAddedEventArgs e, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.aspose.email.MessageAddedEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### MessageAddedEventHandler() {#MessageAddedEventHandler--}
```
public MessageAddedEventHandler()
```


### invoke(Object sender, MessageAddedEventArgs e) {#invoke-java.lang.Object-com.aspose.email.MessageAddedEventArgs-}
```
public abstract void invoke(Object sender, MessageAddedEventArgs e)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object |  |
| e | [MessageAddedEventArgs](../../com.aspose.email/messageaddedeventargs) |  |

### beginInvoke(Object sender, MessageAddedEventArgs e, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.aspose.email.MessageAddedEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object sender, MessageAddedEventArgs e, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object |  |
| e | [MessageAddedEventArgs](../../com.aspose.email/messageaddedeventargs) |  |
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

