---
title: ResourceHtmlRenderingEventArgs
second_title: Aspose.Email for Java API Reference
description: Provides data for the  event what to render for an attachment in the HTML.
type: docs
weight: 641
url: /java/com.aspose.email/resourcehtmlrenderingeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ResourceHtmlRenderingEventArgs extends System.EventArgs
```

Provides data for the [HeadersFormattingOptions.getResourceHtmlRenderingHandler](../../com.aspose.email/headersformattingoptions\#getResourceHtmlRenderingHandler) event: what to render for an attachment in the HTML.
## Constructors

| Constructor | Description |
| --- | --- |
| [ResourceHtmlRenderingEventArgs()](#ResourceHtmlRenderingEventArgs--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCaption()](#getCaption--) | Gets the caption shown for the resource. |
| [getClass()](#getClass--) |  |
| [getException()](#getException--) | Gets the exception that occurred while rendering the resource. |
| [getPathToResourceFile()](#getPathToResourceFile--) | Gets the path of the file to use for the resource, with  ResourceRenderingMode.SaveToFile  or  ResourceRenderingMode.SubstituteFromFile . |
| [getResourceStream()](#getResourceStream--) | Gets the content to embed for the resource, with  ResourceRenderingMode.EmbedIntoHtml ; it has no effect in the other modes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCaption(String value)](#setCaption-java.lang.String-) | Sets the caption shown for the resource. |
| [setException(Exception value)](#setException-java.lang.Exception-) | Sets the exception that occurred while rendering the resource. |
| [setPathToResourceFile(String value)](#setPathToResourceFile-java.lang.String-) | Sets the path of the file to use for the resource, with  ResourceRenderingMode.SaveToFile  or  ResourceRenderingMode.SubstituteFromFile . |
| [setResourceStream(InputStream value)](#setResourceStream-java.io.InputStream-) | Sets the content to embed for the resource, with  ResourceRenderingMode.EmbedIntoHtml ; it has no effect in the other modes. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceHtmlRenderingEventArgs() {#ResourceHtmlRenderingEventArgs--}
```
public ResourceHtmlRenderingEventArgs()
```


### Empty {#Empty}
```
public static final System.EventArgs Empty
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCaption() {#getCaption--}
```
public final String getCaption()
```


Gets the caption shown for the resource.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getException() {#getException--}
```
public final Exception getException()
```


Gets the exception that occurred while rendering the resource.

**Returns:**
java.lang.Exception
### getPathToResourceFile() {#getPathToResourceFile--}
```
public final String getPathToResourceFile()
```


Gets the path of the file to use for the resource, with  ResourceRenderingMode.SaveToFile  or  ResourceRenderingMode.SubstituteFromFile .

**Returns:**
java.lang.String
### getResourceStream() {#getResourceStream--}
```
public final InputStream getResourceStream()
```


Gets the content to embed for the resource, with  ResourceRenderingMode.EmbedIntoHtml ; it has no effect in the other modes.

**Returns:**
java.io.InputStream
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCaption(String value) {#setCaption-java.lang.String-}
```
public final void setCaption(String value)
```


Sets the caption shown for the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setException(Exception value) {#setException-java.lang.Exception-}
```
public final void setException(Exception value)
```


Sets the exception that occurred while rendering the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Exception |  |

### setPathToResourceFile(String value) {#setPathToResourceFile-java.lang.String-}
```
public final void setPathToResourceFile(String value)
```


Sets the path of the file to use for the resource, with  ResourceRenderingMode.SaveToFile  or  ResourceRenderingMode.SubstituteFromFile .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setResourceStream(InputStream value) {#setResourceStream-java.io.InputStream-}
```
public final void setResourceStream(InputStream value)
```


Sets the content to embed for the resource, with  ResourceRenderingMode.EmbedIntoHtml ; it has no effect in the other modes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

