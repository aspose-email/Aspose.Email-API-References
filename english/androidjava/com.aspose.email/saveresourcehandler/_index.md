---
title: SaveResourceHandler
second_title: Aspose.Email for Android via Java API Reference
description:  Represents the handler for HtmlSaveOptions.SaveResourceHandler
type: docs
weight: 375
url: /java/com.aspose.email/saveresourcehandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class SaveResourceHandler extends System.MulticastDelegate
```

Represents the handler for HtmlSaveOptions.SaveResourceHandler
## Constructors

| Constructor | Description |
| --- | --- |
| [SaveResourceHandler()](#SaveResourceHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(AttachmentBase attachment, String[] pathToResource)](#invoke-com.aspose.email.AttachmentBase-java.lang.String---) |  |
| [beginInvoke(AttachmentBase attachment, String[] pathToResource, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.email.AttachmentBase-java.lang.String---com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(String[] pathToResource, System.IAsyncResult result)](#endInvoke-java.lang.String---com.aspose.ms.System.IAsyncResult-) |  |
### SaveResourceHandler() {#SaveResourceHandler--}
```
public SaveResourceHandler()
```


### invoke(AttachmentBase attachment, String[] pathToResource) {#invoke-com.aspose.email.AttachmentBase-java.lang.String---}
```
public abstract void invoke(AttachmentBase attachment, String[] pathToResource)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachment | [AttachmentBase](../../com.aspose.email/attachmentbase) |  |
| pathToResource | java.lang.String[] |  |

### beginInvoke(AttachmentBase attachment, String[] pathToResource, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.email.AttachmentBase-java.lang.String---com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(AttachmentBase attachment, String[] pathToResource, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachment | [AttachmentBase](../../com.aspose.email/attachmentbase) |  |
| pathToResource | java.lang.String[] |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(String[] pathToResource, System.IAsyncResult result) {#endInvoke-java.lang.String---com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(String[] pathToResource, System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pathToResource | java.lang.String[] |  |
| result | com.aspose.ms.System.IAsyncResult |  |

