---
title: ResourceHtmlRenderingEventArgs
second_title: Aspose.Email for Java API Reference
description: Represents additional parameters for ResourceHtmlRendering event.
type: docs
weight: 636
url: /java/com.aspose.email/resourcehtmlrenderingeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ResourceHtmlRenderingEventArgs extends System.EventArgs
```

Represents additional parameters for ResourceHtmlRendering event.
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
| [getCaption()](#getCaption--) | Caprion for resource. |
| [getClass()](#getClass--) |  |
| [getException()](#getException--) | Rendering exception. |
| [getPathToResourceFile()](#getPathToResourceFile--) | Path to resource file. |
| [getResourceStream()](#getResourceStream--) | Stream with resource. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCaption(String value)](#setCaption-java.lang.String-) | Caprion for resource. |
| [setException(Exception value)](#setException-java.lang.Exception-) | Rendering exception. |
| [setPathToResourceFile(String value)](#setPathToResourceFile-java.lang.String-) | Path to resource file. |
| [setResourceStream(InputStream value)](#setResourceStream-java.io.InputStream-) | Stream with resource. |
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


Caprion for resource.

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


Rendering exception.

**Returns:**
java.lang.Exception
### getPathToResourceFile() {#getPathToResourceFile--}
```
public final String getPathToResourceFile()
```


Path to resource file.

**Returns:**
java.lang.String
### getResourceStream() {#getResourceStream--}
```
public final InputStream getResourceStream()
```


Stream with resource. If ResourceRenderingMode is EmbedIntoHtml then this stream will be embedded into the output html, for other types of ResourceRenderingMode this property has no effect.

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


Caprion for resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setException(Exception value) {#setException-java.lang.Exception-}
```
public final void setException(Exception value)
```


Rendering exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Exception |  |

### setPathToResourceFile(String value) {#setPathToResourceFile-java.lang.String-}
```
public final void setPathToResourceFile(String value)
```


Path to resource file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setResourceStream(InputStream value) {#setResourceStream-java.io.InputStream-}
```
public final void setResourceStream(InputStream value)
```


Stream with resource. If ResourceRenderingMode is EmbedIntoHtml then this stream will be embedded into the output html, for other types of ResourceRenderingMode this property has no effect.

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

