---
title: OnenoteOperation
second_title: Aspose.Email for Java API Reference
description:  The status of certain long-running OneNote operations.
type: docs
weight: 541
url: /java/com.aspose.email/onenoteoperation/
---
**Inheritance:**
java.lang.Object
```
public class OnenoteOperation
```

The status of certain long-running OneNote operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [OnenoteOperation()](#OnenoteOperation--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | The operation id. |
| [getLastActionDateTime()](#getLastActionDateTime--) | The time of the last action of the operation. |
| [isLastActionDateTimeSpecified()](#isLastActionDateTimeSpecified--) | Indicates whether LastActionDateTime property is specified. |
| [getCreatedDateTime()](#getCreatedDateTime--) | The start time of the operation. |
| [isCreatedDateTimeSpecified()](#isCreatedDateTimeSpecified--) | Indicates whether CreatedDateTime property is specified. |
| [getError()](#getError--) | The error returned by the operation. |
| [getResourceId()](#getResourceId--) | The resource id. |
| [getResourceLocation()](#getResourceLocation--) | The resource URI for the object. |
| [getStatus()](#getStatus--) | The current status of the operation: notstarted, running, completed, failed |
| [getPercentComplete()](#getPercentComplete--) | The operation percent complete if the operation is still in running status |
### OnenoteOperation() {#OnenoteOperation--}
```
public OnenoteOperation()
```


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
### isLastActionDateTimeSpecified() {#isLastActionDateTimeSpecified--}
```
public final boolean isLastActionDateTimeSpecified()
```


Indicates whether LastActionDateTime property is specified.

**Returns:**
boolean
### getCreatedDateTime() {#getCreatedDateTime--}
```
public final System.DateTimeOffset getCreatedDateTime()
```


The start time of the operation.

**Returns:**
com.aspose.ms.System.DateTimeOffset
### isCreatedDateTimeSpecified() {#isCreatedDateTimeSpecified--}
```
public final boolean isCreatedDateTimeSpecified()
```


Indicates whether CreatedDateTime property is specified.

**Returns:**
boolean
### getError() {#getError--}
```
public final String getError()
```


The error returned by the operation.

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
### getPercentComplete() {#getPercentComplete--}
```
public final String getPercentComplete()
```


The operation percent complete if the operation is still in running status

**Returns:**
java.lang.String
