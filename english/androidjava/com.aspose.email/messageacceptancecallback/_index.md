---
title: MessageAcceptanceCallback
second_title: Aspose.Email for Android via Java API Reference
description:  Callback function which is being called during the conversion process.
type: docs
weight: 298
url: /java/com.aspose.email/messageacceptancecallback/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class MessageAcceptanceCallback extends System.MulticastDelegate
```

Callback function which is being called during the conversion process.
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageAcceptanceCallback()](#MessageAcceptanceCallback--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(MapiMessage mapiMessage)](#invoke-com.aspose.email.MapiMessage-) |  |
| [beginInvoke(MapiMessage mapiMessage, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.email.MapiMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### MessageAcceptanceCallback() {#MessageAcceptanceCallback--}
```
public MessageAcceptanceCallback()
```


### invoke(MapiMessage mapiMessage) {#invoke-com.aspose.email.MapiMessage-}
```
public abstract boolean invoke(MapiMessage mapiMessage)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mapiMessage | [MapiMessage](../../com.aspose.email/mapimessage) |  |

**Returns:**
boolean
### beginInvoke(MapiMessage mapiMessage, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.email.MapiMessage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(MapiMessage mapiMessage, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mapiMessage | [MapiMessage](../../com.aspose.email/mapimessage) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
