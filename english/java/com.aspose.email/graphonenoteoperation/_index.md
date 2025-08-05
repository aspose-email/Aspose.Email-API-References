---
title: GraphOnenoteOperation
second_title: Aspose.Email for Java API Reference
description: The status of certain long-running OneNote operations.
type: docs
weight: 298
url: /java/com.aspose.email/graphonenoteoperation/
---

**Inheritance:**
java.lang.Object
```
public class GraphOnenoteOperation
```

The status of certain long-running OneNote operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphOnenoteOperation()](#GraphOnenoteOperation--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCreatedDateTime()](#getCreatedDateTime--) | The start time of the operation. |
| [getError()](#getError--) | The error returned by the operation. |
| [getId()](#getId--) | The operation id. |
| [getLastActionDateTime()](#getLastActionDateTime--) | The time of the last action of the operation. |
| [getPercentComplete()](#getPercentComplete--) | The operation percent complete if the operation is still in running status |
| [getResourceId()](#getResourceId--) | The resource id. |
| [getResourceLocation()](#getResourceLocation--) | The resource URI for the object. |
| [getStatus()](#getStatus--) | The current status of the operation: notstarted, running, completed, failed |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphOnenoteOperation() {#GraphOnenoteOperation--}
```
public GraphOnenoteOperation()
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
### getCreatedDateTime() {#getCreatedDateTime--}
```
public final System.DateTimeOffset getCreatedDateTime()
```


The start time of the operation.

**Returns:**
com.aspose.ms.System.DateTimeOffset
### getError() {#getError--}
```
public final String getError()
```


The error returned by the operation.

**Returns:**
java.lang.String
### getId() {#getId--}
```
public final String getId()
```


The operation id. Read-only.

**Returns:**
java.lang.String
### getLastActionDateTime() {#getLastActionDateTime--}
```
public final System.DateTimeOffset getLastActionDateTime()
```


The time of the last action of the operation.

**Returns:**
com.aspose.ms.System.DateTimeOffset
### getPercentComplete() {#getPercentComplete--}
```
public final String getPercentComplete()
```


The operation percent complete if the operation is still in running status

**Returns:**
java.lang.String
### getResourceId() {#getResourceId--}
```
public final String getResourceId()
```


The resource id.

**Returns:**
java.lang.String
### getResourceLocation() {#getResourceLocation--}
```
public final String getResourceLocation()
```


The resource URI for the object. For example, the resource URI for a copied page or section.

**Returns:**
java.lang.String
### getStatus() {#getStatus--}
```
public final String getStatus()
```


The current status of the operation: notstarted, running, completed, failed

**Returns:**
java.lang.String
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

