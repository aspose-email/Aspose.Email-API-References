---
title: Identity
second_title: Aspose.Email for Java API Reference
description: https//docs.microsoft.com/en-us/graph/api/resources/identityviewgraph-rest-1.0 The Identity resource represents an identity of an actor.
type: docs
weight: 300
url: /java/com.aspose.email/identity/
---

**Inheritance:**
java.lang.Object
```
public class Identity
```

https://docs.microsoft.com/en-us/graph/api/resources/identity?view=graph-rest-1.0 The Identity resource represents an identity of an actor. For example, an actor can be a user, device, or application.
## Constructors

| Constructor | Description |
| --- | --- |
| [Identity()](#Identity--) |  |
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
| [setThumbnails(ThumbnailSet value)](#setThumbnails-com.aspose.email.ThumbnailSet-) | The ThumbnailSet resource is a keyed collection of thumbnail resources. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Identity() {#Identity--}
```
public Identity()
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
public final ThumbnailSet getThumbnails()
```


The ThumbnailSet resource is a keyed collection of thumbnail resources.

**Returns:**
[ThumbnailSet](../../com.aspose.email/thumbnailset)
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

### setThumbnails(ThumbnailSet value) {#setThumbnails-com.aspose.email.ThumbnailSet-}
```
public final void setThumbnails(ThumbnailSet value)
```


The ThumbnailSet resource is a keyed collection of thumbnail resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ThumbnailSet](../../com.aspose.email/thumbnailset) |  |

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

