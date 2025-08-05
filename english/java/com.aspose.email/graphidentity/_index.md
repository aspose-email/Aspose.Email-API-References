---
title: GraphIdentity
second_title: Aspose.Email for Java API Reference
description: ... The Identity resource represents an identity of an actor.
type: docs
weight: 289
url: /java/com.aspose.email/graphidentity/
---

**Inheritance:**
java.lang.Object
```
public class GraphIdentity
```

[...][] The Identity resource represents an identity of an actor. For example, an actor can be a user, device, or application.


[...]: https://docs.microsoft.com/en-us/graph/api/resources/identity?view=graph-rest-1.0
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphIdentity()](#GraphIdentity--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisplayName()](#getDisplayName--) | The identity's display name. |
| [getId()](#getId--) | Unique identifier for the identity. |
| [getThumbnails()](#getThumbnails--) | The ThumbnailSet resource is a keyed collection of thumbnail resources. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | The identity's display name. |
| [setId(String value)](#setId-java.lang.String-) | Unique identifier for the identity. |
| [setThumbnails(GraphThumbnailSet value)](#setThumbnails-com.aspose.email.GraphThumbnailSet-) | The ThumbnailSet resource is a keyed collection of thumbnail resources. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphIdentity() {#GraphIdentity--}
```
public GraphIdentity()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.

**Returns:**
java.lang.String
### getId() {#getId--}
```
public final String getId()
```


Unique identifier for the identity.

**Returns:**
java.lang.String
### getThumbnails() {#getThumbnails--}
```
public final GraphThumbnailSet getThumbnails()
```


The ThumbnailSet resource is a keyed collection of thumbnail resources.

**Returns:**
[GraphThumbnailSet](../../com.aspose.email/graphthumbnailset)
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




### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Unique identifier for the identity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setThumbnails(GraphThumbnailSet value) {#setThumbnails-com.aspose.email.GraphThumbnailSet-}
```
public final void setThumbnails(GraphThumbnailSet value)
```


The ThumbnailSet resource is a keyed collection of thumbnail resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GraphThumbnailSet](../../com.aspose.email/graphthumbnailset) |  |

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

